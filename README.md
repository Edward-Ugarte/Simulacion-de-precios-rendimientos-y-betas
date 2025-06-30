# Simulacion-de-precios-rendimientos-y-betas
# 📊 Simulación Bursátil con Gretl – Precios, Rendimientos y Betas

Este repositorio documenta un conjunto de simulaciones financieras realizadas en **Gretl 2025b**. Se genera una base sintética de **precios y rendimientos diarios** para tres empresas ficticias, junto a un índice de mercado simulado, con el objetivo de aplicar herramientas de análisis de riesgo como **matrices de covarianza**, **correlaciones** y **estimación de betas**. Todo el código y los datos han sido diseñados para ofrecer un entorno cuantitativo reproducible.

---

## 🔧 Contenidos del repositorio

| Archivo                        | Descripción                                                |
|-------------------------------|-------------------------------------------------------------|
| `simulacion_con_betas.inp`    | Script principal de Gretl: precios, rendimientos y betas    |
| `acciones_con_betas.gdt`      | Base de datos `.gdt` con series simuladas                   |
| `simulacion_activos.csv`      | Precios y rendimientos exportados a CSV                     |
| `precios_y_rendimientos.csv`  | Versión simplificada (sin índice de mercado)                |
| `README.md`                   | Documento explicativo con estructura, resultados y autoría  |

---

## 📈 Objetivos principales

- Simular trayectorias de precios con comportamiento log-normal
- Calcular rendimientos logarítmicos diarios
- Medir riesgo individual mediante desviaciones estándar
- Estimar matrices de covarianzas y correlaciones
- Determinar **betas** vía regresión CAPM
- Exportar datos para análisis externo o visualización

---

## 📊 Resultados esperados (resumen de consola)
