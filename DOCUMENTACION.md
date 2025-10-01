#Sandra Paredes
¿Qué clientes tienen mayor probabilidad de volver a comprar y cuáles productos comprarían?
¿Qué fechas existe mayor venta y qué productos son los que mas se venden?
¿Qué productos se pueden agrupar para tener mayores ganancia?
Estructura BDD Clientes: id_cliente, nombre_cliente, email, ciudad, fecha_alta
Tipo BDD Clientes: tabular
Escala BDD Clientes: Nominal y intervalo  (fecha)
Estructura BDD Productos: id_producto, nombre_producto, categoria, precio_unitario
Tipo BDD Productos: tabular
Escala BDD Productos: nominal y Intervalo(fecha)
Estructura BDD Ventas: id_venta, fecha, id_cliente, nombre_cliente, email, medio_pago
Tipo BDD Ventas: tabular
Escala BDD Ventas: nominal y razon (precio)
Estructura BDD Detalle_ventas: id_venta, id_producto, nombre_producto, cantidad, precio_unitario, importe
Tipo BDD Detalle_ventas: tabular
Escala Detalle_ventas: razon y nominal (medio de pago)