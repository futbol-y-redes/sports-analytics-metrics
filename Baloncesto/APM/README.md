# APM

El Adjusted Plus/Minus (APM) representa una de las métricas más sofisticadas y estadísticamente rigurosas en el análisis del baloncesto moderno. Desarrollado originalmente por Dan Rosenbaum y posteriormente refinado por diversos analistas, el APM utiliza técnicas de regresión avanzadas para aislar la contribución individual de cada jugador al rendimiento del equipo. A diferencia de métricas basadas en estadísticas de caja, el APM evalúa el impacto real en el marcador, proporcionando una medida pura del valor que cada jugador añade cuando está en la cancha.

## ¿Qué es?

El Adjusted Plus/Minus (APM) es una métrica avanzada que utiliza regresión estadística para estimar la contribución individual de un jugador por cada 100 posesiones, ajustando por la calidad de compañeros y rivales. El APM se basa en datos play-by-play para determinar exactamente quién estaba en la cancha durante cada posesión, permitiendo una evaluación más precisa del impacto individual.

La métrica se descompone en:
- **OAPM (Offensive Adjusted Plus/Minus)**: Contribución ofensiva del jugador
- **DAPM (Defensive Adjusted Plus/Minus)**: Contribución defensiva del jugador
- **APM = OAPM + DAPM**: Contribución total del jugador

**Metodología básica:**
El APM utiliza regresión ridge o LASSO para resolver la ecuación:
```
Differential = β₁(Player1) + β₂(Player2) + ... + βₙ(PlayerN) + ε
```

Donde cada βᵢ representa la contribución estimada del jugador i.

**Escala de interpretación:**
- +8.0 o superior: Elite histórico, candidato a MVP
- +6.0 a +8.0: All-Star level, impacto francamente
- +4.0 a +6.0: Muy bueno, starter de calidad
- +2.0 a +4.0: Por encima del promedio
- 0.0 a +2.0: Promedio de la liga
- -2.0 a 0.0: Por debajo del promedio
- -4.0 a -2.0: Limitaciones significativas
- -4.0 o inferior: Impacto negativo considerable

**Variantes modernas:**
- **RAPM (Regularized APM)**: Utiliza regularización para mayor estabilidad
- **Multi-year APM**: Combina múltiples temporadas para reducir ruido
- **Prior-informed APM**: Incorpora información previa (como BPM) como prior bayesiano

## Importancia en el baloncesto moderno

El APM representa el "gold standard" para medir el impacto individual en el baloncesto porque captura toda la contribución de un jugador, incluyendo aspectos que no aparecen en estadísticas tradicionales como espaciamiento, comunicación defensiva, o toma de decisiones. En una era donde el baloncesto se ha vuelto más complejo y posicional, el APM proporciona la evaluación más pura del valor real de un jugador.

El APM es especialmente valioso para:

**Evaluación pura de impacto**: mide directamente cómo cambia el rendimiento del equipo con la presencia del jugador
**Identificación de valor oculto**: revela jugadores que contribuyen significativamente sin generar estadísticas llamativas
**Análisis defensivo**: proporciona la mejor métrica disponible para evaluar el impacto defensivo individual
**Validación de otras métricas**: sirve como referencia para validar métricas basadas en estadísticas de caja

## Aplicaciones

**Evaluación de jugadores**: permite identificar quién realmente ayuda a ganar partidos, independientemente de sus estadísticas individuales.

**Decisiones de rotación**: informa sobre qué combinaciones de jugadores son más efectivas y qué jugadores optimizan el rendimiento del equipo.

**Análisis de intercambios**: proporciona la evaluación más objetiva del valor real de intercambio de cada jugador.

**Identificación de especialistas**: revela jugadores que son especialmente valiosos en roles específicos (defense, spacing, etc.).

**Evaluación de sistemas**: ayuda a entender qué jugadores funcionan mejor en diferentes esquemas tácticos.

**Desarrollo de talento**: identifica áreas específicas donde los jugadores jóvenes están contribuyendo o necesitan mejorar.

