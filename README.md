PRUEBA FINAL OPCION A 

Nombre: Karen Mangui

Tema : Cancer de mama

INTRODUCCION


El cáncer de mama es un tipo de cáncer que se origina en el tejido mamario. Se produce cuando las células de la mama comienzan a crecer y multiplicarse de manera anormal y descontrolada. El cáncer de mama es el tipo de cáncer más común en mujeres a nivel mundial, aunque también puede afectar a los hombres
Los síntomas del cáncer de mama pueden incluir un bulto en la mama, cambios en la apariencia de la piel de la mama, hundimientos o retracciones del pezón, secreción del pezón y cambios en el tamaño o la forma de la mama.

El diagnóstico del cáncer de mama se realiza mediante una combinación de exploración física, mamografía, ecografía y biología. El tratamiento puede incluir cirugía, radioterapia, quimioterapia, terapia hormonal y terapias dirigidas.

La prevención del cáncer de mama incluye la adopción de un estilo de vida saludable, como la realización de ejercicio físico regular, una dieta equilibrada, la evitación del tabaco y la limitación del consumo de alcohol. Además, es importante realizar revisiones periódicas y mamografías a partir de los 40 años de edad o antes si se tiene un historial familiar de cáncer de mama.


EXOLICACION DEL PROYECTO

Este proyecto consiste en  tomar la base de datos de las persoans con cancer de mama de los cuales se requiere realizar el analisis de los datos extraidos , para comenza se realiza una limpiesa de los datos para asi poder verificas si todos son correctos si esque no existe valores nulos o valores duplicados.

En este caso pudismos observar que si hubieron datos nulos los cuales se editaron y se eliminaron de la base , despues de realizar  este cambio en la variable  se volvio a comprobar que los datos  este correctos y ya no se encuentren los valores nulos.

Despues de reaizar este analicis descriotivo , se añadio  un analicis de correlacion esteo se hace antes de eleguir las variables a analizar para poder eleguir las que tengan mas correlacion.

En mi caso utilice todas las variable spara poder  tener un modelo mas ajutado.

Realice  un a modelo de arbol de decision  el cual  creamos con una profundidad del 3 .El modelo del árbol de decisión es una técnica de análisis y toma de decisiones que se utiliza para resolver problemas de manera sistemática. Se trata de un modelo gráfico que representa las posibles soluciones a un problema y las consecuencias de cada una de ellas, permitiendo evaluar y comparar las distintas opciones y elegir la más adecuada.

Despues de eso podemos  realizar otro modelo el cual elegui el de los vecinos mas cercanos , El modelo de los KNN (K-Nearest Neighbors) es un algoritmo de aprendizaje automático supervisado que se utiliza para la clasificación y regresión de datos. Este modelo se basa en la idea de que los puntos de datos que están más cerca entre sí son más similares y, por lo tanto, es más probable que pertenezcan a la misma clase o tengan valores similares.

En términos simples, el modelo KNN se utiliza para predecir la clase de un nuevo punto de datos basado en las clases de los puntos de datos cercanos. Para ello, se utiliza una medida de distancia para encontrar los K puntos de datos más cercanos y se toma la clase mayoritaria entre esos puntos para predecir la clase del nuevo punto.

Por ultimo  el modelo elegido  es el de Boosting . El modelo de Boosting es un algoritmo de aprendizaje automático supervisado que se utiliza para mejorar la precisión de los modelos de clasificación y regresión. Este modelo se basa en la idea de combinar múltiples modelos de aprendizaje débiles para formar un modelo de aprendizaje fuerte y preciso.

En términos simples, el modelo de Boosting funciona construyendo un conjunto de modelos de aprendizaje secuenciales débiles, donde cada modelo se centra en los errores del modelo anterior. Es decir, se le da mayor peso a los puntos de datos que se clasifican incorrectamente en el modelo anterior, para que en el siguiente modelo tengan mayor probabilidad de ser clasificados correctamente.

CONCL

Despues de realizar los diferentes modelos el mejor modelo que se acopla a los datos es el de los vecinos mas cercanos ya que en el valor de la matriz de comfusion  es el que mas que acopla al  modelo y menos dispersion tiene.

