# Trabajo-final-de-semestre
# Tarea-4
tarea N°4 de big data, correspondiente a la actividad de cierre de semestre

#EJERCIO 1:
 Uso la funcion dada, y R contabiliza los componentes de la variable, a travez de comandos length, list, unlist, sample.

#EJERCICIO 2:
El "set.seed" lo que logro observar de este comando es que ordena los datos de una manera no clara, ademas,sirve para que cuando se haga un agrupacion de componentes aleatorios, esta agrupación no cambie cuando se ejecute el mismo comando, así,si quiero examinar los datos o componentes entregados, al correr el comando otra vez, el orden de los componentes no cambia, todo esto siempre y cuando se ejecute antes el "set.seed".

#EJERCICIO 3:
Lo primero que puedo observar bajo el plano de los componentes recolectados corresponden a noticias de una crisis económica,al realizar los pasos descritos en el ejercicio y utilizando set.seed(66) y comparando con el calculo de los porcentajes sin set.seed, el resultado arroja los mismos porcentajes, lo que deja como conclusion que set.seed ordena los datos aleatorios para que sean faciles de procesar en r. En el caso de considerar o no a los "neutros" solo impacta en la diferencia entre las opiniones externas, si se consideran "neutros" la diferencia entre positivo y negativo es de 9% y sino se consideran "neutros", la diferencia es de 12%.

#EJERCICIO 4:
 Al ejecutar este ejercicio se debe dejar de contar los numeros y se comienza a contar las agrupaciones de numeros designados a traves de la función if y el conector "o" designado con |, los cuales permiten llevar la cuenta utilizando una variable "cuenta" que aumenta o disminuye en 1 unidad dependiendo de las cartas que resulten. La cuenta final es -13.

#EJERCICIO 5:
 Al usar "set.seed" en el ejercicio de antes, dio como resultado el mismo numero de "cuenta" que es -13, esto muestra que la probabilidad de que ocurra el mismo procedimieento es el mismo, inclusive utilizando set.seed se mantiene lo aleatorio. Tecnicamente todas las cartas tienen la misma probabilidad de salir. Al usar set.seed(31), r retribuye más posibilidades de hacer salir cartas mas altas puesto que a cuenta queda en -13, por lo tanto, las cartas que estan por salir son cartas bajas o neutras.

#EJERCICIO 6:

esta en r
