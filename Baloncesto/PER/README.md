# **PER**

En la búsqueda por una métrica que capture la contribución total de un jugador de baloncesto en una sola cifra, pocas han sido tan influyentes como el "Player Efficiency Rating", conocido universalmente como PER. Desarrollado por el analista John Hollinger a finales de los años 90, el PER representó una revolución en el análisis del baloncesto al intentar condensar todas las contribuciones estadísticas de un jugador en una métrica unificada y estandarizada. Aunque ha evolucionado y encontrado competidores más sofisticados, el PER sigue siendo una referencia fundamental en el análisis moderno del baloncesto profesional.

## ¿Qué es?

El **Player Efficiency Rating (PER)** es una métrica que intenta medir la producción total de un jugador por minuto jugado, ajustada por el ritmo del equipo y estandarizada de manera que el promedio de la liga sea siempre 15.0. El PER incorpora prácticamente todas las estadísticas de la caja de estadísticas, tanto positivas como negativas, para generar una calificación única que permite comparar jugadores independientemente de su posición, estilo de juego o minutos jugados.

La fórmula completa del PER es extremadamente compleja e incluye múltiples pasos:

1. **Cálculo del uPER (PER no ajustado)**:
   - Combina estadísticas positivas: puntos, rebotes, asistencias, robos, tapones
   - Resta estadísticas negativas: pérdidas de balón, faltas, tiros fallados
   - Aplica factores de ponderación específicos para cada estadística

2. **Ajuste por ritmo**: se normaliza por las posesiones del equipo para eliminar el sesgo de equipos que juegan más rápido

3. **Estandarización de la liga**: se ajusta para que el promedio de la liga sea exactamente 15.0

**Fórmula simplificada conceptual**:
```
PER = (Contribuciones positivas - Contribuciones negativas) / Minutos × Factor de ajuste
```

Donde las contribuciones incluyen todas las estadísticas principales ponderadas por su impacto estimado en el éxito del equipo.

## Interpretación de valores

El PER utiliza una escala donde 15.0 es siempre el promedio de la liga:

- **PER > 30**: Histórico, nivel de leyenda (Jordan, LeBron, Shaq en sus mejores temporadas)
- **PER 25-30**: MVP candidato, temporada excepcional
- **PER 20-25**: All-Star, jugador de élite
- **PER 17-20**: Starter sólido, por encima del promedio
- **PER 15-17**: Ligeramente por encima del promedio
- **PER 12-15**: Por debajo del promedio, rol player
- **PER < 12**: Contribución cuestionable

Para contexto histórico, Michael Jordan tiene el PER más alto de una temporada (31.7 en 1987-88), mientras que jugadores como LeBron James, Shaquille O'Neal y Wilt Chamberlain han tenido múltiples temporadas por encima de 30.

## Fortalezas del PER

1. **Métrica unificada**: condensa múltiples aspectos del juego en un solo número fácil de interpretar.

2. **Ajustado por minutos**: permite comparar jugadores con diferentes cargas de minutos.

3. **Ajustado por ritmo**: elimina el sesgo hacia equipos que juegan más posesiones.

4. **Ampliamente adoptado**: reconocido y utilizado por medios, equipos y aficionados.

5. **Datos históricos**: disponible para todas las temporadas desde 1951-52.

6. **Fácil de comunicar**: un solo número que resume la efectividad general.

## Aplicaciones

1. **Comparación de jugadores**: evalúa jugadores de diferentes posiciones y estilos en una escala común.

2. **Análisis de temporada**: identifica las mejores y peores temporadas individuales de la historia.

3. **Evaluación de rendimiento**: mide la consistencia y evolución de jugadores a lo largo del tiempo.

4. **Análisis de valor**: ayuda a determinar si un jugador está siendo utilizado eficientemente.

5. **Contexto histórico**: facilita comparaciones entre diferentes eras del baloncesto.

6. **Identificación de breakout seasons**: detecta mejoras significativas en el rendimiento.

7. **Análisis de lesiones**: evalúa el impacto de lesiones en el rendimiento general.

## Limitaciones

- **Sesgo ofensivo**: sobrevalora las estadísticas ofensivas y puede subestimar especialistas defensivos.

- **No captura defensa individual**: muchas contribuciones defensivas no aparecen en estadísticas tradicionales.

- **Ponderaciones arbitrarias**: los pesos asignados a cada estadística pueden no reflejar su verdadero valor.

- **Sensible al contexto del equipo**: jugadores en equipos mejores pueden tener PER inflado por mejor eficiencia.

- **No considera clutch performance**: trata todos los minutos por igual, sin importar la situación del partido.

- **Estadísticas de caja limitadas**: ignora aspectos como espaciamiento, química de equipo, o liderazgo.

- **Puede penalizar especialistas**: jugadores con roles muy específicos pueden ser subestimados.

## Evolución y alternativas modernas

Aunque el PER fue revolucionario, el análisis moderno ha desarrollado métricas más sofisticadas como:

- **BPM (Box Plus/Minus)**: incorpora análisis de regresión más avanzado
- **VORP (Value Over Replacement Player)**: mide valor sobre un jugador de reemplazo
- **Win Shares**: estima contribución a las victorias del equipo
- **RAPTOR y EPM**: utilizan datos de tracking y play-by-play

Sin embargo, el PER mantiene su relevancia por su simplicidad conceptual y amplia adopción.

## Recursos

- **Basketball Reference – Datos históricos de PER**  
  Base de datos completa con PER de todos los jugadores desde 1951-52.  
  https://www.basketball-reference.com/

- **John Hollinger – Creador del PER**  
  Explicaciones originales y refinamientos de la métrica por su creador.  
  ESPN: https://www.espn.com/nba/hollinger/statistics

- **NBA.com/Stats – PER y métricas avanzadas**  
  Herramientas oficiales para filtrar y analizar PER por contexto.  
  https://www.nba.com/stats/

- **Cleaning the Glass – PER contextualizado**  
  Análisis de PER ajustado por oponente y situación.  
  https://cleaningtheglass.com/

- **Basketball Analytics con Python**  
  Tutoriales para calcular PER y métricas relacionadas.  
  GitHub: https://github.com/swar/nba_api

- **Sports Reference Blog – Análisis de PER**  
  Artículos técnicos sobre limitaciones y aplicaciones del PER.  
  https://www.sports-reference.com/blog/

## Referencias

- Hollinger, J. (2004). *Pro Basketball Forecast 2004-05*. Potomac Books.
- Hollinger, J. (2005). *Pro Basketball Prospectus 2005-06*. Potomac Books.
- Oliver, D. (2004). *Basketball on Paper: Rules and Tools for Performance Analysis*. Potomac Books.
- Kubatko, J. (2007). *Starting Point for Analyzing Basketball Statistics*. Journal of Quantitative Analysis in Sports.
- Basketball Reference. (2023). *PER Explanation and Historical Data*. https://www.basketball-reference.com/about/per.html
- Rosenbaum, D. T. (2004). *Measuring How NBA Players Help Their Teams Win*. 82games.com.
- Myers, D. (2020). *The Evolution of Basketball Analytics: Beyond Traditional Metrics*. Journal of Sports Analytics.
- Engelmann, J. (2017). *Modern Basketball Analytics: From PER to Player Tracking*. MIT Sloan Sports Analytics Conference.