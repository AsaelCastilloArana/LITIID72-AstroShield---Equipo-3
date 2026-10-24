# LITIID72-AstroShield---Equipo-3
Integrantes:

Castillo Arana Abisai Asael
24394141
González Garcia Jorge Alexander
24393205
Erick Francisco Liévano Gómez 
24383182
Cristopher Alexis Hay Arceo
24393195

Proyecto AstroShield — Evolucionar una constelación inteligente
Bienvenido al repositorio oficial de AstroShield, un sistema inteligente desarrollado como proyecto académico para diseñar, optimizar y validar constelaciones de satélites mediante técnicas de inteligencia artificial y computación evolutiva.

Descripción del Proyecto
El reto principal de AstroShield consiste en ubicar de manera óptima un conjunto limitado de 8 satélites para observar 6 regiones terrestres críticas, respetando estrictamente zonas restringidas por acumulación de desechos espaciales y posiciones ocupadas por objetos preexistentes.

Para resolver este problema computacional de alta complejidad geométrica, el sistema implementa un Algoritmo Genético de Codificación Real (RCGA) sobre una esfera tridimensional, integrando operadores adaptativos, selección por torneo con reglas de factibilidad de Deb y una función de aptitud multicriterio que equilibra la cobertura regional, el centrado milimétrico y la seguridad orbital.

Declaración de Uso de Inteligencia Artificial y Validación del Equipo
Durante el desarrollo del proyecto AstroShield, el equipo utilizó herramientas de Inteligencia Artificial generativa como asistente de consulta técnica, estructuración de código y revisión de documentación. El diseño conceptual del modelo evolutivo, la definición de las reglas de negocio y la validación experimental fueron ejecutados y verificados directamente por los integrantes del equipo.

¿Para qué se utilizaron las herramientas de IA?
- Consulta de formulación matemática y geodésica: Apoyo para estructurar la implementación en código de la fórmula ortodrómica de Haversine y la ecuación de trazado de anillos geodésicos (computeGeodesicCirclePoints) con el fin de evitar deformaciones visuales cerca de los polos y en el cruce del antimeridiano.
- Prototipado de visualización gráfica y maquetación: Asistencia en la configuración de propiedades de cámaras, trazas Scattergeo en Plotly (para Google Colab) y generación de escenas en Three.js / Canvas 2D para agilizar la construcción de la interfaz gráfica.   
- Estructuración y formato de reportes técnicos: Apoyo en la organización de tablas en formato Markdown y redacción limpia de las justificaciones técnicas que el equipo definió para cada entregable.

¿Qué verificaciones y correcciones realizó el equipo sobre los resultados obtenidos?
El equipo no utilizó las salidas de la IA de forma directa sin auditoría; por el contrario, se realizaron las siguientes verificaciones y ajustes manuales:
-Verificación manual de conversión de unidades (Kilómetros vs. Grados)
-Detección y corrección del problema de "colapso de respaldos" en regiones de Prioridad Alta
-Ajuste de pesos en la función de penalización
-Auditoría de correspondencia entre telemetría numérica y visualización 3D
