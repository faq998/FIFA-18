# FIFA-18
![For Loop Image](https://github.com/faq998/Im-genes/raw/main/FIFA_18_Logo.png)

En este repositorio se intentará determinar cuáles son las variables que entran en juego, viendo cuáles son las más importantes y poder analizar en profundidad el desempeño de los jugadores de las ligas más importantes del mundo de acuerdo a la información aportada por FIFA del año 2018.


## Introducción
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/DALLE2~1.WEB)

Este proyecto tiene como objetivo realizar un proceso de Extracción, Transformación y Carga (ETL) seguido de un Análisis Exploratorio de Datos (EDA). 
El ETL se encarga de procesar la información cruda, y el EDA permite obtener una comprensión más profunda de los datos mediante la visualización y análisis de patrones clave.

## Alcances del Proyecto
El proyecto cubre las siguientes fases principales:
1. **ETL**: En esta fase, los datos son extraídos de la fuente original, transformados para adecuarlos a los análisis posteriores, y finalmente cargados para su procesamiento.
2. **EDA**: Una vez que los datos han sido procesados, se realiza un análisis exploratorio que incluye la identificación de patrones, correlaciones y posibles outliers.

## Stack Tecnológico
Para llevar a cabo este proyecto, se ha utilizado el siguiente stack tecnológico:
- **Lenguajes**: Python
- **Librerías**:
  - `sqlalchemy`: Manejo de conexiones a bases de datos y consultas SQL.
  - `pandas`: Para la manipulación y análisis de datos estructurados en formato de DataFrame.
  - `numpy`: Cálculos numéricos y operaciones con arrays.
  - `matplotlib` y `seaborn`: Para la visualización de los datos y la creación de gráficos.
  - `sklearn`: Implementación de algoritmos de aprendizaje automático, como la regresión lineal.


## Conclusiones respecto a las fuentes de información
<img src="https://github.com/faq998/Im-genes/blob/main/Regresi%C3%B3n%20Habilidades%20vs%20Valor%20de%20Mercado.png" alt="Regresión de habilidades vs Valor Mercado" width="500">

- Se observa que las habilidades cuyo incremento generan un mayor incremento en la valoración que el mercado realiza de los jugadores (pendiente de las rectas) son el regate, la finalización y el poder de remate. Estas habilidades tienen en común que generalmente se asocian a jugadores ofensivos.
- En un segundo grupo se observan la agilidad, la velocidad y la capacidad de intercepción.
- En un tercer grupo, como habilidad menos valorada se observa la capacidad de marca, ligada fundamentalmente a jugadores defensivos.
- Se conlcuye entonces que los jugadores mejores valorados en términos económicos por el mercado, son aquellos que destacan en habilidades ofensivas, como son delanteros y mediocampistas de ataque. En contrapartida, los defensores o mediocampistas asociados a habilidades defensivas, son menos valorados económicamente por el mercado.
  
<img src="https://github.com/faq998/Im-genes/blob/main/Valor%20Mercado%20vs%20Overall.png" alt="Mejor inversión por jugador" width="500">
- Neymar demuestra tener una mejor relacion Value/Overall, lo cual determina que para realizar una inversión en jugadores, él sería la mejor y no Cristiano Ronaldo (según FIFA). 

<img src="https://github.com/faq998/Im-genes/blob/main/Clubes.png" alt="Mejores jugadores por posición" width="500">

- La relación entre "Overall"  valor de mercado ("Value") nos permite hacer una comparación de acuerdo a cada una de las posiciones.
- Esto nos deja ver qué jugadores por posición se centra cada club en adquirir, y determinar si vale o no la pena realizar la inversión.
- El Real Madrid tiene las mejores inversiones en Defensa y Mediocampo.
- El Bayern Munich en Arquero y Delantero.
- Barcelona en Defensa, Mediocampo y Delantera.
- El Chelsea en Defensa.
- Paris Saint Germain (Neymar) en Delantera.
- Atlético Madrid en Defensa con tareas Ofensivas (Carrilero izquierdo).
- Por último el Manchester City con mejores inversiones en Mediocampo, Delantera y Defensa (Carrilero derecho).

- Finalmente se observa que hay jugadores con un alto nivel en donde pueden jugar en distintas posiciones siendo los mejores y a un valor de mercado subestimado, tales como Luis Suárez y Kevin De Bruyne.


## Conclusiones finales 
Este proyecto ha permitido obtener insights clave a partir de los datos procesados. 
El uso del ETL facilitó la preparación de los datos para un análisis más profundo, mientras que el EDA brindó visualizaciones claras de patrones y relaciones significativas en los datos. 
Se sugiere que el siguiente paso sea realizar un análisis predictivo más avanzado, así como optimizar las transformaciones de datos para mejorar el rendimiento.

