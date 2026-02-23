#  Proyecto Predicción de ventas en Olímpica  


---

###  Integrantes  
- **Juan Andrés Ramos Cardona**  
- **Sergio Cadavid**

---

## Contexto del Proyecto

En un entorno retail altamente competitivo, la capacidad de anticipar el comportamiento de las ventas constituye una ventaja estratégica clave. Las decisiones relacionadas con inventario, promociones, reposición y planeación comercial dependen en gran medida de la calidad de los análisis de datos históricos.

Este proyecto se desarrolla en colaboración con **Olímpica**, una de las principales cadenas de retail en Colombia, con el objetivo de construir una base analítica sólida para el desarrollo de modelos avanzados de predicción de ventas utilizando técnicas de Machine Learning y Deep Learning.

La presente entrega corresponde a la **Fase 1 del proyecto**, enfocada en la construcción de un **Análisis Exploratorio de Datos (EDA)** robusto y detallado, que permita comprender profundamente la estructura, calidad y comportamiento del dataset proporcionado.

---

##  Objetivo de la Fase 1

El propósito principal de esta fase es:

- Auditar la calidad y consistencia del dataset entregado.
- Identificar la granularidad real de la información.
- Analizar el comportamiento de las ventas.
- Evaluar el impacto preliminar de promociones y descuentos.
- Detectar posibles anomalías, outliers o inconsistencias.
- Definir los requerimientos necesarios para trabajar con el dataset completo.

Esta fase es fundamental para garantizar que las etapas posteriores de modelado predictivo se construyan sobre bases sólidas y correctamente interpretadas.

---

##  Descripción del Dataset (Muestra Inicial)

La muestra proporcionada por Olímpica corresponde a registros de ventas a nivel de línea de factura, lo que implica que cada fila representa la venta de un producto específico dentro de un ticket de compra.

Las variables principales incluyen:

- Identificación de producto (PLU_SAP)
- Identificación de tienda (CENTRO)
- Fecha de venta
- Cantidad vendida
- Valor de venta
- Información de promociones y descuentos
- Clasificación comercial

Esta estructura permite posteriormente realizar agregaciones a distintos niveles:

- Producto–Tienda–Día  
- Categoría–Tienda–Día  
- Tienda–Día  

Lo cual resulta ideal para modelos de series de tiempo.

---

##  Metodología del Análisis Exploratorio

El análisis se desarrolla siguiendo un enfoque estructurado:

1. **Auditoría técnica del dataset**
   - Tipos de datos
   - Nulos y duplicados
   - Validación de llaves

2. **Limpieza y transformación**
   - Conversión de variables numéricas
   - Construcción de variables derivadas
   - Validación de consistencia

3. **Análisis descriptivo de ventas**
   - Distribuciones
   - Productos líderes
   - Variabilidad

4. **Análisis preliminar de promociones**
   - Frecuencia de descuentos
   - Impacto en ventas
   - Coherencia entre variables promocionales

5. **Conclusiones y recomendaciones**
   - Variables adicionales requeridas
   - Sugerencias para el dataset completo
   - Preparación para la fase de modelado

---

##  Proyección del Proyecto

Una vez finalizada esta fase exploratoria, el proyecto avanzará hacia:

- Construcción de modelos base (baseline models)
- Implementación de modelos avanzados (LSTM y comparativos)
- Evaluación con métricas industriales (MAE, RMSE, WMAPE)
- Análisis de impacto comercial

El marco metodológico estará alineado con literatura reciente en forecasting retail, particularmente enfoques que combinan Deep Learning y modelos de gradiente boosting.

---

##  Importancia Estratégica

Este proyecto no se limita a un ejercicio académico. Representa una oportunidad de:

- Generar insights aplicables a la operación real.
- Evaluar la capacidad predictiva del histórico de ventas.
- Identificar variables críticas para la toma de decisiones comerciales.
- Establecer una base para futuras implementaciones analíticas en producción.