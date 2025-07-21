# Clima y Calidad del ambiente en Latinoamerica ( SQL + Excel Pivot Tables )

-Este proyecto explora datos sobre calidad del aire y condiciones climáticas en ciudades de América Latina.  
Combina análisis en **SQL** y **tablas dinámicas de Excel** para identificar patrones ambientales y comparar condiciones entre países y ciudades.

# ⚠️ Aclaración de responsabilidad: Desarrollé este Readme con orientación de la IA "Claude" con el único fin de perfeccionarlo y que sea lo mas profesional posible, sin sacrificar mis ideas originales pensadas para el "Readme". Es decir, fue solo una ayuda, mas no una automatización total del proceso.

# 📌 Objetivos buscados en el proyecto:
- Limpieza y orden del DataSet original (organización de celdas, orden de fecha, eliminación de celdas vacias, etc.
- Analizar el Índice de Calidad del Aire (AQI) en LATAM.
- Detectar las ciudades con mayor concentración de contaminantes (PM2.5, PM10).
- Comparar cómo varía la temperatura, humedad y AQI según país, mes o ciudad.
- Visualizar estos patrones mediante gráficos en Excel.
  
# 🛠️ Herramientas y Tecnologías:
- **Excel**: Limpieza de datos y tablas dinámicas.
- **SQL**: Consultas analíticas y toma de decisión.
- **DB Fiddle**: Plataforma para ejecutar consultas SQL.

# 🔧 Proceso de Limpieza de Datos:
Para la limpieza y organización del DataSet, realicé lo siguiente:
- Eliminación de filas vacias de columnas relevantes (AQI, PM2.5)
- Estandarización de las fechas.
- Corrección de nombres de ciudades duplicados o mal escritos.
- Eliminación de valores atípicos extremos en mediciones de contaminantes.

# 🗃️ Aspectos del DataSet:
-**Nombre**: Clima y Calidad del aire en LATAM.
-**Fuente**: Kaggle – Dataset: (https://www.kaggle.com/datasets/anycaroliny/latin-america-weather-and-air-quality-data)  
 
# 🧮 Columnas Destacadas del Proyecto:
- Fecha
- País / Ciudad
- Temperatura (°C)
- Humedad (%)
- AQI
- PM2.5, PM10, CO, NO2, SO2, O3

# 🧪 Análisis con SQL
El archivo vinculado a SQL contiene consultas para responder preguntas como:
- ¿Cuál es la ciudad con peor calidad del aire?
- ¿Qué país tiene el mayor promedio de AQI?
- ¿Cómo varía el AQI a lo largo de los meses?
- ¿Existe relación entre temperatura y contaminación?
(Las consultas fueron ejecutadas en DB Fiddle Online.)

# 📊 Análisis con Excel
El archivo Excel incluye:
- Tablas dinámicas con filtros por ciudad, país, contaminante y mes.
- Gráficos comparativos de PM2.5, AQI y temperatura.
- Ranking de ciudades con mayor contaminación.
- Evolución mensual de condiciones ambientales.

> 📎 Capturas de gráficos incluidos en la carpeta [`images/`](./images)
