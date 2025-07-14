# Proyecto de Visualización de Datos para E-commerce en Locker Studio

Este repositorio contiene la documentación y los recursos relacionados con un proyecto de visualización de datos de e-commerce utilizando Locker Studio. El proyecto se divide en varias etapas, abarcando desde los fundamentos de Business Intelligence y la calidad de datos hasta la creación de dashboards interactivos y el storytelling de los hallazgos.

## Estructura del Repositorio

* **`docs/`**: Contiene los documentos detallando cada etapa del proyecto.
    * `Etapa 1_ Fundamentos y Calidad de Datos.pdf`: Etapa 1: Fundamentos y Calidad de Datos.
    * `Etapa 2_ Preparación y Análisis de Datos.xlsx`: Etapa 2: Preparación y Análisis de Datos.
    * `Etapa 3_ Dashboards y Visualización Interactiva.pdf`: Etapa 3: Dashboards y Visualización Interactiva.
    * `Etapa 4_ Final del proyecto y Storytelling.pptx`: Etapa 4: Presentación Dashboard y Storytelling
* **`README.md`**: Este archivo.

## Descripción de las Etapas

### Etapa 1: Fundamentos y Calidad de Datos

Esta etapa se centró en comprender los conceptos básicos de Business Intelligence (BI) y evaluar la calidad de los datos de ventas de un e-commerce.

**Actividades Realizadas:**

1.  **Captación del cliente:** Se diseñó un informe explicando la importancia de BI para un e-commerce, incluyendo ejemplos de herramientas.
2.  **Investigación (contexto ético y legal):** Se realizó un caso de estudio sobre una violación de ética en datos en el ámbito del comercio electrónico. Se analizó el contexto, las faltas éticas y legales (recolección sin consentimiento, uso de datos sensibles, falta de transparencia, tercerización sin control), las consecuencias (sanciones económicas, pérdida de confianza, daño reputacional y las lecciones aprendidas para evitar errores futuros.
3.  **Investigación (exploración y búsqueda de fuentes de datos):** Se identificaron tres fuentes públicas de datos relacionadas con el e-commerce:
    * **Cámara Argentina de Comercio Electrónico (CACE)**: Para analizar tendencias de consumo y segmentación de usuarios.
    * **Statista – E-commerce en Argentina**: Para comparar mercados e identificar productos populares.
    * **Wuala.net – Datos Clave de E-commerce**: Para entender el perfil del consumidor y tendencias.
4.  **Obtención y calidad de datos:** Se importó un conjunto de datos de ventas a Google Sheets y se aplicó un checklist de calidad de datos. Se encontraron valores faltantes en `ID_Ventas`, datos duplicados y un formato de fechas no uniforme. Se recomendó eliminar duplicados, unificar el formato de fechas y actualizar los datos. Puedes ver el formulario del checklist aquí: [Formulario de Calidad de Datos](https://docs.google.com/forms/d/e/1FAIpQLSeT7-fvMgu_nwdxatzkWVxGMkHkhU5LnJkArrD1UULCbjalsQ/viewform?usp=dialog)[cite: 67].

### Etapa 3: Dashboards y Visualización Interactiva

Esta etapa se enfoca en la creación de los dashboards y la selección de los gráficos adecuados en Locker Studio[cite: 68, 69].

**Gráficos Utilizados y su Propósito:**

* **"Ventas totales por mes" (Gráfico de líneas):** Utilizado para mostrar tendencias a lo largo del tiempo, siendo una elección adecuada por su limpieza y claridad. Se considera la inclusión de una línea horizontal para el promedio de ventas mensuales.
* **"Método de pago" (Gráfico circular):** Permite entender las proporciones de cada método de pago.
* **"Promedio de compra por cliente" (Treemap - versión original):** Diseñado para visualizar el promedio de compra por cliente, permitiendo identificar rápidamente a los clientes con un alto promedio.
* **"Productos más vendidos" (Tabla):** Se utiliza para identificar rápidamente los productos más vendidos.

**Optimización:**

* Se decidió optimizar el gráfico de **"Promedio de compra por cliente"** ya que el treemap original puede presentar problemas de interpretación. La nueva versión se centrará en mostrar el top 10 de clientes para facilitar la identificación y comparación de los clientes con el promedio de compra más alto, mejorando la legibilidad de los valores exactos.

### Etapa 4: Final del Proyecto y Storytelling

En esta etapa se presentan los hallazgos clave a través de los dashboards y se realiza el storytelling de los datos[cite: 87, 88].

Puedes acceder al dashboard en Locker Studio aquí: [Dashboard de E-commerce en Locker Studio](https://lookerstudio.google.com/reporting/495f1084-597b-4651-9dfc-7c9f955bd3ed)[cite: 89].

**Indicadores Clave (para el año 2024):**

* **Ventas totales:** 10.441.
* **Clientes:** 307.
* **Productos vendidos:** 59.006, con junio como el mes más activo.
* **Promedio de productos por venta:** Más de 3 productos por venta (3.48).
