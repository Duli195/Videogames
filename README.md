# Análisis del Mercado de Videojuegos — Tendencias, Ventas y Preferencias Regionales

Descripción general

Este proyecto tiene como objetivo analizar el comportamiento del mercado global de videojuegos, explorando cómo las ventas, géneros, plataformas y calificaciones han evolucionado a lo largo del tiempo.
A partir del conjunto de datos games.csv, se realizó un proceso de preparación, limpieza y análisis exploratorio para identificar patrones en los lanzamientos, las preferencias de los jugadores y las diferencias entre regiones.
El estudio abarca desde la detección de valores ausentes hasta pruebas estadísticas que comparan las calificaciones de los usuarios entre plataformas y géneros. Durante el análisis se desarrollaron visualizaciones descriptivas que muestran:

La evolución del número de lanzamientos por año.

Las plataformas con mayores ventas globales y regionales.
La distribución de ventas por género y región.
La relación entre las reseñas de críticos y usuarios con las ventas.
Las diferencias significativas en calificaciones entre plataformas y tipos de juegos.

Conclusiones

Preparación y limpieza de datos
Se revisaron y transformaron las columnas para corregir errores de formato, convertir tipos de datos y tratar valores ausentes.
Se reemplazaron los valores 'tbd' de la columna user_score por NaN para evitar sesgos en el análisis.

Análisis general

El número de lanzamientos alcanzó su pico entre 2008 y 2011, seguido por una reducción en años posteriores.
Las plataformas históricamente más exitosas fueron PS2, X360 y Wii, mientras que PS4 y 3DS dominaron los últimos años del análisis.
Los géneros de Acción, Deporte y Shooter concentraron la mayoría de las ventas globales.
Se observó una correlación positiva entre las críticas de expertos y las ventas, especialmente en plataformas como PS4, mientras que la influencia de las calificaciones de usuarios fue más débil.

Preferencias regionales

Norteamérica y Europa mostraron preferencia por consolas de sobremesa como X360 y PS3.
Japón destacó por su preferencia hacia plataformas portátiles como 3DS y DS, y por su afinidad con los juegos de Rol (RPG).
Las clasificaciones ESRB influyeron más en los mercados de NA y EU que en Japón.

Resultados de las pruebas de hipótesis

H₁: Se detectó una diferencia significativa entre las calificaciones promedio de usuarios en Xbox One y PC, lo que sugiere distintos perfiles de usuario por plataforma.
H₂: No se encontró diferencia significativa entre las calificaciones de los géneros Acción y Deportes, lo que indica una percepción similar entre jugadores en esos segmentos.

Recomendaciones

Enfocar las campañas de marketing de juegos de acción y disparos en los mercados de Norteamérica y Europa, especialmente en PS4 y XOne.
En Japón, priorizar la promoción de juegos de rol (RPG) en consolas portátiles.
Considerar la influencia de las reseñas de críticos como un indicador clave de ventas futuras.
