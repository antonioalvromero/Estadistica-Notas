# Pronosticos
Generalmente se toman decisiones sin conocer el futuro.
## Pasos para elaborar un pronostico
1. Determinar el uso
2. Determinar los articulos o las cantidade que que se van a pronosticar
3. Determinar el horizonte de tiempo
4. Seleccionar el o los modelos de pronostico
5. Validar el modelo



## Modelos Cuantitativos para pronosticar

- ### Modelos de series de timepo
  - Se intenta predecir el futuro a partir de datos historicos.
- ### Modelos causales
  - Intentan incluir factores que influyen en el comportamiento de datos.
  - Normalmente se trabaja con analisis de regresion
- ### Modelos cualitativos
  - Se incorporan factores subjetivos como las opiniones de personas.

## Diagramas de dispersion y Series de tiempo

Un diagrama de dispersion para una serie de tiempo se grafica en dos dimensiones. con el tiempo en el eje horizontal. La variable que se pronostica(como las ventas) se coloca en el eje vertical.

## Medidas de exactitud del pronostico

### Desviacion Media Absoluta (DMA)
Es una medida de exactitud que es la suma de los valores absolutos de los errores de pronostivos individuales y luego se divide entre el numero de errores (n)

Me dice cuanto se separan unos datos de otros.

Se usa para comparar datos o la evaluacion de modelos para saber cual es mejor.

# Modelos Serie de tiempo
## Componenetes de una serie de tiemmpo
Analizar esto significa desglosar los datos historicos en sus componentes y luego proyectar hacia el futuro

3. Ciclos> son patrones en los datos anuale que ocurren cada cierto numero de años.
4. Variaciones aleatorias> son saltos en los datos ocasionados por el azar y por situaciones inusuales.

Entender los componenetes de una serie de tiempo ayuda a seleccionar la tecnica de pronosticos adecuada.

### Promedios Moviles
Un promedio movil de 4 meses por ejemplo se encuentra simplemente sumando

### Promedio Movil Ponderado
Permite asignar diferentes pesos a las observaciones previas.

Entonces se le pone mas peso a lo que ha sucedido mas reciente

---
Los promedios moviles simples y ponderados son efectivos en cuanto a suavizar fluctuaciones repentinas en el patron de demanda, con la finalidad de dar estimaicones

### Problemas
- Entre mas grande la cantidad de datos se pierde la confianza

---

## Suavizamiento Exponencial

## Suavizamiento Exponencial con ajuste de tendencia
Si hay una tendencia presente en los datos deberia usar un modelo de pronostico que la incorpore de manera explicita al pronostico.