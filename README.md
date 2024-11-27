Aplicación de técnicas de aprendizaje supervisado; modelo de regresión múltiple, modelo de regresión polinomial, KNN de regresión, Random Forest de regresión
y técnica de aprendizaje no supervisado; K-prototype para el análisis de conglomerados con variables mixtas, sobre variables de turismo receptor para 
predecir el gasto turístico y/o identificar perfiles de visitantes receptores a Santander-Colombia.

Librerías scikit-learn para aprendizaje estadístico computacional, librerías de Seaborn y Matplotlib para visualización de datos, Lenguaje de programación Python, 
entorno de trabajo Google Colab.

https://github.com/DianaGarcesPortilla/Machine_Learning/blob/main/Aprendizaje_estad%C3%ADstico_computacional.ipynb

1. Introducción
   
Desde mediados de febrero de 2017 a abril del 2018 en el departamento de Santander Colombia se llevó a cabo un estudio de turismo receptor, es decir,
estudiar el flujo de visitantes que llegan a Santander, con el objetivo de caracterizarlo en función de las variables propuestas por Organización 
Mundial de Turismo para la medición del turismo receptor que comprenden: el motivo principal del viaje, las noches de estancia, el tamaño del grupo de viaje,
el transporte utilizado y el gasto turístico. Adicionalmente se contemplaron características demográficas como lugar de residencia, género y edad.

Antes de exponer los objetivos del análisis supervisado y no supervisado se aclaran dos conceptos importantes sobre el turismo receptor:

Visitante: Un visitante es una persona que viaja a un destino principal distinto al de su entorno habitual, por una duración inferior a un año, con cualquier 
finalidad principal (ocio, negocios u otro motivo personal) que no sea la de ser empleado por una entidad residente en el país o lugar visitados.

Gasto turístico: Hace referencia a la suma pagada por la adquisición de bienes y servicios de consumo y de objetos valiosos para uso propio o para regalar, 
antes y durante los viajes turísticos. Incluye los gastos incurridos por los propios visitantes, así como los gastos pagados o reembolsados por otros.

Para la aplicación de las técnicas de análisis supervisado se propone como variable respuesta el gasto turístico en función de las covariables: género, edad,
lugar de residencia, motivo principal del viaje, número de municipios visitados, actividades realizadas, el transporte utilizado para llegar y
movilizarse durante la estancia, el tamaño del grupo de viaje y el nivel de satisfacción.

En función de los hallazgos del estudio exploratorio se propone el uso de los modelos de regresión, KNN y Radom Forest, para el análisis supervisado.
Posteriormente para el l uso del método de aprendizaje no supervisado se aplica k-prototype, por la presencia de variables mixtas.
Nota: la base de datos es confidencial

*World Tourism Organization (UNWTO). (2014). International Recommendations for Tourism Statistics 2008.




