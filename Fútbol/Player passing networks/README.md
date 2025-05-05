# Redes de pases en fútbol

El análisis táctico en el fútbol ha evolucionado con la incorporación de herramientas matemáticas y computacionales, entre las cuales destaca la **teoría de grafos**. Esta permite representar e interpretar el flujo de juego de un equipo mediante **redes de pases**, donde cada jugador se modela como un nodo y cada pase como una arista (o conexión) entre nodos. Esta representación facilita el análisis estructural del comportamiento colectivo de un equipo, revelando patrones de posesión, asociaciones frecuentes, zonas de mayor actividad y centralidad de ciertos jugadores en el sistema táctico.

## ¿Qué son?

Una **red de pases** es una estructura matemática que modela las interacciones entre los jugadores de un equipo mediante una representación tipo grafo. Formalmente, una red de pases puede ser definida como un grafo dirigido y ponderado:

- **Dirigido**: cada pase va desde un jugador (origen) hacia otro (destino).
- **Ponderado**: cada conexión puede tener un peso, usualmente el número de veces que se ha producido ese pase.

### Componentes básicos:

- **Nodos (vértices)**: representan a los jugadores.
- **Aristas (enlaces)**: representan pases entre jugadores.
- **Peso de las aristas**: puede indicar la frecuencia o la calidad de los pases (por ejemplo, pases clave, asistencias, expected assists, etc.).
- **Posición de los nodos**: puede fijarse usando las posiciones promedio desde las cuales un jugador entrega o recibe pases.

Este enfoque permite visualizar cómo se organiza un equipo durante la posesión del balón y detectar posibles dependencias, rigideces estructurales o fortalezas en el juego asociativo.

## Aplicaciones

1. **Análisis táctico**: Determinar qué jugadores están más involucrados en la distribución del balón.
2. **Centralidad y roles**: Medir la influencia relativa de un jugador dentro del flujo de juego mediante métricas como *degree centrality*, *betweenness centrality*, o *eigenvector centrality*.
3. **Comparación entre partidos o equipos**: Observar cómo cambia la estructura de juego según el rival, resultado, o formación táctica.
4. **Identificación de cuellos de botella**: Detectar zonas donde el balón se circula demasiado o donde se rompe la fluidez.
5. **Apoyo a *scouting* y reclutamiento**: Mediante el análisis de cómo se integran jugadores a la red colectiva.

Algunas de las métricas comunes de la teoría de grafos que se aplican al fútbol son:

- ***Degree centrality***: número de conexiones de un nodo.
- ***Betweenness centrality***: mide cuántas veces un jugador actúa como puente en la red.
- ***Clustering coefficient***: indica el nivel de cooperación entre grupos de jugadores.
- ***Density***: nivel de conectividad global de la red.
- ***Eigenvector centrality***: mide la influencia de un nodo considerando también la importancia de sus vecinos.

## Limitaciones

- **No mide calidad del pase**: un pase frecuente no es necesariamente un pase efectivo.
- **No considera contexto defensivo**: no se incorpora la presión rival o la posición del oponente.
- **Dependencia del contexto posicional**: una red de pases cambia significativamente según la táctica empleada, el rival o la situación del partido.

## Recursos

### 1. **FC Python – Redes de Pases básicas con `networkx`**
Tutorial introductorio para construir una red de pases con datos de StatsBomb.  
🔗 https://fcpython.com/visualisation/passing-networks

### 2. **Friends of Tracking – Redes de pases con posicionamiento**
Explicación en YouTube de cómo construir redes que incorporan la posición media de los jugadores.  
🔗 https://www.youtube.com/watch?v=5nUuBjY3v40

### 3. **StatsBomb – Open Data**
Puedes descargar los datos de eventos necesarios para construir redes de pases con Python.  
🔗 https://github.com/statsbomb/open-data  
Cliente en Python: https://github.com/statsbomb/statsbombpy

### 4. **Friends of Tracking GitHub**
Incluye notebooks para redes de pases, mapas de calor y mucho más.  
🔗 https://github.com/Friends-of-Tracking-Data-FoTD

## Referencias

- FC Python. (2019). *Passing Networks in Football using Python*. https://fcpython.com/visualisation/passing-networks  
- Friends of Tracking. (2020). *Football Passing Networks with Player Positions*. YouTube. https://www.youtube.com/watch?v=5nUuBjY3v40  
- StatsBomb. (2023). *Open Data Repository*. GitHub. https://github.com/statsbomb/open-data  
- StatsBombPy. (2023). *Python Client for StatsBomb Data*. GitHub. https://github.com/statsbomb/statsbombpy  
- Bastian, A. (2020). *Python API for Understat*. GitHub. https://github.com/amosbastian/understat  
