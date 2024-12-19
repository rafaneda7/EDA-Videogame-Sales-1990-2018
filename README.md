Análisis Exploratorio de Datos (EDA): Ventas de Videojuegos 🎮
Descripción General
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) del mercado de videojuegos entre 1990 y 2018, evaluando las ventas globales y regionales por género, plataforma y región geográfica. El objetivo es entender las tendencias de mercado y proporcionar insights clave para mejorar la toma de decisiones estratégicas en la industria.

Contenidos
Introducción
Metodología
Limpieza de datos
Análisis univariante
Análisis bivariante
Análisis multivariante
Análisis y Resultados
Géneros más rentables
Distribución regional de ventas
Comportamiento de compañías líderes
Tendencias temporales
Conclusiones y Recomendaciones
Datos
Fuente de Datos
El dataset utilizado fue obtenido de Kaggle.

Variables categóricas: console, genre, publisher, developer.
Variables numéricas: total_sales, na_sales, pal_sales, jp_sales, critic_score, other_sales.
Variables temporales: release_date, update_date.
Tratamiento de Datos
Valores nulos:
Se asumió que los desarrolladores y publicadores se superponen cuando uno está ausente.
Ventas faltantes se rellenaron con 0.
Fechas incompletas se combinaron para reducir los valores nulos.
Agrupación de Géneros: Se consolidaron géneros en categorías principales para simplificar el análisis.
Principales Insights
Géneros más rentables:
Action, Shooter y Sports dominan el mercado global.
Tendencias regionales:
Norteamérica y Europa prefieren géneros como Shooter y Sports.
Japón se destaca por su preferencia por RPG, Puzzle y Strategy.
Temporalidad:
Las ventas se concentran en los meses de octubre y noviembre, probablemente debido a la temporada navideña.
Liderazgo de compañías:
Sony (PlayStation) y Microsoft (Xbox) lideran las ventas globales.
Nintendo tiene un desempeño sobresaliente en Japón.
Conclusiones
Regiones: Adaptar estrategias a preferencias regionales.
Temporalidad: Enfocar lanzamientos importantes en el último trimestre.
Géneros líderes: Priorizar géneros populares en futuras campañas.
Personalización regional: Campañas específicas para Japón basadas en RPG y similares.
Requisitos
Tecnologías utilizadas
Python: pandas, numpy, matplotlib, seaborn.
Jupyter Notebook: Para la visualización y análisis interactivo.
Presentaciones: Archivos PDF y PPT para documentar los resultados.
Instalación
Clona el repositorio:
bash
Copiar código
git clone https://github.com/rafaneda7/eda-videojuegos.git
Instala las dependencias:
bash
Copiar código
pip install -r requirements.txt
Ejecuta los análisis en los notebooks disponibles.
Contacto
Autor: Rafael Neda
Correo: rafael.angel.neda@gmail.com
Ubicación: Valencia, España
Visita el repositorio en GitHub.
