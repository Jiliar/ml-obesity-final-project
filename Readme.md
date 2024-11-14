# 📊 Proyecto de Clasificación de Niveles de Obesidad

## 📝 Propósito del Proyecto
En América Latina, la obesidad se ha convertido en un grave problema de salud pública, especialmente en países como México, Perú y Colombia. Este proyecto utiliza modelos de **Machine Learning** y análisis de datos para desarrollar un sistema de clasificación que evalúa los niveles de obesidad a partir de hábitos alimenticios y condiciones físicas. Utilizando un 77% de datos sintéticos y un 23% de datos reales recolectados, el proyecto optimiza la evaluación de obesidad, proporcionando información clave para intervenciones de salud pública.

### 📚 Archivos Incluidos
- **Cuadernos**: Notebooks de Jupyter para análisis de datos y modelos de clasificación.
- **Datos**: Origen de datos en formatos CSV, XLSX, TXT, etc.
- **Modelos**: Almacena los archivos de modelos entrenados en formato `.joblib`.

## 🚀 Instrucciones de Instalación y Ejecución

Para ejecutar este proyecto, se instaló **Poetry** y **IPython Kernel**. Las dependencias se instalaron usando Poetry para asegurar la reproducibilidad y consistencia del entorno.

### Paso 1: Clona el repositorio y navega a la carpeta del proyecto
- `https://github.com/Jiliar/ml-obesity-final-project.git`
- `cd ml-obesity-final-project/`

### Paso 2: Instala las dependencias
Asegúrate de tener Poetry instalado. Luego ejecuta el siguiente comando para instalar todas las dependencias necesarias:
`poetry install`

### Paso 3: Activa el entorno y lanza Jupyter Notebook
Activa el entorno y abre Jupyter Notebook para explorar y ejecutar los cuadernos:
- `poetry shell`
- `jupyter notebook`

## 📦 Dependencias

- `python = "^3.10"`
- `shap = "^0.46.0"`
- `pandas = "^2.2.3"`
- `seaborn = "^0.13.2"`
- `scikit-learn = "^1.5.2"`
- `xgboost = "^2.1.2"`

## 📂 Estructura del Proyecto

### Directorios:

- **Cuadernos:** 📓 Directorio donde se ubican los notebooks de Jupyter (.ipynb) para análisis y visualización de datos.
- **Datos:** 📊 Directorio que almacena los orígenes de datos en formatos como csv, xlsx, txt.
- **Modelos:** 🤖 Almacena los archivos de modelos entrenados en formato .joblib para futuras predicciones.

### Archivos:

- `Datos/ObesityDataSet_raw_and_data_sinthetic.csv`: Archivo principal de datos con información de obesidad en varios niveles, obtenida de datos sintéticos y recopilados.
- `Cuadernos/Agrupación de Datos - Obesidad.ipynb`: Notebook de Jupyter con el análisis y agrupación de los datos de obesidad, enfocado en la identificación de patrones en los niveles de obesidad.
 
## 👥 Integrantes del Proyecto
- Jiliar Antonio Silgado Cardona