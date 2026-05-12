# Proyecto_Madrid_al_descubierto 

Proyecto para el concurso de reutilización de datos abiertos del Ayuntamiento de Madrid
Madrid Al Descubierto: Análisis Inteligente de Ciudades Urbanas 🏙️📊

<img width="965" height="554" alt="Portada_proyecto_madrid_al_descubierto_2026" src="https://github.com/user-attachments/assets/4d772912-ac20-4922-b4c3-8335330088f4" />



📋 __Resumen del Proyecto__

Este repositorio contiene el desarrollo técnico y la memoria estratégica para la Solicitud de Participación en los Premios a la Reutilización de los Datos Abiertos del Ayuntamiento de Madrid.

El proyecto trasciende la visualización de datos convencional para ofrecer una herramienta de diagnóstico territorial. Hemos analizado los microdatos de la Encuesta de Calidad de Vida 2025 para identificar brechas críticas en seguridad, conciliación y salud ambiental, prescribiendo soluciones basadas en evidencia para un Madrid más cohesionado.


👥 __Autoras__ 

Milena Anahí Aguilera Castroverde - linkedin.com/in/milena-aguilera-castroverde

Valeria Angélica Mora Salcedo - linkedin.com/in/valeriamoras

Aliris del Carmen Escobar Reyes - linkedin.com/in/alirisescobarreyes

Rocío Montero Delgado - linkedin.com/in/rocio-montero-delgado

Lorena Alejandra Serra Sánchez - linkedin.com/in/lorena-a-serra


🎯 __El Problema: La "Paradoja de Satisfacción"__

Madrid presenta una alta valoración general de servicios, pero esconde brechas invisibles entre sus 21 distritos. Nuestro análisis se centra en los contrastes entre distritos de alta satisfacción (Barajas, Salamanca, Chamberí) frente a aquellos con mayores retos (Villaverde, Puente de Vallecas y Usera).

Hallazgos clave:
Brecha de Seguridad: Caída de percepción de hasta 2.1 puntos en el indicador nocturno en distritos específicos.

Déficit de Conciliación: Correlación directa entre tipos de hogar (monoparentales/familias jóvenes) y la insatisfacción con equipamientos 0-3 años.

Salud Urbana: Necesidad de expansión de zonas de bajas emisiones basada en la percepción de calidad del aire y ruido.


🛠️ __Metodología Técnica__

Ingesta y Limpieza: Procesamiento de 8.593 registros mediante Python (Pandas/NumPy) para normalizar microdatos y tratar nulos.

Análisis Exploratorio (EDA): Identificación de correlaciones entre variables demográficas (género, edad, tipo de hogar) y satisfacción.

Visualización: Dashboard interactivo que permite un análisis interseccional por distrito y perfil social.

Geolocalización: Mapeo del "gradiente de bienestar" para priorizar inversiones públicas.


💡 __Propuestas de Impacto__

Plan "Sendas Seguras": Corredores de iluminación inteligente en rutas críticas de transporte.

Nodos de Micro-Escuelas: Reequilibrio de infraestructura infantil en parcelas infrautilizadas según déficit detectado.

Supermanzanas Periféricas: Mejora de la habitabilidad fuera de la M-30 en puntos calientes de insatisfacción ambiental.


📂 __Estructura del Repositorio__

/notebooks: EDA_proyecto.ipynb - Código fuente del análisis y limpieza.

/data: Referencias a los datasets del Portal de Datos Abiertos.

/docs: Memoria técnica del proyecto (Formato DIN A4).

/visuals: Capturas de pantalla del Dashboard y gráficas analíticas.


🔗 __Datos Abiertos Utilizados__

Este proyecto reutiliza conjuntos de datos del Portal de Datos Abiertos del Ayuntamiento de Madrid:

Encuesta de Calidad de Vida y Satisfacción con los Servicios Públicos (2025).

Estadísticas de actuaciones de la Policía Municipal.

Inventario de Equipamientos Municipales y Bases Demográficas.
