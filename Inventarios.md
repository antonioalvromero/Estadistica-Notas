# Modelos de control de inventarios
Un inventario es uno de los activos mas importantes de una empresa representa 50% del capital invertido, por lo que es necesario tener un control adecuado sobre el mismo. Para esto se utilizan diferentes modelos de control de inventarios, cada uno con sus ventajas y desventajas.

## Modelos de control de inventarios
### Planeacion y control de inventarios
- Planeacion es principalmente a que inventario debe almacenarse y como se adquiere.(manufactura o compra)
- El control de inventarios se refiere a como se mantiene el inventario, como se almacena, como se protege, etc.
- El control de inventario tiene varias funciones:
1. Desacoplamiento: Desenlaar los procesos de manufactura dentro de una ORG, para que cada proceso pueda operar de manera independiente.
2. Almacenaje de recursos: Hay productos que son de temporada, por lo que se necesitan almacenar para su venta en la temporada.
3. Oferta y demanda irregulares: hay productos que tienen una demanda irregular, por lo que se necesita mantener un inventario para satisfacer la demanda.
4. Descuentos por cantidad: Se pueden obtener descuentos por comprar en grandes cantidades, por lo que se necesita mantener un inventario para aprovechar estos descuentos.

### Decisiones de inventarios
- Cuanto pedir: Se refiere a la cantidad de inventario que se debe pedir para satisfacer la demanda.Se tiene que considerar el costo de ordenar, el costo de mantener inventario, el costo de faltante(por perdida de clientes), etc.

Factores del costo por ordenar:
1. Desarrollo y envio de la orden
2. Procesamiento e inspeccion del inventario entrante
3. Pago de facturas
4. Indagacion del inventario
5. Servicios de luz, agua, telefono,etc para departamento de compras
6. Sueldos y salarios del personal de compras

Factores del costo de mantener inventario:
1. Costo de capital: Es el costo de oportunidad de tener el dinero invertido en inventario en lugar de invertirlo en otra cosa. Cuanto me va a costar ese inventario una vez que lo venda.
2. Salarios
3. Costo de servcios
4. Suministros
5. Merma(robo, deterioro, etc)
6. Seguros
7. Impuestos
8. Suministros(papel para el almacen, etc)

**Los costos por ordenar generalmente son independientes del tamaño del pedido, mientras que los costos de mantener inventario generalmente son proporcionales al tamaño del inventario.**

### Determinacion de cuanto ordenar
- Cantidad de lote economico (CLE): 
  - Demanda se conoce y es constante
  - Tiempo de colocar el pedido y entrega es constante
  - La recepcion del pedido es instantanea
  - El costo por unidad es constante durante el año
  - No hay faltantes

Con las siguientes variables desarrollamos expresiones para los costos anuales por ordenar y almacnear inventario:
- Q = cantidad de pedido
- D = demanda anual
- Co = costo por ordenar
- Ch = costo por mantener inventario por unidad
- CLE o Q* = numero optimo de unidades a ordenar

$$\text{Nivel promedio de inventario} = \frac{Q}{2}$$

$$\text{Costo anual por ordenar} = \frac{D}{Q} \times Co$$

$$\text{Costo anual por mantener inventario} = \frac{Q}{2} \times Ch$$

Cuando hay equilibrio tenemos los costos totales mas bajos

Costo anual por almacenar = Costo anual por ordenar
$$\frac{Q}{2} \times Ch = \frac{D}{Q} \times Co$$

$$Q^* = \sqrt{\frac{2DCo}{Ch}}$$

Los costos totales anuales se pueden calcular como:
$$CT = \frac{D}{Q} \times Co + \frac{Q}{2} \times Ch$$

## Costo de compra de los articulos del inventario

Nivel moneatario Promedio del intenario = 
$$\frac{CQ}{2} $$

## Punto de Reorden
El tiempo entre colocar una orden y recibirla se llama tiempo de entrega o tiempo de colocacion del pedido. Durante este tiempo se sigue consumiendo inventario, por lo que es necesario tener un punto de reorden para saber cuando colocar una nueva orden.

### Cuando ordenar?

- El inventario debe estar disponible

