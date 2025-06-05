Informe Explicativo del Análisis.

Objetivo del Proyecto
-El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) sobre campañas de marketing telefónico llevadas a cabo por una institución bancaria portuguesa, combinando información de comportamiento y demográfica de los clientes. El propósito es identificar patrones que permitan entender qué tipo de cliente es más propenso a aceptar una campaña.

Fuentes de Datos
-bank-additional.csv
-Datos de campañas de marketing, incluyendo duración de llamadas, historial de contactos y respuesta a la campaña (y).

customer-details.xlsx
-Datos demográficos y de comportamiento web de clientes (ingresos, niños en casa, fecha de ingreso al banco, visitas al sitio web). Incluye tres hojas correspondientes a distintos años.


Análisis Descriptivo
-Dataset de campañas (df_bank)
-La mayoría de los clientes no aceptaron la campaña (y = no).
-Profesiones como "student" y "retired" mostraron una mayor tasa de aceptación.
-Llamadas más largas tienden a estar asociadas a mayor probabilidad de aceptación.
-Contacto por teléfono móvil fue más efectivo que por teléfono fijo.
-Clientes sin préstamos personales o hipotecas respondieron mejor.

Dataset de clientes (df_customers)
-La mayoría de los clientes tienen 0 o 1 hijo.
-Ingreso anual medio: alrededor de 50.000€, con distribución sesgada hacia ingresos bajos.
-Clientes con más visitas web no necesariamente tienen mayores ingresos.
-La mayoría se unió al banco entre 2012 y 2014.


Visualización de Datos
Se crearon histogramas, diagramas de caja (boxplots), countplots y mapas de calor para representar:
-Distribuciones de edad, duración, ingresos y visitas web.
-Comparación de tasas de aceptación según variables categóricas.
-Correlaciones entre variables numéricas y la respuesta a la campaña.

Conclusiones Finales
-El factor más importante para el éxito de una campaña es la duración de la llamada.
-El tipo de contacto y la situación financiera del cliente también influyen.
-Aunque los datos demográficos como ingresos o número de hijos son útiles, no determinan por sí solos la aceptación de campañas.
-Se recomienda enfocar las campañas en clientes mayores, sin préstamos activos, y con historial positivo previo.