# credit-card-fraud-detection

## Descripción del Problema a Solucionar:

El fraude con tarjetas de crédito es un problema significativo y creciente que afecta a consumidores y a instituciones financieras en todo el mundo. Detectar transacciones fraudulentas de manera rápida y precisa es crucial para minimizar pérdidas financieras y proteger la información de los usuarios. El reto consiste en desarrollar modelos de clasificación eficientes que puedan distinguir entre transacciones legítimas y fraudulentas con alta precisión.

En este proyecto, aplicamos técnicas de aprendizaje automático utilizando Árboles de Decisión y Máquinas de Vectores de Soporte (SVM) para detectar transacciones fraudulentas con tarjetas de crédito. También exploramos el uso de la biblioteca Snap ML de IBM, que ofrece implementaciones eficientes de modelos de ML en CPU/GPU, para mejorar el rendimiento del proceso de detección.

## Descripción del Dataset:

El dataset utilizado en este proyecto proviene de transacciones realizadas con tarjetas de crédito por titulares europeos en septiembre de 2013. Las principales características del dataset incluyen:

Información de la Transacción: Montos de las transacciones, fechas y horas.
Características Derivadas: Variables derivadas de componentes principales (PCA) para anonimizar la información sensible.
Etiqueta de Fraude: Indicador binario que señala si la transacción es fraudulenta (1) o legítima (0).
El dataset incluye una serie de registros con diversas características de las transacciones, lo que permite entrenar y evaluar modelos de clasificación para predecir la probabilidad de fraude.
