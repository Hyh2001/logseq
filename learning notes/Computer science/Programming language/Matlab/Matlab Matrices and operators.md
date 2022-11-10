# matrices and arrays

## size of a [[Latex Matrix]] or an array
	size(x)
## representation of matrix
	X = [ 1 2 3 4 5 6; 7 8 9 10 11 12]
	X = [ 1 2 3 4
			5 6 7 8] % is equal to above
### empty matrix
	x = []
	### accessing part of a matrix
### access part of a matrix

	X(a,b) %a specify rows and b specify columns
#### access multiple parts
	X(a,[b,c]) % see column b and c 
	X(a,b:c) % see columns from b to c 
	X(a,:) % see all the columns 
	X(1,2:end) % end means the last row or column 
### assign values to undefined parts
Will keep the value and fill other places with zeros
### combination of matrices
Should be in the shape of rectangles after combination

	[A1 A2 A3] %along x direction
	[A1;A2;A3] %along y direction 
### Transpose
	A’
## [[Complex numbers]]
	x = 3 +4j or x = 3 + 4i
# operator
A function that is invoked by a symbol 
## colon operator (:)
1:3:7 a list begins at 1, end at 7 and step is 3

	a:b:c. %if c is unreachable and the computer will choose the number that near it most that will not over c