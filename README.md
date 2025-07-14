# Proyecto de Visualización de Datos para E-commerce en Locker Studio

Este repositorio contiene la documentación y los recursos relacionados con un proyecto de visualización de datos de e-commerce utilizando Locker Studio. El proyecto se divide en varias etapas, abarcando desde los fundamentos de Business Intelligence y la calidad de datos hasta la creación de dashboards interactivos y el storytelling de los hallazgos.

## Estructura del Repositorio

* **`docs/`**: Contiene los documentos detallando cada etapa del proyecto.
    * `Etapa 1_ Fundamentos y Calidad de Datos - Emilia Fernández_.docx`: Documentación de la Etapa 1.
    * `Etapa 3_ Dashboards y Visualización Interactiva.docx`: Documentación de la Etapa 3.
    * `Proyecto Final Integrador Etapa 4_ Final del proyecto y Storytelling.pptx`: Presentación de la Etapa 4.
* **`README.md`**: Este archivo.

## Descripción de las Etapas

### Etapa 1: Fundamentos y Calidad de Datos

[cite_start]Esta etapa se centró en comprender los conceptos básicos de Business Intelligence (BI) y evaluar la calidad de los datos de ventas de un e-commerce[cite: 1, 2].

**Actividades Realizadas:**

1.  [cite_start]**Captación del cliente:** Se diseñó un informe explicando la importancia de BI para un e-commerce, incluyendo ejemplos de herramientas (Data Warehousing [cite: 9, 10][cite_start], herramientas de analítica como Power BI [cite: 14][cite_start], Tableau [cite: 15][cite_start], Qlik Sense[cite: 16]; [cite_start]ETL [cite: 17, 18][cite_start]; y visualización de datos [cite: 19, 20][cite_start]) y sus beneficios[cite: 3, 4, 7, 8].
2.  [cite_start]**Investigación (contexto ético y legal):** Se realizó un caso de estudio sobre una violación de ética en datos en el ámbito del comercio electrónico[cite: 21]. [cite_start]Se analizó el contexto [cite: 23, 24, 25, 26, 27, 28][cite_start], las faltas éticas y legales (recolección sin consentimiento [cite: 30, 31][cite_start], uso de datos sensibles [cite: 32, 33][cite_start], falta de transparencia [cite: 34][cite_start], tercerización sin control [cite: 35][cite_start]), las consecuencias (sanciones económicas [cite: 37, 38][cite_start], pérdida de confianza [cite: 39, 40][cite_start], daño reputacional [cite: 41][cite_start]) y las lecciones aprendidas para evitar errores futuros[cite: 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52].
3.  [cite_start]**Investigación (exploración y búsqueda de fuentes de datos):** Se identificaron tres fuentes públicas de datos relacionadas con el e-commerce[cite: 53]:
    * [cite_start]**Cámara Argentina de Comercio Electrónico (CACE)**: Para analizar tendencias de consumo y segmentación de usuarios[cite: 55].
    * [cite_start]**Statista – E-commerce en Argentina**: Para comparar mercados e identificar productos populares[cite: 55].
    * [cite_start]**Wuala.net – Datos Clave de E-commerce**: Para entender el perfil del consumidor y tendencias[cite: 55].
4.  [cite_start]**Obtención y calidad de datos:** Se importó un conjunto de datos de ventas a Google Sheets y se aplicó un checklist de calidad de datos[cite: 56, 57]. [cite_start]Se encontraron valores faltantes en `ID_Ventas` [cite: 59][cite_start], datos duplicados [cite: 60] [cite_start]y un formato de fechas no uniforme[cite: 61]. [cite_start]Se recomendó eliminar duplicados [cite: 64][cite_start], unificar el formato de fechas [cite: 65] [cite_start]y actualizar los datos[cite: 63, 66]. [cite_start]Puedes ver el formulario del checklist aquí: [Formulario de Calidad de Datos](https://docs.google.com/forms/d/e/1FAIpQLSeT7-fvMgu_nwdxatzkWVxGMkHkhU5LnJkArrD1UULCbjalsQ/viewform?usp=dialog)[cite: 67].

### Etapa 3: Dashboards y Visualización Interactiva

[cite_start]Esta etapa se enfoca en la creación de los dashboards y la selección de los gráficos adecuados en Locker Studio[cite: 68, 69].

**Gráficos Utilizados y su Propósito:**

* [cite_start]**"Ventas totales por mes" (Gráfico de líneas):** Utilizado para mostrar tendencias a lo largo del tiempo, siendo una elección adecuada por su limpieza y claridad[cite: 70, 71, 72, 73]. [cite_start]Se considera la inclusión de una línea horizontal para el promedio de ventas mensuales[cite: 74].
* [cite_start]**"Método de pago" (Gráfico circular):** Permite entender las proporciones de cada método de pago[cite: 75, 76].
* [cite_start]**"Promedio de compra por cliente" (Treemap - versión original):** Diseñado para visualizar el promedio de compra por cliente, permitiendo identificar rápidamente a los clientes con un alto promedio[cite: 77, 78, 79].
* [cite_start]**"Productos más vendidos" (Tabla):** Se utiliza para identificar rápidamente los productos más vendidos[cite: 80, 81].

**Optimización:**

* [cite_start]Se decidió optimizar el gráfico de **"Promedio de compra por cliente"** ya que el treemap original puede presentar problemas de interpretación[cite: 84]. [cite_start]La nueva versión se centrará en mostrar el top 10 de clientes para facilitar la identificación y comparación de los clientes con el promedio de compra más alto, mejorando la legibilidad de los valores exactos[cite: 85, 86].

### Etapa 4: Final del Proyecto y Storytelling

[cite_start]En esta etapa se presentan los hallazgos clave a través de los dashboards y se realiza el storytelling de los datos[cite: 87, 88].

[cite_start]Puedes acceder al dashboard en Locker Studio aquí: [Dashboard de E-commerce en Locker Studio](https://lookerstudio.google.com/reporting/495f1084-597b-4651-9dfc-7c9f955bd3ed)[cite: 89].

**Indicadores Clave (para el año 2024):**

* [cite_start]**Ventas totales:** 10.441[cite: 95, 101, 218].
* [cite_start]**Clientes:** 307[cite: 96, 101, 218].
* [cite_start]**Productos vendidos:** 59.006 [cite: 97, 102, 219][cite_start], con junio como el mes más activo[cite: 99, 102, 219].
* [cite_start]**Promedio de productos por venta:** Más de 3 productos por venta (3.48)[cite: 100, 103, 220].
