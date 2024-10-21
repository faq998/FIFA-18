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


## Análisis respecto a las fuentes de información

### Comparativa delanteros
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/Comparativa%20delanteros.png)
- La gráfica permite concluir cuales son las habilidades fuertes y las no tan fuertes de cada jugador comparándolo con los restantes 4 mejores en su posición.
- Por ejemplo, Messi destaca respecto a los demás en regate y Ronaldo destaca en poder de remate como puntos favorables.
- Por otro lado, se pueden ver puntos no tan fuertes de algunos jugadores, como la velocidad de Suarez o el poder de remate de Neymar.


### Regresión de habilidades vs Valor Mercado
<img src="https://github.com/faq998/Im-genes/blob/main/Regresi%C3%B3n%20Habilidades%20vs%20Valor%20de%20Mercado.png" alt="Regresión de habilidades vs Valor Mercado" width="1000">

- Se observa que las habilidades cuyo incremento generan un mayor incremento en la valoración que el mercado realiza de los jugadores (pendiente de las rectas) son el regate, la finalización y el poder de remate. Estas habilidades tienen en común que generalmente se asocian a jugadores ofensivos.
- En un segundo grupo se observan la agilidad, la velocidad y la capacidad de intercepción.
- En un tercer grupo, como habilidad menos valorada se observa la capacidad de marca, ligada fundamentalmente a jugadores defensivos.
- Se conlcuye entonces que los jugadores mejores valorados en términos económicos por el mercado, son aquellos que destacan en habilidades ofensivas, como son delanteros y mediocampistas de ataque. En contrapartida, los defensores o mediocampistas asociados a habilidades defensivas, son menos valorados económicamente por el mercado.

### Mejor inversión por jugador
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/Valor%20Mercado%20vs%20Overall.png)
- Neymar demuestra tener una mejor relacion Value/Overall, lo cual determina que para realizar una inversión en jugadores, él sería la mejor y no Cristiano Ronaldo (según FIFA). 


### Mejores jugadores por posición
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/Clubes.png)

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

### Distribución de jugadores por edad
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/Potencial%20por%20edad.png)

<p>Referido al potencial de un jugador según su edad, no es lo mismo contar en la plantilla con una "Joven promesa" (con todo el potencial a desarrollar a lo largo de su carrera), con la rentabilidad de un jugador en edad de "Máximo potencial" ni con el valor decreciente de un jugador "Cercano al retiro".</p>
<p>Para ello, este dataset se dividió segun posición de jugador en el campo de juego (defensa,mediocampo y delantero) y según potencial por edad (mencionados anteriormente).</p>
<p>Como principal hallazgo, se encontro una frecuencia relativa similar, siendo que la mayoria de los sujetos (en las 3 zonas del campo) correspondían a la categoría "Máximo potencial", y en menor medida aquellos "Cercanos al retiro".</p>

### Joven promesa
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/joven%20promesa.png)

### Máximo potencial
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/maximo%20potencial.png)

### Cercano al retiro
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/cercano%20al%20retiro.png)


<p>En base a la division anteriormente descripta, se buscó indagar los principales 5 jugadores por cada posición, como asi tambien por potencial según edad.</p>
<p>La finalidad de la misma fue notar visualmente (empleando gráficos de barras) aquellos jugadores mejor puntuados segun su posición en el campo (como una guía rapida sobre jugadores a fichar según zona de juego, teniendo en cuenta potencial a futuro, condicionado por edad).</p>


