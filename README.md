# NLP-TweetClassifier

Twitter es actualmente una dinámica e ingente fuente de contenidos que, dada su popularidad e impacto, genera enorme interés para realizar distintos estudios de Social Media Analytics.

En este proyecto se va a aplicar NLP para extraer y procesar tweets de distintas celebridades, para posteriormente aunarlos y construir un clasificador que sepa distinguir el escritor de cada tweet.

### Pasos a seguir

1. La librería que se ha usado para la extracción de tweets es ![python-twitter](https://code.google.com/p/python-twitter/), el cual es un wrapper en Python para acceder al API de Twitter. 

2. Para poder extraer los datos de Twitter se necesita tener una cuenta en Twitter y, a partir de esa cuenta de Twitter, tenemos que crear una “Twitter App” asociada a ella. Una Twitter App es esencialmente un mecanismo que proporciona Twitter para desarrolladores que quieran acceder a los contenidos de Twitter a través de programas. Al crear una Twitter App, Twitter nos proporciona una serie de claves que son las que tenemos que usar en el programa para identificarnos de cara a Twitter cuando queremos extraer tweets de la red social. Para crear una Twitter App se deben seguir las instrucciones dadas en ![https://apps.twitter.com/app/new](https://apps.twitter.com/app/new). Las claves de la cuenta del autor de este proyecto están ocultas por seguridad. Para poder ejecutarlo debéis crear una propia Twitter App.

3. El primer objetivo de este proyecto consiste en, para dos pares de personalidades distintas, descargar el máximo número de tweets posible de su timeline. En este caso se han escogido las siguientes personalidades: por un lado, Rihanna y Elon Musk, y por otro, los periodistas de baloncesto Adrian Wojnarowski y Chris Haynes. Lo importante es que los miembros del primer par son bastante distintos entre sí, mientras que los del segundo par son similares.

4. Experimento de clasificación de tweets. El objetivo es construir un clasificador automático de tweets que pueda predecir quién ha escrito un determinado tweet. Se han realizado dos experimentos de clasificación en dos clases asociados a los dos pares de personalidades elegidos. Como se puede ver en los resultados, lo lógico es que para la pareja de personalidades distinta se obtenga una mejor predicción que para la otra.

5. Como actividad extra con Twitter, podemos realizar un análisis de sentimientos de los tweets de las celebridades usando *VADER*, y analizar los resultados que se obtienen.

Este proyecto se presenta en formato de Jupyter Notebook con explicaciones detalladas, adjuntando también un fichero .html donde podemos ver el resultado de la ejecución de cada celda.
