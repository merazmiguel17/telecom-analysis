# telecom-analysis
## Objetivo del Proyecto
El objetivo principal de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. A través del análisis estadístico, buscamos:

Identificar patrones de uso de llamadas y mensajes.
Detectar comportamientos atípicos (outliers) que representen necesidades diferenciadas.
Segmentar a los usuarios por edad y nivel de consumo para optimizar la oferta comercial y mejorar la experiencia del usuario.

## Datasets Utilizados
El análisis se basa en tres fuentes de datos principales:

plans.csv: Detalle de los planes actuales (precio, minutos/mensajes incluidos y costos por excedentes).
users_latam.csv: Información demográfica de los clientes (edad, ciudad, fecha de registro y plan contratado).
usage.csv: Registro real del uso de servicios (duración de llamadas y cantidad de mensajes enviados).

## Etapas del Análisis
El proyecto se desarrolló siguiendo estas fases:

# Carga y Limpieza: Importación de datos, manejo de valores ausentes (como churn_date) y estandarización de tipos de datos.

# Agregación de Datos: Consolidación del consumo por usuario para unirlo con su perfil demográfico en un DataFrame único (user_profile).

# Análisis Estadístico: Visualización mediante Boxplots para identificar la dispersión de los datos y cálculo de límites mediante el Método del Rango Intercuartílico (IQR).

## Segmentación:

Por Uso: Clasificación en 'Bajo uso', 'Uso medio' y 'Alto uso' mediante lógica condicional.
Por Edad: Clasificación en 'Joven', 'Adulto' y 'Adulto Mayor'.

# Visualización: Creación de gráficos de barras (countplots) para entender la distribución de los segmentos.

# Insights Ejecutivos: Identificación del segmento de mayor valor (Adultos de Uso Medio) y recomendaciones comerciales basadas en hallazgos.
