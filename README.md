# Bienvenidos a la página de GitHub del grupo FutbolyRedes

Este repositorio ha sido creado por el **grupo de investigación FutbolyRedes** de la **Universidad Rey Juan Carlos** (Madrid, España). Aquí recopilamos información sobre **métricas avanzadas** utilizadas en diferentes deportes, ofreciendo una visión general sobre cómo se analizan las actuaciones individuales y colectivas en disciplinas como el **fútbol**, el **baloncesto** y el **bádminton**.

Si te interesa el análisis deportivo basado en datos, este es tu sitio.

---
## 📌 Secciones

### [⚽ Fútbol](/Fútbol/)

El fútbol es un deporte complejo que se puede analizar desde múltiples dimensiones. Aquí te presentamos algunas de las métricas avanzadas más utilizadas en el análisis del rendimiento y la táctica:

- [**xG (Expected Goals)**](Fútbol/xG/README.md): estima la probabilidad de que un disparo termine en gol en función de variables como la distancia a portería, el ángulo del tiro y la situación de juego.
- [**xA (Expected Assists)**](Fútbol/xA/README.md): mide la probabilidad de que un pase termine en gol, permitiendo evaluar la creatividad de los jugadores.
- [**PPDA (Passes Per Defensive Action)**](Fútbol/PPDA/README.md): indica cuántos pases realiza el equipo rival antes de que se produzca una acción defensiva (presión alta o recuperación de balón).
- **Progressive Passes**: pases que avanzan el balón de manera significativa hacia la portería contraria.
- **Packing**: cuantifica cuántos jugadores rivales han sido eliminados con un pase o una conducción.
- **Possession Value Models (VAEP, Expected Threat)**: modelos que asignan un valor a cada acción en función de cómo afecta a la probabilidad de marcar o recibir un gol.

Estas métricas permiten un análisis más profundo del rendimiento individual y colectivo, y son ampliamente utilizadas en scouting, táctica y análisis post-partido.

### 🏀 Baloncesto
El baloncesto es un deporte altamente cuantificable, y el análisis avanzado ha evolucionado para ofrecer métricas que permiten evaluar con mayor precisión tanto el rendimiento individual como colectivo. Estas son algunas de las más utilizadas:

- **eFG% (Effective Field Goal Percentage)**: ajusta el porcentaje de tiros de campo para reflejar el valor adicional de los triples.
Fórmula: (FGM + 0.5 × 3PM) / FGA

- **TS% (True Shooting Percentage)**: mide la eficiencia del jugador al lanzar, considerando tiros de campo, triples y tiros libres.
Fórmula: PTS / (2 × (FGA + 0.44 × FTA))

- **PER (Player Efficiency Rating)**: métrica compuesta que resume la producción estadística de un jugador por minuto. Tiene en cuenta acciones positivas y negativas.

- **PIR (Performance Index Rating)**: común en competiciones europeas, suma estadísticas positivas y resta las negativas para valorar el rendimiento global.

- **Offensive Rating / Defensive Rating**:

    - OffRtg: estima los puntos producidos por cada 100 posesiones ofensivas.

    - DefRtg: estima los puntos permitidos por cada 100 posesiones defensivas.

- **BPM (Box Plus/Minus)**: estima el impacto de un jugador en el marcador por 100 posesiones, basado en estadísticas de caja estándar y el contexto del equipo.

- **APM (Adjusted Plus/Minus)**: mide el impacto real de un jugador en el rendimiento del equipo, ajustando por los compañeros y rivales en cancha.

- **WS (Win Shares)**: estima la cantidad de victorias en las que ha contribuido un jugador, separadas en ofensivas y defensivas.

- **Cuatro Factores de la Victoria (Four Factors)**: identificados por Dean Oliver como claves para ganar partidos: eFG%, tasa de pérdidas (turnover rate), rebote ofensivo (offensive rebound rate), tiros libres por tiro de campo (free throw rate).
- **AST/TO (assist to turnover ratio)**: relación entre asistencias y pérdidas de balón. Mide la eficiencia en la distribución del juego.

Estas métricas ofrecen una visión más profunda del impacto de los jugadores y equipos, y son fundamentales para el scouting, el análisis de partidos y la toma de decisiones estratégicas en el baloncesto moderno.

### 🏸 Bádminton

El bádminton, aunque menos estudiado en términos de métricas avanzadas que otros deportes, también cuenta con indicadores clave para evaluar el rendimiento:

- **Shot Quality Index (SQI)**: Evalúa la efectividad de cada golpe en función de su velocidad, trayectoria y efecto.
- **Rally Length Analysis**: Determina el número de golpes por intercambio y su relación con la fatiga y el rendimiento táctico.
- **Shuttle Speed Metrics**: Analiza la velocidad del volante en diferentes tipos de golpeo (smash, drop shot, clear, etc.).
- **Movement Efficiency**: Mide la distancia recorrida por el jugador y su relación con el rendimiento energético.
- **Winning Probabilities per Shot**: Modelo que estima la probabilidad de ganar un punto en función del tipo de golpeo y la posición en la cancha.

El uso de estas métricas ayuda a comprender mejor los patrones de juego, permitiendo mejorar la toma de decisiones y la planificación del entrenamiento.

---
## 💻 Software
¿Quieres implementar estas métricas por tu cuenta? Aquí tienes herramientas útiles:

- [StatsBomb Open Data Tools](https://github.com/statsbomb)
- [Open Source Soccer Analytics (FC Python)](https://fcpython.com)
- [Sports Analytics en Python y R](https://github.com/soccermatics)

---
## 📊 Datos
Si buscas datasets deportivos para hacer tus propios análisis, aquí tienes algunos recursos gratuitos:

- [StatsBomb Open Data (Fútbol)](https://github.com/statsbomb/open-data)
- [Football Data (CSV de partidos y ligas)](https://www.football-data.co.uk)
- [Badminton World Federation Data](https://bwfbadminton.com/)

---

Esperamos que este repositorio te ayude a entender mejor el uso de métricas avanzadas en el deporte. Si tienes sugerencias o quieres contribuir, ¡contáctanos o abre un issue! 🚀
