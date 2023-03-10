# 馃搱 Cuadro de mandos personal: DATOS SOBRE ALUMNOS EN LA ESCUELA DE IDIOMAS 馃搳

## Objetivo
Dise帽o de un cuadro de mandos personal para visualizaci贸n de datos sobre los alumnos que se han matriculado durante los a帽os 2020 y 2021 en las Escuelas de Idiomas Espa帽olas.

## Los datos
Los datos los he descargado como .csv desde un porta de datos libres de una de las Comunidades Aut贸nomas. Al descargar el archivo, cojo los datos de manera local. Los campos principales que he decidido mostrar son los siguientes: nivel de idioma, idiomas disponibles, provincias, n煤mero de alumnos y n煤mero de grupos por provincia y de cada idioma.

## Preparaci贸n de la aplicaci贸n
La aplicaci贸n se llama `app.py`. He a帽adido un `requirements.txt` con las dependencias de mi aplicaci贸n, streamlit y pandas.

## Visualizaci贸n de los datos
He preparado la aplicaci贸n para que los datos se muestren en tablas y en gr谩ficos. Para que sea interactivo, he utilizado Altair para mostrar widgets como campos de selecci贸n o checbox. Incluso he puesto una barra lateral para uno de los gr谩ficos, el usuario puede decidir los datos que quiere mostrar seg煤n el idioma que elija.

## Publicaci贸n de la aplicaci贸n
Para publicar la aplicaci贸n, lo he hecho con Streamlit Cloud. He creado una cuenta y he subido mi aplicaci贸n. He creado un repositorio en GitHub y he conectado mi cuenta de Streamlit Cloud con mi cuenta de GitHub. De esta manera, cada vez que hago un push a mi repositorio, se actualiza la aplicaci贸n en Streamlit Cloud.

La url de mi aplicaci贸n es: https://mariaquilez-cuadro-de-mandos-personal-app-3jnxck.streamlit.app/
