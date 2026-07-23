# sistema-de-reportes-diarios
# 📊 Sistema de Reportes Diarios | Daily Reporting System

[Español](#español) | [English](#english)

---

<a name="español"></a>
## 🇪🇸 Español

### 📌 Descripción General
El **Sistema de Reportes Diarios** es una aplicación web ligera y automatizada diseñada para optimizar y agilizar el registro de operaciones, arrimes y control de minería/materiales en campo. Su objetivo principal es **eliminar el llenado manual de datos**, reduciendo errores humanos y centralizando el flujo de trabajo operativo.

El sistema permite gestionar unidades de producción, generar correlativos de actas de forma automática, llevar el control consolidado diario/mensual y exportar información de manera instantánea a hojas de cálculo (Excel) e imágenes listas para compartir (PNG).

### ✨ Características Principales
* **Gestión de Catálogo:** Registro, habilitación, deshabilitación y eliminación de unidades de producción.
* **Correlativo Automático de Actas:** Generación automática y en tiempo real de números de actas según el mes y año en curso.
* **Consolidado Dinámico:** Generación automática de la plantilla mensual con los días del mes (1 al 28, 30 o 31) y vista recortada "Hasta Hoy" o "Mes Completo".
* **Módulo de Arenas (Plantas Berakah y Sarrapia):** Seguimiento especializado con desglose de toneladas, tenores, estatus de negociación o rechazo y observaciones.
* **Exportación de Datos:** 
  * Captura de tablas a formato **PNG** (ancho completo, ideal para reportes por mensajería o presentaciones).
  * Exportación de resúmenes detallados a **Excel (.xlsx)**.
* **Almacenamiento Local (Offline-first):** Uso de `localStorage` para garantizar la persistencia de datos directamente en el navegador sin depender de un servidor externo.

### 🛠️ Tecnologías Utilizadas
* **HTML5:** Estructura semántica de la aplicación.
* **Tailwind CSS:** Framework para estilos rápidos, modernos y adaptables.
* **JavaScript (Vanilla JS):** Lógica del sistema, manipulación del DOM y gestión de datos.
* **Librerías Externas:**
  * `html2canvas` — Para la generación de capturas de tablas en PNG.
  * `XLSX (SheetJS)` — Para la exportación de reportes a Excel.

---

<a name="english"></a>
## 🇬🇧 English

### 📌 Overview
The **Daily Reporting System** is a lightweight, automated web application designed to streamline and accelerate operational records, delivery tracking, and field control. Its main goal is to **eliminate manual data entry**, minimizing human error and centralizing operational workflows.

The system manages production units, automatically generates document reference codes, maintains consolidated daily/monthly tracking, and allows instant export of report data to spreadsheets (Excel) and shareable images (PNG).

### ✨ Key Features
* **Catalog Management:** Add, enable, disable, and remove production units.
* **Automatic Reference Coding:** Real-time generation of document tracking numbers based on the current month and year.
* **Dynamic Monthly Views:** Automatic layout filling for all days of the month (1 through 28, 30, or 31) with filtered toggle options ("Up to Today" vs. "Full Month").
* **Sands/Materials Module (Berakah & Sarrapia Plants):** Specialized tracking including tonnage, grade/tenor, status (negotiated or rejected), and custom observations.
* **Data Export:**
  * Table capture to high-quality **PNG** images (full-width optimized for mobile messaging or slide decks).
  * Detailed summaries exported directly to **Excel (.xlsx)**.
* **Local Storage (Offline-first):** Uses `localStorage` for immediate data persistence right in the browser without requiring external database servers.

### 🛠️ Built With
* **HTML5:** Semantic web structure.
* **Tailwind CSS:** Modern, fast, and responsive utility-first styling.
* **JavaScript (Vanilla JS):** Application logic, DOM manipulation, and data handling.
* **External Libraries:**
  * `html2canvas` — For rendering tables into PNG images.
  * `XLSX (SheetJS)` — For exporting reports to Excel spreadsheets.
