# Un modelo para detección de fraudes en transacciones financieras.



Para mi una de las aplicaciones más interesantes y útiles en la práctica del ML es la detección de fraudes en transacciones financieras, un campo de acción que puede ser manejado desde el enfoque de modelos de clasificación o también desde el análisis de anomalías. 

En general explorar y experimentar en la creación de modelos de ML para detección de fraudes, se hace un poco más complejo por la falta de set de datos disponibles públicamente, lo cual es entendible ya que pocas entidades financieras están dispuestos a poner información financiera y operativa potencialmente sensible en el dominio público.

El objetivo de este notebook exponer una aproximación sencilla al problema de la la detección de fraudes, que espero le pueda servir a alguien ya sea como una referencia inicial en el problema de detección de fraudes, o quizá como  punto de arranque para la creación de modelos más complejos. 

El set datos usado en este proyecto es un dataset sintético creado por PaySim quien ha generado partir de transacciones reales privadas de un servicio de dinero móvil implementado en un país africano, un set de datos sintético que simula una operación transaccional normal a la cual se ha inyectado comportamiento malicioso para luego evaluar el desempeño de modelos de detección de fraudes.. El set de datos original se encuentra disponible en la plataforma Kaggle (https://www.kaggle.com/ntnu-testimon/paysim1)