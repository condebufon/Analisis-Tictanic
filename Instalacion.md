<h4>⏩⏩Paso 1: Instalar Python y pip</h4>
Asegúrate de tener Python y pip instalados en tu sistema. Puedes verificar esto ejecutando los siguientes comandos en tu terminal:

```batch
python --version
pip --version
```
<h4>⏩⏩Paso 2: Crear un entorno virtual</h4>
Crea un entorno virtual para evitar conflictos entre paquetes. Ejecuta el siguiente comando en la terminal:

```batch
python -m venv nombre_del_entorno
```
Reemplaza nombre_del_entorno con el nombre que desees para tu entorno.
<h4>⏩⏩Paso 3: Activar el entorno virtual</h4>
Activa el entorno virtual con uno de los siguientes comandos, dependiendo de tu sistema operativo:
Windows:

```batch
nombre_del_entorno\Scripts\activate
```
macOS/Linux:

```batch
source nombre_del_entorno/bin/activate
```
<h4>⏩⏩Paso 4: Instalar Jupyter y otras dependencias</h4>
Con el entorno virtual activado, instala Jupyter y las bibliotecas necesarias. Ejecuta:

```batch
pip install jupyter pandas numpy matplotlib seaborn
```
Esto instalará Jupyter y las bibliotecas comunes que probablemente necesites para el análisis de datos.

<h4>⏩⏩Paso 5: Clonar el repositorio</h4>
Clona el repositorio de GitHub en tu máquina local usando el siguiente comando:

```batch
git clone https://github.com/condebufon/Analisis-Tictanic.git
```
Esto creará una carpeta llamada Analisis-Tictanic con todos los archivos del repositorio.

<h4>⏩⏩Paso 6: Navegar al directorio del repositorio</h4>
Cambia al directorio del repositorio clonado:

```batch
cd Analisis-Tictanic
```
<h4>⏩⏩Paso 7: Iniciar Jupyter Notebook</h4>
Inicia Jupyter Notebook con el siguiente comando:

```batch
jupyter notebook
```
Esto abrirá una nueva pestaña en tu navegador web donde podrás ver los archivos del repositorio.