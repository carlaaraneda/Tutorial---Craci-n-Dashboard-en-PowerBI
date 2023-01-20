<h1 align="center"> Tutorial - Cración Dashboard en PowerBI </h1> 

El  presente tutoria  tiene por  objetivo la creación de  un dashboard utilizando la herramienta Microsoft Power BI.
Existen 2 maneras para utilizar esta herramienta, la primera es descargar la versión de escritorio y la segunda corresponde a trabajar en la web de manera online.
Dicho esto, ahora se detallará paso a paso las instrucciones de desarrollo de un Dashboard:

**Paso 1:** Descargar e instalar Microsoft Power BI desde el siguiente link: https://powerbi.microsoft.com/es-es/desktop/. Una vez descargado el instalador (archivo .exe) siga las indicacaciones hasta finalizar la instalación.

Importante: La versión de escritorio de Microsoft Power BI sólo está disponible para el sistema operativo Microsoft Windows. Si usted posee Mac OS deberá desarrollar sus tableros de visualización desde la aplicación online: https://app.powerbi.com/home

**Paso 2:**  Una vez instalada con éxito la aplicación de escritorio (en caso contrario, utilizar la aplicación online), procederemos a realizar el tutorial que consistirá en replicar parte del proyecto de visualización: "Dashboard de ejemplo" correspondiente a datos de PSU y SIMCE.

![image](https://user-images.githubusercontent.com/52829923/213713988-de57eacb-1166-42cc-9662-40f3ad37baa5.png)

Comenzamos presionando "OBTENER DATOS" como se muestra en la imagen de a continuación:


![image](https://user-images.githubusercontent.com/52829923/213748199-e1080fa4-7cbd-40ce-a17d-2bb555565c18.png)

cargamos los archivos uno a uno: 
- C4Lab4 (COMUNA).xlsx
- C4Lab4 (PSU).xlsx
- C4Lab4 (SIMCE).accdb

Para el archivo de COMUNA seleccionamos las 4 tablas que se han de cargar:

![image](https://user-images.githubusercontent.com/52829923/213754909-db1b7edb-2535-415d-b13c-92773f28337e.png)

Presuinamos **transformar datos** como se indica en la imagen de a continuación: 

![image](https://user-images.githubusercontent.com/52829923/213754946-1af902bc-7069-42a1-b394-1b530aeed8ce.png)

Luego, seleccionamos la tabla "COLEGIOS" y en la barra de herramientas seleccionamos "reducir filas" --> "quitar filas" --> "quitar filas superiores". Aparecerá la ventana que se muestra a continuación, donde debemos ingresar el número de filas que queremos eliminar, para nuestro caso en particular es 1, y presionamos ACEPTAR:

![image](https://user-images.githubusercontent.com/52829923/213755018-92363aed-9f3d-4af4-9fd5-5e68693044f7.png)


![image](https://user-images.githubusercontent.com/52829923/213755091-121588d6-3da7-4ea2-a58f-fb8e2ea5d037.png)

Posteriormente, presionamos "utilizar la primera fila como encabezado":

![image](https://user-images.githubusercontent.com/52829923/213756925-a00af6b7-c326-47f7-9fb6-f8b2a55ab378.png)

Quedando la tabla COMUNA como se muestra a continuación: 

![image](https://user-images.githubusercontent.com/52829923/213756961-e7ef2db1-9cec-4ee9-b8f1-aba7b2792be6.png)








El README file contiene: Título y
descripción del proyecto, instrucciones
claras de cómo usarlo, cómo replicarlo
y ejecutarlo en un setting local,
información de la licencia y posibles
restricciones de uso. Además, incluye
detalles técnicos de las librerías y
versiones de las herramientas utilizadas

El proyecto se puede ejecutar en
plataforma web online, sin necesidad 
de descargarlo localmente. Contiene
secciones de: carga y visualización de
datos, metodología de análisis,
alcances, supuestos y limitaciones del
análisis, resultados y conclusiones.

El proyecto contiene herramientas de
análisis adecuados para el volumen y
tipos de datos. Se incluye herramientas
de visualización y gráficas que permiten
la interpretación directa de los
resultados, sin necesidad de cargar los
datos en otro software (e.g. Excel). Se
incluye además, las justificaciones
técnicas de los métodos estadísticos y
analíticas de datos utilizadas
