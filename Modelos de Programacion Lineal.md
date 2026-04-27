# Modelos de Programación Lineal
PL es una tecnica de modelado matematico que ayuda a resolver problemas de optimizacion lineal, donde el objetivo es maximizar o minimizar una funcion lineal sujeta a un conjunto de restricciones lineales.

## Requerimientos de un problema de PL
Se utiliza en problemas de muchos tipos. Todos los problemas tienen propiedades y suposiciones comunes.

1. Minimizar o maximizar un objetivo.
   1. Todos los problemas buscan minimizar o maximizar alguna cantidad. Esto es la **Funcion Objetivo**.
   2. Todo objetivo se debe establecer con claridad.
2. Limitaciones o restricciones.
   1. Todo problema tiene limitaciones o restricciones que acotan el grado en el que se puede alcanzar el objetivo.
   2. Personal, maquinarias, materiales, tiempo, etc.
3. Alternativas Disponibles.
   1. Si no hay alternativas, entonces no hay problema de optimización.
4. Relaciones matematicas lineales.
   1. La funcion objetivo y las restricciones se deben expresar en ecuaciones o desigualdades lineales(de primer grado)
5. Certeza
   1. Existen condiciones de certeza, es decir se conoce con certeza el número en el objetivo y en las restricciones. No cambian durante el estudio.
6. Divisibilidad
   1. Las soluciones no necesitan números enteros.
7. Variables no negativas
   1. Todas las respuestas o variables no son negativos

## Formulacion de problemas con PL
Se desarrolla un modelo matematico que representa un problema, para esto se debe entender el problema y luego traducirlo a un modelo matematico. Para esto se siguen los siguientes pasos:
1. Entender cabalmente el problema.
2. Identificar el objetivo y las restricciones.
3. Definir las variables de decisión.
4. Utilizar las variables de decisión para expresar el objetivo y las restricciones en forma de ecuaciones o desigualdades lineales.

**Importante**:Entender la relacion entre las variables de decision, el objetivo y las restricciones es fundamental para formular un modelo de PL correcto.

## Region factible
La region factible es el conjunto de todas las soluciones que cumplen con las restricciones del problema. Es decir, es el conjunto de todas las combinaciones de variables de decision que satisfacen las restricciones. La region factible puede ser representada graficamente en un plano cartesiano, donde cada punto representa una solucion factible. El objetivo es encontrar la solucion optima dentro de esta region factible.

## Recta de Isoutilidad
La recta de isoutilidad es una herramienta grafica que se utiliza para representar el objetivo en un problema de PL. Es una linea recta que representa todas las combinaciones de variables de decision que tienen el mismo valor del objetivo. La pendiente de la recta de isoutilidad depende del coeficiente de las variables en la funcion objetivo. El objetivo es encontrar la recta de isoutilidad que sea tangente a la region factible, ya que esto indica la solucion optima.

## Holgura y excedente
Holgura = cantidad de un recurso que no se utiliza en una solucion optima.

Para una restriccion menor o igual a, la holgura se calcula como:


$$\text{Holgura} = \text{Cantidad disponible} - \text{Cantidad utilizada}$$

El excedente se emplea con restricciones de tipo mayor o igual a, y se calcula como:

$$\text{Excedente} = \text{Cantidad utilizada} - \text{Cantidad minima}$$

La holgura y el excedente son importantes para entender la eficiencia de una solucion optima y para identificar posibles mejoras en el uso de los recursos.

Si la restriccion tiene holgura o excedente 0 se considera una restriccion precisa.


