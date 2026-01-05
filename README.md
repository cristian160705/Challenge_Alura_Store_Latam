# 📊 Challenge Data Science: Análisis Estratégico Alura Store Latam

Este repositorio contiene la solución al Challenge de Data Science de Alura Latam. El objetivo principal es realizar un análisis exploratorio y descriptivo de datos para tomar una decisión de negocio crítica: determinar cuál de las 4 sucursales de la cadena debe ser vendida para financiar un nuevo emprendimiento.

## 🎯 Objetivo del Proyecto

Ayudar al Sr. Juan (dueño de la cadena) a identificar la tienda con menor desempeño integral. Para ello, se procesaron datasets de ventas, envíos y calificaciones de clientes para evaluar la eficiencia operativa y comercial de cada sucursal.

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** Python 3.x
* **Análisis de Datos:** Pandas
* **Visualización:** Matplotlib
* **Entorno de Desarrollo:** Google Colab / Jupyter Notebook

## 📂 Estructura del Análisis

El proyecto sigue un flujo de trabajo de Data Science estructurado:

1.  **Carga de Datos:** Importación de 4 datasets (formato CSV) correspondientes a las Tiendas 1, 2, 3 y 4.
2.  **Exploración y Limpieza:**
    * Revisión de tipos de datos (`info`).
    * Detección de valores nulos.
    * Análisis estadístico descriptivo (`describe`).
3.  **Análisis de Métricas Clave (KPIs):**
    * 💰 **Facturación Total:** Suma de precios de venta.
    * 📦 **Volumen de Ventas:** Cantidad de transacciones por categoría.
    * ⭐ **Satisfacción del Cliente:** Promedio de calificaciones (1-5).
    * 🚚 **Logística:** Costo promedio de envío.
    * 🏆 **Productos:** Identificación de Top Sellers y productos con bajo rendimiento.
4.  **Visualización:** Generación de gráficos de barras horizontales y matrices de subplots para comparar el desempeño entre sucursales.

## 📊 Principales Hallazgos

Tras el procesamiento de los datos, se obtuvieron los siguientes insights:

* **Ingresos:** La **Tienda 1** es la líder en facturación (~$1.150M), mientras que la **Tienda 4** es la que menos genera (~$1.038M).
* **Volumen:** Todas las tiendas manejan un volumen de transacciones similar (~2,359 ventas), lo que indica que la diferencia radica en el *Ticket Promedio*.
* **Satisfacción:** La **Tienda 3** tiene la mejor calificación promedio (4.05), indicando alta fidelidad.
* **Categorías:** "Muebles" y "Electrónicos" son las categorías dominantes en todas las sucursales.

## 🚀 Conclusión y Recomendación

Basado en el análisis de datos, la recomendación final para el inversor es:

> **VENDER LA TIENDA 4**

**Justificación:**
La Tienda 4 presenta la menor eficiencia financiera. A pesar de realizar un esfuerzo operativo idéntico al de las otras tiendas (mismo volumen de ventas y gestión logística), genera aproximadamente un **10% menos de ingresos** que la tienda líder. No destaca en satisfacción al cliente ni en posicionamiento de mercado, lo que la convierte en el activo con mayor costo de oportunidad.

## 💻 Cómo ejecutar este proyecto

1.  Clona este repositorio:
    ```bash
    git clone [https://github.com/TU_USUARIO/challenge-alura-store.git](https://github.com/TU_USUARIO/challenge-alura-store.git)
    ```
2.  Instala las dependencias necesarias:
    ```bash
    pip install pandas matplotlib
    ```
3.  Abre el archivo `.ipynb` en Jupyter Notebook o Google Colab.
4.  Ejecuta las celdas secuencialmente para reproducir el análisis y las gráficas.

---
**Autor:** [Tu Nombre]
*Proyecto realizado como parte del programa de formación de Alura Latam.*
