# E-Commerce Performance Analysis: Hot Sale 2017

## 📊 Descripción del Proyecto
Este proyecto analiza el rendimiento de un e-commerce durante el evento "Hot Sale" de noviembre de 2017. El objetivo principal fue procesar datos crudos de transacciones para evaluar la rentabilidad de las campañas de marketing, identificar el canal de adquisición más eficiente y comprender el comportamiento de compra a nivel regional y temporal.

A través de la extracción y transformación de datos, se construyó un dashboard interactivo que permite a los tomadores de decisiones visualizar métricas clave de negocio y optimizar futuros presupuestos de marketing.

## 🛠️ Stack Tecnológico
* **Limpieza de Datos:** Excel
* **Procesamiento y Análisis (SQL):** Google BigQuery
* **Visualización:** Looker Studio

## ⚙️ Arquitectura de Datos
El flujo de trabajo consistió en:
1. **Data Processing:** Limpieza inicial en Excel y posterior carga a BigQuery, donde se ejecutaron consultas SQL para unir tablas relacionales (órdenes, ítems, productos y clientes) y calcular métricas complejas como el ROI y márgenes de ganancia.
2. **The Connection:** Integración directa de los datasets procesados desde BigQuery hacia la herramienta de BI.
3. **Interactive Visualization:** Creación de un panel en Looker Studio para democratizar los hallazgos.

## 💡 Insights Clave
A partir del análisis de **7.289 pedidos** que generaron un ingreso bruto total de **$1.153.364,20**, se destacan los siguientes descubrimientos:

* **Eficiencia de Canales (El poder del CRM):** El **Email** demostró ser el canal de adquisición más eficiente por un amplio margen. Con una inversión de apenas $3.000, generó $292.200 en ingresos, logrando un **ROI del 2.923%**. En comparación, Google Ads requirió cinco veces más presupuesto ($15.000) para alcanzar un volumen de ingresos similar.
* **Comportamiento Temporal:** Las ventas no se distribuyeron de manera uniforme. El Black Friday (24 de noviembre) concentró un pico masivo de **$175.178** en un solo día.
* **Concentración Geográfica:** El estado de São Paulo (SP) fue el motor principal de ventas, aportando casi el 35% del ingreso total ($401.001).
* **Preferencias de Consumo:** Las categorías "Hogar Textil" (17.5%) y "Relojes y Regalos" (17.2%) lideraron el volumen de ingresos durante el evento.

## 📂 Archivos del Repositorio
* `querys de sql.txt`: Contiene el código SQL ejecutado en BigQuery. Incluye 4 consultas principales para analizar ROI, ticket por región y tendencias diarias.
* `Proyecto_E-commerce_.pdf`: Exportación en formato PDF del dashboard finalizado en Looker Studio.
* `foto.jpg`: Esquema visual de la arquitectura de datos utilizada en el proyecto.

> *Proyecto desarrollado por Joaquín Garcia de la Vega.*
