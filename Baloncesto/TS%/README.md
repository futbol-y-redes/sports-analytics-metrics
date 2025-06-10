# **TS%**

En el panorama actual del análisis de baloncesto, donde la eficiencia ofensiva se ha convertido en un factor determinante del éxito, pocas métricas son tan reveladoras como el "True Shooting Percentage" o "porcentaje de tiro verdadero", conocido como TS%. Esta métrica representa la evolución natural de las estadísticas tradicionales de tiro, incorporando todos los métodos de anotación para ofrecer la imagen más completa y precisa de la eficiencia ofensiva de un jugador o equipo. El TS% se ha establecido como el estándar de oro para evaluar la capacidad de convertir posesiones en puntos.

## ¿Qué es?

El **True Shooting Percentage (TS%)** es la métrica más comprehensiva para medir la eficiencia de tiro en baloncesto. A diferencia del FG% tradicional o incluso del eFG%, el TS% incluye todos los métodos de anotación: tiros de campo de dos puntos, triples y tiros libres, ponderados por su valor en puntos y ajustados por las posesiones utilizadas.

La fórmula del TS% es:

**TS% = Puntos totales / (2 × (Intentos de tiro de campo + 0.44 × Intentos de tiros libres))**

El factor **0.44** es una constante empírica que aproxima la relación entre tiros libres intentados y posesiones utilizadas, considerando que muchos tiros libres se producen en situaciones de "and-1" o faltas técnicas que no consumen posesiones adicionales.

Para entender mejor su valor, consideremos algunos ejemplos:

- **Jugador A**: 20 puntos en 10 tiros de campo (todos de 2), TS% = 100%
- **Jugador B**: 24 puntos en 8 triples convertidos de 10 intentos, TS% = 120%
- **Jugador C**: 25 puntos (6 de 10 en tiros de campo + 13 de 15 tiros libres), TS% ≈ 89%

## Superioridad sobre otras métricas

El TS% supera a otras métricas de eficiencia porque:

1. **Incluye tiros libres**: reconoce que generar faltas y convertir tiros libres es una habilidad valiosa
2. **Pondera correctamente**: cada método de anotación se valora según su contribución real en puntos
3. **Ajusta por posesiones**: utiliza el denominador más preciso para reflejar las oportunidades realmente consumidas
4. **Métrica unificada**: permite comparaciones directas entre jugadores con estilos completamente diferentes

Un jugador como James Harden, especialista en generar faltas, puede tener un eFG% moderado pero un TS% excelente debido a su capacidad para ir a la línea de tiros libres. Inversamente, un jugador con buen FG% pero que raramente va a la línea puede tener un TS% menos impresionante.

## Aplicaciones

1. **Evaluación integral de jugadores**: proporciona la medida más precisa de la contribución ofensiva individual, independientemente del estilo de juego.

2. **Análisis de eficiencia de equipos**: permite identificar qué equipos maximizan mejor sus posesiones ofensivas.

3. **Comparación histórica**: facilita comparaciones entre diferentes eras del baloncesto, ajustando por los cambios en el juego.

4. **Identificación de talento**: revela jugadores que pueden no destacar en estadísticas tradicionales pero son altamente eficientes.

5. **Estrategia ofensiva**: informa decisiones sobre distribución de tiros y utilización de jugadores en situaciones clave.

6. **Análisis de clutch**: evalúa la eficiencia en momentos críticos del partido.

7. **Desarrollo de jugadores**: identifica áreas específicas de mejora en la selección y conversión de tiros.

## Interpretación de valores

- **TS% > 60%**: Excelente eficiencia, nivel All-Star
- **TS% 55-60%**: Muy buena eficiencia, starter sólido
- **TS% 50-55%**: Eficiencia promedio de la liga
- **TS% 45-50%**: Eficiencia por debajo del promedio
- **TS% < 45%**: Eficiencia pobre, problemática para el equipo

Para contexto, el promedio de la NBA suele rondar el 55-57%, mientras que los mejores tiradores de élite pueden superar consistentemente el 65%.

## Limitaciones

- **No considera la dificultad de los tiros**: un triple abierto y uno muy defendido tienen el mismo peso si ambos entran.

- **Factor 0.44 es aproximado**: aunque ampliamente aceptado, puede no ser perfectamente preciso para todos los casos.

- **No incluye valor de las asistencias**: se centra únicamente en la conversión, no en la creación de juego.

- **Sensible al volumen**: pequeñas muestras pueden generar valores engañosos.

- **No considera el contexto temporal**: no diferencia entre garbage time y situaciones de alta presión.

- **Impacto de las faltas técnicas**: tiros libres de faltas técnicas pueden inflar ligeramente el TS%.

## Recursos

- **Basketball Reference – Base de datos de TS%**  
  Estadísticas históricas completas con TS% para todos los jugadores desde 1979-80.  
  https://www.basketball-reference.com/

- **NBA.com/Stats – Herramientas de análisis avanzado**  
  Plataforma oficial con filtros avanzados para TS% por situación, oponente y contexto.  
  https://www.nba.com/stats/

- **Cleaning the Glass – Análisis contextualizado**  
  Estadísticas ajustadas por ritmo y oponente, con TS% contextualizado.  
  https://cleaningtheglass.com/

- **FiveThirtyEight RAPTOR – Métricas avanzadas**  
  Incorpora TS% en sus modelos predictivos y análisis de jugadores.  
  https://projects.fivethirtyeight.com/nba-player-ratings/

- **NBA API para Python**  
  Herramientas para extraer y calcular TS% programáticamente.  
  GitHub: https://github.com/swar/nba_api  
  PyPI: https://pypi.org/project/nba-api/

- **Thinking Basketball – Análisis educativo**  
  Videos y artículos explicando la importancia del TS% en contexto.  
  YouTube: https://www.youtube.com/c/ThinkingBasketball

## Referencias

- Kubatko, J., Oliver, D., Pelton, K., & Rosenbaum, D. T. (2007). *A Starting Point for Analyzing Basketball Statistics*. Journal of Quantitative Analysis in Sports.
- Oliver, D. (2004). *Basketball on Paper: Rules and Tools for Performance Analysis*. Potomac Books.
- Hollinger, J. (2005). *Pro Basketball Forecast 2005-06*. Potomac Books.
- Rosenbaum, D. T. (2004). *Measuring How NBA Players Help Their Teams Win*. 82games.com.
- Basketball Reference. (2023). *Glossary of Basketball Statistics*. https://www.basketball-reference.com/about/glossary.html
- Engelmann, J. (2017). *A New Way to Evaluate NBA Players*. MIT Sloan Sports Analytics Conference.
- Myers, D. (2020). *The Evolution of Basketball Analytics: From Box Score to Play-by-Play*. Journal of Sports Analytics.