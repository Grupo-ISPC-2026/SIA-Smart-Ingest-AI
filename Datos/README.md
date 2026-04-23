# Datos — Dataset SIA (Smart Ingest AI)

Este dataset fue construido para el **Proyecto Integrador 2026** de la Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial del ISPC.

El dataset consolida 500 registros y 8 variables que modelan el ciclo de vida de la mercadería en un punto de venta. Integra datos reales de catálogos minoristas con variables logísticas y operativas simuladas, diseñadas para validar métricas de asimetría de precios y la tasa de error en la ingesta de datos (Error OCR).

> **Nota:** Este CSV es un extracto modificado para cumplir con los requisitos de la Evidencia 1 de Análisis de Datos. El dataset completo está disponible en [Kaggle](https://www.kaggle.com/siaispc/datasets-sia).

---

## Diccionario de Variables

| Variable | Tipo | Descripción |
|---|---|---|
| `EAN` | Cualitativa | Código de barras único del producto |
| `Descripcion` | Cualitativa | Nombre del producto |
| `Categoria` | Cualitativa | Rubro del producto |
| `Precio_Compra` | Cuantitativa Continua | Costo del producto |
| `Variacion_Precio_Porc` | Cuantitativa Continua | Porcentaje de variación de precio |
| `Cantidad_Recibida` | Cuantitativa Discreta | Unidades recibidas en la factura |
| `Dias_Reposicion` | Cuantitativa Discreta | Días transcurridos desde la última compra |
| `Error_OCR` | Binaria (0/1) | Indica si hubo error en la carga (1 = Error) |
