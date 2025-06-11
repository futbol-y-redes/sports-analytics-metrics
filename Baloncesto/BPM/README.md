# BPM

El Box Plus/Minus (BPM) representa uno de los avances más significativos en las métricas de impacto global en el baloncesto moderno. Desarrollado por Daniel Myers y posteriormente refinado por la comunidad analítica, el BPM estima la contribución de un jugador por cada 100 posesiones comparado con un jugador promedio de la liga. Esta métrica todo-en-uno captura tanto el impacto ofensivo como defensivo, proporcionando una evaluación integral del valor de un jugador más allá de las estadísticas tradicionales.

## ¿Qué es?

El Box Plus/Minus (BPM) es una métrica avanzada que estima la contribución de un jugador por cada 100 posesiones en comparación con un jugador promedio de la liga (establecido en 0.0). El BPM utiliza únicamente estadísticas de caja (box score) para calcular tanto el impacto ofensivo (OBPM) como defensivo (DBPM), combinándolos en una métrica integral.

La métrica se compone de:
- **OBPM (Offensive Box Plus/Minus)**: Impacto ofensivo del jugador
- **DBPM (Defensive Box Plus/Minus)**: Impacto defensivo del jugador  
- **BPM = OBPM + DBPM**: Impacto total del jugador

**Escala de interpretación:**
- +10.0 o superior: MVP level, históricamente dominante
- +8.0 a +10.0: Candidato a MVP, elite absoluto
- +6.0 a +8.0: All-Star level, jugador francamente
- +4.0 a +6.0: Muy bueno, starter sólido
- +2.0 a +4.0: Por encima del promedio
- 0.0 a +2.0: Promedio de la liga
- -2.0 a 0.0: Por debajo del promedio
- -2.0 o inferior: Jugador de rotación limitada

**Ejemplos históricos:**
- Michael Jordan (1988-89): +12.1 BPM
- LeBron James (2008-09): +11.7 BPM  
- Stephen Curry (2015-16): +11.4 BPM
- Giannis Antetokounmpo (2019-20): +11.1 BPM

## Importancia en el baloncesto moderno

En una era donde el baloncesto se ha vuelto más complejo y multifacético, el BPM ofrece una métrica unificada que captura la contribución total de un jugador. A diferencia de métricas que requieren datos de tracking o play-by-play, el BPM utiliza únicamente estadísticas de caja, haciéndolo accessible para análisis histórico y comparaciones a través del tiempo.

El BPM es especialmente valioso para:

**Evaluación integral**: proporciona una sola métrica que encapsula tanto offense como defense
**Comparaciones históricas**: permite comparar jugadores de diferentes eras usando datos consistentes
**Identificación de valor oculto**: revela jugadores que contribuyen más allá de las estadísticas básicas
**Análisis de impacto**: cuantifica cómo la presencia de un jugador afecta el rendimiento del equipo

## Aplicaciones

**Evaluación de jugadores**: permite comparar jugadores con roles completamente diferentes usando una métrica común que captura su valor total.

**Análisis de roster**: ayuda a identificar qué combinaciones de jugadores maximizan el impacto colectivo del equipo.

**Decisiones de intercambios**: informa sobre el valor real que cada jugador aporta, más allá de su reputación o estadísticas tradicionales.

**Desarrollo de talento**: identifica áreas específicas donde un jugador puede mejorar su impacto (offense vs defense).

**Análisis histórico**: permite estudiar la evolución del juego y comparar jugadores de diferentes épocas.

**Evaluación de contratos**: proporciona contexto sobre si el salario de un jugador corresponde a su contribución real.

**Identificación de tendencias**: ayuda a entender cómo diferentes estilos de juego impactan el rendimiento del equipo.

## Limitaciones

**Dependencia de estadísticas de caja**: no captura contribuciones que no aparecen en el box score, como espaciamiento ofensivo o comunicación defensiva.

**Sesgo hacia jugadores de alto uso**: puede favorecer a jugadores que manejan más el balón y generan más estadísticas.

**Limitaciones defensivas**: el DBPM es menos preciso que el OBPM debido a las limitaciones de las estadísticas defensivas tradicionales.

**No considera contexto de equipo**: no ajusta completamente por la calidad de los compañeros o el sistema de juego.

**Tamaño de muestra**: puede ser volátil para jugadores con minutos limitados o temporadas cortas.

**No es predictivo**: es una métrica descriptiva que no necesariamente predice rendimiento futuro.

**Sesgos de posición**: puede estar sesgado hacia ciertas posiciones que naturalmente acumulan más estadísticas.

## Recursos

**Basketball Reference – Estadísticas completas de BPM**
Base de datos comprehensive con BPM histórico para todos los jugadores de la NBA desde 1973-74.
https://www.basketball-reference.com/

**NBA.com/Stats – Herramientas de análisis avanzado**
Portal oficial con estadísticas avanzadas incluyendo BPM y herramientas de filtrado por temporada.
https://www.nba.com/stats/

**Cleaning the Glass – Análisis contextualizado**
Sitio especializado que proporciona BPM ajustado y análisis contextual de la métrica.
https://cleaningtheglass.com/

**Basketball Analytics con Python**
Tutoriales para calcular BPM y análisis correlacionados usando APIs de datos NBA.
GitHub: https://github.com/swar/nba_api
Documentación: https://github.com/swar/nba_api/tree/master/docs

**BPM Calculator Tool**
Herramienta online para calcular BPM manualmente y entender los componentes de la fórmula.
https://www.basketball-reference.com/about/bpm2.html

**Kaggle – Datasets avanzados de baloncesto**
Conjuntos de datos con métricas avanzadas para practicar análisis de BPM y correlaciones.
https://www.kaggle.com/datasets/justinas/nba-players-data

**Basketball Study Hall**
Análisis académico y explicaciones detalladas de métricas avanzadas incluyendo BPM.
https://www.basketballstudyhall.com/

## Referencias

Myers, D. (2014). A New Way to Evaluate NBA Players: Box Plus/Minus. APBRmetrics.
https://www.basketball-reference.com/about/bpm2.html

Rosenbaum, D. T. (2004). Measuring How NBA Players Help Their Teams Win. 82games.com.

Kubatko, J. (2007). Introducing... Box Plus/Minus. Basketball Reference Blog.

Basketball Reference. (2023). Box Plus/Minus Methodology. 
https://www.basketball-reference.com/about/bpm2.html

Myers, D. (2020). Box Plus/Minus 2.0: Refinements and Improvements. APBRmetrics Annual Research Paper.

Engelmann, J. (2017). A New Player Evaluation Technique. MIT Sloan Sports Analytics Conference.

Ilardi, S. & Barzilai, A. (2008). Adjusted Plus-Minus Ratings: New and Improved for 2007-08. 82games.com.

Fearnhead, P. & Taylor, B. M. (2011). On Estimating the Ability of NBA Players. Journal of Quantitative Analysis in Sports.