### Arqueros
![For Loop Image](https://github.com/faq998/Im-genes/blob/main/Distribucion%20por%20arqueros.png)

![For Loop Image](https://github.com/faq998/Im-genes/blob/main/mejores%20arqueros%20por%20potencial.png)


<p>Por último, el siguiente gráfico de barras muestra los 5 principales jugadores según potencial por edad para la posición de arquero.</p>
<p>A diferencia de los "barplot" anteriores, a simple vista, podemos notar un aumento en la habilidad de "GK" a medida que aumenta la edad, posiblemente por la adquisición de experiencia a lo largo de los años, y al ser una posición donde las aptitudes físicas no son tan determinantes (en contraposición de la demandante resistencia de las demas zonas del campo).</p>


## Conclusiones del Proyecto FIFA 18

### 1. Máximo Valor de Talento por Posición Preferida
- A partir del análisis de los datos de FIFA 18, se ha observado que ciertos jugadores tienen un valor de talento máximo en sus posiciones preferidas. Esto sugiere una relación clara entre las posiciones de campo y la valorización de los jugadores en el contexto del juego.
- Los jugadores que destacan por su "Valor de Talento" máximo suelen pertenecer a equipos reconocidos internacionalmente, como Chelsea, París Saint-Germain, Atlético de Madrid y Manchester City. Esto indica que los equipos de élite en el fútbol global tienden a tener jugadores que lideran en talento en sus respectivas posiciones.

### 2. Diferencias por Posiciones
- **Delantera**: Las posiciones de delanteros (ST, CF) muestran una fuerte presencia de jugadores con valores altos de talento, lo que refleja la importancia de los atacantes en la dinámica del juego. Jugadores como **Luis Suárez** sobresalen en estas posiciones.
- **Mediocampo**: Los centrocampistas (CM, CAM, CDM) también son jugadores clave, especialmente aquellos que pueden realizar transiciones rápidas entre defensa y ataque. Jugadores como **K. De Bruyne** y **T. Kroos** son ejemplos notables de centrocampistas con un talento excepcional.
- **Defensa**: Las posiciones defensivas (CB, LB, RB) también presentan jugadores valiosos, aunque con menores diferencias en talento comparado con las posiciones ofensivas. Esto refleja la solidez defensiva de los equipos de primer nivel.
- **Porteros**: Si bien el número de jugadores destacados en la posición de portero (GK) es menor, su importancia es fundamental para los equipos, y jugadores como **M. Neuer** destacan como los porteros de mayor talento.

### 3. Distribución del Talento entre Clubes
- Es evidente que el talento está distribuido principalmente entre clubes de renombre internacional. Equipos como el **Paris Saint-Germain** y el **Manchester City** poseen algunos de los jugadores con mayor "Valor de Talento" en sus posiciones, lo que subraya la correlación entre el éxito de un equipo y la calidad de sus jugadores.
- Jugadores como **L. Messi** en el FC Barcelona o **K. De Bruyne** en el Manchester City destacan por sus contribuciones cruciales, tanto en la vida real como en el juego.

### 4. Importancia del Análisis de Talento
- Este tipo de análisis puede ser útil no solo para los aficionados del fútbol que juegan FIFA 18, sino también para aquellos interesados en el rendimiento real de los jugadores. El análisis de datos proporciona una visión clara de qué jugadores son clave en determinadas posiciones, así como la importancia que tienen en sus respectivos clubes.
- En el contexto de FIFA 18, conocer los jugadores con los valores de talento más altos por posición puede ayudar a los jugadores a optimizar sus equipos y estrategias en el juego, aprovechando al máximo a los jugadores que destacan en posiciones clave.

### 5. Observaciones Generales
- A pesar de que hay muchas estrellas destacadas en el juego, la mayoría de las posiciones parecen tener jugadores sobresalientes que pueden marcar la diferencia en el campo. Esto resalta la importancia de contar con un equipo balanceado que pueda competir en todas las áreas del campo.
- La relación entre el valor de talento y el rendimiento en el juego refleja la importancia de tener una estrategia clara que maximice el uso de estos jugadores élite en sus posiciones preferidas.



## Conclusiones finales 
Este proyecto ha permitido obtener insights clave a partir de los datos procesados. 
El uso del ETL facilitó la preparación de los datos para un análisis más profundo, mientras que el EDA brindó visualizaciones claras de patrones y relaciones significativas en los datos. 
Se sugiere que el siguiente paso sea realizar un análisis predictivo más avanzado, así como optimizar las transformaciones de datos para mejorar el rendimiento.

