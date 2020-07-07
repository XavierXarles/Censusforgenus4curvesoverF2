# Censusforgenus4curvesoverF2

A file with all genus 4 curves over F_2, up-to-isomorphism. Also the magma file used to compute it.

The file 
CurvesGenus4p2ModuloIso.magma
contains the magma code used to compute the results. Also some computations concerning some of the data. 

The file 
ListCurvesGenus4p2.txt 
contains 3 lists: 

1. the first one is formed by list N containing the points over $F_{2^r}$ for $r=1,2,3,4$, which determine the jacobian up to isogeny. 

2. The second list H contains lists formed by list of the form [p,q], where p and q are polynomials over $F_2$; they correspond to hyperelliptic curves with equation

y^2+q*y= p

in such a way that H[i][j] is a curve with number of points  N[i]. 

3. The third list C contains lists formed by lists of two polynomials $f$ and $g$ in $F_2[X,Y,Z,T]$, of degre 2 and 3 respectively, such that the projective curve with canonical equations f=0, g=0   C[i][j] is a curve with number of points  N[i].



