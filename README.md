El S&P 500 es un índice bursátil que sigue el rendimiento de las 500 empresas más grandes que cotizan en la bolsa de valores de Estados Unidos, por lo que no es un activo individual que se pueda comprar o vender directamente. Sin embargo, se pueden utilizar instrumentos financieros como ETFs, futuros y opciones para tomar posiciones en el S&P 500 y seguir diferentes estrategias de inversión.

En general, las estrategias de inversión en el S&P 500 se pueden dividir en dos categorías: estrategias a largo plazo y estrategias a corto plazo.

## Estrategias a largo plazo:

Inversión pasiva en el S&P 500: una estrategia a largo plazo común en el S&P 500 es simplemente invertir en un fondo cotizado (ETF) que siga el índice, con el objetivo de obtener ganancias a largo plazo en función del rendimiento del mercado en general.

Inversión en acciones de empresas de alta calidad: otra estrategia a largo plazo es invertir en acciones de empresas que forman parte del S&P 500 y que tienen un historial de crecimiento y rentabilidad a largo plazo.

## Estrategias a corto plazo:

Inversión en ETFs inversos: una estrategia a corto plazo es invertir en ETFs inversos, que se diseñan para seguir el movimiento inverso del S&P 500. Esto permite a los inversores obtener ganancias cuando el índice disminuye en valor.

Trading diario: los inversores que utilizan esta estrategia compran y venden el S&P 500 en el mismo día, esperando obtener ganancias a corto plazo en función de las fluctuaciones diarias del mercado.

Es importante tener en cuenta que cualquier estrategia de inversión conlleva riesgos y es importante analizar cuidadosamente las opciones antes de tomar cualquier decisión de inversión. También es importante diversificar la cartera de inversiones y tener un horizonte de inversión claro para lograr los objetivos a largo plazo.

## ¿Por qué seguir una estrategia de largo plazo?

Generalmente se requiere un mayor conocimiento y experiencia del mercado bursátil para las estrategias a corto plazo, ya que involucran operaciones más frecuentes y de corta duración. Las estrategias a corto plazo como el trading diario y la inversión en ETFs inversos pueden ser riesgosas y pueden llevar a pérdidas significativas si no se comprenden bien.

Para tener éxito en las estrategias a corto plazo, los inversores deben estar bien informados sobre el mercado y las noticias financieras, y también deben tener una buena comprensión de las técnicas de análisis técnico y fundamental. Es importante saber cómo leer gráficos de precios, interpretar indicadores técnicos y estar al tanto de los eventos que puedan afectar al mercado.

Además, las estrategias a corto plazo suelen requerir una dedicación más intensiva de tiempo y recursos que las estrategias a largo plazo. Los inversores que utilizan estrategias a corto plazo deben estar dispuestos a monitorear constantemente el mercado y actuar rápidamente ante los cambios de precio.

En general, las estrategias a corto plazo pueden ser más arriesgadas que las estrategias a largo plazo, y requieren una mayor comprensión y experiencia del mercado bursátil. Se recomienda que los inversores novatos comiencen con estrategias a largo plazo y se familiaricen con el mercado antes de aventurarse en las estrategias a corto plazo.

# El proyecto:

# mercado-bursatil-recomendaciones

El presente proyecto busca analizar el mercado bursátil de las principales 500 empresas pertenecientes al índice SP500 (Standard & Poor's 500 Index) en el período comprendido entre el año 2000 y el presente año 2023. El análisis se enfocará en distintos aspectos, como la variación de precios en el tiempo, la comparación entre distintas acciones, el cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otras), recomendaciones basadas en el retorno y riesgo de inversión, y la creación de KPIs útiles para la toma de decisiones de inversión.

El informe del proyecto está compuesto por un análisis exploratorio de los datos (EDA), el cual incluye un resumen de estadísticas descriptivas, análisis univariados y bivariados, entre otros, que permita entender mejor los datos, encontrar patrones, outliers y/o anomalías, etc. Este análisis se presenta en un notebook (.ipynb) con adecuado uso de markdowns y comentarios.

Se incluye un dashboard, que permite visualizar la información de forma clara y coherente, y algunos KPIs sugerios junto con su funcionalidad. 

Como resultado, se espera obtener una visión general del mercado bursátil y generar recomendaciones de inversión, incluyendo en qué compañías invertir y qué día de la semana es recomendable hacerlo, todo con el objetivo de que una empresa que busca invertir en este mercado pueda tomar decisiones informadas.

En este repositorio podrá encontrar todos los archivos necesarios para el análisis y presentación de los resultados.

## Objetivos

Se proponen los siguientes objetivos:

1. Realizar un análisis exploratorio de los datos para conocer la situación del mercado bursátil en los últimos 23 años, incluyendo la variación de precios en el tiempo, comparación entre distintas acciones y cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otros).

