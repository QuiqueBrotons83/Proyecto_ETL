# Proyecto ETL: Análisis de Hoteles y Eventos en Madrid

## Descripción del Proyecto

**Objetivo:** Extraer, transformar y cargar (ETL) datos de hoteles y eventos en Madrid para generar insights relevantes.

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

