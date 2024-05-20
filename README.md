## Tarea Final - Machine Learning

Alumno: Guillermo Lodeiro

Profesores: Jose Angel Carballo, Luis Garmendia, María José Gómez

Institución: Universidad Complutense de Madrid

La tarea asignada en el curso, fue la participación de los alumnos en la [Competición Pump It Up: Data Mining the Water Table](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) de DrivenData. 
La idea es poner en práctica las técnicas de depuración de datos aprendidas a lo largo del curso, utilizando librerías de análisis, manipulación y visualización como: Pandas, Numpy, Matplotlib, Seaborn, Ploty entre otras.
Además, se utilizo la librería Pycaret para encontrar los mejores modelos para el caso. Utilizando la librería Scikit Learn, se buscaron los mejores hiperparámetros para el modelo de Random Forest, se generaron predicciones
y se midio el rendimiento mediante Cross Validation.

En el trabajo se realizaron varios preprocesados con el objetivo de encontrar el óptimo para el modelo. Se eliminaron, imputaron y crearon variables, tambien, mediante la librería imbalanced-learn, se utilizó Smote para el balanceo de 
datos en la variable objetivo. 

Luego de varios intentos, el mejor score obtenido en la competición fue de 81.80% (tener en cuenta que la posición #1 en el ranking es de 82.94%).
