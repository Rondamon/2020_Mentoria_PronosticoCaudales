# Título: “Me anticipo a las crecidas en nuestros ríos”


Mentores: Javier Alvarez y María Magdalena Baraquet


Descripción:

La predicción precisa y anticipada de caudales que escurren durante crecidas en nuestros ríos son de interés fundamental para la gestión de riesgo de desastres naturales. En la actualidad, estas predicciones se realizan en la provincia de Córdoba utilizando modelos de base física para representar los procesos de generación de escurrimientos. El principal inconveniente de este enfoque yace en la necesidad de una importante cantidad de información experimental requerida para caracterizar cada uno de los procesos físicos involucrados en la cuenca, y así poder calibrar los parámetros de los modelos.

Por otra parte, en Argentina, y en particular en Córdoba, las cuencas se encuentran pobremente aforadas, es decir, disponen de pocos registros hidro-meteorológicos. Esta situación puede suplirse en parte con información hidrometeorológica obtenida de reanálisis climáticos, los cuales son el resultado de la combinación de múltiples fuentes de información climática (estaciones meteorológicas, satélites, etc.) junto con la aplicación de algún algoritmo matemático (desde interpolaciones lineales hasta redes neuronales). Sin embargo, la variable clave para la gestión de riesgos de inundación son los caudales, cuyos registros son aún más escasos que las demás variables meteorológicas. En este sentido, numerosos trabajos científicos confirman que las redes neuronales artificiales "ANN", resultan una alternativa importante a los modelos conceptuales tradicionales en el caso que los datos disponibles sean escasos espacial y temporalmente y de calidad pobre.

A partir de lo anterior, el área de estudio que se propone para esta mentoría es la cuenca alta de Río Tercero, donde se encuentran localizados la mayor cantidad de embalses de la Provincia de Córdoba y donde la gestión del recurso hídrico resulta crucial por numerosos factores: generación hidroeléctrica, control de inundaciones repentinas, turismo, agua potable, entre tantos otros. En esta zona se generan habitualmente tormentas intensas y repentinas que han despertado el interés de investigadores nacionales e internacionales. Tal es así que, en los años 2018 y 2019 se estuvo trabajando en conjunto con investigadores de Estados Unidos y de otras partes de Argentina en el marco del Proyecto RELAMPAGO, cuya etapa de análisis de la información registrada en ese proyecto continúa hasta el año 2021.

En conclusión, en esta mentoría se propone en primer lugar, analizar algunos registros de observaciones hidrometeorológicas y de caudales escurridos en la cuenca de los ríos Quillinzo, La Cruz y Santa Rosa, principales tributarios del Embalse de Río Tercero. Se espera que los alumnos evalúen la cantidad y calidad de los registros de datos. Además se propone analizar técnicas para rellenar las series de datos hidro-meteorológicos y suplir la falta de datos espacialmente. En este sentido se propone complementar la escasez de información con reanálisis climáticos.

En segundo lugar, se propone modelar la evolución de caudales utilizando redes neuronales artificiales "ANN" y con análisis de series temporales (ARIMA). Para ello se propone dividir el conjunto de datos en partes para evaluar la capacidad de predicción a diferentes umbrales (horas, dias y semanas). Para esto, se deberán utilizar ventanas móviles de calibración y separar una pequeña proporción para una validación independiente.



Trataremos de responder algunas de las siguientes preguntas:

¿Qué distribución de probabilidad poseen los diferentes tipos de datos? ¿Se observan cambios al analizar diferentes pasos de tiempo?
¿Existe alguna relación entre los diferentes tipos de datos?

¿Es posible suplir la falta de información en cada serie y espacialmente con otras fuentes de datos?

¿Podemos predecir si en las próximas horas o días los caudales crecerán?

¿Es posible estimar la magnitud de los caudales para las próximas horas o días?

¿Cuál es la mejor herramienta matemática para realizar estas predicciones?


Hitos de la mentoría:

29/6 práctico de análisis y visualización, para entender los patrones de los datos en la cuenca alta del río Tercero se espera:
-	Entender qué distribución de probabilidades representan a los datos
-	¿Cambian los estadísticos espacialmente?

19/7 práctico de análisis y curación, que consistirá en cuantificar en cada estación, el número de datos faltantes respecto al total de datos y evaluar la metodología ideal para rellenar la serie. 

16/8 práctico de introducción al aprendizaje automático, que consistirá en intentar implementar un algoritmo perceptrón e intentar aplicar K-means con diferentes variables climáticas.

13/9 práctico de aprendizaje supervisado, que consistirá en intentar predecir si los caudales crecerán en diferentes horizontes de tiempo.

27/9 práctico de aprendizaje no supervisado, que consistirá en intentar predecir la magnitud de los caudales en diferentes horizontes de tiempo.

6/11/2020 – 7/11/2020 presentación de mentorías. Para esta etapa, te propongo comparar las predicciones realizadas con análisis de series temporales (ARIMA) y con redes neuronales.

