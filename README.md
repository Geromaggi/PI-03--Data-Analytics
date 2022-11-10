#                                                     PROYECTO III DATA SCIENCE - DATA ANALYTICS

![image](https://user-images.githubusercontent.com/93155829/201111049-9684cac9-a672-40ad-98fe-803faf4cd97a.png)


Hola! Bienvenidos al README que contiene una descripcion del proyecto realizado.

# Trabajo realizado  

![image](https://user-images.githubusercontent.com/93155829/201118613-ee54842a-1d81-4492-ba20-3dab489ac5da.png)

La Organización de Aviación Civil Internacional (OACI), organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, nos solicito la elaboración de un informe y un dashboard interactivo que recopile tal información. Ademas de este dataset, se ha buscado mas informacion sobre las causas de los accidentes aereos. Estos datasets los podemos encontrar en el siguiente link: http://www.planecrashinfo.com/category.htm

Teniendo nuestra informacion, el proceso que se realizo fue el siguiente:

-Analisis Exploratorio de los datos, ETL. Estos dos procesos son fundamentales para nuestro trabajo y los podemos encontrar en la carpeta llamada 'Scripts' de este repositorio.

EL EDA consistio en sacar diferentes metricas, conclusiones sobre los datos que se obtuvieron. Vimos el tipo de dato de cada columna, los valores nulos, las columnas, la informacion de cada columna, a que se referia cada una, etc. Luego llego nuestro proceso de ETL. La fase de extraccion ya la dijimos, el dataset principal fue brindado por la Organización de Aviación Civil Internacional (OACI), y los datasets adicionales fueron encontrados por nuestra parte. El proceso de Transformacion, siendo este el que mas tiemo lleva, consistio en analizar la informacion recopilada de cada dataset, ver cada columna, ver el tipo de cada columna y verificar que corresponda, agregar columnas necesarias, y cruzar la informacion de todos los datasets para dejar uno solo que va a ser el que ingestemos en nuestra base de datos. Luego de esto, se subio a la base de datos MySQL, el dataset que usaremos para el analsis de datos.

-Dashboard interactivo. Este es el corazon de este proyecto ya que lo que se pretende es dar un pantallazo general de la informacion.

Habiendo terminado todo tipo de tratamiento con los datos, desde nuestra base de datos MySQL enviamos los archivos a nuestra herramienta de visualizacion. El analista de datos, cuando da una presentacion, puede abarcar muchos temas, nosotros nos centramos en las consecuencias que generaron y que generan hoy en dia los accidentes aereos. Las consecuencias son muchas (consecuencias naturales, de infraestructura, entre otras), pero la mayor de todas son las victimas que dejan. En el dashboard se presenta la cantidad de fallecidos tomando los 3 paises que mas daño causaron(mas fallecidos). Sobre estos 3 se visualizo los tipos de vuelos realizados, las operadoras correspondientes, la cantidad de fallecidos a lo largo de los años, etc. Luego de exponer estos datos, se pueden ver las principales causas(obtenidas puntualmente de los datasets) de los accidentes aereos. Y para terminar se proponen 3 soluciones.   


# Herramientas utilizadas

![image](https://user-images.githubusercontent.com/93155829/201120374-3a602cd3-d823-4bd4-bccf-10c763119679.png)

- Python, Jupyter Notebook (EDA, ETL)
- MySQL (Base de datos)
- Power BI (herramienta de visualizacion) 


# Conclusion

Los resultados del análisis de datos deben compartirse de una manera eficaz que preserve la informacion recopilada. El análisis de datos, realizado de manera correcta y utilizando "buenos" datos, permite analizar mejor las alternativas, abre un nuevo abanico de posibilidades y mejora el conocimiento que se tiene de cada una de ellas. 

Muchas gracias a todos! 
