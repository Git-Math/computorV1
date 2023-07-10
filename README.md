# Computor V1
Solves a polynomial equation of degree less than or equal to 2.

## How to run
From the root of the repository run `node computor.js equation`

## Examples
```
$ node computor.js "5 * X^0 + 4 * X^1 - 9.3 * X^2 = 1 * X^0"
Reduced form: 4 + 4 * X - 9.3 * X^2 = 0
Polynomial degree: 2
a = -9.3
b = 4
c = 4
delta = b^2 - 4ac = 164.8
racine(delta) = 12.837445
Discriminant is strictly positive, the two solutions are:
0.905239
-0.475131

$ node computor.js "5 + 4 * X^1 = 4"
Reduced form: 1 + 4 * X = 0
Polynomial degree: 1
The solution is:
-0.25

$ node computor.js "5 - 4 * X^1 + 9.3 * X^2 = 1"
Reduced form: 4 - 4 * X + 9.3 * X^2 = 0
Polynomial degree: 2
a = 9.3
b = -4
c = 4
delta = b^2 - 4ac = -132.8
racine(delta) = 11.523888 i
Discriminant is negative, the two complexe solutions are:
0.215054 - 0.619564 i
0.215054 + 0.619564 i
```
