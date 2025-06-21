# Proyecto de Análisis del Dataset de Zargazo

## 📄 Descripción

Este proyecto permite descargar y analizar un dataset público relacionado con el fenómeno del zargazo. Utiliza la API de Kaggle para obtener los datos y diversas librerías para su procesamiento y visualización.

---

## 📁 Estructura del Proyecto

- **clasificador_sargazo.ipynb** — Notebook principal donde se ejecuta la descarga y análisis del dataset.  
- **zargazo_dataset/** — Carpeta que se crea automáticamente al ejecutar el notebook y donde se almacenará el dataset descargado.  
- **kaggle.json** — Archivo con las credenciales de Kaggle que debe colocarse en la misma carpeta donde está el notebook antes de ejecutar el proyecto.
- **outputs.csv** — archivo con las predicciones de las etiquetas con el nivel de zargazo para las fotos de playas

---

## 🔑 Cómo configurar Kaggle

1. Crea una cuenta en [Kaggle](https://www.kaggle.com/).

2. inicia sesion en kaggle y ve a tu perfil en la parte superior izquierda

3. Ve a la sección **settings** en tu perfil .  

4. En la sección **API**, haz clic en **Create New API Token** para descargar tu archivo **kaggle.json**.  

5. Coloca el archivo **kaggle.json** en la misma carpeta donde tienes el notebook **descarga_DS.ipynb** antes de ejecutar el proyecto, ya sea que ejecutes el notebook localmente o en Google Colab.

## 📥 Cómo descargar este repositorio

- abra la terminal en el escritorio o donde quiera que se descargue el proyecto y use el siguiente comando

```
git clone https://github.com/jesus24e/Data-Set-Zargazo.git Clasificador_zargazo
```
- este comando creara una carpeta llamada **Clasificador_zargazo** con el archivo ipynb dentro, despues solo tiene que abrir ese proyecto en el entorno que prefierea (Google colaboratory o Visual Studio Code por ejemplo)