**Análisis de contratos**: proporciona la base más sólida para evaluar si el salario de un jugador corresponde a su contribución real.

**Construcción de plantilla**: informa sobre qué tipos de jugadores se complementan mejor para maximizar el rendimiento del equipo.

## Limitaciones

**Tamaño de muestra**: requiere grandes cantidades de datos para ser confiable, especialmente problemático para rookies o jugadores con minutos limitados.

**Ruido estadístico**: extremadamente volátil en muestras pequeñas, requiere múltiples temporadas para estabilizarse.

**Multicolinealidad**: jugadores que siempre juegan juntos pueden tener estimaciones imprecisas debido a la dificultad de separar sus contribuciones.

**Sesgo de lineup**: puede estar influenciado por las decisiones de rotación del entrenador y la calidad general de la plantilla.

**Complejidad computacional**: requiere técnicas estadísticas avanzadas y grandes datasets para calcular correctamente.

**Dependencia temporal**: los resultados pueden cambiar significativamente al añadir o quitar partidos de la muestra.

**Efectos de interacción**: no captura completamente cómo ciertos jugadores se potencian mutuamente (chemistry effects).

**Regresión a la media**: valores extremos tienden a moderarse con muestras más grandes, lo que puede subestimar a jugadores verdaderamente elite.

## Recursos

**NBA.com/Stats – Tracking Data**
Fuente oficial de datos play-by-play necesarios para cálculos APM, incluyendo lineup data.
https://www.nba.com/stats/

**Cleaning the Glass – APM Analysis**
Sitio especializado que publica estimaciones APM regulares y análisis contextualizado.
https://cleaningtheglass.com/

**PBP Stats – Play-by-Play Data**
Herramientas y APIs para acceder a datos play-by-play detallados necesarios para APM.
https://github.com/dblockil42/basketball_reference_scraper

**Basketball Analytics con R**
Tutoriales específicos para implementar APM usando regresión ridge y LASSO.
GitHub: https://github.com/rajshah4/BasketballAnalytics

**APM Calculator Tools**
Implementaciones open-source de diferentes variantes de APM (RAPM, Multi-year, etc.).
GitHub: https://github.com/EvanZ/nba-api-plus-minus

**Academic Papers on APM**
Repositorio de papers académicos sobre metodología APM y sus refinamientos.
https://www.sloansportsconference.com/

**Basketball Study Hall – APM Deep Dives**
Análisis técnico y explicaciones metodológicas detalladas sobre APM.
https://www.basketballstudyhall.com/

**Kaggle – Advanced Basketball Datasets**
Datasets con datos play-by-play y lineup data para practicar implementaciones APM.
https://www.kaggle.com/datasets/nathanlauga/nba-games

## Referencias

Rosenbaum, D. T. (2004). Measuring How NBA Players Help Their Teams Win. 82games.com.
http://www.82games.com/comm30.htm

Ilardi, S. & Barzilai, A. (2008). Adjusted Plus-Minus Ratings: New and Improved for 2007-08. 82games.com.

Sill, J. (2010). Improved NBA Adjusted +/- using Regularization and Out-of-Sample Testing. MIT Sloan Sports Analytics Conference.

Engelmann, J. (2017). A New Age of Adjusted Plus-Minus. MIT Sloan Sports Analytics Conference.

Macdonald, B. (2011). Adjusted Plus-Minus for NHL Players using Ridge Regression with Goals, Shots, Fenwick, and Corsi. Journal of Quantitative Analysis in Sports.

Myers, D. (2015). Regularized Adjusted Plus-Minus: A Novel Approach to Player Evaluation. APBRmetrics Research.

Kubatko, J. & Oliver, D. (2013). A Starting Point for Analyzing Basketball Statistics. Journal of Quantitative Analysis in Sports.

Fearnhead, P. & Taylor, B. M. (2011). On Estimating the Ability of NBA Players. Journal of Quantitative Analysis in Sports.

Deshpande, S. K. & Jensen, S. T. (2016). Estimating an NBA player's impact on his team's chances of winning. Journal of Quantitative Analysis in Sports.