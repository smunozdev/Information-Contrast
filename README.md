# Contraste de información en tiempos del COVID-19
¿Son las noticias de un medio de información objetivas y imparciales? ¿Podemos definir las relaciones entre los conceptos hablados en la sección de opinión para obtener una fotografía de cómo piensa un medio particular?

Esto es lo que hemos estudiado y analizado en esta Hackathon. Obteniendo datos mediante web-scrapping y analizándolos sin supervisar con técnicas de análisis multivariante y inferencia de variedades geométricas, aplicadas a los datos codificados con la tecnología Word2Vec. Hemos obtenido resultados, sorprendentemente acertados, sobre las relaciones de los conceptos y opiniones del diario digital líder en España, "El Español".

Todos los resultados han estado recogidos en el notebook que hemos confeccionado en estas 12 horas. Finalmente, hemos confeccionado un mapa que representa las relaciones y distancias entre los temas. Aquí debajo se puede ver cómo es este mapa.

## Zonas particulares del mapa
### "Cataluña", "155", "Victimismo", "Procés", "Huidos"...
![Catalunya concept map](https://github.com/Huguet57/Information-Contrast/blob/master/images/catalunya.png)

### "Corrupción", "Gúrtel", "Cifuentes", "Máster", "Esperanza"...
![Corrupción concept map](https://github.com/Huguet57/Information-Contrast/blob/master/images/corrupción.png)

### "Gobierno", "Derecha", "Pactar", "Mayorías", "Bloqueo"...
![Gobierno concept map](https://github.com/Huguet57/Information-Contrast/blob/master/images/gobierno.png)

### "Internacional", "Trump", "Refugiados", "China", "Climático"...
![Internacional concept map](https://github.com/Huguet57/Information-Contrast/blob/master/images/internacional.png)

### "Delito", "Forcadell", "Exconsejeros", "Malversación", "Llarena"...
![Presos concept map](https://github.com/Huguet57/Information-Contrast/blob/master/images/presospoliticos.png)

### "Coronavirus", "Yihadista", "Immigrantes", "Economía", "Empleo"...
![Coronavirus concept map](https://github.com/Huguet57/Information-Contrast/blob/master/images/coronavirus.png)

## El mapa completo
![UMAP global map](https://github.com/Huguet57/Information-Contrast/blob/master/images/umap.png)
Podemos ver que en el mapa, los datos tienen un sentido global. Es decir, podemos ver en el norte palabras relacionadas en notícias internacionales. En el sur, vemos palabras involucrando crímenes, corrupción y prisión. En la derecha palabras sobre gobiernabilidad, ideologías y partidos políticos. Finalmente, en la izquierda vemos las palabras más numéricas de notícias involucrando datos. 
