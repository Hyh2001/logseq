# math model
## For two-dimensional:
if we vector $b$ onto a subspace with its basis be $a$ (the subspace can be represented as $p = ca$ )
we will have:
1.$a^T(b- ca) = 0$, $c$ is scalar
2.we can have c = $a^Tb/a^Ta$ 
3.$P =a (a^Tb/a^Ta)$
## For n-dimensional:
using a matrix $P = A(A^TA)^{-1}A^T$ to represent projection
### properties:
1.[[Symmetric matrix]]
2.$P^2 = P$
3.$pb = b$ for $b$ is in the column space
4.$pb = 0$ for $b$ is orthogonal to the column space   
5.the projection matrix corresponding to $e$ is $P_e = (I-p)b$


# why we need projection:
1.to solve $Ax = b$ by using $Ax^\hat{} = p$ which p is the projection of $b$ on column space of $A$ 
2.$error =b - p = b - Ax^\hat{}$ and we can see that $error$ is perpendicular to the column space of $A$ which is in the [[Left nullspace]]
3.$A^T(b-Ax^\hat{}) = 0$
$x^\hat{} = (A^TA)^{-1}A^Tb$
$p = Ax^\hat{} = A(A^TA)^{-1}A^Tb$
4.projection matrix:
$P = A(A^TA)^{-1}A^T$
