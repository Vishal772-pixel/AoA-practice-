LCS-LENGTH(X.Y)

m <- length[X]

2 n <-length[Y]

for i <-1 tom

do c[i. 0] <-0

for j <-0 to n

do c[0. j] <-0

for i <- 1 to m

do for j <- 1 to n

do if x; m yj

then c[i. j] <- c[i-1,j-1]+1

b[i,j] -" slash arrow "

else if c[i - 1 , j] >= c[i,j - 1]

then c[i, j] - c[i - 1, j]

b[i. j] -"upper arrow"

else c[i. j] <cli. j -1]

b[i, j ]-"side arrow"



return c and b



PRINT-LCS(b,X.i.j)

ifi=0or j = 0

then return

if b[i, j] =" slash arrow "

then PRINT-LCS(b, X, i -1, j-1)

print x

else if b[i, j] =" above or upper arrow"

then PRINT-LCS(b, X, i -1, j)

else PRINT-LCS(b, X,i, j-1)
