# 확률과 통계 - 한양대학교 이상화 교수

## 1. 조건부 확률과 Bayes 정리

1) sample space -> S(set)
2) Event(A) : A ⊂ S
3) Conditional Prob ( 조건부 확률 ):
    
    P( B | A ) = P( A ∩ B ) / P(A)
               = P( A ∩ B | S) / P( A | S )

    ex.) P( 오늘 날씨 | 어제 날씨 )
    -> 어제날씨 : 전제.  즉, P(목적 | 전제) 형태

4) Total Prob
    
    P(A) = P( A1 ∩ A ) + P( A2 ∩ A ) + ... + P(An ∩ A)
    
        {A1, A2, A3, ... , An} : Partition of S
        
    -> P(A1) = P( A | A1 ) x P( A1 )
    
    ∴ P(A) = Σ P( A| Ak ) x P( Ak )

5) Bayesian Theorem

    P( A | B ) = P( B | A ) / P( A ) = P( A | B ) x P(B) / P(A)

    P( A | B ) = P( B ∩ A ) / P( B )

        ex) P( Ai | A ) = P( A | Ai ) x P( Ai )

            cf) Ai : Unknown Input, A : Observation ( output )

        ex1) Binary Symmetric Channel

            input symbols : {x1, x2} -> 송신기

            output symbols : {y1, y2} -> 수신기

