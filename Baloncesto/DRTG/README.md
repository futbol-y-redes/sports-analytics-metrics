# DRTG

El Defensive Rating (DRTG) es la contraparte defensiva del Offensive Rating y representa uno de los intentos más importantes de cuantificar el impacto defensivo en el baloncesto. Desarrollado también por Dean Oliver como parte de su trabajo en análisis avanzado, el DRTG estima cuántos puntos permite un jugador o equipo por cada 100 posesiones defensivas. Aunque medir la defensa individual sigue siendo uno de los mayores desafíos en el análisis deportivo, el DRTG proporciona una base fundamental para evaluar el impacto defensivo, especialmente a nivel de equipo.

## ¿Qué es?

El Defensive Rating (DRTG) es una métrica que mide la eficiencia defensiva calculando cuántos puntos permite un jugador o equipo por cada 100 posesiones defensivas. Al igual que el ORTG, normaliza por posesiones en lugar de tiempo para eliminar las diferencias de ritmo de juego y proporcionar una medida pura de la efectividad defensiva.

**Fórmula básica:**
DRTG = (Puntos permitidos / Posesiones defensivas) × 100

**A nivel de equipo:**
- DRTG del equipo = (Total de puntos permitidos / Total de posesiones defensivas) × 100

**A nivel individual:**
El cálculo individual es considerablemente más complejo y controvertido:
- Se basa en las estadísticas defensivas individuales (robos, rebotes, tapones)
- Utiliza estimaciones de stops defensivos
- Se ajusta por la calidad defensiva del equipo
- Incorpora minutos jugados y contexto de equipo

**Escala de interpretación (individual):**
- <100 DRTG: Elite defensivo, impacto histórico
- 100-105 DRTG: Excelente defensor, All-Defense level
- 105-108 DRTG: Buen defensor, sobre promedio
- 108-112 DRTG: Promedio de la liga
- 112-115 DRTG: Por debajo del promedio
- 115-118 DRTG: Defensa deficiente
- >118 DRTG: Liability defensiva significativa

**Escala de interpretación (equipo):**
- <100 DRTG: Defensa histórica, elite absoluto
- 100-105 DRTG: Excelente defensa, top 5 liga
- 105-108 DRTG: Buena defensa, sobre promedio
- 108-112 DRTG: Promedio de la liga
- 112-115 DRTG: Por debajo del promedio
- >115 DRTG: Defensa deficiente

**Ejemplos históricos notables:**
- Boston Celtics (2007-08): 98.9 DRTG (equipo)
- San Antonio Spurs (2003-04): 88.4 DRTG (equipo)
- Detroit Pistons (2003-04): 90.1 DRTG (equipo)
- Ben Wallace (2003-04): 94.1 DRTG (individual)
- Tim Duncan (2002-03): 95.8 DRTG (individual)

## Importancia en el baloncesto moderno

En una era donde el análisis ofensivo ha avanzado significativamente, el DRTG representa uno de los intentos más serios de cuantificar el impacto defensivo. Aunque las limitaciones en las estadísticas defensivas tradicionales hacen que el DRTG individual sea menos preciso que su contraparte ofensiva, sigue siendo fundamental para evaluar la efectividad defensiva, especialmente cuando se combina con otras métricas y análisis visual.

El DRTG es especialmente valioso para:

**Evaluación de sistemas defensivos**: permite comparar la efectividad de diferentes esquemas defensivos normalizando por ritmo
**Análisis histórico**: facilita comparaciones de defensas entre diferentes eras del juego
**Identificación de tendencias**: ayuda a entender cómo ha evolucionado la defensa en la liga
**Evaluación contextual**: proporciona una base para análisis más profundos del impacto defensivo

## Aplicaciones

**Evaluación de sistemas defensivos**: permite comparar objetivamente la efectividad de diferentes filosofías defensivas (switching vs. drop coverage, etc.).

**Análisis de equipo**: identifica qué equipos son verdaderamente elite defensivamente una vez ajustado por ritmo de juego.

**Construcción de lineup**: ayuda a determinar qué combinaciones defensivas son más efectivas en diferentes contextos.

**Evaluación de coaching**: proporciona una métrica para evaluar la efectividad de los sistemas defensivos implementados.

