Análisis de Sentimiento de Comentarios de Usuarios

Polaridad, Subjetividad y Evaluación de Percepciones

1. Introducción

El presente proyecto tiene como objetivo analizar la percepción de los usuarios a partir de comentarios textuales, aplicando técnicas de análisis de sentimiento.
Mediante el uso de métricas de polaridad y subjetividad, se busca comprender no solo si las opiniones son positivas o negativas, sino también el grado de carga emocional con el que son expresadas.

El análisis se apoya en estadística descriptiva y visualización interactiva, permitiendo explorar patrones, proporciones y distribuciones relevantes para la toma de decisiones.

2. Marco Teórico
2.1 Análisis de Sentimiento

El análisis de sentimiento es una técnica del Procesamiento del Lenguaje Natural (NLP) que permite identificar y cuantificar la orientación emocional de un texto.
Su aplicación resulta especialmente útil para transformar datos no estructurados —como comentarios de usuarios— en variables numéricas que pueden ser analizadas estadísticamente.

En este proyecto, el análisis de sentimiento permite evaluar la percepción general de los usuarios y segmentar las opiniones según su carga emocional.

2.2 Polaridad

La polaridad representa la orientación emocional del texto, indicando si el contenido expresa una percepción positiva, negativa o neutral.

Rango de valores: [-1, 1]
- Valores positivos: sentimiento positivo
- Valores negativos: sentimiento negativo
- Valor 0: neutralidad

La polaridad se utiliza para clasificar los comentarios y analizar la distribución general del sentimiento presente en el corpus.

2.3 Subjetividad

La subjetividad mide el grado en que un texto refleja opiniones personales, emociones o juicios, en contraposición a afirmaciones objetivas o descriptivas.

Rango de valores: [0, 1]
- Valores bajos: lenguaje objetivo
- Valores altos: lenguaje subjetivo o emocional

Esta métrica permite evaluar el estilo de expresión de los usuarios y contextualizar la intensidad emocional de los comentarios.

2.4 Modelo de Cuadrantes: Polaridad vs. Subjetividad

La combinación de polaridad y subjetividad permite construir un modelo de cuatro cuadrantes que segmenta los comentarios según su orientación emocional y su grado de carga subjetiva:

- Q1 – Positivo / Subjetivo: opiniones positivas expresadas de forma emocional
- Q2 – Negativo / Subjetivo: quejas emocionales o reacciones negativas intensas
- Q3 – Negativo / Objetivo: críticas negativas de carácter racional o descriptivo
- Q4 – Positivo / Objetivo: valoraciones positivas basadas en hechos o experiencias concretas

Este enfoque permite un análisis más profundo que la simple clasificación positiva/negativa, facilitando la identificación de riesgos y oportunidades.

2.5 Enfoque Analítico y Estadístico

El proyecto se basa en:
- Estadística descriptiva
- Análisis exploratorio de datos (EDA)
- Conteos y proporciones
- Comparación de subconjuntos

No se realizan modelos predictivos ni inferencia estadística, ya que el objetivo principal es descriptivo y exploratorio.

3. Objetivos del Proyecto

- Analizar la distribución del sentimiento en los comentarios de usuarios.
- Evaluar el balance entre percepciones positivas, negativas y neutras.
- Identificar el peso relativo de las opiniones subjetivas negativas.
- Comprender cómo se distribuyen los comentarios en función de su carga emocional y objetividad.

4. Preguntas del Análisis

Esta sección se presenta antes de los resultados, ya que define el marco interpretativo del dashboard y orienta la lectura de los gráficos.

4.1 ¿Cuál es la distribución general del sentimiento en los comentarios?

Respuesta:
La mayor parte de los comentarios presenta un sentimiento neutral (42,42 %), seguido por comentarios positivos (30,30 %) y negativos (27,27 %).
Esto indica que la mayoría de los usuarios no expresa una percepción emocional extrema.

4.2 ¿Predominan los comentarios positivos o negativos?

Respuesta:
Los comentarios positivos superan levemente a los negativos, con una diferencia aproximada del 3 %.
Esto sugiere una percepción general moderadamente favorable, aunque sin una distancia significativa entre ambas categorías.

4.3 ¿Qué proporción de los comentarios son subjetivos?

Respuesta:
Una parte relevante del corpus presenta un alto grado de subjetividad, lo que indica que muchos usuarios expresan opiniones personales y emociones más que descripciones objetivas.

4.4 ¿Qué peso tienen las quejas emocionales (Q2) dentro del total subjetivo?

Respuesta:
Los comentarios clasificados como Negativos – Subjetivos (Q2) representan aproximadamente el 31,67 % del total de comentarios subjetivos.
Esto demuestra que, si bien predominan las opiniones positivas en contextos de alta subjetividad, existe un volumen relevante de quejas emocionales que requiere atención específica.

4.5 ¿Cuál es el balance general entre percepciones positivas y negativas considerando todos los estilos de expresión?

Respuesta:
Al agrupar los comentarios positivos (Q1 + Q4) y negativos (Q2 + Q3), se observa:

- Positivos: 52,63 %
- Negativos: 47,37 %

Esto refleja un balance relativamente equilibrado, con una leve predominancia de percepciones positivas.

4.6 ¿Qué cuadrantes concentran mayor volumen de comentarios?

Respuesta:
Los cuadrantes positivos (especialmente el positivo–objetivo) concentran una parte significativa de los comentarios, mientras que el cuadrante negativo–subjetivo destaca como el principal foco de riesgo emocional.

4.7 ¿Qué aportan los comentarios individuales al análisis cuantitativo?

Respuesta:
El análisis a nivel de comentario permite contextualizar los valores agregados, identificar patrones recurrentes de queja o satisfacción y comprender las causas detrás de los resultados numéricos observados.

5. Conclusiones

El análisis revela que la percepción general de los usuarios es mayormente neutral o levemente positiva.
Sin embargo, la presencia de un volumen relevante de comentarios negativos subjetivos sugiere la necesidad de profundizar en las causas emocionales de las quejas, ya que estas suelen tener mayor impacto en la experiencia del usuario.

El enfoque combinado de polaridad y subjetividad aporta una visión más rica y accionable que la clasificación tradicional del sentimiento.

6. Visualizaciones Principales

- Scatter plot Polaridad vs Subjetividad (mapa de sentimiento)
- KPIs de conteo y proporciones
- Donuts de distribución y balance
- Histograma de polaridad
- Tabla de detalle de comentarios
- Segmentadores por fecha y fuente

7.  Tecnologías Utilizadas

- Python (cálculo de polaridad y subjetividad)
- Power BI (modelado, DAX y visualización)
- DAX (medidas y columnas calculadas)
- GitHub (documentación del proyecto)

8.  Enfoque Analítico

- Estadística descriptiva
- Análisis exploratorio de datos (EDA)
- Conteos, proporciones y comparaciones
- Sin modelos predictivos ni inferencia estadística

9. Autor

Juan Palo Mercado - Analista de Datos
Proyecto orientado a análisis exploratorio, visualización y comunicación de insights.