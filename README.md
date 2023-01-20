<h1 align="center"> Tutorial - Dashboard en PowerBI: Mi primer objeto visual </h1> 

El  presente tutorial  tiene por  objetivo la creación de  un dashboard utilizando la herramienta Microsoft Power BI. Dado que el foco está en principiantes, nos enfocaremos en la creación de un primer objeto visual utilizando la herramienta.

Existen 2 maneras para utilizar esta herramienta, la primera es descargar la versión de escritorio y la segunda corresponde a trabajar en la web de manera online.
Dicho esto, ahora se detallará paso a paso las instrucciones de desarrollo de un Dashboard:

***********************************************************************************************************************************************************************

**Paso 1:** Descargar e instalar Microsoft Power BI desde el siguiente link: https://powerbi.microsoft.com/es-es/desktop/. Una vez descargado el instalador (archivo .exe) siga las indicacaciones hasta finalizar la instalación.

Importante: La versión de escritorio de Microsoft Power BI sólo está disponible para el sistema operativo Microsoft Windows. Si usted posee Mac OS deberá desarrollar sus tableros de visualización desde la aplicación online: https://app.powerbi.com/home
***********************************************************************************************************************************************************************

**Paso 2:**  Una vez instalada con éxito la aplicación de escritorio (en caso contrario, utilizar la aplicación online), procederemos a realizar el tutorial que consistirá en replicar parte del proyecto de visualización: "Dashboard de ejemplo" correspondiente a datos de PSU y SIMCE.

![image](https://user-images.githubusercontent.com/52829923/213713988-de57eacb-1166-42cc-9662-40f3ad37baa5.png)

***********************************************************************************************************************************************************************

**Paso 3: Carga de Datos**
Comenzamos presionando "OBTENER DATOS" como se muestra en la imagen de a continuación:

![image](https://user-images.githubusercontent.com/52829923/213748199-e1080fa4-7cbd-40ce-a17d-2bb555565c18.png)

Cargamos los archivos uno a uno, comenzando con: 
- C4Lab4 (COMUNA).xlsx
Para el archivo de COMUNA seleccionamos las 4 tablas que se han de cargar:

![image](https://user-images.githubusercontent.com/52829923/213754909-db1b7edb-2535-415d-b13c-92773f28337e.png)

***********************************************************************************************************************************************************************

**Paso 4: Transformar datos**

Presionamos **transformar datos** como se indica en la imagen de a continuación: 

![image](https://user-images.githubusercontent.com/52829923/213754946-1af902bc-7069-42a1-b394-1b530aeed8ce.png)

Luego, seleccionamos la tabla "COLEGIOS" y en la barra de herramientas seleccionamos "reducir filas" --> "quitar filas" --> "quitar filas superiores". Aparecerá la ventana que se muestra a continuación, donde debemos ingresar el número de filas que queremos eliminar, para nuestro caso en particular es 1, y presionamos ACEPTAR:

![image](https://user-images.githubusercontent.com/52829923/213755018-92363aed-9f3d-4af4-9fd5-5e68693044f7.png)


![image](https://user-images.githubusercontent.com/52829923/213755091-121588d6-3da7-4ea2-a58f-fb8e2ea5d037.png)

Posteriormente, presionamos "utilizar la primera fila como encabezado":

![image](https://user-images.githubusercontent.com/52829923/213756925-a00af6b7-c326-47f7-9fb6-f8b2a55ab378.png)

Quedando la tabla COLEGIOS como se muestra a continuación: 

![image](https://user-images.githubusercontent.com/52829923/213756961-e7ef2db1-9cec-4ee9-b8f1-aba7b2792be6.png)

IMPORTANTE: Muchas veces no es necesario transformar los datos, dado que vienen listos para CARGAR. En ese caso, te sugiero saltarte este paso.

***********************************************************************************************************************************************************************
Realizamos el paso 4 con las tablas: COMUNA, REGION y VARIABLES. Las tablas COMUNA y REGION no necesitan ninguna transformación.
***********************************************************************************************************************************************************************
Ahora procedemos a realizar los pasos 3 y 4 para los 2 archivos restantes:
- C4Lab4 (SIMCE).accdb
- C4Lab4 (PSU).xlsx

NOTA: Para cargar "bases de datos" de Access debes presionar "OBTENER DATOS" --> "MAS..." y presionar "bases de datos access" como muestra la siguiente imagen:

![image](https://user-images.githubusercontent.com/52829923/213765614-7b7c4a08-ae99-4cb2-8a29-0036db8d619a.png)

***********************************************************************************************************************************************************************

**Paso 5: Crear relaciones entre las tablas cargadas**

Para crear las relaciones entre las tablas debes arrastrar el "id" de la tabla con la tabla asociada respectiva. La siguiente imagen resume todas las realaciones entre tablas que hay que desarrollar:

![image](https://user-images.githubusercontent.com/52829923/213773615-69f6f678-7d4f-4c67-9482-23aa44d66a29.png)


**IMPORTANTE:** es necesario renombrar los "ID" de cada tabla, para facilitar esta etapa.

***********************************************************************************************************************************************************************

**Paso 6: Crear objetos visuales**

Comenzamos seleccionando el gráfico de torta en la barra VISUALIZACIONES:

![image](https://user-images.githubusercontent.com/52829923/213776787-9245d4a1-c267-41f0-b92a-af0ef72664df.png)

Posteriormente, al objeto gráfico de torta, le añadimos los elementos "leyenda" y "valores" desde la barra CAMPOS:

![image](https://user-images.githubusercontent.com/52829923/213776809-b71c146c-7eb4-447d-959f-48d7a7faf846.png)

Una vez selecciononados los valores, el objeto visual gráfico de torta queda de la siguiente manera:

![image](https://user-images.githubusercontent.com/52829923/213776845-31f9aa7e-7894-45d9-8f70-3e72e41e393a.png)

***********************************************************************************************************************************************************************

**COMENTARIO FINAL SOBRE EL TUTORIAL**

Este trabajo tiene por objetivo instalar y tener un primer acercamiento con la herramienta de Microsoft Power BI.






