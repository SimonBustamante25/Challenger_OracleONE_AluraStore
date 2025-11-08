# Challenger_OracleONE_AluraStore

# Análisis de Rendimiento de Tiendas

## Propósito del Análisis

Este proyecto tiene como objetivo principal evaluar el desempeño de cuatro tiendas minoristas para identificar aquella con el menor rendimiento y, en consecuencia, determinar si debería ser considerada para una posible venta. El análisis se basa en diversas métricas clave para obtener una visión completa del rendimiento financiero y operativo de cada ubicación.

## Datos

El análisis se realizó utilizando datos de ventas y operaciones de cuatro tiendas diferentes. Cada conjunto de datos (representado por los archivos `tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, y `tienda_4.csv`) contiene información detallada sobre transacciones, incluyendo producto, categoría, precio, costo de envío, fecha de compra, vendedor, lugar de compra, calificación, método de pago, cantidad de cuotas, latitud y longitud.

Los datos fueron cargados y procesados utilizando la librería pandas en Python.

## Desarrollo y Análisis

Se llevaron a cabo las siguientes etapas de análisis:

1.  **Análisis de Facturación:**
    *   **Ingresos por tienda:** Se calcularon y compararon los ingresos totales generados por cada tienda. La **Tienda 4** registró los ingresos más bajos.
    *   **Ingresos por fecha:** Se visualizó la evolución diaria de los ingresos para cada tienda en los años 2022 y 2023. La **Tienda 4** mostró consistentemente ingresos diarios generalmente inferiores y el promedio más bajo.

2.  **Ventas por Categoría:**
    *   Se analizó la cantidad de productos vendidos por cada categoría en cada tienda.
    *   Se calculó y visualizó la facturación generada por las principales categorías de productos en cada tienda (presentado en gráficos de pastel).

3.  **Calificación Promedio de la Tienda:**
    *   Se calculó y comparó la calificación promedio obtenida por cada tienda (en una escala, presumiblemente de 1 a 5 estrellas). Las calificaciones fueron similares entre tiendas, con la **Tienda 4** teniendo una calificación ligeramente menor pero muy cercana a las demás.

4.  **Productos Más y Menos Vendidos:**
    *   Se identificaron los productos con mayor y menor cantidad de ventas en cada tienda.

5.  **Costo de Envío Promedio por Tienda:**
    *   Se calculó y comparó el costo de envío promedio para cada tienda. La **Tienda 4** tuvo el costo promedio más bajo.

## Conclusión y Recomendación

Basado en un análisis exhaustivo de los datos, considerando especialmente los **ingresos totales** y la **evolución histórica de los ingresos diarios**, se concluye que la **Tienda 4** es la que presenta el rendimiento financiero más débil en comparación con las otras tres tiendas.

Aunque la Tienda 4 tiene un costo de envío promedio ligeramente menor y una calificación promedio comparable a las otras, la diferencia significativa en sus ingresos la posiciona como la candidata más lógica para la venta si el objetivo es optimizar el portafolio de tiendas y maximizar la rentabilidad general.

Por lo tanto, la **recomendación** es **vender la Tienda 4**.
