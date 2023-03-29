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

# Recomendaciones de empresas

Para generar recomendaciones, se crearon 8 combinaciones de perfil de riesgo con objetivo de inversión. 
A continuación se describen los criterios utilizados: 

Para el perfil "Conservador" y el objetivo "Preservación de capital", se definen los siguientes umbrales y rangos para las métricas:
Umbral diario de volatilidad: 0.02
Umbral anual de volatilidad: 0.2
Umbral de beta: 1.0
Rango de retornos anuales: (0.0427, 0.06)
Se recomendarán las compañías que cumplen con estos criterios y que se consideran seguras para preservar el capital del inversor.

Para el perfil "Conservador" y el objetivo "Ingreso", se definen los siguientes umbrales y rangos para las métricas:
Umbral diario de volatilidad: 0.01
Umbral anual de volatilidad: 0.15
Umbral de beta: 1.0
Rango de retornos anuales: (0.0427, 0.06)
Rango de retornos diarios: (0, 0.005)
Umbral de capitalización de mercado: 500000000
Umbral de volumen diario: 1000000
Se recomendarán las compañías que cumplen con estos criterios y que generan un ingreso estable y seguro para el inversor conservador.

Para el perfil "Moderado" y el objetivo "Ingreso", se definen los siguientes umbrales y rangos para las métricas:
Rango de retornos anuales: (0.06, 0.12)
Umbral anual de volatilidad: 0.22
Umbral diario de volatilidad: 0.015
Umbral de beta: 1.0
Umbral de volumen diario: 1000000
Se recomendarán las compañías que cumplen con estos criterios y que generan un ingreso moderado para el inversor moderado.

Para el perfil "Moderado" y el objetivo "Crecimiento", se definen los siguientes umbrales y rangos para las métricas:
Rango de retornos anuales: (0.1, 0.2)
Umbral anual de volatilidad: 0.23
Umbral diario de volatilidad: 0.02
Umbral de beta: 1.1
Umbral de capitalización de mercado: 10000000000
Umbral de volumen diario: 4000000
Se recomendarán las compañías que cumplen con estos criterios y que se consideran oportunidades de crecimiento para el inversor moderado.

Para el perfil "Agresivo" y el objetivo "Ingreso", se definen los siguientes umbrales y rangos para las métricas:
Rango de retornos anuales: (0.15, 0.18)
Umbral anual de volatilidad: 0.3
Umbral diario de volatilidad: 0.02
Umbral de beta: 1.2
Umbral de capitalización de mercado: 20000000000
Umbral de volumen diario: 4000000
Se recomendarán las compañías que cumplen con estos criterios y que ofrecen un alto potencial de ingresos para el inversor agresivo.

Para el perfil "Agresivo" y el objetivo "Crecimiento", se definen los siguientes umbrales y rangos para las métricas:
Rango de retornos anuales: (0.15, 0.25)
Umbral anual de volatilidad: 0.35
Umbral diario de volatilidad: 0.03
Umbral de beta: 1.3
Umbral de capitalización de mercado: 30000000000
Umbral de volumen diario: 5000000
Se recomendarán las compañías que cumplen con estos criterios y que se consideran oportunidades de alto crecimiento para el inversor agresivo.

Para el perfil "Especulativo" y el objetivo "Ingreso", se definen los siguientes umbrales y rangos para las métricas:
Rango de retornos anuales: (0.18, 0.25)
Rango de retornos diarios: (0.0005, 0.005)
Umbral anual de volatilidad: 0.5
Umbral diario de volatilidad: 0.05
Umbral de beta: 1.5
Umbral de capitalización de mercado: 5000000000
Umbral de volumen diario: 1000000
Se recomendarán las compañías que cumplen con estos criterios y que generan un ingreso alto y especulativo para el inversor especulativo.

