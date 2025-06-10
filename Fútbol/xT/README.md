# xT
El análisis moderno del fútbol ha evolucionado más allá de las métricas tradicionales para incluir conceptos más sofisticados que capturan aspectos sutiles del juego. Una de estas métricas innovadoras es el "Expected Threat" o "amenaza esperada", comúnmente conocido como xT. Desarrollado por Karun Singh, el xT representa un avance significativo en la evaluación de acciones que no terminan directamente en disparo, pero que contribuyen al progreso ofensivo del equipo hacia situaciones de mayor peligro.

## ¿Qué es?
El Expected Threat (xT) es una métrica que cuantifica el valor de cada acción en el campo de juego en términos de su contribución a la probabilidad de marcar un gol en los próximos movimientos. A diferencia del xG, que solo evalúa disparos, el xT asigna un valor a cada posesión del balón, considerando desde qué zona del campo se origina la acción y hacia dónde se mueve el balón.
La métrica se basa en dividir el campo en una cuadrícula (típicamente de 12x8 o 16x12 zonas) y asignar a cada zona un valor que representa la probabilidad de que una posesión desde esa ubicación termine en gol dentro de los próximos movimientos. El xT de una acción se calcula como:
xT = Valor de la zona de destino - Valor de la zona de origen
Esto significa que:

xT positivo: la acción aumenta la amenaza ofensiva (progreso hacia el arco rival)
xT negativo: la acción reduce la amenaza ofensiva (retroceso o pérdida de posición)
xT cercano a cero: la acción mantiene un nivel similar de amenaza

Por ejemplo, un pase desde el medio campo hacia el área rival tendrá un xT alto y positivo, mientras que un pase hacia atrás desde una posición avanzada tendrá un xT negativo.

## Cómo calcularlo
El proceso para calcular xT implica varios pasos:

Dividir el campo en zonas: se crea una cuadrícula que segmenta el terreno de juego.
Analizar datos históricos: se estudian miles de posesiones para determinar, desde cada zona, qué probabilidad existe de marcar en los próximos movimientos.
Crear la matriz de valores: cada zona recibe un valor basado en análisis estadístico de datos reales.
Calcular xT por acción: para cada pase, regate o acción, se resta el valor de la zona origen del valor de la zona destino.
Agregar valores: se suman los xT individuales para obtener métricas por jugador, equipo o partido.

## Aplicaciones

Evaluación de jugadores creativos: identifica a jugadores que contribuyen al ataque más allá de goles y asistencias, como centrocampistas que progresan el balón hacia zonas peligrosas.
Análisis de patrones de juego: permite identificar las rutas más efectivas de ataque y las zonas del campo donde el equipo genera más amenaza.
Valoración de pases progresivos: cuantifica el valor de pases que rompen líneas o progresan el juego, incluso si no terminan en disparo inmediato.
Detección de talento: jugadores con alto xT suelen tener buena capacidad para leer el juego y encontrar espacios.
Análisis táctico: ayuda a entender cómo diferentes formaciones y estrategias afectan la generación de amenaza ofensiva.

## Limitaciones

Simplificación espacial: la división en zonas puede no capturar completamente la complejidad posicional del fútbol.
No considera el contexto defensivo: no tiene en cuenta la presión de los defensores o la organización defensiva rival.
Dependiente de datos históricos: la precisión depende de la calidad y cantidad de los datos utilizados para crear la matriz de valores.
No diferencia tipos de acción: un pase y un regate que terminan en la misma zona tienen el mismo xT, independientemente de la dificultad técnica.
Limitación temporal: se basa en probabilidades a corto plazo y puede no capturar el valor de jugadas de construcción más largas.

## Recursos

Karun Singh – Artículo original sobre xT
El creador de la métrica explica el concepto y la metodología en detalle.
Singh, K. (2019). Introducing Expected Threat (xT). Medium.
https://karun.in/blog/expected-threat.html
StatsBomb – Implementación y análisis
StatsBomb ha incorporado variantes de xT en sus análisis y proporciona ejemplos de aplicación.
GitHub: https://github.com/statsbomb/open-data
Python Client: https://github.com/statsbomb/statsbombpy
Friends of Tracking – Tutorial de xT en Python
Implementación práctica con código y explicaciones detalladas.
Friends of Tracking. (2020). Expected Threat Model Tutorial. YouTube.
https://www.youtube.com/watch?v=KXSLKwADXKI
FC Python – Ejemplo de implementación
Tutorial paso a paso para crear un modelo xT básico.
FC Python. (2019). Expected Threat (xT) Model Tutorial.
https://fcpython.com/expected-threat-xt-model-tutorial/
Soccer Analytics Handbook – Capítulo sobre xT
Análisis académico de la métrica con ejemplos de aplicación.
Mead, J. (2020). Understanding Expected Threat in Football Analytics.

## Referencias

Singh, K. (2019). Introducing Expected Threat (xT). Medium. https://karun.in/blog/expected-threat.html
StatsBomb. (2023). Open Data Repository. GitHub. https://github.com/statsbomb/open-data
StatsBombPy. (2023). Python Client for StatsBomb Open Data. GitHub. https://github.com/statsbomb/statsbombpy
Friends of Tracking. (2020). Expected Threat Tutorial. YouTube. https://www.youtube.com/watch?v=KXSLKwADXKI
FC Python. (2019). Expected Threat (xT) Model Tutorial. https://fcpython.com/expected-threat-xt-model-tutorial/
Mead, J. (2020). Soccer Analytics: A Comprehensive Guide to Advanced Metrics. Analytics Press.
Rathke, A. (2017). An examination of expected goals and shot efficiency in soccer. Journal of Human Sport and Exercise.