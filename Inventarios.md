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

Los costos por ordenar generalmente son independientes del tamaño del pedido, mientras que los costos de mantener inventario generalmente son proporcionales al tamaño del inventario.

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

$$\text{Nivel promedio de inventario} = \frac{Q}{2}$$

$$\text{Costo anual por ordenar} = \frac{D}{Q} \times Co$$

$$\text{Costo anual por mantener inventario} = \frac{Q}{2} \times Ch$$

Cuando hay equilibrio tenemos los costos totales mas bajos

Costo anual por almacenar = Costo anual por ordenar
$$\frac{Q}{2} \times Ch = \frac{D}{Q} \times Co$$