**Análisis de matchups**: permite estudiar cómo diferentes estilos defensivos funcionan contra diferentes tipos de ataques.

**Identificación de impacto**: aunque imperfecto, ayuda a identificar jugadores con impacto defensivo significativo.

**Análisis situacional**: evalúa la efectividad defensiva en diferentes contextos (playoffs vs. regular season, clutch vs. non-clutch).

**Desarrollo de jugadores**: permite tracking del progreso defensivo de jugadores jóvenes dentro del contexto de equipo.

## Limitaciones

**Dependencia extrema del contexto de equipo**: el DRTG individual está fuertemente influenciado por la calidad defensiva de los compañeros.

**Estadísticas defensivas limitadas**: las stats tradicionales (robos, tapones) no capturan completamente el impacto defensivo.

**No mide defensa posicional**: no refleja la calidad de la defensa individual en situaciones específicas.

**Sesgo hacia jugadores de equipo**: jugadores en mejores defensas automáticamente tienen mejores DRTG individuales.

**No considera switching**: en la era moderna del switching, es difícil asignar responsabilidad defensiva individual.

**Limitaciones en reboteo**: el rebote defensivo influye el DRTG pero no es puramente individual.

**No captura deterrence**: el efecto disuasorio de jugadores elite no se refleja completamente.

**Variabilidad por posición**: diferentes posiciones tienen diferentes oportunidades de generar estadísticas defensivas.

**Falta de contexto de matchup**: no considera la dificultad de los jugadores defensidos.

## Recursos

**Basketball Reference – DRTG histórico completo**
Base de datos comprehensive con DRTG para todos los jugadores y equipos desde 1973-74.
https://www.basketball-reference.com/

**NBA.com/Stats – Advanced Defensive Stats**
Portal oficial con DRTG actual y herramientas de análisis defensivo avanzado.
https://www.nba.com/stats/

**Cleaning the Glass – DRTG contextualizado**
Análisis defensivo que contextualiza DRTG con otras métricas y ajustes situacionales.
https://cleaningtheglass.com/

**Second Spectrum – Advanced Defensive Analytics**
Plataforma que combina DRTG con tracking data para análisis defensivo más preciso.
https://www.secondspectrum.com/

**Synergy Sports – DRTG por tipo de defensa**
Herramientas profesionales que desglosan efectividad defensiva por situaciones específicas.
https://www.synergysports.com/

**Basketball Analytics con Python**
Tutoriales para calcular DRTG y combinar con otras métricas defensivas.
GitHub: https://github.com/swar/nba_api
Documentación: https://github.com/swar/nba_api/tree/master/docs

**Defensive Metrics Research**
Repositorio de investigación académica sobre métricas defensivas y sus limitaciones.
GitHub: https://github.com/basketballanalytics/defensive-metrics

**PBP Stats – Detailed Defensive Analysis**
Herramientas para análisis defensivo detallado usando datos play-by-play.
https://www.pbpstats.com/

## Referencias

Oliver, D. (2004). Basketball on Paper: Rules and Tools for Performance Analysis. Potomac Books.
[Introduce el concepto de Defensive Rating al baloncesto]

Kubatko, J. (2007). The Challenge of Measuring Individual Defense. APBRmetrics Research Paper.

Rosenbaum, D. T. (2004). Measuring How NBA Players Help Their Teams Win. 82games.com.

Basketball Reference. (2023). Defensive Rating Methodology and Limitations.
https://www.basketball-reference.com/about/ratings.html

Ilardi, S. & Barzilai, A. (2008). The Problem with Individual Defensive Metrics. 82games.com.

Engelmann, J. (2017). Modern Approaches to Defensive Analytics. MIT Sloan Sports Analytics Conference.

Myers, D. (2018). The Evolution of Defensive Metrics: From DRTG to Tracking Data. Basketball Analytics Quarterly.

Cervone, D. et al. (2016). A Multiresolution Stochastic Process Model for Predicting Basketball Possession Outcomes. Journal of the American Statistical Association.

Franks, A. et al. (2015). Characterizing the Spatial Structure of Defensive Skill in Professional Basketball. Annals of Applied Statistics.

Maheswaran, R. et al. (2012). Deconstructing the Rebound with Optical Tracking Data. MIT Sloan Sports Analytics Conference.