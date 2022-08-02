# Proyecto 7


## Requisitos

1. Álgebra lineal con numpy
2. Regresión lineal
3. Webinar: paquetes en python

## Descripción

Cree un paquete que contenga únicamente el objeto `LinearRegression`. Este objeto debe incluir los siguientes atributos:

1. Coeficientes beta
2. Errores estándar
3. Estadístico t
4. p-values
5. Intervalos de confianza

Y los siguientes métodos

1. Ajuste
2. Predicción
3. Resumen (entrega la tabla de resultados)
4. Prueba de heterocedasticidad `Breusch-Pagan`.
5. Prueba Jarque-Bera para normalidad de los errores.

Solo están permitidos los paquetes `numpy` y `scipy.stats`. Las pruebas deben ser construidas.
## Verificación

Prueba en clase de los resultados del objeto y comparación con los resultados del paquete `statsmodels`
