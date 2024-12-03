# Análisis del Dilema del Prisionero y la Racionalidad Limitada

## Descripción

Este proyecto explora el concepto de **racionalidad limitada** a través de la simulación de un **juego iterado del dilema del prisionero**. Utilizando el dilema del prisionero como caso de estudio, se busca ejemplificar cómo las decisiones de los jugadores, influenciadas por la incertidumbre y los resultados pasados, evolucionan a lo largo del tiempo.

En este análisis, se ha implementado un **dashboard interactivo** para visualizar cómo las probabilidades de cooperación de los jugadores cambian a lo largo de 300 rondas de juego, basadas en el aprendizaje y adaptación a los pagos y decisiones del oponente.

## Objetivos

1. **Demostrar la racionalidad limitada**: A través de la simulación de decisiones en el dilema del prisionero, el objetivo es mostrar cómo los jugadores ajustan sus estrategias en función de la información imperfecta y los pagos obtenidos en rondas previas.
2. **Visualización de la evolución de las decisiones y pagos**: Mediante gráficos interactivos, se ilustra cómo las decisiones de los jugadores (cooperar o traicionar) y los pagos acumulados evolucionan a lo largo del juego.
3. **Exhibir las probabilidades de cooperación**: El comportamiento de cada jugador se muestra en función de las probabilidades de cooperación que cambian dinámicamente con cada ronda.

## Tecnologías Utilizadas

- **R**: Lenguaje de programación utilizado para la simulación y creación de visualizaciones.
- **ggplot2**: Paquete de R para la creación de gráficos.
- **flexdashboard**: Herramienta utilizada para construir el dashboard interactivo.
- **DT**: Paquete de R para la visualización de tablas interactivas.
- **dplyr y reshape2**: Paquetes para la manipulación de datos.

## Instrucciones de Uso

### 1. Ejecución del código

El código de simulación está estructurado para simular 300 rondas de un juego iterado del dilema del prisionero, donde dos jugadores ajustan sus probabilidades de cooperación basándose en los resultados previos.

### 2. Interactividad

#### En el dashboard, encontrarás:

- Gráficos de la evolución de las probabilidades de cooperación: Muestra cómo las probabilidades de cooperación de cada jugador cambian a lo largo de las rondas.
- Gráficos de decisiones acumulativas: Representa las decisiones acumulativas de cooperación y traición para cada jugador.
- Gráficos de los pagos acumulados: Muestra cómo los pagos de cada jugador se acumulan durante el juego.
- Tabla de historial: Presenta una tabla interactiva con el historial de decisiones y pagos de cada jugador en cada ronda.
### 3. Resultados 

Al ejecutar la simulación, se observará cómo las estrategias de los jugadores evolucionan con el tiempo, adaptándose a las decisiones previas y los pagos obtenidos. Este comportamiento refleja el concepto de racionalidad limitada, ya que los jugadores toman decisiones no perfectas basadas en la información incompleta disponible en cada momento.

### 4. Conclusión

Este trabajo demuestra cómo el dilema del prisionero puede ser utilizado para ilustrar la racionalidad limitada, un concepto clave en la teoría de juegos y la toma de decisiones. A través de la simulación interactiva, se pueden observar cómo las decisiones de los jugadores cambian a lo largo del tiempo y cómo estos ajustes reflejan su capacidad limitada para procesar toda la información disponible.



