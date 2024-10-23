# 🐍 Lab 4.3: Generación de Base de Datos con Python y CSV

## 📖 Descripción
Este proyecto consiste en la creación de una base de datos utilizando Python a partir de archivos CSV proporcionados. El objetivo es automatizar el proceso de ingestión de datos en una base de datos relacional, realizar consultas SQL para obtener información relevante y responder a las preguntas planteadas en el Jupyter Notebook del laboratorio.

Los archivos CSV proporcionados contienen datos meteorológicos y de localización que han sido procesados para crear tablas en una base de datos que luego es consultada para obtener información útil.

## 🗂️ Estructura del Proyecto

```bash
├── data/                  # Archivos CSV con los datos originales
│   ├── municipios.csv      # Información de los municipios
│   ├── df_aemet_final.csv  # Datos meteorológicos procesados
│   ├── api_foursquare.csv  # Datos de localización de la API Foursquare
├── notebooks/             # Jupyter Notebooks con la implementación
│   ├── Lab.4.3.Python-SQL.ipynb  # Notebook principal del proyecto
├── README.md              # Descripción del proyecto (este archivo)
```

## 🛠️ Instalación y Requisitos

Para ejecutar este proyecto necesitarás las siguientes herramientas y bibliotecas:

- **Python 3.8** o superior.
- **Bibliotecas requeridas**:
  - pandas
  - sqlite3
  - numpy

Puedes instalar las bibliotecas ejecutando el siguiente comando:

```bash
pip install pandas sqlite3 numpy
```

## 🚀 Instrucciones de Ejecución

1. Clona este repositorio en tu máquina local.
2. Coloca los archivos CSV dentro de la carpeta `data/`.
3. Abre el archivo Jupyter Notebook (`Lab.4.3.Python-SQL.ipynb`).
4. Ejecuta las celdas del Notebook paso a paso para generar la base de datos y realizar las consultas SQL requeridas.

## 📊 Resultados y Conclusiones

- Se han generado tablas a partir de los archivos CSV utilizando Python y `sqlite3`.
- Se realizaron diversas consultas SQL para extraer información útil, como el clima en los municipios de interés y lugares destacados usando la API de Foursquare.
- El proyecto facilita la creación automatizada de bases de datos relacionales a partir de datos CSV.

## 🔄 Próximos Pasos

- Optimizar las consultas SQL para mejorar el rendimiento.
- Explorar la integración con otras APIs para enriquecer los datos.
- Mejorar el proceso de limpieza de datos antes de la ingestión.
 
