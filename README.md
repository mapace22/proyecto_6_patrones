# proyecto_6_patrones
Patrones de éxito en Tienda de videojuegos "Line Ice" | Limpieza, manipulación y transformación | Detectar proyectos prometedores | Planificar estrategia de Marketing

# PROYECTO: ¡A JUGAR SE HA DICHO!

## RESUMEN DEL PROYECTO
Este proyecto se enfoca en el análisis de datos de "Tienda line Ice", una plataforma global de venta de videojuegos. 
El objetivo principal es identificar patrones de éxito en el mercado de videojuegos a partir de un conjunto de datos público que incluye reseñas, géneros, plataformas e historial de ventas hasta 2016.
La misión es planificar una campaña publicitaria para el año 2017, adquiriendo experiencia en la limpieza, manipulación y transformación de datos. 
Se explora también la clasificación ESRB de los juegos para entender las audiencias.

## OBJETIVO
- El objetivo principal es identificar patrones de éxito en el mercado de los videojuegos que permitan a la empresa:
  - Detectar proyectos de juegos prometedores.
  - Planificar estrategias de marketing más efectivas para el año 2017.

## METODOLOGÍA DE ANÁLISIS
### 1. DESCRIPCIÓN DE LOS DATOS
- Se trabajó con un único conjunto de datos que incluye información sobre:
  - Juegos
  - Plataformas
  - Año de lanzamiento
  - Género
  - Ventas por región (Norteamérica, Europa, Japón y otras)
  - Puntuación de críticos y usuarios,
  - Clasificación ESRB.

### 2. PREPROCESAMIENTO DE DATOS
- Reemplazo y Conversión:
  - Se limpiaron los datos
  - Se ajustaron los tipos de datos de las columnas para un análisis más eficiente
  - Se gestionaron los valores ausentes.

- Valores Ausentes: Se identificaron y trataron los valores nulos en las columnas Name, Genre, Year_of_Release, Critic_Score, User_Score y Rating.

- Cálculo de Ventas Totales: Se calculó el total de ventas globales sumando las ventas de cada región.

### 3. ANÁLISIS DE DATOS
- Análisis Temporal: Se examinó la distribución de lanzamientos de juegos a lo largo de los años.
- Análisis de Plataformas: Se estudiaron las ventas por plataforma, sus ciclos de vida y su impacto en el mercado.
- Perfil del Usuario por Región: Se identificaron las plataformas principales, géneros y clasificaciones ESRB más populares en Norteamérica, Europa y Japón.
- Visualizaciones: Se utilizaron diagramas de caja y gráficos de dispersión para visualizar la distribución y la relación entre variables como ventas, puntuación y año de lanzamiento.

### 4. PRUEBA DE HIPÓTESIS
Se realizaron pruebas de hipótesis para determinar si:
Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son diferentes.
Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
Se estableció un umbral de significancia (alfa) y se formuló una hipótesis nula y una alternativa para cada prueba.

## CONCLUSIONES PRINCIPALES
El proyecto fue aprobado, lo que indica un análisis correcto y exhaustivo.
Se identificaron patrones de éxito en el mercado de videojuegos.
Se lograron conclusiones sólidas para planificar una campaña publicitaria efectiva para el año 2017, incluyendo la identificación de plataformas y géneros clave por región.

## TECNOLOGÍAS UTILIZADAS
Python
Pandas
NumPy
Matplotlib

Jupyter Notebook
