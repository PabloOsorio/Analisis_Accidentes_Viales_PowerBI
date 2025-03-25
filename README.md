# Proyecto de Power BI - [Accidentes viales de Estados Unidos 2022]

## Descripción
Este es mi primer proyecto utilizando Power BI basado en el curso "Power BI sin complicaciones de A2 Capacitación: Excel" y el dataset proporcionado por la Administración Nacional de Seguridad en el Tráfico en las Carreteras (NHTSA). El conjunto de datos cubre todos los accidentes viales ocurridos en Estados Unidos durante el año 2022, incluyendo información sobre las personas involucradas, las ubicaciones de los accidentes y los tipos de lesiones (incluyendo decesos).

El principal objetivo de este proyecto es explorar y analizar los datos para obtener insights significativos relacionados con los accidentes viales. Además he utilizado este proyecto para practicar el uso de diversas herramientas y consultas de Power BI, con el fin de mejorar mis habilidades en la visualización de datos y la identificación de patrones clave.

## Datos

- Fuente de datos: www.a2capacitacion.com/descargables%252bpower%252bbi+2.zip
- Los datos estan traducidos al español por el creador del curso. 
No esta el link del dataset original pero buscando en internet encontre la siguiente liga y parece es el dataset en su version en ingles https://catalog.data.gov/dataset/fatality-analysis-reporting-system-fars-2022-accidents1 

## Dashboard
Aquí hay imagenes de los dashboards finales.
([Imagenes\dashboard_1.png](https://github.com/PabloOsorio/Analisis_Accidentes_Viales_PowerBI/tree/main/Imagenes))

## Insights 

### Dashboard_1 - En este primer dashboard se presentan los resultados del análisis exploratorio inicial, destacando métricas clave como el número total de decesos, el total de accidentes y el promedio de bajas por accidente. Estos indicadores proporcionan una visión general de la gravedad de los accidentes viales en los Estados Unidos durante el año 2022.

Algunos hallazgos relevantes incluyen:

Un promedio de 1.08 decesos por accidente, lo que refleja la severidad de los incidentes registrados.

Un aumento significativo de decesos durante los meses de calor (Julio, Agosto, Septiembre, Octubre)

California como el estado con la mayor cantidad de accidentes fatales.

En cuanto a posibles explicaciones, el promedio de decesos por accidente podría estar influenciado por la subrepresentación de accidentes menores, ya que los incidentes fatales suelen recibir mayor atención y registro. El incremento de decesos en meses cálidos podría correlacionarse con el incremento de viajes y mayor exposición al riesgo. Finalmente, el elevado número de decesos en California podría explicarse por su condición demográfica y el mayor número de vehículos en circulación.



### Dashboard_2 - Este segundo dashboard analiza aspectos relacionados con el tipo de población involucrada en accidentes viales, los decesos según el tipo de vialidad y las principales causas de los accidentes.

1. Tipo de Población:
Los datos revelan que las zonas urbanas registran la mayor cantidad de accidentes viales. Este fenómeno podría atribuirse al ritmo de vida más acelerado(frenetico) y a la mayor concentración de vehículos en espacios reducidos, lo que incrementa la probabilidad de colisiones.

2. Decesos por Tipo de Calle:
Como era previsible, las vialidades principales como las Highways Estatales, las US Highways y las calles locales presentan un mayor número de decesos. Esto puede explicarse por el elevado volumen de tránsito y las velocidades más altas en las primeras dos vías

3. Causas de Accidentes:
En cuanto a las causas, los accidentes son diversos, pero predominan aquellos originados por la interacción con otros vehículos en movimiento y los incidentes por volcaduras. Estos factores reflejan la complejidad del tráfico urbano, donde las decisiones de otros conductores y las condiciones del camino pueden ocasionar accidentes graves



### Dashboard_3 _ Este último dashboard proporciona un análisis sobre las marcas automotrices con mayor cantidad de decesos, el género más afectado en accidentes viales, y una evaluación de los estados con más decesos por cada 100,000 habitantes. Además incluye un mapa de calor de los Estados Unidos que visualiza la concentración geográfica de los accidentes.

1. Marcas Automotrices:
Es importante destacar que la presencia de ciertas marcas en los datos no implica necesariamente que se trate de vehículos inseguros. La alta incidencia podría estar relacionada con la popularidad y la cantidad de vehículos en circulación de dichas marcas.
Chevrolet y Ford encabezan la lista, ocupando el primer y segundo lugar, respectivamente.
Honda y Toyota también figuran con una alta presencia en los accidentes reportados.
Harley Davidson aparece en el tercer lugar, lo que podría reflejar una mayor vulnerabilidad de los motociclistas en comparación con los conductores de automovil

2. Género de las victimas:
Los datos indican que los hombres representan la mayor proporción de decesos en accidentes viales, lo cual es coherente con tendencias globales donde factores como el comportamiento de conducción y la exposición a riesgos pueden influir en estos datos

3. Análisis por Estado:
Para obtener una visión más equitativa, se utilizó la métrica de decesos por cada 100,000 habitantes, ajustando los resultados a la población de cada estado. Con dicho enfoque se observan que los estados con mayor tasa de mortalidad son:

Mississippi

Wyoming

Nuevo México

Carolina del Sur

Arkansas

Alabama

Estos resultados sugieren una mayor incidencia de accidentes fatales en los estados del Sur y las regiones desérticas, donde factores como la infraestructura vial y conductas de manejo pueden contribuir a este fenómeno.
Cabe resaltar que, a pesar de ser el estado con más decesos en términos absolutos, California no aparece en el top 20 cuando se ajusta por población. Esto refleja cómo una alta densidad poblacional puede influir en la percepción de los accidentes

## Cómo Ver el Proyecto? 

1. Descargar el archivo `.pbix`.
2. Abrirlo con **Power BI Desktop**.