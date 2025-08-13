# challenge1-data-science-latam
📊 Alura Store Latam - Análisis de Ventas
Este proyecto realiza un análisis exploratorio de datos (EDA) de ventas en diferentes tiendas de Alura Store Latam, usando Python y Pandas.
El dataset contiene información de productos, precios, costos de envío, ubicación de la compra, calificaciones y métodos de pago.

📂 Datos utilizados
Se utilizan cuatro archivos CSV
tienda_1.csv
tienda_2.csv
tienda_3.csv
tienda_4.csv
Cada archivo contiene las siguientes columnas:
| Columna                | Descripción                                                          |
| ---------------------- | -------------------------------------------------------------------- |
| Producto               | Nombre del producto vendido                                          |
| Categoría del Producto | Clasificación del producto (Electrónicos, Muebles, etc.)             |
| Precio                 | Precio unitario del producto                                         |
| Costo de envío         | Monto del envío                                                      |
| Fecha de Compra        | Fecha en formato `dd/mm/yyyy`                                        |
| Vendedor               | Nombre del vendedor                                                  |
| Lugar de Compra        | Ciudad donde se realizó la compra                                    |
| Calificación           | Puntuación del 1 al 5 otorgada por el cliente                        |
| Método de pago         | Medio utilizado para pagar (Tarjeta de crédito, débito, Nequi, etc.) |
| Cantidad de cuotas     | Número de pagos acordados                                            |
| lat, lon               | Coordenadas geográficas de la ciudad                                 |
📈 Análisis realizados
Análisis de facturación
Calcular la facturación total sumando el precio y el costo de envío.
Identificar tendencias de ventas por fecha.
Ventas por categoría
Agrupar y sumar ventas por categoría de producto.
Visualizar las categorías más rentables.
Calificación promedio de la tienda
Calcular el promedio de calificación otorgado por los clientes.
Productos más y menos vendidos
Identificar los productos más demandados.
Determinar aquellos con menor rotación.
Envío promedio por tienda
Calcular el costo de envío promedio por ubicación.
