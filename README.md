Con el data set en el archivo "datos_prestamo.csv" tiene información de una empresa que otorga créditos. Hasta ahora, hay un grupo de personas (el equipo de crédito) que estudia registro a registro y decide si prestarle o no. En el último mes, han llegado muchos más registros de los que puede atender el equipo de crédito. Alguien sugirió crear un modelo para poder decidir a quien prestarle.

- ¿Crees que sea una buena idea? ¿ Por qué?

Es una buena idea crear un modelo, pero en un solo mes tendríamos una muestra muy pequeña. Es necesario recopilar datos durante un período más largo.

 - Si la respuesta fue sí, ¿qué tipo de probema es según los datos que tienes? (Supervisado o No Supervisado)
 
Es un problema de aprendizaje supervisado porque conocemos las etiquetas, lo que significa que los datos ya están etiquetados con la respuesta correcta.

- Haz las transformaciones que necesites a los datos y desarrolla algún modelo.

Creé un notebook llamado 'desafio_go_bravo.ipynb' donde describo todos los pasos para construir el modelo. Utilicé un modelo de clasificación donde la variable de respuesta es 'Estatus_prestamo'.

En base a los resultados obtenidos

- ¿Cómo sabes que es un buen modelo?

Para decidir si un modelo es bueno, utilizo métricas como precisión, recall, f1-score y matriz de confusión. Sin embargo, debido a que la muestra era muy pequeña, el modelo no clasificó tan bien, teniendo algunas medidas bajas para la clase cero (dinero prestado).

- Si fueras el líder del área de crédito, ¿Sigues con tu estructura actual ó utilizas el modelo obtenido? ¿Por qué?

Continuaría con el modelo actual y extraería una muestra más grande del conjunto de datos y luego crearía un modelo.
