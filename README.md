Por favor leer el cuaderno "ExplicacionModelosYDatos" para los aspectos más técnicos del trabajo. 

Tableros.twb contiene el archivo del tablero de control usado para la elaboración de parte de la presentación.

Hay un solo archivo en el que se realizan las labores de carga y preprocesamiento de los datos, así como análisis previo de los mismos (EDA).
El cuaderno "DataExplorationBusinessContext" se encarga de dejar guardado como caché el dataframe después de la depuración de los datos, por lo que se debe correr primero antes de intentar correr los cuadernos "DecTree", "KNN" y "MLP".

Se hizo de esta manera para tener bajo acoplamiento entre el proceso de EDA y limpieza de datos, y los modelos como tal, buscando que en un futuro, el trabajo fuese extensible y fuese legible y fácil añadir más modelos y archivos de ser necesario.

Por lo demás, cada cuaderno es autocontenido en cuanto a comentarios y Markdown que explica cada detalle de los modelos, el contexto de negocio y las decisiones. 

Atentamente:

* Natalia Sanabria Forero - 201532265
* Jorge Andrés Esguerra Alarcón - 201719920
* Christian Forigua (Dueño de este modelo) - 201713023