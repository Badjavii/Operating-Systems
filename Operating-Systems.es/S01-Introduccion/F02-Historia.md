# Historia de los Sistemas Operativos

Los sistemas operativos han ido evolucionando con el pasar del tiempo. La historia de los sistemas operativos esta profundamente relacionada con la historia de las computadoras. Anteriormente hice un repositorio de [Organizacion del Computador](https://github.com/Badjavii/Core-Compu) en donde se habla de la [historia de las computadoras](https://github.com/Badjavii/Core-Compu/blob/main/S01-Computer-Organization/F01.1-Computer-Organization.es/D02-Historia-Del-Computador.md) y puedes revisarlo. Sin embargo, veremos un breve repaso de sus generaciones.

Recordemos que antes del siglo XX tuvimos ciertos antecedentes de lo que luego se llamaria Computadora. Los antecedentes mas relevantes fueron:
- **El abaco:** Creado en el 500 a.C.
- **Pascalina:** Una maquina que fue creada por Shails Pascal en 1641.
- **Telar de Jacquard:** Un telar mecanico que utilizaba tarjetas perforadas. Fue inventado por Joseph Jacquard en 1801.
- **Maquina diferencial:** Lograba calcular polinomios, pero su inventor, Charles Babbage, no logro terminarla en 1822.
- **Maquina analitica:** En 1833, Charles Babbage diseñó un prototipo de computadora mecanica programable, y Lady Ada Lovelace (matematica y escritora) escribio un algoritmo para esa maquina. Lovelace se convirtio en la **primera programadora**, mientras que Babbage se convirtio en el **Padre de la computacion**.
- **Maquina Tabuladora Electrica:** Creada en 1889 por Herman Hollerith. Fue crucial en el desarrollo del procesamiento de datos. Herman Hollerith es considerado el **Padre de la Informatica**.
- **Maquina de Turing:** Un prototipo conceptual de máquina que puede realizar cualquier cálculo que pueda ser expresado por medio de un algoritmo. Alan Turing se convirtio en el **Padre de la informatica moderna.**

Cabe destacar que ninguna de estas maquinas eran electronicas, por lo que, obviamente **no contaban con un sistema operativo.**

## Primera generación (1945-1955): Tubos de vacio 

Las computadoras electronicas nacen. Las mas relevantes fueron la Z1 (Konrad Zuse), la ENIAC (J. Presper y William Mauchley), UNIVAC, la Mark 1 (Howard Aiken), ABC () y la EDVAC (Von Neumann). Todas estas fueron maquinas de calculo que usaban componentes electrónicos que utilizan el vacío para controlar el flujo de electrones (y la corriente electrica). Esos componentes son los tubos de vacio.

En aquella epoca, la operacion de un computador era muy complejo y tardaba demasiado. Las primeras computadoras se operaban a traves de **conexiones** que vendrian siendo cableados fisicos que se tenian que cambiar manualmente. Las computadoras podian tener cientos de conexiones y estas tenian que ser reconfiguradas con frecuencia y eso implicaba a el uso de muchas personas para operar una sola computadora. No existian los lenguajes de programacion y mucho menos los sistemas operativos.

A finales de la decada de los 50, se dio la transicion de las conexiones a las tarjetas perforadas.

## Segunda generación (1955-1965): Transitores y sistemas de procesamiento por lotes

Gracias a los transitores, las computadoras se hicieron mas precisas, rapidaz y confiables. Tambien nacieron los primeros lenguajes de programacion y, por primera vez, hubo una separacion entre fabricantes, programadores, operadores y mantenimiento.

Las maquinas eran bastante costosas y eran pocas las organizaciones que podian adquirirlas. Para ejecutar un programa, el programador debia escribirlo en hojas de papel (en FORTRAN o ensamblador) para despues perforar las tarjetas. Este proceso manual generaba enormes ineficiencias: los operadores perdían hasta el 50% del tiempo caminando entre salas para cargar programas, compiladores y datos en sistemas como el IBM 1401/7094, donde la CPU permanecía ociosa durante estos cambios.

```mermaid
---
title: Procesamiento por lotes (IBM 1401 + 7094)
---
flowchart TB

    A>Programar Tarjetas perforadas]
    --> B[IBM 1401: Lectura de tarjetas] 
    -->|Cinta entrada| C[IBM 7094: Procesamiento CPU Principal]
    -->|Cinta resultados| D[IBM 1401: Impresión de resultados]
```

La solución fue el procesamiento por lotes automatizado: los trabajos se recolectaban en cintas magnéticas que luego se procesaban secuencialmente sin intervención humana. El IBM 1401 manejaba la entrada/salida mientras el 7094 hacía los cálculos, aumentando la utilización de CPU del 30% al 85%. Este sistema sentó las bases para los primeros sistemas operativos con monitores residentes que gestionaban la transición automática entre trabajos.