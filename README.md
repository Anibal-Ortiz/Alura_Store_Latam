# Alura_Store_Latam

# Desafío 1 - Análisis de Datos Alura Store 📊

Este repositorio contiene la solución al primer desafío de datos de Alura Latam. El objetivo es analizar los datos de ventas, rendimiento y reseñas de las 4 tiendas (o canales de venta) de la cadena "Alura Store" para identificar la operación menos eficiente y presentar una recomendación de venta fundamentada al "Sr. Juan".

El análisis completo, la limpieza de datos, la visualización y el informe final se encuentran en el notebook de Jupyter: `AluraStoreLatam.ipynb`.

## 📈 Análisis Realizado

Para determinar la tienda/canal menos eficiente, se analizaron 5 métricas clave y un análisis geográfico opcional:

1.  **Facturación Total:** Comparación de los ingresos brutos generados por cada tienda.
2.  **Ventas por Categoría:** Identificación de las categorías de productos más vendidas en cada tienda (usando un gráfico de barras agrupadas).
3.  **Calificación Promedio:** Cálculo de la satisfacción media del cliente (reseñas) para cada tienda.
4.  **Productos Populares:** Análisis de los 10 productos más y menos vendidos.
5.  **Costo de Envío Promedio:** Comparación de la eficiencia logística midiendo el costo de envío promedio.
6.  **(Extra) Análisis Geográfico:** Creación de mapas de calor (`hist2d`) para visualizar la concentración de ventas por ciudad (Bogotá, Medellín, Cali, Cartagena) y confirmar que todas las tiendas compiten en los mismos mercados.

## 💻 Tecnologías y Dependencias

Este proyecto se desarrolló íntegramente en Python utilizando un Jupyter Notebook. Las principales bibliotecas necesarias para ejecutar el análisis son:

* **Pandas:** Para la carga, manipulación y análisis de los datos CSV.
* **Matplotlib:** Para la generación de todas las visualizaciones (gráficos de barras, dispersión y mapas de calor).
* **Jupyter Notebook / Jupyter Lab:** Para la ejecución interactiva del código.

## 🚀 Cómo Ejecutar el Proyecto

Para explorar el análisis, sigue estos pasos:

1.  **Clonar el repositorio (o descargar los archivos):**
    ```bash
    git clone https://github.com/Anibal-Ortiz
    cd Alura_Store_Latam
    ```

2.  **Instalar las dependencias:**
    (Se recomienda crear un entorno virtual)
    ```bash
    pip install pandas matplotlib jupyter
    ```

3.  **Iniciar Jupyter:**
    ```bash
    jupyter notebook
    ```

4.  **Abrir el Notebook:**
    En el navegador, abre el archivo `AluraStoreLatam.ipynb`.

5.  **Ejecutar el análisis:**
    Puedes ejecutar todas las celdas seleccionando "Kernel" > "Restart & Run All".

## 💡 Conclusión del Análisis (Recomendación)

El análisis concluyó que la tienda que el Sr. Juan debería vender es la **Tienda 1**.

**Justificación:** A pesar de ser la tienda con la facturación más alta ($1.15B), el análisis cruzado de métricas reveló que es la operación más ineficiente y con peor servicio:

* **Peor Calificación:** Tiene la calificación de cliente más baja (3.98 estrellas).
* **Mayor Costo:** Tiene el costo de envío promedio más alto ($26,019), compitiendo en las mismas ciudades que la Tienda 4 (la más eficiente, con $23,459).

Vender la Tienda 1 permite eliminar la operación más problemática y, al mismo tiempo, obtener el mayor capital para el nuevo emprendimiento del Sr. Juan.
