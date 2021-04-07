# Perrin

# Tipos de datos

2 + 2

# Datos basicos

class(2) # numeros reales
class('Italo') # cadena de caracteres
class(TRUE) # logico

2 + 'italo'

# creacion de variables

nombre <- 'Italo' 
nombre 

PI <- 3.14161785
PI + 2

print(PI) # muestra el valor por la consola

# Operadores aritmeticos
a <- 2
b <- 3

a + b # suma 
a - b
a * b
a / b
a ^ b # potencia : alt + 94

sqrt(9)
exp(1)
log(3)
abs(-10)
pi

# operadores comparacion

a < b
a > b
a == b
a != b
a <= b
a >= b

# Operadores  logicos

c1 <- TRUE & TRUE # alt + 38

FALSE | FALSE # alt + 124

! TRUE


# DATOS ESTRUCTURADOS

edad <- c(17, 23, 34, 45, 54)
is.vector(edad)

a <- vector('numeric', 5)
a

length(edad)

b <- c()
b
b <- c(b, 2)
b



# secuencias 
dias_mes <- 1:31
dias_mes

secuencia <- seq(from=1, to=31, by=2)
secuencia

repeticiones <- rep('italo', times=10)
repeticiones

# Factor 
factores <- factor(c('T1', 'T1', 'T2', 'T0'))
factores
levels(factores)

# MATRIZ

m <- 11:30
length(m)

dim(m) <- c(4, 5)
m

m <- matrix(11:30, nrow = 4, ncol = 5)
m

rbind(m, c(55,59,68,32,65))

dimensiones <- dim(m)
dimensiones

dim(matrix())

# indexado

c1 <- m[3, 4]

# subseleccion

m2 <- m[2:4, 1:3]
m2


# Data Frame

d <- data.frame(x=1:10, y=rep('Italo', 10))
d
