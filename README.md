**ETL de Datos de Hoteles y Eventos en Madrid**

*Descripción del Proyecto*

Este proyecto tiene como objetivo extraer, transformar y cargar (ETL) datos de reservas hoteleras en Madrid, incorporando información de la competencia y eventos relevantes para análisis.

*Estructura del Proyecto*

El proyecto está estructurado en los siguientes pasos:

*Extracción de Datos*

Lectura de datos desde un archivo Parquet (reservas_hoteles.parquet).

Web Scraping de hoteles de la competencia desde la web de Ibis Accor.

Consumo de la API de eventos del Ayuntamiento de Madrid.

*Transformación de Datos*

Limpieza y estandarización de datos.

Conversión de tipos de datos y validación de valores nulos.

Enriquecimiento de los datos de reservas con eventos en Madrid.

*Carga de Datos*

Creación y carga de datos en PostgreSQL con el siguiente esquema:

ciudad

eventos

hoteles

clientes

reservas

*Consultas y Análisis*

Identificación de los 10 clientes con mayor gasto.

Comparación de ingresos entre hoteles propios y de la competencia.

Análisis temporal de reservas y precios.

*Instalación y Uso*

Requisitos

Python 3.8+

PostgreSQL

Bibliotecas necesarias:

pandas 
psycopg2 s
elenium 
requests


**Contribuciones*

Si deseas contribuir, por favor haz un fork del repositorio y envía un Pull Request con tus mejoras.

*Contacto*

Para cualquier duda o sugerencia, contáctame en quiquebrotons83@gmail.com.