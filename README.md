![Logo](https://github.com/ClaudioRojasMon/Calificaciones-en-tiempo-de-Covid/blob/main/LinkedIn%20Cover%20Photo.png)


<h1>Calificaciones en tiempo de Covid (parte I)</h1>


**Introducción** A  pesar de la pandemia, una de las prácticas que los docentes no pudieron dejar de realizar fue evaluar a sus estudiantes. Los medios a través del cual, buscaron verificar los aprendizajes fueron diversos: videos; formularios de google, trabajos escritos enviados por e-mail, guías en papel enviadas a las casas y entregadas en el mismo formato en las porterías de los establecimientos. etc. 
Por lo mismo, una pregunta surge de todo ello fue: **¿Cuál fue la diferencia entre notas obtenidas el  2020 con la  de años anteriores y posteriores?** 

Para responder esta inquietud,  decidimos recurrir a los datos oficiales que entrega el Mineduc. Por lo cual, utilizamos la base de datos del Mineduc: "Notas y egresados de enseñanza media" de los años 2018, 2019, 2020, 2021. Consideramos el  2018 como punto de partida , porque fue el año que se creó la última región: Ñuble y como punto final el 2021, porque aun no están publicados los datos del 2022.  

Las visualizaciones muestran los resultados de los promedios del nivel IV medio en cada uno de estos años en establecimientos educativos Científicos Humanistas, debido a su foco prioritario en la continuación de estudios en la educación terciaria. 
**Los resultados se presentan por regiones y solo tienen un carácter exploratorio.**

**¿Qué hicimos?**
Descargamos las bases de datos junto a sus documentos que reseñan cada una de las variables. 
Primero cada DF fue revisado y se aplicó la limpieza de datos (Nan; eliminación de filas con datos faltantes, conversión de object a float), para lo cual trabajamos con librería de Python. 
Posteriormente  concatenamos los DF.  En este caso notamos, que el df del 2021 tiene un declarado 330.005 estudiantes en relación a laos 978.137 del 2020 pero reporta mayor número de egresado: 280.013, 40.000 aprox. que los años anteriores. No hay información de esta diferencia en el Mineduc.
Organizamos la información en función de nuestra pregunta guía  y visualizamos con Seaborn incluyendo el valor de la mediana.
Reseñamos algunas conclusiones

**Conclusiones**
La pandemia tuvo un impacto en las notas el año 2020, ya que las notas de IV medio a nivel nacional subieron desde  7 decimas en relación a los dos años anteriores.
A nivel de regiones 9 de las regiones estuvo igual o sobre la media el 2020 menor  al 2018(10) y similar en relación al 2019 (9). 
El 2021, el promedio de IV disminuye pero se mantiene más cerca del año 2020 que del 2019 o 2018. Esto podría ser porque muchos colegios mantuvieron durante alguna parte del año sistema virtual o híbrido, lo cual, impacta en el tipo de evaluaciones que se realiza y por ende, en la calificación que se otorga.
Si a esto le sumamos, la presión del NEM y Ranking más el impacto del decreto 67 permite proyectar que las notas se mantendrán sobre el 6.0 y quizás sigan aumentando. (¡A la espera de los resultados 2022!). 
La duda que se instala hasta que punto el aumento de las calificaciones son reflejo del logro de aprendizajes reales de los y las estudiantes y no unamera certificación deuda actividad, tarea o prueba realizada.

**Enlace a Archivos**: Debido al peso de los mismos, dejamaos el link para que puedan ser descargados directamente de la web del MINEDUC: https://datosabiertos.mineduc.cl/notas-y-egresados-de-ensenanza-media/
