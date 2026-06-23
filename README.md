# 📊 RappiPlus - Análisis de Rentabilidad y Desempeño Comercial

## Descripción

Este proyecto tiene como objetivo analizar la rentabilidad y el desempeño comercial de RappiPlus mediante la integración y limpieza de diferentes fuentes de datos relacionadas con órdenes de compra, catálogo de productos y gastos de marketing.

A través de un proceso de preparación de datos y análisis exploratorio, se identifican indicadores clave de negocio (KPIs) que permiten evaluar ingresos, costos, inversión publicitaria y rentabilidad general.

---

## Objetivos

* Limpiar y validar la calidad de los datos.
* Detectar y eliminar registros duplicados.
* Corregir inconsistencias en variables categóricas.
* Gestionar valores faltantes y anomalías.
* Calcular métricas clave del negocio.
* Evaluar la rentabilidad de la operación.
* Analizar el comportamiento de ventas y marketing.

---

## Proceso de Limpieza de Datos

### Validaciones realizadas

* Eliminación de registros duplicados utilizando `id_pedido`.
* Conversión de columnas de fecha al tipo `datetime`.
* Identificación de valores faltantes.
* Estandarización de nombres de países.
* Corrección de valores negativos en variables numéricas.
* Verificación de tipos de datos.
* Validación de consistencia entre tablas.

---

## KPIs Calculados

### Rentabilidad

* Revenue Total
* Costo Total
* Inversión en Marketing
* Profit

### Ventas

* Ticket Promedio
* Cantidad Promedio por Orden
* Producto Más Vendido

### Marketing

* Gasto por Canal
* Distribución de inversión por fuente de adquisición

---

## Herramientas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Resultados

El análisis permitió determinar:

* El ingreso total generado por las ventas.
* Los costos asociados a los productos vendidos.
* El impacto de la inversión en marketing.
* La rentabilidad final del negocio.
* Los productos con mejor desempeño.
* Los canales de adquisición con mayor inversión.

---
