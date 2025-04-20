# Definicion de un sistema operativo

Es dificil definir lo que es un sistema operativo. Ese concepto ha ido cambiando con el tiempo. Sin embargo, tenemos certeza de cuales son las dos funciones principales del sistema operativo:

## Funcion 1 - El sistema operativo como una maquina extendida (o virtual)

Cuando hablamos de una maquina extendida (o virtual), nos referimos a un entorno de trabajo especial para el usuario. 

El entorno de trabajo por defecto de una computadora es primitivo y muy poco agradable para el usuario. Se trata de operaciones de bajo nivel como configurar lecturas de disco, tratamiento de interrupciones, incidentes y cualquier otro tipo de manejo de los componentes fisicos de la computadora.

Dicho entorno primitivo era ineficiente y por eso se decidio hacerlo invisible por medio de un software. Ese software que oculta la verdad acerca del hardware es el sistema operativo. Entonces, **la primera funcion** es brindarle al usuario un nivel de abstraccion para hacer su entorno mas comodo.

Esta funcion da un concepto del sistema operativo que entra dentro de una vision de **abajo hacia arriba (top-down)**.

## Funcion 2 - El sistema operativo como un controlador de recursos

Una vision alternativa, de **arriba hacia abajo (botton-up)**, define que el sistema operativo tiene la funcion de controlar los componentes fisicos. Proporciona asignaciones ordenadas y controladas del hardware para los distintos softwares.

El sistema operativo es capaz de poner orden en un potencial caos. Un caos representarse como la falta de recursos, o saturacion por exceso de programas ejecutandose al mismo tiempo, etc.

Para tener una mejor idea, imaginemos que el usuario manda a la computadora para que imprima varios documentos al mismo tiempo en una misma impresora. Sabemos que las impresoras regularmente solo pueden trabajar sobre una sola hoja a la vez. Si le pedimos que imprima varios documentos al mismo tiempo tendremos como resultado una hoja en la que se imprimieron varios trosos de los documentos. Ningun documento se imprimio completo, la hoja no se entiende y todo el proceso se volvio un caos. Pues, el sistema operativo es capaz de ordenar ese caos haciendo que los documentos se impriman uno por uno a pesar de que el usuario mando a imprimirlos todos al mismo tiempo. 

Antes el usuario era el que tenia que esperar a que un documento se imprimiera para luego imprimir otro, pero ahora el sistema operativo se encarga de eso.