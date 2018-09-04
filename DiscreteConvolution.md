# 이산확률 변수와 Convolution

1. 이산확률변수의 합.

    Z = X + Y

    X, Y 는 Discrete한 정수의 집합이다.

    P(Z = z) = P(X + Y = Z)

    P𝒙𝑦 = ( x  , y )

        (-1, z+1 )

        ( 0, z   )

        ( 1, z-1 )

            ...

        ( k, z-k )

    = P(Z = z)

    = P𝗑ʏ(X=k, Y=z-k)

    만약, X 랑 Y가 독립이면, 다음이 성립한다.
    = Σ P𝒙(k) * P𝑦(Z=k) ⇒ convolution



2. 독립 이항분포의 합

    X ~ B(n,p) = Pｘ(x) = nCx * Pˣ * ( 1 - p ) 


