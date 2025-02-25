# Project-VideoGames-Analysis

# Análisis de Ventas de Videojuegos - Ice

### 📝 Descripción del Proyecto:
Este proyecto analiza datos históricos de ventas de videojuegos para identificar patrones clave que influyen en el éxito comercial de un título. Se examinan variables como plataformas, géneros, reseñas de usuarios y críticos, y clasificaciones ESRB con el objetivo de optimizar estrategias de marketing y planificación de ventas.

### 🎯 Objetivo del Proyecto:
Determinar qué factores contribuyen al éxito de un videojuego para ayudar a la tienda online Ice a mejorar su planificación publicitaria y tomar decisiones informadas sobre títulos con alto potencial de ventas en 2017.

### Descripción de datos
- Name (Nombre)
- Platform (Plataforma)
- Year_of_Release (Año de lanzamiento)
- Genre (Género) 
- NA_sales (ventas en Norteamérica en millones de dólares estadounidenses) 
- EU_sales (ventas en Europa en millones de dólares estadounidenses) 
- JP_sales (ventas en Japón en millones de dólares estadounidenses) 
- Other_sales (ventas en otros países en millones de dólares estadounidenses) 
- Critic_Score (máximo de 100) 
- User_Score (máximo de 10) 
- Rating (ESRB)

## Etapas de Análisis

1. **Limpieza de Datos**:
    - Convertir los nombres de las columnas a minúsculas para evitar errores de tipografía.
    - Manejar los valores ausentes imputando datos adecuados o marcando los valores como `unknown`.
    - Realizar análisis exploratorio de datos para identificar tendencias iniciales y detectar posibles outliers.
    

2. **Análisis de Ventas**:
    - Evaluar la suma total de ventas por juego y plataforma.
    - Analizar la distribución de lanzamientos de juegos a lo largo de los años y su impacto en las ventas.
    - Identificar las plataformas más rentables y evaluar la duración de su ciclo de vida.
    

3. **Impacto de Reseñas y Críticas**:
    - Investigar cómo las calificaciones de usuarios y críticos afectan las ventas de juegos en diferentes plataformas.
    - Analizar la correlación entre las reseñas y el éxito comercial de un juego.
    

4. **Distribución por Género**:
    - Examinar la distribución de juegos por género y su rentabilidad.
    - Identificar patrones de ventas en géneros populares y de nicho.
    

5. **Análisis Regional**:
    - Determinar las plataformas más populares en Norteamérica, Europa y Japón, y las diferencias en las cuotas de mercado.
    - Evaluar cómo las clasificaciones ESRB afectan las ventas en cada región.
    

6. **Formulación de Hipótesis**:
    - Comparar las calificaciones promedio de usuarios para diferentes plataformas y géneros, y probar la significancia de las diferencias observadas.


7. **Conclusiones**:
    - Resumir los hallazgos clave del análisis, destacando los factores que influyen en el éxito de los videojuegos, y proporcionar recomendaciones estratégicas para futuras campañas publicitarias.
------

### 📊 Conclusiones Finales:
- Plataformas más rentables: La PS2 es la plataforma con mayores ventas totales (1,255.77M), seguida por la X360 (971.42M) y la PS3 (939.65M). Sin embargo, la Wii mostró una tendencia a la baja en rentabilidad, mientras que las consolas de PlayStation han mantenido un ciclo de vida más estable con nuevas versiones.
- Géneros más vendidos: Los videojuegos de Acción, Deportes y Shooter dominan las ventas, mientras que los géneros de Aventura y Estrategia son menos rentables, aunque pueden ser exitosos en mercados de nicho.
- Impacto de las reseñas: Existe una correlación positiva entre las calificaciones de críticos y usuarios con las ventas, especialmente en plataformas como PS2, donde mejores puntuaciones impulsan significativamente el éxito comercial.
- Diferencias regionales: En Norteamérica, las plataformas más vendidas son X360 y PS2, mientras que en Europa dominan PS2 y PS3. En Japón, las consolas portátiles como DS y 3DS son las más populares.
- Clasificación ESRB: En NA y EU, los juegos con clasificación E (Everyone) tienen más ventas, mientras que en Japón, las clasificaciones ESRB parecen tener menor impacto debido a diferencias en los sistemas de clasificación.

## 🛠 Habilidades Adquiridas:
- Análisis exploratorio de datos (EDA)
- Visualización de datos con Matplotlib y Seaborn
- Modelado de ventas y rentabilidad
- Pruebas de hipótesis y análisis estadístico
- Limpieza y preprocesamiento de datos con pandas y NumPy

## 📚 Lecciones Aprendidas:
- Importancia del análisis regional: La popularidad de las plataformas y géneros varía según la ubicación, lo que destaca la necesidad de estrategias de mercado específicas.
- Impacto de las reseñas: Las opiniones de los usuarios y críticos pueden definir el éxito de un videojuego, por lo que las empresas deben monitorear activamente estas métricas.
- Ciclo de vida de las plataformas: Las consolas tienen un período de auge y caída, lo que significa que las campañas publicitarias deben ajustarse en función de estos cambios.