2. Generar recomendaciones de inversión basadas en el retorno y riesgo de inversión, enfocadas en empresas o rubros de éstas.

3. Crear KPIs útiles para la toma de decisiones de inversión.

4. Desarrollar un dashboard interactivo utilizando la herramienta Streamlit que permita visualizar y explorar los datos analizados y presentar las recomendaciones y KPIs generados.

## Metodología

En el notebook EDA.ipynb se realizó lo siguiente: 

Un análisis de datos del S&P 500 y se comparó con diferentes indicadores macroeconómicos como la inflación, tasa de desempleo, tasa de interés de la FED y confianza del consumidor. También se comparó el índice S&P 500 con los ETFs de los sectores económicos que lo componen.

En la primera parte, se cargó y exploró el archivo con los datos del S&P 500. Se creó un gráfico para visualizar la evolución del índice a lo largo del tiempo y se calcularon diferentes estadísticas descriptivas para entender la distribución de los precios de cierre ajustados. Se realizó una prueba de estacionariedad y se ajustó el índice por inflación.

En la segunda parte, se descargaron los datos de diferentes indicadores macroeconómicos y se compararon con el índice S&P 500. Se crearon gráficos para visualizar la evolución de la inflación, tasa de desempleo, tasa de interés de la FED y confianza del consumidor. Se calculó la matriz de correlación entre el índice S&P 500 y los diferentes indicadores macroeconómicos. Además, se creó un diccionario con los ETFs de los sectores económicos y se comparó el precio de cierre ajustado promedio de cada sector con el índice S&P 500. Por último, se creó un gráfico para visualizar la evolución del índice S&P 500 y los ETFs de los diferentes sectores económicos.

En el notebook complemento_EDA.ipynb se realizó lo siguiente:

 Aquí se decidió enfocarse en analizar un número limitado de empresas (5) de las más grandes y con mayor capitalización de mercado para determinar si conviene invertir en el S&P 500 como índice o en empresas individuales. Para ello, se descargaron datos históricos de precios de cierre utilizando la librería yfinance en Python y se calcularon los rendimientos diarios de las empresas y del S&P 500. Luego, se calcularon las estadísticas de rendimiento y riesgo para cada empresa y para el S&P 500, y se generó un gráfico de dispersión para comparar los rendimientos y el riesgo de cada empresa en relación con el S&P 500. También se generaron gráficos adicionales para comparar el rendimiento y la volatilidad anual de las empresas y del índice en los últimos 5 años, y se graficaron los precios de cierre ajustados de las empresas y del índice en función del tiempo.

En el notebook metricas_500_empresas.ipynb se realizó lo siguiente: 

Se utilizó la librería yfinance para descargar los precios de cierre ajustados de las acciones de las empresas que conforman el índice S&P500, para el periodo comprendido entre el 1 de enero del 2018 y el 28 de marzo del 2023. Posteriormente se agrega el índice S&P500 al dataframe y se exporta a un archivo parquet para ser utilizado posteriormente.

Se realiza un cálculo para eliminar las empresas que no tienen información completa para los últimos 5 años, utilizando el método "dropna" del objeto DataFrame de Pandas.

Se calculan los retornos diarios para cada empresa, a través del método "pct_change" del objeto DataFrame de Pandas.

A partir de los retornos diarios, se calculan los siguientes indicadores financieros:

Retorno anualizado
Volatilidad diaria y anualizada
Coeficiente de Sharpe
Índice de Treynor
Coeficiente de información
Cada uno de estos cálculos se realiza mediante ciclos para cada una de las empresas que conforman el S&P500, y se utilizan los métodos y funciones de la librería numpy y pandas para los cálculos matemáticos.


