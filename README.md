# mercado-bursatil-recomendaciones

El presente proyecto busca analizar en detalle el mercado bursátil de las principales 500 empresas pertenecientes al índice SP500 (Standard & Poor's 500 Index) en el período comprendido entre el año 2000 y el presente año 2023. El análisis se enfocará en distintos aspectos, como la variación de precios en el tiempo, la comparación entre distintas acciones, el cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otras), recomendaciones basadas en el retorno y riesgo de inversión, y la creación de KPIs útiles para la toma de decisiones de inversión.

El informe del proyecto está compuesto por un análisis exploratorio de los datos (EDA), el cual incluye un resumen de estadísticas descriptivas, análisis univariados y bivariados, entre otros, que permita entender mejor los datos, encontrar patrones, outliers y/o anomalías, etc. Este análisis se presenta en un notebook (.ipynb) con adecuado uso de markdowns y comentarios.

Se incluye un dashboard, que permite visualizar la información de forma clara y coherente, y algunos KPIs sugerios junto con su funcionalidad. 

Como resultado, se espera obtener una visión general del mercado bursátil y generar recomendaciones de inversión, incluyendo en qué compañías invertir y qué día de la semana es recomendable hacerlo, todo con el objetivo de que una empresa que busca invertir en este mercado pueda tomar decisiones informadas.

En este repositorio podrá encontrar todos los archivos necesarios para el análisis y presentación de los resultados.

Se propones los siguientes objetivos:

1) Realizar un análisis exploratorio de los datos para conocer la situación del mercado bursátil en los últimos 23 años, incluyendo la variación de precios en el tiempo, comparación entre distintas acciones y cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otros).

2) Generar recomendaciones de inversión basadas en el retorno y riesgo de inversión, enfocadas en empresas o rubros de éstas.

3) Crear KPIs útiles para la toma de decisiones de inversión.

4) Desarrollar un dashboard interactivo utilizando la herramienta Streamlit que permita visualizar y explorar los datos analizados y presentar las recomendaciones y KPIs generados.

Metodología:

1) Para lograr el objetivo #1 se realizará lo siguiente: 

1.1 Descargar los datos históricos del índice SP500 y de las empresas que lo conforman utilizando la librería yfinance.
1.2 Realizar una exploración inicial de los datos, observando la distribución de variables numéricas, la presencia de outliers o valores faltantes, y cualquier otra característica relevante.
1.3 Visualizar la variación de precios en el tiempo, tanto del índice SP500 como de las acciones individuales, utilizando gráficos de línea.
1.4 Comparar la variación de precios entre las diferentes acciones mediante la creación de gráficos de líneas superpuestas.
1.5 Calcular y visualizar estadísticas bursátiles relevantes, tales como la volatilidad, el promedio móvil, el retorno diario, el riesgo, entre otras.
1.6 Identificar cualquier patrón, tendencia o comportamiento relevante a través de la exploración y el análisis de los datos.
Descargar los datos históricos del índice SP500 y de las empresas que lo componen utilizando el módulo yfinance.

2) Para lograr el objetivo #2 se realizará lo siguiente:

2.1 Seleccionar las empresas que tengan una buena relación riesgo-retorno en el período analizado.
2.2 Realizar un análisis de correlación para identificar aquellas empresas que tengan una correlación baja entre ellas, es decir, que no se comporten de manera similar en el mercado.
2.3 Identificar rubros que hayan tenido un buen rendimiento en el período analizado y seleccionar empresas dentro de estos rubros.
2.4 Realizar un análisis de regresión para identificar aquellas empresas que tengan un buen ajuste a la tendencia del mercado.
2.5 Utilizar la técnica de clustering para agrupar empresas similares y seleccionar aquellas que se encuentren en grupos con buen desempeño.
2.6 Analizar noticias y eventos recientes que puedan afectar el desempeño futuro de las empresas.
2.7 Presentar recomendaciones de inversión en base a los análisis realizados.

NOTA: Es importante tener en cuenta que las recomendaciones de inversión no son una garantía de ganancia, sino que son una orientación en base a los análisis realizados y a la situación actual del mercado.

3) Para lograr el objetivo #3 se seguirán estos pasos:

3.1 Identificar las variables y métricas más relevantes para la inversión en bolsa. Esto podría incluir, por ejemplo, la rentabilidad, el riesgo, la volatilidad, el volumen de operaciones, la capitalización de mercado, entre otros.
3.2 Seleccionar las empresas del índice SP500 sobre las cuales se construirán los KPIs. Es importante que las empresas sean representativas del mercado bursátil y que incluyan una variedad de sectores y rubros.
3.3 Calcular los KPIs para cada empresa. Estos pueden incluir métricas como la rentabilidad promedio, el riesgo relativo, la volatilidad, la relación precio-beneficio (P/E ratio), entre otros.
3.4 Evaluar y comparar los KPIs de las diferentes empresas para identificar aquellas que ofrecen mejores oportunidades de inversión. Es importante tener en cuenta el contexto del mercado bursátil y otros factores externos que puedan influir en la inversión.
3.5 Presentar los KPIs de forma clara y concisa, utilizando visualizaciones y gráficos interactivos para facilitar la comprensión y la toma de decisiones de inversión.
3.6 Realizar un seguimiento constante de los KPIs y actualizarlos regularmente para mantenerse al tanto de los cambios en el mercado y hacer ajustes en las decisiones de inversión si es necesario.

4) Para lograr el objetivo #4 se seguirán los siguientes pasos: 

4.1 Seleccionar la herramienta de visualización de datos y framework Streamlit para la creación del dashboard.
4.2 Crear un archivo de Python que contenga el código para generar el dashboard.
4.3 Importar los datos procesados y analizados en los objetivos anteriores para su uso en el dashboard.
4.4 Seleccionar las visualizaciones y gráficos que se utilizarán para mostrar la información de manera clara y concisa.
4.5 Crear las funciones y objetos interactivos necesarios para la exploración y manipulación de los datos.
4.6 Crear una interfaz de usuario amigable que permita al usuario interactuar con el dashboard.
4.7 Probar el dashboard y asegurarse de que la información se muestre de manera clara y coherente.
4.8 Hacer ajustes y mejoras según sea necesario.
4.9 Desplegar el dashboard en una plataforma en línea para su acceso y uso por parte de la empresa.


Se documentará todo el proceso en un notebook de Jupyter y en este repositorio de GitHub.
