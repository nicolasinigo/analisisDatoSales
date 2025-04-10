📊 Análisis de Datos de Ventas
Este proyecto analiza un conjunto de datos de ventas (sales_data.csv) para obtener insights sobre el comportamiento de los clientes, productos más vendidos, regiones con mayores ingresos, métodos de pago preferidos y variaciones en el tiempo.

📁 Estructura del Dataset
El dataset contiene 500 registros con las siguientes columnas:

Columna	Descripción
order_id	ID único del pedido
customer_id	ID del cliente
order_date	Fecha del pedido
product	Nombre del producto
category	Categoría del producto
quantity	Cantidad comprada
price	Precio unitario
payment_type	Método de pago utilizado
region	Región de origen de la compra
Se creó una nueva columna:

total: cantidad * precio (valor total por pedido)

🔍 Análisis Realizado
1. Ingresos por Categoría
La categoría con mayores ingresos fue Home.

Visualización: gráfico de torta.

2. Cantidad de Ventas por Región
La región con más ventas fue North.

Visualización: gráfico de torta.

3. Ingresos por Región
La región con más ingresos fue también North.

Visualización: gráfico de barras horizontales.

4. Métodos de Pago
El método de pago más utilizado fue Cash.

Visualización: gráfico de barras horizontales.

5. Ventas por Método de Pago y Región
Se analizaron y graficaron las ventas y los ingresos por región y método de pago.

Visualización: gráficos de barras agrupadas.

6. Ticket Promedio
El ticket promedio general fue de $1478.

El ticket más alto por región fue en West, y por método de pago con Cash.

Visualización: gráfico de barras.

7. Evolución Mensual y Trimestral
Las ventas mensuales y trimestrales muestran un pico en Q3 de 2024.

Visualización: gráficos de líneas.

🛠️ Herramientas Utilizadas
Python 3

Pandas – para manipulación de datos

Matplotlib – para visualizaciones

Jupyter Notebook / IDE local

📈 Conclusiones
Home es la categoría más rentable.

North es la región con mayor volumen y total de ventas.

Cash domina como método de pago.

El análisis temporal muestra una fuerte concentración de ventas en el tercer trimestre de 2024.
