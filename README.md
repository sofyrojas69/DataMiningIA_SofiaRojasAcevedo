# Proyecto de Minería de Datos: Análisis de Factores en Ventas Comerciales

## 1. Objetivo y Pregunta Central
- **Objetivo:** Analizar los factores determinantes en las ventas totales de una tienda minorista utilizando técnicas de minería de datos asistidas por Inteligencia Artificial.
- **Pregunta de investigación:** ¿Qué factores (precio unitario, descuento aplicado o calificación del cliente) influyen más en el volumen y valor de las ventas de los productos?

## 2. Fuente de los Datos y Proceso de Limpieza
- **Fuente:** Dataset estructurado de transacciones comerciales con registros limpios listos para análisis.
- **Proceso de limpieza:** Verificación de ausencia de valores nulos, estandarización de formatos de fecha (`YYYY-MM-DD`), normalización de variables numéricas y eliminación de duplicados. El archivo final limpio se guardó como `datos_limpios.xlsx`.

## 3. Técnicas de Minería de Datos Aplicadas
- **Regresión Lineal Múltiple:** Utilizada para modelar la relación entre la variable dependiente (`Ventas_Totales`) y las variables independientes (`Precio_Unitario`, `Descuento_Aplicado`, `Calificacion_Cliente`).
- **Análisis Descriptivo y Correlación:** Evaluación visual mediante gráficos de dispersión y barras para identificar tendencias de consumo por categoría de producto.

## 4. Resultados Obtenidos y Conclusiones
- Se identificó que el `Precio_Unitario` tiene una relación proporcional directa con el valor de la venta, mientras que los descuentos superiores al 20% logran dinamizar significativamente las ventas.
- La `Calificacion_Cliente` actúa como un indicador clave de estabilidad en la recompra.

## 5. Limitaciones y Recomendaciones Futuras
- **Limitaciones:** El tamaño de la muestra actual está diseñado a escala inicial para demostración de modelos.
- **Recomendaciones:** Incorporar un volumen mayor de registros históricos (hasta 500 filas) y agregar variables temporales estacionales.
