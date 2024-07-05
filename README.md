# Sistema de Clasificación de Reseñas de Amazon

## Descripción General
Este proyecto implementa un sistema de clasificación de reseñas utilizando técnicas de aprendizaje automático y procesamiento de lenguaje natural en un Jupyter Notebook. Utiliza modelos de clasificación de texto para determinar la polaridad de las reseñas de Amazon, clasificándolas como positivas o negativas.

## Características
- **Clasificación de Sentimientos:** Clasifica las reseñas de productos en sentimientos positivos o negativos.
- **Procesamiento de Texto Avanzado:** Utiliza técnicas como tokenización, eliminación de stopwords y TF-IDF para preparar los datos para el modelado.
- **Modelado Predictivo:** Emplea modelos de machine learning para predecir el sentimiento basado en el texto de las reseñas.
- **Visualización de Datos:** Integra visualizaciones para explorar los datos y los resultados del modelo.

## Conjunto de Datos
El conjunto de datos consiste en 34,686,770 reseñas de Amazon de 6,643,669 usuarios sobre 2,441,053 productos. Los metadatos de cada producto están disponibles en `train.csv` y `test.csv`, con etiquetas de polaridad, títulos de reseñas y texto de reseñas.

- **Fuente:** [Amazon Reviews Polarity Dataset en Kaggle](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews)
- **Contenido:** Incluye 1,800,000 muestras de entrenamiento y 200,000 muestras de prueba en cada polaridad de sentimiento.

## Descarga del Conjunto de Datos
Debido al tamaño considerable del conjunto de datos de reseñas de Amazon, no está incluido directamente en el repositorio. Para utilizar este proyecto, necesitarás descargar el conjunto de datos manualmente.

### Instrucciones para la Descarga
1. Visita la página del [Amazon Reviews Polarity Dataset en Kaggle](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews).
2. Crea una cuenta en Kaggle si aún no tienes una.
3. Una vez en la página del dataset, haz clic en "Download" (Descargar) para obtener el archivo comprimido del dataset.
4. Extrae el archivo ZIP en una ubicación adecuada que será utilizada para ejecutar los notebooks de Jupyter.

### Preparación del Entorno
Tras descargar y extraer el dataset, asegúrate de que los archivos `train.csv` y `test.csv` están accesibles desde el directorio donde ejecutarás tus notebooks de Jupyter. Esto permitirá que el código cargue y procese los datos sin problemas adicionales de configuración.

## Nota Importante
Por favor, verifica la integridad de los archivos descargados antes de usarlos, especialmente si encuentras problemas al cargar los datos en los notebooks. Esto te ayudará a evitar errores comunes relacionados con archivos corruptos o incompletos.


## Prerrequisitos
- Jupyter Notebook o Jupyter Lab
- Python 3.8 o superior
- Bibliotecas Python: NumPy, Pandas, Scikit-learn, Matplotlib, NLTK

## Configuración e Instalación
1. Descarga el dataset desde Kaggle:
   ```bash
   kaggle datasets download -d kritanjalijain/amazon-reviews
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install numpy pandas matplotlib scikit-learn nltk
   ```
3. Extrae el dataset y mueve los archivos CSV al directorio de trabajo.

4. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Uso
Sigue las instrucciones en el Jupyter Notebook para cargar el conjunto de datos, realizar el preprocesamiento, entrenar el modelo de clasificación y evaluar los resultados.

## Ejemplo de Uso
Para clasificar nuevas reseñas y predecir su sentimiento, carga la reseña en el formato adecuado y utiliza el modelo entrenado para obtener predicciones.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor envía un pull request o abre un issue.

## Contacto
- **Nombre del Autor:** [Manuel Luján vilchez]
- **Correo Electrónico:** [mlujan@invokeapp.io]
- **LinkedIn:** [Perfil de LinkedIn](https://www.linkedin.com/in/manuel-lujan-vilchez-166499b1/)

## Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo [LICENSE.md](LICENSE) para más detalles.

## Agradecimientos
Agradecimientos a Xiang Zhang y a Kaggle por proporcionar el conjunto de datos utilizado en este proyecto.
