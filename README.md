# Singular Value Decomposition
Linear Algebra in Machine Learning:

We use Singular Value Decompostion (SVD) to compress images.
If we have an image X, of order m x n, we try to decompose the matrix to U x S x VT  and approximate X by some low rank (r) product.
Therefore, approximation of X: 
Xmxn  ≅  Ur x Sr x VrT  
So consider this 2D image, which is an array X of m rows and n columns and instead of storing all mxn matrix, we are just gonna store r of them where r <<< m or n 
