#Ejercicio R 
T = (9.25-10)/(4.5/sqrt(25))
T#mostramos t
qt(0.05, df = 25-1)
pt(q=T, df = 25-1, lower.tail = TRUE)
#Hipotesis científica:

#Es que el tiempo de carga promedio de la laptop  
#es inferior a 10 minutos debido a una nueva tecnologia de litio.
#tipo de prueba
#Prueba de t student de 1 cola a la izquierda
#Hipotesis estadistica:

#H0: μ > 10 minutos 
#H1: μ < 10 minutos 

# Nivel de significancia
alfa=0.05
#t calculado
T = (9.25-10)/(4.5/sqrt(25))
#t critico
qt(0.05, df = 25-1)
# valor de p
pt(q=T, df = 25-1, lower.tail = TRUE)