#### La formula para calcular el punto de reorden es:

d= demanda diaria
L= tiempo de entrega en dias
$$PRO = d \times L$$

Ejemplo: Si la demanda diaria es de 100 unidades y el tiempo de entrega es de 5 dias, el punto de reorden seria:
$$PRO = 100 \times 5 = 500$$

Esto quiere decir que cuando el invetario llega a 500 unidades, se debe colocar una nueva orden para reabastecer el inventario.

#### Posicion del inventario = Inventario disponible + inventario en la orden

## CLE sin supuesto de reabastecimiento instantaneo
Se aplica cuando:


Por ser un modelo adecuadno para los entornos de produccion, se tiene un costo por preparación.

Incluye los costos directos:
- La mano de obra directa
- Costos de ingenieria y diseño
- Suministros
- Servicios de luz, agua, telefono, etc para el departamento de produccion

Los costos indirectos:
- Mano de obra indirecta
- Costos de mantenimiento
- Costos de alquiler
- Internet
- Seguros

La cantidad optima de produccion se obtiene igualando los costos de preparacion con los costos de almacenar o mantener y despejando la cantidad de la orden:

- Q = numero de piezas por orden
- Cs = costo por preparar una orden
- Ch = costo anual por mantener una unidad en inventario
- p = tasa de produccion por dia
- D = demanda anual
- d = demanda diaria
- t = magnitud de la corrida de produccion en dias

Nivel maximo del inventario = 
$$ Q(1 - \frac{d}{p})$$
 
Inventario promedio =
$$ \frac{Q}{2} \times \left(1 - \frac{d}{p}\right) $$

Costo anual por mantener inventario =
$$ \frac{Q}{2} \times \left(1 - \frac{d}{p}\right) \times Ch $$

Cuando se fabrica el producto a tiempo, el costo por preparar sustituye al costo por ordenar, por lo que se igualan los costos para obtener la cantidad optima de produccion:

costo anual por preparacion =
$$ \frac{D}{Q} \times Cs $$

Costo anual por ordenar =

$$ \frac{Q}{2} \times \left(1 - \frac{d}{p}\right) \times Ch $$

Q* =
$$ \sqrt{\frac{2D \times Cs}{Ch \times (1 - \frac{d}{p})}} $$


Costos totales = costo anual por preparar + costo anual por mantener inventario
$$CT = \frac{D}{Q} \times Cs + \frac{Q}{2} \times \left(1 - \frac{d}{p}\right) \times Ch $$

Ejemplo: 
Demanda por año	10000			
Costo  Preparacion	100			
Costo Anual de almacenar	0.5			
        
Unidades de refrigeracion diaria	80			
Promedio de la demanda diaria	60			
        
Dias que se producen al año	167			

Cuantas unidades debe producir por lote?
Q* =
$$ \sqrt{\frac{2 \times 10000 \times 100}{0.5 \times (1 - \frac{60}{80})}} $$

Cuánto dura cada ciclo de produccion?
t =
$$ \frac{Q^*}{p} $$

$$ t = \frac{4000}{80} = 50 dias$$

El numero de corridoas de produccion al año es:
$$ \frac{D}{Q^*} $$
$$ \frac{10000}{4000} = 2.5 corridas por año $$


## Modelos de descuentos por Cantidad
- Los CLE no utilizan descuetos por cantidad, si este tipo de descuentos esta presente, se tiene que utilizar un modelo de descuentos por cantidad para determinar la cantidad optima de pedido.

D= Demanda anual en unidades.

Co = Costo por ordenar cada orden

C = Costo por unidad

Ch = Costo anual por mantener una unidad en inventario

CD = Costo de material
I = Porcentaje de descuento por cantidad

Costo total = costo de material + costo por ordenar + costo por mantener inventario

$$CT = CD + \frac{D}{Q} \times Co + \frac{Q}{2} \times Ch $$


### Pasos
1. Para cada precio de descuenro C se calcula la LCE
2. Si  CLE < minimo para descuetom se ajusta la cantidad a Q = minimo para descuento
3. Se calcula el costo total para cada precio de descuento

Formula CLE

$$Q^* = \sqrt{\frac{2DCo}{IC}}$$


