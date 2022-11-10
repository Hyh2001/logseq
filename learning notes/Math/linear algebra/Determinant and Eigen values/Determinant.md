# definition
Noted as $det A$ or $|A|$, 
### For determinant, it has three basic properties with more 8 properties can be got from the three basic ones.  To compute the determinant, we need to first understand cofactors. With cofactors we can compute the inverse of a square matrix and moreover use Cramer’s rule to compute x.
## properties
### 1
$det I = 1$
### 2
If you exchange two rows of a determinant, it reverses the sign of the determinant
### 3
multiply one row by $t$, $\begin{vmatrix} ta & tb\\ c& d \end{vmatrix} = t\begin{vmatrix} a & b\\ c& d \end{vmatrix}$, add between rows $\begin{vmatrix} a+e & b+f\\ c& d \end{vmatrix} = \begin{vmatrix} a & b\\ c& d \end{vmatrix} + \begin{vmatrix} e &f\\ c& d \end{vmatrix}$
$\begin{vmatrix} a & b\\ c& d \end{vmatrix} = ad -bc$
### 4
If two rows are equal, $det(A) = 0$
Prove: two rows are equal, then liner dependent
### 5
subtract $l*row \quad 1$ from $row \quad k$ ,the determinant will not change
Prove: $\begin{vmatrix} a & b\\ c-la& d-lb \end{vmatrix} = \begin{vmatrix} a & b\\ c& d \end{vmatrix} + \begin{vmatrix} a &b\\ -la& -lb \end{vmatrix}$
### 6
Row of zeros will lead to $det A = 0$
### 7
For a triangular matrix , $det A$ equals to the product of its diagonals
### 8
$det A =0$ When $A$ is singular 
### 9
$det AB = (det A) (det B)$ And $det A^{-1} = 1/ det A$
$det zA = z^ndetA$ $z$ is a number 
### 10
$det A^T = det A$
Prove: $|A^T| = |A| => |U^TL^T| = |LU| => |U^T||L| = |L||U|$
## formula
### prove
$\begin{vmatrix} a & b\\ c & d\end{vmatrix} = \begin{vmatrix} a & 0 \\ c &d \end{vmatrix} + \begin{vmatrix} 0 & b\\ c & d\end{vmatrix} = \begin{vmatrix} a & 0 \\ c & 0\end{vmatrix} + \begin{vmatrix} a & 0 \\0 &d \end{vmatrix} + \begin{vmatrix} 0 & b\\c & 0\end{vmatrix} + \begin{vmatrix}0 & b\\ 0& d \end{vmatrix} = ad-bc$
for n dimensional 
$det A = \sum_{n!}^{} +- a_{1\alpha}a_{2\beta}…a_{n\gamma}$
$(\alpha,\beta,\gamma)$ are terms in $(1,2,3,….,n)$

### cofactor 
For 3 dimensional 
$det A = a_{11}(a_{22}a_{33}-a_{23}a_{32})+a_{12}(….)+a_{13}(…)$
### final formula 
The cofactor is $C_{ij} = (-1)^{i+j}detM_{ij}$
And $detA = a_{1j}C_{1j} +a _{2j}C_{2j}+…+a{nj}C{nj}$

## Find A inverse
A^{-1} = (1/detA)C^T$
$C$ is called the cofactor matrix and $C_{mn}$ is the cofactor of $A_{mn}$
Prove:
To prove $AC^T = (detA)I$
We found that $AC^T = \begin{array}{l} detA& 0 &0 &0& 0… \\ 0 &detA &0& 0& 0.. \\ 0 &0 &detA& 0& 0.. \\ … \end{array}$
### 1.why other entries are zeros?
Because they can be treat as a determinant to a matrix with zero rows or columns 
### 2.why diagonal entries are zeros?
Because they form the determinants of A 

## Cramer’s rule
For $x = (1/detA)C^Tb$
The answer to it is $x_1 = detB_1/detA, x_2 = detB_2/detA$
### For matrix $B_1,B_2,…$
$B_1 = \begin{matrix}[ b & A_2 & A_3 …]\end{matrix}$
$B_2 = \begin{matrix}[ A_1 & b & A_3 …]\end{matrix}$
…
Prove:
$\begin{array}{l} [A]\end{array} \begin{bmatrix} x_1 & 0 &0 \\ x_2&1&0 \\ x_3&0&1 \end{bmatrix} = \begin{bmatrix} b_1 & a_{12} &a_{13} \\ b_2&a_{22}&a_{23}\\ b_3&a_{32}&a_{33}\end{bmatrix}=B_1$
so $(detA)(x_1) = detB_1$

## use determinant to find volumes
 $|det A|$ = volume of a box
### sign of determinants:
Tell us whether the box is right-handed or left-handed
### Prove
