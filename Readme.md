# ?? Proyecto de Clasificaci��n de Niveles de Obesidad

## ?? Prop��sito del Proyecto
En Am��rica Latina, la obesidad se ha convertido en un grave problema de salud p��blica, especialmente en pa��ses como M��xico, Per�� y Colombia. Este proyecto utiliza modelos de **Machine Learning** y an��lisis de datos para desarrollar un sistema de clasificaci��n que eval��a los niveles de obesidad a partir de h��bitos alimenticios y condiciones f��sicas. Utilizando un 77% de datos sint��ticos y un 23% de datos reales recolectados, el proyecto optimiza la evaluaci��n de obesidad, proporcionando informaci��n clave para intervenciones de salud p��blica.

### ?? Archivos Incluidos
- **Cuadernos**: Notebooks de Jupyter para an��lisis de datos y modelos de clasificaci��n.
- **Datos**: Origen de datos en formatos CSV, XLSX, TXT, etc.
- **Modelos**: Almacena los archivos de modelos entrenados en formato `.joblib`.

## ?? Instrucciones de Instalaci��n y Ejecuci��n

Para ejecutar este proyecto, se instal�� **Poetry** y **IPython Kernel**. Las dependencias se instalaron usando Poetry para asegurar la reproducibilidad y consistencia del entorno.

### Paso 1: Clona el repositorio y navega a la carpeta del proyecto
- `https://github.com/Jiliar/ml-obesity-final-project.git`
- `cd ml-obesity-final-project/`

### Paso 2: Instala las dependencias
Aseg��rate de tener Poetry instalado. Luego ejecuta el siguiente comando para instalar todas las dependencias necesarias:
`poetry install`

### Paso 3: Activa el entorno y lanza Jupyter Notebook
Activa el entorno y abre Jupyter Notebook para explorar y ejecutar los cuadernos:
- `poetry shell`
- `jupyter notebook`

## ?? Dependencias

- `python = "^3.12"`
- `pandas = "^2.2.3"`
- `seaborn = "^0.13.2"`
- `scikit-learn = "^1.5.2"`
- `numpy = "^2.1.3"`

## ?? Estructura del Proyecto

### Directorios:

- **Cuadernos:** ?? Directorio donde se ubican los notebooks de Jupyter (.ipynb) para an��lisis y visualizaci��n de datos.
- **Datos:** ?? Directorio que almacena los or��genes de datos en formatos como csv, xlsx, txt.
- **Modelos:** ?? Almacena los archivos de modelos entrenados en formato .joblib para futuras predicciones.

### Archivos:

- `Datos/ObesityDataSet_raw_and_data_sinthetic.csv`: Archivo principal de datos con informaci��n de obesidad en varios niveles, obtenida de datos sint��ticos y recopilados.
- `Cuadernos/Agrupaci��n de Datos - Obesidad.ipynb`: Notebook de Jupyter con el an��lisis y agrupaci��n de los datos de obesidad, enfocado en la identificaci��n de patrones en los niveles de obesidad.
 
## ?? Integrantes del Proyecto
- Jiliar Antonio Silgado Cardona