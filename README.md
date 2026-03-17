##########################################
# Lista de exercícios 1
# Autor: Alan Sasaki
# Data: 17/03/2026
##########################################
# Removendo os objetos ativos
rm(list=ls())

# -- Exercício 1 --

# (a)
3 + 4 * 8

# (b)
(3 + 4) * 8

# (c)
8 * 5 + 2 * 3

# (d)
8 * (5 + 2) * 3

# (e)
2^3 + 2 * sqrt(3)

# (f)
(2 * 8) / 3 + 5 / (6 + 8)

# (g)
sum(1:8)

# (h)
prod(1:8)

# (i)
(1 + 1 / 8)^3

# (j)
cos(pi)

# (k)
sin(pi)^2 + cos(pi)^2

# (l)
log(9)

# (m)
abs(8 - 9)

# (n)
2 / factorial(7) + sqrt(2) / 2

# -- Exercício 2 --

# (a)
M = matrix(c(5, 0, 6, 9, 6, 4, 3, 5, 2), ncol=3, byrow=TRUE)
M 

# (b)
dim(M)

# (c)
diag(M)

# -- Exercício 3 --

# (a)
a = 1:10
a
mode(a); class(a)

# (b)
b = letters[1:6]
b
mode(b); class(b)

# (c)
c = matrix(letters[1:6], ncol=2)
c
mode(c); class(c)

# (d)
d = c("verde", "azul", "rosa")
d
mode(d); class(d)

# (e)
e = c(4i, 8i, 9i)
e
mode(e); class(e)

# (f)
f = c(5>2, 7<2, 8>3)
f
mode(f); class(f)

# (g)
g = date()
g
mode(g); class(g)
