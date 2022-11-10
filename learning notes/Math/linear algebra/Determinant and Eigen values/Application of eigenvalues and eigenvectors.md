# diagonalizing
## math model 
### prerequisites:
n-independent eigenvectors
$S^{-1}AS = B$  or $A = SBS^{-1}$
Suppose we have n [[Linear independence]] eigenvectors of $A$
And we put them in columns of $S$ 
For $AS$ we get $AS = \begin{array}{l}[\lambda_1x_1 & \lambda_2x_2 &… &\lambda_nx_n ]\end{array}$
Separate $x$ out:
$AS = \begin{array}{l}[x_1& x_2 &… &x_n] \end{array}*\begin{bmatrix} \lambda_1  & 0 &0…\\ 0& \lambda_2&0 … \\ 0 &0 &…\lambda_n\end{bmatrix} = SB$
The diagonals of $B$ are [[Eigenvalues]]
### quick calculation of exponent 
We can get $A^k = SB^kS^{-1}$
#### solve for $u_k = A^ku_0$
$u_0 = c_1x_1+c_2x_2… = SC$
$x$ are eigenvectors
And $u_k = B^kSC$
### when A is diagonalizable
1.All eigenvalues are different
2.with repeated eigenvalues, we need to check eigenvectors

