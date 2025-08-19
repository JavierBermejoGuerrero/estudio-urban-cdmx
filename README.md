Estudio Urbano CDMX

Descripción del Proyecto

Este proyecto tiene como objetivo analizar y visualizar la concentración de población y vivienda en la Ciudad de México, utilizando datos geográficos (latitud y longitud) y representándolos en mapas interactivos.
Se parte de un dataset nacional de localidades y se filtran únicamente los registros correspondientes a la CDMX. El sistema genera visualizaciones que permiten:

•	Identificar zonas de alta densidad de población.
•	Mostrar divisiones por alcaldía en un mapa.
•	Agregar etiquetas con el nombre de cada alcaldía para facilitar el análisis.

Este tipo de análisis es útil para planificación urbana, estudios de mercado, políticas públicas o proyectos inmobiliarios.
________________________________________

Requisitos

Antes de iniciar, asegúrate de tener instalado en tu sistema:

•	Python 3.8+
•	Git
•	Un entorno virtual (recomendado: venv o conda)

Dependencias principales (indicadas en requirements.txt):

•	pandas
•	geopandas
•	matplotlib / folium
•	jupyter (si deseas correr notebooks interactivos)
________________________________________

Instalación y Uso

1. Clonar el repositorio
Abre una terminal y ejecuta:
git clone https://github.com/JavierBermejoGuerrero/estudio-urban-cdmx.git
2. Acceder al directorio del proyecto
cd estudio-urban-cdmx
3. Crear un entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate   # en Linux/Mac
venv\Scripts\activate      # en Windows
4. Instalar dependencias
pip install -r requirements.txt
5. Ejecutar el análisis
Si es un notebook Jupyter:
jupyter notebook
y abre el archivo principal (censo_cdmx.ipynb).

________________________________________

Resultados

•	Mapas interactivos de la CDMX con división por alcaldías.
•	Identificación visual de zonas con mayor concentración de población y vivienda.
•	Posibilidad de extender el análisis a otras variables urbanas.

________________________________________

Autor

Proyecto desarrollado por Javier Bermejo Guerrero como parte de una prueba técnica profesional para análisis de datos urbanos.
