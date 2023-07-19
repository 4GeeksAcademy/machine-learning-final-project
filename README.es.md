<!-- hide -->
# Proyecto final de Machine Learning 
<!-- endhide --> 

- A lo largo de este bootcamp, hemos estudiado diferentes modelos basados en proyectos de distintas áreas e índoles. Ahora es el momento de crear tu propio proyecto utilizando el agoritmo que creas que es más adecuado para tu problema.
- Tendrás que buscar un conjunto de datos apto para trabajar con él, procesarlo, entrenar a un modelo y finalmente disponibilizarlo para poder ser consumido.

> “El trabajo duro siempre vence al talento cuando el talento no trabaja duro” - Tim Notke

## 🌱  Cómo iniciar este proyecto

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.
4. Inicia tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez hayas finalizado el proyecto, deberás entregar:

- El enlace a tu repositorio del Github (ya implementado).
- El enlace a tu aplicación web de Machine Learning implementada.

## 📝 Instrucciones

### Grupos de trabajo

Para realizar el proyecto final, los alumnos se organizarán en equipos de 2 a 3 personas. El trabajo debe ser colaborativo.

### Fases del proyecto

#### Paso 1: Definición del problema

Comienza por definir un problema y conviértelo en un problema de Machine Learning. Este es el primer paso, ya que los datos deben cubrir una necesidad determinada y el proceso de Machine Learning tener como fin satisfacer esa necesidad.

La elección del conjunto de datos debe satisfacer unos requisitos mínimos en cuanto a número de filas y de variables predictoras. Como mínimo, debe contener:

- 10.000 instancias (filas)
- 10 variables predictoras, de las cuales debe haber al menos 1 variable categórica.

#### Paso 2: Obtencion y carga del conjunto de datos

Puesto que en el mundo real los datos no suelen llegar en un fichero csv plano, se deben adquirir estos datos mediante una de las siguientes vías:

- Extracción de datos de alguna página web o portal utilizando técnicas de web scraping.
- Explotación de una base de datos pública utilizando lenguaje SQL (la base de datos debe soportar este lenguaje).
- Explotación de una API pública para obtener datos.

Una vez tengamos los datos, debemos almacenarlos en un documento CSV y cargarlos en Python utilizando Pandas.

#### Paso 3: Realiza un EDA completo

Este segundo paso es vital para asegurar que nos quedamos con las variables estrictamente necesarias y eliminamos las que no son relevantes o no aportan información. Utiliza el Notebook de ejemplo que trabajamos y adáptalo a este caso de uso.

Asegúrate de dividir convenientemente el conjunto de datos en `train` y `test` como hemos visto en lecciones anteriores.

#### Paso 4: Construye el modelo y optimízalo

Una vez tengas los datos listos, decide qué modelo se adapta mejor a ellos y entrénalo. En caso de duda, prueba a utilizar varios de los que ya has estudiado. Selecciona el que mejor se adapte a los datos.

Recuerda que el paso de optimización de hiperparámetros es muy importante para explorar y lograr alcanzar la mejor versión del modelo.

#### Paso 5: Despliega el modelo

Crea una aplicación web de Machine Learning utilizando tu modelo guardado. Puedes usar Flask, Streamlit o cualquier otra herramienta que conozcas.
Usa Heroku u otra plataforma de computación en la nube que prefieras para implementar tu aplicación web y compartirla con el mundo.

### Presentación

La presentación durará 5 minutos por grupo, así que asegúrate de usar tu tiempo de manera eficiente. El código será revisado, así que no pierdas tiempo explicándolo. Céntrate en los puntos importantes, como si estuvieras intentando vender el proyecto a las partes interesadas de tu empresa o a unos inversores. Ten en cuenta que probablemente no tengan una formación técnica, así que trata de usar palabras simples y una presentación fácil de entender. Recuerda que la calidad supera a la cantidad.

Puntos importantes recomendados para mencionar en tu presentación de 5 minutos:

- ¿Cuál es problema de negocio que quieres solucionar?
- ¿Cómo recopilaste los datos?
- Patrones importantes encontrados en los datos
- ¿Qué algoritmo y métrica de evaluación utilizaste para construir tu modelo final?
- Muestra tu aplicación web en funcionamiento y menciona cómo se puede mejorar en el futuro.

> “El secreto para salir adelante es empezar.” - Mark Twain