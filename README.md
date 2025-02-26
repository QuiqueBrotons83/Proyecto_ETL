# Proyecto ETL: Análisis de Hoteles y Eventos en Madrid

## Descripción del Proyecto

**Objetivo:** Extraer, transformar y cargar (ETL) datos de hoteles y eventos en Madrid para generar insights relevantes. 
Con  ello conseguimos un Análisis Eda de los datos, Transformación de las columnas y tipo de dato para que sea eficaz para 
su posterior analisis y carga a un BBDD. A continuación nuestro Objetivo es realizar un scraping de una web en el trabajamos
los aspectos más fundamentales del scrapeo. Y para finalizar accedemos a la web del Ayuntamiento de Madrid para ver los eventos
y conseguir mediante API los eventos que nos piden en el proyecto. Filtrando por nuestros interes para su extracción.


## Requisitos

### **Extracción de Datos**
- **Hoteles:** Cargar archivo `reservas_hoteles.parquet`.
- **Competencia:** Web scraping de [Ibis Accor](https://ibis.accor.com/es/destination/city/hotels-madrid-v2418.html).
- **Eventos:** API del Ayuntamiento de Madrid: [Eventos en Madrid](https://datos.madrid.es/portal/site/egob/).

### **Transformación de Datos**
- Limpieza y estructuración de los datos extraídos.
- Enriquecimiento de reservas con información de eventos en las mismas fechas.

### **Carga de Datos**
- Cargamos todas las tablas para insertar los csv, correspondientes de Hoteles_unidos, y eventos.
- Almacenar datos en PostgreSQL con las tablas correspondientes.
- Despúes de la carga realizamos querys para garantizar que todo esta correcto.




## **Autora/Autor**
- **Quique Brotons**  
- Contacto: [quiquebrotons83@gmail.com]  

