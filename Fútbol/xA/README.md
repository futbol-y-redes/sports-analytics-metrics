# xA

En la última década, el análisis avanzado de datos ha transformado radicalmente la manera en que se evalúa el rendimiento en el fútbol. Mientras que los **Expected Goals (xG)** se han convertido en una métrica estándar para medir la calidad de un disparo, su contraparte menos conocida pero igualmente útil, las **Expected Assists (xA)**, proporciona una herramienta complementaria para analizar la creatividad ofensiva de los jugadores. La métrica xA permite ir más allá de las asistencias tradicionales, al cuantificar no solo si un pase terminó en gol, sino qué tan probable era que el disparo posterior al pase se convirtiera en gol.

## ¿Qué son?

Las **Expected Assists (xA)** son una métrica que estima la probabilidad de que un pase se convierta en una asistencia, en función de la calidad del disparo que genera. Es decir, el xA de un pase es igual al valor xG del disparo que lo sigue. Así, en lugar de registrar una asistencia solo cuando el disparo termina en gol, se mide el valor potencial del pase en términos de generar una oportunidad de gol de alta calidad.

Esta métrica permite identificar a los jugadores que crean muchas y buenas ocasiones, incluso si sus compañeros no logran convertirlas. En resumen:

- Si un jugador realiza un pase que genera un disparo con 0.4 de xG, ese pase tiene un xA de 0.4.
- Si el mismo jugador hace cinco pases que generan tiros de 0.2 xG, entonces su xA total es 1.0, aunque ninguno haya acabado en gol.

El cálculo de xA depende de la implementación de un modelo de xG. Los pasos son los siguientes:

1. **Recolectar todos los pases que terminan en disparo.**
2. **Evaluar cada disparo con un modelo xG.**
3. **Asignar ese valor xG al pase que lo originó.**

Por lo tanto, el xA es una métrica derivada del modelo xG, y su precisión depende en gran parte de la calidad de dicho modelo.

## Aplicaciones

1. **Medición del rendimiento creativo**: se puede evaluar a los jugadores que generan más ocasiones de calidad, incluso si no acumulan muchas asistencias.
2. **Detección de talento**: jugadores con altos valores de xA suelen tener buen "visión de juego" y capacidad para crear peligro.
3. **Diagnóstico táctico**: comparar el xA con el número real de asistencias ayuda a entender si un equipo está fallando en la finalización.
4. **Complemento del xG**: junto al xG, el xA permite entender mejor las dinámicas de ataque de un equipo: quién crea y quién finaliza.

## Limitaciones

- **Dependencia del modelo xG**: si el modelo xG es impreciso, también lo será el cálculo del xA.
- **No todos los pases son considerados**: solo los pases que resultan en un disparo son tenidos en cuenta. Asistencias potenciales sin remate quedan fuera.
- **No mide la dificultad del pase**: el xA no distingue entre un pase corto y simple o una asistencia técnicamente brillante, siempre que el disparo resultante tenga el mismo xG.

## Recursos

- **StatsBomb Open Data + Python**  
  StatsBomb ofrece una API pública y notebooks de ejemplo que permiten identificar pases que llevan a tiros.  
  GitHub: https://github.com/statsbomb/open-data  
  Python Client: https://github.com/statsbomb/statsbombpy

- **Karun Singh – Modelado de xG + derivación de xA**  
  Aunque su tutorial se centra en xG, explica cómo derivar xA al vincular disparos con sus pases previos.  
  Singh, K. (2020). *Expected Goals (xG) Model from scratch in Python*. Medium.  
  https://karun.in/blog/expected-goals-xg.html

- **FC Python – Tutoriales en xG y enlaces con xA**  
  Incluyen explicaciones sobre cómo asociar asistencias con los valores xG.  
  FC Python. (2018). *Expected Goals (xG) Model Tutorial*.  
  https://fcpython.com/statsbomb-xg-model-python-tutorial/

- **Friends of Tracking – Visualización de xG y xA**  
  Curso de la Universidad de Liverpool con ejemplos prácticos de análisis posicional, xG y xA.  
  Friends of Tracking. (2020). *Expected Goals & Assists Explained*. YouTube.  
  https://www.youtube.com/watch?v=1fN7RK1gu3Y

- **Understat – Datos históricos de xA y xG**  
  Página web con métricas xA y xG por jugador, equipo y partido.  
  https://understat.com  
  Python API (no oficial): https://github.com/amosbastian/understat

## Referencias

- Singh, K. (2020). *Expected Goals (xG) Model from scratch in Python*. Medium. https://karun.in/blog/expected-goals-xg.html  
- StatsBomb. (2023). *Open Data Repository*. GitHub. https://github.com/statsbomb/open-data  
- StatsBombPy. (2023). *Python Client for StatsBomb Open Data*. GitHub. https://github.com/statsbomb/statsbombpy  
- Friends of Tracking. (2020). *Expected Goals Tutorial*. YouTube. https://www.youtube.com/watch?v=1fN7RK1gu3Y  
- FC Python. (2018). *Expected Goals (xG) Model Tutorial*. https://fcpython.com/statsbomb-xg-model-python-tutorial/  
- Understat. (2023). *Expected Goals and Assists Data*. https://understat.com  
- Bastian, A. (2020). *Python API for Understat*. GitHub. https://github.com/amosbastian/understat  
