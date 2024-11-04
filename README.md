<h2 align="center">
<img width=300px height=200px src=titanic.jpg>
  
:construction: Analisis-Tictanic :construction:
</h2>

Desde hace tiempo, me he sentido atraído por la historia del Titanic. Muchos investigadores han dedicado su esfuerzo a reconstruir los restos del famoso barco, con el objetivo de comprender cómo fueron sus horas finales y las de sus pasajeros.Espero que te guste esta versión. 
<h1>⏩⏩ Instalación y Ejecución </h1>
- Python (versión 3.6 o superior)
- pip (gestor de paquetes de Python)
-jupyter

<h1>⏩⏩ Clonación y Ejecución <div id="clonar-y-ejecytar"></div> </h1>

1. Para clonar el repositorio se puede hacer de la siguiente forma:
	Ve a la página del proyecto en GitHub y haz clic en el botón "Code", luego selecciona "Download ZIP" para descargar el proyecto como un archivo comprimido. Alternativamente, puedes usar el siguiente enlace:
	
```batch
	https://github.com/condebufon/ProyectoXanduria/archive/refs/heads/base.zip
```

2. Descomprimir el Archivo 
	* Extrae el contenido del archivo ZIP descargado en una carpeta de tu elección.
	
3. Navegar al Directorio del Proyecto
	*Accede al directorio del proyecto descomprimido:
	

4. Generar un entorno virtual de python e instalar las dependencias de este proyecto:

> Sistemas basados en GNU/Linux
```batch
python3 -m venv virtual
source virtual/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```
> Sistemas Windows
```batch
python -m venv virtual
virtual\Scripts\activate.bat
python -m pip install --upgrade pip
pip install -r requirements.txt

```
6. Ejecutar el Servidor
	Finalmente, ejecuta el servidor de desarrollo:
	```batch
	python manage.py runserver
	Ahora puedes acceder a la aplicación en tu navegador en http://127.0.0.1:8000.	
	```
<h1>⏩⏩Trabajo futuro <div id="trabajo-futuro"></div></h1>

<h3 align=justify>Análisis Inicial del Dataset Utilizado</h3>
En esta sección, se realizará un análisis exhaustivo del dataset que se utilizará en el proyecto. Se examinarán las características principales del conjunto de datos, incluyendo:

<h4 align=justify>
<h4>Origen de los Datos: Descripción de la fuente de datos y su relevancia para el proyecto.</h4>
<h4>Estructura del Dataset: Análisis de las columnas, tipos de datos y la cantidad de registros.</h4>
<h4>Calidad de los Datos: Identificación de problemas potenciales como valores nulos, duplicados o inconsistencias que puedan afectar el análisis posterior.</h4>
Estrategia ETL a Seguir
<h3>La estrategia ETL (Extracción, Transformación y Carga) </h3>
<p align=justify> es fundamental para garantizar que los datos sean útiles y estén listos para el análisis. La estrategia se desglosa en tres etapas:
<h4 align=justify>Extracción:
Métodos de Extracción: Se describirá cómo se extraerán los datos desde la fuente original, ya sea a través de APIs, bases de datos o archivos planos.</h4>
Frecuencia de Extracción: Determinación de si la extracción será puntual o periódica.
<h4 align=justify>Transformación:
Motivos para Transformar: Explicación sobre la necesidad de limpiar y preparar los datos para el análisis. Esto incluye la normalización de formatos y la eliminación de registros irrelevantes.
Métodos de Transformación: Detalle sobre las técnicas utilizadas, como la agregación, filtrado y creación de nuevas columnas.</h4>
<h4 align=justify>Carga:
Destino de Carga: Descripción del sistema o base de datos donde se cargarán los datos transformados.
Frecuencia de Carga: Indicación sobre si la carga será en tiempo real o programada</h4>


cualquier duda o observacion contactar a: https://api.whatsapp.com/send/?phone=573157511161
