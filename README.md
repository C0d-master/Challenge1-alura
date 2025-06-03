# Análisis de Datos de Ventas y Facturación de Tiendas

Este proyecto realiza un análisis exploratorio de datos de ventas, facturación y calificaciones de cuatro tiendas diferentes, usando Python con las librerías **pandas** y **matplotlib**. 

---

## Contenido

- Carga y limpieza de datos desde archivos CSV.
- Cálculo de ingresos totales por tienda.
- Análisis de ventas por categoría de productos.
- Cálculo de calificación promedio de cada tienda.
- Identificación de los productos más y menos vendidos.
- Análisis del costo de envío promedio por tienda.
- Visualizaciones para apoyar el análisis.

---

## Archivos de datos

Los datos provienen de los siguientes archivos CSV alojados en un repositorio público de GitHub:

- [Tienda 1](https://github.com/alura-es-cursos/challenge1-data-science-latam/blob/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [Tienda 2](https://github.com/alura-es-cursos/challenge1-data-science-latam/blob/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [Tienda 3](https://github.com/alura-es-cursos/challenge1-data-science-latam/blob/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [Tienda 4](https://github.com/alura-es-cursos/challenge1-data-science-latam/blob/main/base-de-datos-challenge1-latam/tienda_4.csv)

---

## Tecnologías

- Python 3.x
- pandas
- matplotlib

---

## Descripción del análisis

### 1. Análisis de facturación  
Se calcula el total de ingresos por tienda sumando los precios de todos los productos vendidos.

### 2. Ventas por categoría  
Se agrupan las ventas según la categoría del producto, mostrando las categorías con mayor volumen de ventas.

### 3. Calificación promedio  
Se calcula la calificación promedio de los productos vendidos en cada tienda para medir la satisfacción general.

### 4. Productos más y menos vendidos  
Se identifican los productos con mayor y menor cantidad de ventas, mostrando gráficas para facilitar la interpretación.

### 5. Costo de envío promedio  
Se calcula el costo promedio de envío por tienda y se visualiza para comparar los gastos logísticos entre las tiendas.

---

## Cómo ejecutar el proyecto

1. Clona este repositorio.
2. Asegúrate de tener instalado Python 3 y las librerías requeridas:
   ```bash
   pip install pandas matplotlib
