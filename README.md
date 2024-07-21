# Análisis de Datos de Instacart

## Descripción del Proyecto

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos utilizando un conjunto de datos de pedidos de Instacart. Los datos proporcionados incluyen información sobre pedidos, productos, pasillos y departamentos. El análisis se centra en entender los patrones de compra, la distribución de productos, y realizar un análisis semanal de las ventas.

## Datasets

- `instacart_orders.csv`: Información sobre los pedidos.
- `products.csv`: Detalles de los productos disponibles.
- `aisles.csv`: Información sobre los pasillos.
- `departments.csv`: Información sobre los departamentos.

## Instrucciones

### Paso 1: Cargar y Limpiar los Datos

1. Cargar los datos en DataFrames de Pandas.
2. Realizar una limpieza básica de los datos:
   - Manejo de valores nulos.
   - Verificación de formatos de datos.

### Paso 2: Análisis Exploratorio de Datos

#### [A] Verificaciones y Visualizaciones Básicas

1. Verificar los valores en las columnas `order_hour_of_day` y `order_dow`.
2. Crear gráficos que muestren:
   - Número de personas que hacen pedidos dependiendo de la hora del día.
   - Día de la semana en que la gente hace sus compras.
   - Tiempo que la gente espera hasta hacer su próximo pedido.

#### [B] Análisis Comparativos y Distribuciones

1. Comparar la distribución de `order_hour_of_day` entre miércoles y sábados.
2. Visualizar la distribución del número de pedidos por cliente.
3. Identificar los 20 principales productos más frecuentemente pedidos.

#### [C] Análisis Detallado

1. Determinar cuántos artículos compra la gente por lo general en un pedido.
2. Identificar los 20 principales artículos que se vuelven a pedir con más frecuencia.
3. Calcular la proporción de pedidos repetidos por producto.
4. Calcular la proporción de productos pedidos que se vuelven a pedir para cada cliente.
5. Identificar los 20 principales artículos que la gente pone en sus carritos primero.

### Paso 3: Análisis adicionales. Por ejemplo
#### Ventas por Departamento

1. Agrupar productos por departamento y contar el número de productos.
2. Visualizar el número de productos por departamento.

#### Análisis Semanal

1. Realizar un análisis de las ventas semanales:
   - Agrupar los pedidos por semana.
   - Visualizar las ventas semanales.

### Conclusiones

El proyecto demuestra cómo realizar un análisis exploratorio de datos utilizando Pandas y Matplotlib para visualizar patrones de compra y distribuciones de productos en un conjunto de datos de pedidos de Instacart.

## Requisitos

- Python 3.x
- Pandas
- Matplotlib

## Ejecución

1. Clonar este repositorio.
2. Instalar los requisitos necesarios.
3. Ejecutar el script de análisis para generar las visualizaciones y análisis descritos.

