# **xG**

En los últimos años, el análisis del fútbol ha experimentado una profunda transformación gracias al auge del análisis de datos. Entre las métricas más influyentes en este campo se encuentra el concepto de "Expected Goals" o "goles esperados", comúnmente abreviado como xG. Esta métrica se ha convertido en una herramienta esencial para evaluar el rendimiento ofensivo de jugadores y equipos, más allá del resultado final de un partido o de los goles realmente marcados.

## ¿Qué son?

Los *expected goals* (xG o "goles esperados") son una métrica avanzada en el fútbol que mide la probabilidad de que un disparo termine en gol. Se basa en un análisis estadístico de miles de tiros similares en el pasado, considerando factores como:

* **La distancia al arco**: un tiro desde cerca tiene más posibilidades de ser gol que uno lejano.

* **El ángulo del disparo**: cuanto más centrado esté el jugador respecto a la portería, mayor es la probabilidad de marcar.

* **La parte del cuerpo utilizada**: un remate con el pie dominante suele tener más opciones de éxito que uno con la cabeza o el pie menos hábil.

* **La situación del jugador**: un disparo en carrera o con presión de defensores suele ser menos efectivo que uno en una posición estable y sin marcaje.

* **El tipo de jugada**: un penalti, por ejemplo, tiene un xG alto (aproximadamente 0.76, porque un 76 % de los penales suelen acabar en gol).

* **Tipo de asistencia**: pase raso, centro, balón largo, etc.

Estos factores se introducen en modelos que pueden ser tan simples como una regresión logística o tan complejos como redes neuronales profundas (RNNs, CNNs), dependiendo del nivel de detalle del conjunto de datos y del objetivo del análisis.

Cada disparo recibe un valor de xG entre 0 y 1, donde 0 significa que es casi imposible que termine en gol y 1 significa que casi siempre acaba en la red. Al sumar los xG de todos los tiros de un equipo en un partido, se obtiene una estimación de cuántos goles debería haber marcado en función de la calidad de sus oportunidades.

El xG se usa para analizar el rendimiento de jugadores y equipos más allá del simple número de goles. Por ejemplo, si un delantero tiene un xG alto pero pocos goles, puede significar que está fallando ocasiones claras. Si un equipo gana 1-0 pero su xG es solo 0.5, quizás tuvo suerte o marcó un gol difícil.

En resumen, los expected goals ayudan a entender mejor el rendimiento real de un equipo o jugador, separando la calidad de las oportunidades creadas de la eficacia a la hora de definir.

## Limitaciones

Aunque poderosa, la métrica xG no está exenta de limitaciones:

- **No incluye la posición del portero**: muchos modelos no incorporan esta variable debido a la dificultad de obtenerla, lo que puede reducir la precisión.
- **No considera el contexto táctico completo**: factores como el cansancio, la presión del momento, o la toma de decisiones pueden afectar al resultado real.
- **Diferencias entre modelos**: cada proveedor (Opta, StatsBomb, FBref, Understat, etc.) tiene su propia implementación del modelo xG, lo que puede provocar discrepancias.

## Recursos

Existen múltiples recursos en línea que permiten aprender más sobre los xG y cómo construir modelos similares. A continuación, se presentan algunas referencias útiles, muchas de las cuales incluyen ejemplos en Python:

- **StatsBomb - Open Data y Tutoriales en Python**  
  StatsBomb ofrece conjuntos de datos detallados de partidos, incluyendo información para construir modelos de xG. Además, tienen notebooks públicos en Python:
  - https://github.com/statsbomb/open-data  
  - https://github.com/statsbomb/statsbombpy

- **Karun Singh – Cómo construir un modelo xG desde cero en Python**  
  Singh proporciona un tutorial completo utilizando regresión logística:  
  Singh, K. (2020). *Building an Expected Goals (xG) model from scratch in Python*. Medium.  
  https://karun.in/blog/expected-goals-xg.html

- **Friends of Tracking – Curso de Ciencia de Datos en Fútbol**  
  Este grupo académico de la Universidad de Liverpool ofrece tutoriales en YouTube con código incluido:  
  Friends of Tracking. (2020). *Expected Goals: Understanding xG models in football*. YouTube.  
  https://www.youtube.com/watch?v=1fN7RK1gu3Y

- **FC Python – Ejemplo simple de modelo xG**  
  Un ejemplo didáctico con scikit-learn:  
  FC Python. (2018). *Expected Goals (xG) Model Tutorial*.  
  https://fcpython.com/statsbomb-xg-model-python-tutorial/

- **Understat – xG en tiempo real y datos históricos**  
  Understat permite descargar datos históricos de xG para ligas europeas:  
  https://understat.com  
  Además, existen APIs no oficiales en Python:  
  https://github.com/amosbastian/understat

## Referencias

- Karun Singh. (2020). *Building an Expected Goals (xG) model from scratch in Python*. Medium. https://karun.in/blog/expected-goals-xg.html
- StatsBomb. (2023). *Open Data Repository*. GitHub. https://github.com/statsbomb/open-data
- StatsBombPy. (2023). *Python Client for StatsBomb Open Data*. GitHub. https://github.com/statsbomb/statsbombpy
- Friends of Tracking. (2020). *Expected Goals Tutorial*. YouTube. https://www.youtube.com/watch?v=1fN7RK1gu3Y
- FC Python. (2018). *Expected Goals (xG) Model Tutorial*. https://fcpython.com/statsbomb-xg-model-python-tutorial/
- Understat. (2023). *xG Data for Top European Leagues*. https://understat.com
- Bastian, A. (2020). *Python API for Understat*. GitHub. https://github.com/amosbastian/understat

