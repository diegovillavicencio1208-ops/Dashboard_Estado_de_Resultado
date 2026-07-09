# 📊 Automatización Estado dde Resultados(P&L)

## Descripción
Dashboard en Power BI que sistematiza la creación del Estado de Resultados (P&L) de una empresa, manteniendo el formato tradicional en que se presenta este informe financiero: ingresos, costos, utilidad bruta, utilidad neta, pero de forma interactiva y actualizada automáticamente con cada nuevo período de datos.

> Basado en el artículo y tutorial de **[Valerie Junk](https://www.valeriejunk.nl/profit-and-loss-statement-in-power-bi/)** - *Profit and Loss Statement in Power BI*. Esta implementación adapta el modelo al español y extiende la lógica comparativa año actual vs. año anterior con títulos dinámicos.

---

## Objetivo
Eliminar la elaboración manual y repetitiva del Estado de Resultados, entregando un reporte financiero que conserva el formato contable estándar (desglose por mes y comparativo del año actual vs. el año anterior), pero que se actualiza automáticamente al cargar nuevos datos, sin necesidad de reconstruir el informe cada período.

---

## Dashboard

🔗 [Ver dashboard interactivo en Power BI](https://app.powerbi.com/view?r=eyJrIjoiYmZmOGQ4MWItM2QyYS00MTg4LTgzNzItODFhOWZkMGVmODljIiwidCI6IjU1N2NiNjMxLWI3ZjQtNGM1NC1hNjljLWM4MzQ1NWQxMzEyOCIsImMiOjR9&pageName=db809bd683c06d063af7)

[![Dashboard Estado de Resultados](https://github.com/diegovillavicencio1208-ops/Estado_de_Resultado/blob/25fc315cf4f4de755a49f8970131fa991b6355a3/Finanancial_report.png)](https://app.powerbi.com/view?r=eyJrIjoiYmZmOGQ4MWItM2QyYS00MTg4LTgzNzItODFhOWZkMGVmODljIiwidCI6IjU1N2NiNjMxLWI3ZjQtNGM1NC1hNjljLWM4MzQ1NWQxMzEyOCIsImMiOjR9&pageName=db809bd683c06d063af7)

---

## Características
- Estado de Resultados con el formato contable estándar (ingresos, costos, utilidad bruta, utilidad neta), generado automáticamente
- Desglose mensual de ingresos, costos y utilidades
- Análisis comparativo año actual vs. año anterior vs. diferencia (Δ)
- Títulos dinámicos que se actualizan automáticamente según los datos disponibles
- Filas calculadas (Utilidad Bruta, Margen Bruto %, Utilidad Neta) integradas en la misma matriz mediante IDs virtuales
- Tarjetas KPI con indicadores de variación (▲/▼) y formato condicional por color
- Slicer dinámico de comparación generado desde el año más reciente cargado

---

## Tecnologías
- Power BI Desktop
- DAX
- Power Query (M)
- Excel

---

## Dataset
**Fuente:** Datos transaccionales de una empresa, estructurados en una tabla de hechos (`Fct_Transacciones`) con dimensiones de cuenta contable (`Dim_Cuenta`) y calendario (`DIM_Calendario`).

---

## Documentación
- 📘 [Documentación técnica](https://github.com/diegovillavicencio1208-ops/Dashboard_Estado_de_Resultado/blob/08079672f22ea7df74624e5d01ac3040679ea960/Documentacion_Tecnica.md)
- 📊 [Dashboard interactivo](https://app.powerbi.com/view?r=eyJrIjoiYmZmOGQ4MWItM2QyYS00MTg4LTgzNzItODFhOWZkMGVmODljIiwidCI6IjU1N2NiNjMxLWI3ZjQtNGM1NC1hNjljLWM4MzQ1NWQxMzEyOCIsImMiOjR9&pageName=db809bd683c06d063af7)

---

- ## Contactos

[![Email](https://img.shields.io/badge/EMAIL-FFC107?style=for-the-badge&logo=gmail&logoColor=black)](mailto:diegovillavicenciodl@gmail.com)
[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diegovillavicenciodl/)
[![Website](https://img.shields.io/badge/WEBSITE-8E001C?style=for-the-badge&logo=google-chrome&logoColor=white)](https://diegovillavicencio.framer.website/)
---