Para el perfil "Especulativo" y el objetivo "Crecimiento", se definen los siguientes umbrales y rangos para las métricas:
Rango de retornos anuales: (0.2, 0.3)
Rango de retornos diarios: (0.001, 0.01)
Umbral anual de volatilidad: 0.6
Umbral diario de volatilidad: 0.07
Umbral de beta: 2.0
Umbral de capitalización de mercado: 2000000000
Umbral de volumen diario: 2000000
Se recomendarán las compañías que cumplen con estos criterios y que se consideran oportunidades especulativas de alto crecimiento para el inversor especulativo.

La diferencia entre la estrategia de un perfil conservador con objetivo de preservación de capital y un perfil conservador con objetivo de ingreso radica en los objetivos de inversión. El perfil conservador con objetivo de preservación de capital se enfoca en proteger el capital invertido y reducir al mínimo cualquier riesgo de pérdida, por lo que se centra en invertir en compañías y activos considerados seguros y estables. Este perfil busca principalmente preservar el capital a largo plazo, y por lo tanto, está dispuesto a sacrificar mayores ganancias potenciales para minimizar el riesgo.

Por otro lado, el perfil conservador con objetivo de ingreso se enfoca en generar ingresos estables y seguros a través de la inversión en compañías y activos con un historial comprobado de pagar dividendos y generar rendimientos. Este perfil busca principalmente mantener el capital invertido y generar un ingreso pasivo a través de inversiones de bajo riesgo, en lugar de buscar un crecimiento significativo en el capital invertido.

En resumen, mientras que el perfil conservador con objetivo de preservación de capital busca minimizar el riesgo y proteger el capital invertido a largo plazo, el perfil conservador con objetivo de ingreso busca generar ingresos estables y seguros a través de inversiones de bajo riesgo.

La diferencia entre la estrategia de un perfil moderado con objetivo de ingreso y un perfil moderado con objetivo de crecimiento es que el primero busca principalmente generar ingresos a través de inversiones en compañías que ofrezcan un rendimiento estable y predecible, mientras que el segundo busca principalmente invertir en compañías que tengan un alto potencial de crecimiento a largo plazo, aunque esto implique una mayor volatilidad en el corto plazo. En otras palabras, el perfil moderado con objetivo de ingreso busca principalmente mantener la estabilidad del capital, mientras que el perfil moderado con objetivo de crecimiento busca maximizar el crecimiento a largo plazo, aunque esto pueda implicar asumir un mayor riesgo en el corto plazo.

La diferencia entre agresivo ingreso y agresivo crecimiento es que en el primer caso, el objetivo principal es generar ingresos elevados y sostenidos a través de inversiones agresivas, mientras que en el segundo caso, el objetivo principal es maximizar el crecimiento a largo plazo, asumiendo un nivel de riesgo elevado. En otras palabras, en el perfil agresivo ingreso se busca generar ingresos por encima del promedio del mercado, mientras que en el perfil agresivo crecimiento se busca superar significativamente el rendimiento del mercado en general, aunque esto implique asumir un mayor riesgo.

El perfil especulativo con objetivo de ingreso y el perfil especulativo con objetivo de crecimiento difieren en su enfoque en la inversión y en la tolerancia al riesgo. El perfil especulativo con objetivo de ingreso busca generar un flujo de efectivo constante a través de inversiones que ofrezcan altos rendimientos, pero a menudo implican un mayor riesgo y volatilidad en el precio de las acciones. Por otro lado, el perfil especulativo con objetivo de crecimiento busca principalmente invertir en compañías que tengan un alto potencial de crecimiento a largo plazo, aunque esto también puede implicar un mayor riesgo y volatilidad en el corto plazo.

En resumen, el perfil especulativo con objetivo de ingreso se enfoca en generar ingresos a corto plazo a través de inversiones especulativas, mientras que el perfil especulativo con objetivo de crecimiento busca maximizar el potencial de crecimiento a largo plazo, aunque esto implique un mayor riesgo y volatilidad en el corto plazo. Ambos perfiles tienen una mayor tolerancia al riesgo que los perfiles conservadores y moderados, y por lo tanto, pueden ser más adecuados para inversores que buscan oportunidades de alto riesgo y alta recompensa.

Para consultar las recomendaciones generadas ir a: 

