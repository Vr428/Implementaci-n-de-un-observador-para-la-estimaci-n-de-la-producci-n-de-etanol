# Implementación de un observador para la estimación de la producción de etanol
Implementacion de un observadpr para la estamación de la producción de etanol utilizando simulink y una tarjeta electronica arduino UNO.
## Autor
Angel Jovan Vargas Rodriguez Residencia Profesional para Ingenieria Biomedica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: [angel.vargas193@tectijuana.edu.mx](mailto:angel.vargas193@tectijuana.edu.mx)
## Resumen
En este proyecto de residencia, se implementó un modelo de observador en Simulink para estimar variables clave de un proceso biotecnológico utilizando una tarjeta Arduino Uno. Las simulaciones en MATLAB compararon las trayectorias de las variables del sistema [1] (biomasa, consumo de glucosa y producción de etanol) con sus estimaciones, mostrando una alta concordancia y validando la precisión del observador de Luenberger de orden completo. El observador demostró alta precisión en la estimación de las variables del sistema, capturando adecuadamente las dinámicas del crecimiento microbiano y la producción de etanol. Las estimaciones del observador estaban muy cerca de los datos experimentales, reflejando su eficacia en el monitoreo y control en tiempo real de variables que no pueden ser medidas directamente con suficiente frecuencia o precisión. La implementación en una plataforma de hardware limitada como la Arduino Uno presentó desafíos en términos de memoria y capacidad de procesamiento, pero se demostró que es posible desarrollar soluciones efectivas mediante una gestión eficiente de los recursos y la optimización del código. En conclusión, este trabajo validó y mejoró herramientas de estimación basadas en observadores, ofreciendo nuevas perspectivas para sistemas de control eficientes en entornos con recursos limitados. Se recomienda ajustar los parámetros del observador y considerar este enfoque para otros procesos biotecnológicos o industriales donde el monitoreo preciso de variables sea crucial.
##Contexto 
Las competencias previas que el alumno debe tener para desarrollar esta actividad de enseñanza son las siguientes:

- Emplea un lenguaje de programación para la solución de problemas.
- Emplea técnicas de modelado de sistemas para aplicaciones en procesos biológicos y fisiológicos.
- Aplica métodos numéricos para la solución de ecuaciones diferenciales ordinarias que permitan resolver problemas que involucran sistemas dinámicos en ingeniería.
- Entiende los conceptos de la teoría de la probabilidad y estadística para organizar, clasificar, analizar e interpretar datos para la toma decisiones en aplicaciones de ingeniería.

## Asignatura o departamentos donde se puede usar la Actividad

Ingeniería Biomédica Sistemas Dinámicos Biestadística Modelado Matemático

## Nota para los Educadores usando la Actividad
Objetivo General

Implementar un observador orden completo, tipo Luenberger, para la estimación de la producción de etanol en fermentación continua.

Objetivos Específicos

1. Analizar el modelo matemático del proceso de fermentación y observador de Luenberger para la estimación de la producción de etanol.

2. Desarrollar un algoritmo que permita la implementación del observador en una tarjeta electrónica.

3. Emular el sistema de fermentación continua para la producción de etanol aplicando el modelo matemático *K. marxianus* y los datos experimentales.

4. Evaluar la convergencia del observador mediante la comparación del error entre las soluciones proporcionadas por el observador y las obtenidas a partir del modelo matemático y/o datos experimentales.

## Evaluacion 

A definir por el docente.

## Recursos adicionales

[5] Y. Salazar, P. A. Valle, E. Rodríguez, N. O. Soto-Cruz, J. B. Páez-Lerma, y F. J. Reyes-Sánchez, "Mechanistic modelling of biomass growth, glucose consumption, and ethanol production by *Kluyveromyces marxianus* in batch fermentation," *Entropy*, vol. 25, no. 3, p. 497, Mar. 2023, consultado el 16 de octubre de 2023. [https://doi.org/10.3390/e25030497](https://doi.org/10.3390/e25030497)
