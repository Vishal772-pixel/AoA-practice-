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
then c[i. j] <cli-1,j-1]+1
b[i. j] -" slash arrow "
else if cli - 1. j1 2 cli. j - 1]
then cli, j] - cli - 1, j]
b[i. jl -"t"
else c[i. j] <cli. j -1]
bli, j -"*"



return c and b



PRINT-LCS(b,X.i.j)
ifi=0or j = 0
then return
if b[i, j] =" slash arrow "
then PRINT-LCS(b, X, i -1, j-1)
print x
elseif b[i, j] =" above or upper arrow"
then PRINT-LCS(b, X, i -1, j)
else PRINT-LCS(b, X,i, j-1)
