# Determinant
The determinant of a linear transformation is equal to the factor by which an arbitrary hypervolume (=area for 2 dimensions) is stretched under the transformation.
A determinant of zero represents a transformation to a lower dimension. It also means that the columns of the matrix must be linearly dependent.
A negative determinant represents a change in orientation ("flipping" the axes around).

$\det(AB) = \det(A)\det(B)$

Source: 3Blue1Brown, The determinant | Chapter 6, Essence of linear algebra

# Inverse matrix
The inverse $A^{-1}$ of a matrix $A$ solves the problem $A^{-1}A = 1$.
It only exists if the determinant of $A$ is not zero, i.e. $A$ hast full rank.

# Rank
The rank of a matrix is equal to the number of dimensions that result from applying the matrix (i.e. where input vectors land after applying the transformation).

# Eigenvalues and eigenvectors
Eigenvectors are those vectors that are only stretched by a linear transformation but not rotated. The associated eigenvalue gives the factor by which an eigenvector is stretched.

Source: 3Blue1Brown, E igenvectors and eigenvalues | Chapter 14, Essence of linear algebra

# Definiteness
A matrix $A$ is called positive definite if 
$x^TAx$ is postive for all non-zero real vectors $x$. This is the case (for Hermitian matrices) if all eigenvalues are positive.