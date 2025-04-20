# Definición de un Sistema Operativo

Es difícil definir qué es un sistema operativo. Este concepto ha ido cambiando con el tiempo. Sin embargo, tenemos certeza de cuáles son las dos funciones principales del sistema operativo:

## Función 1 - El sistema operativo como una máquina extendida (o virtual)

Cuando hablamos de una máquina extendida (o virtual), nos referimos a un entorno de trabajo especial para el usuario.

El entorno de trabajo por defecto de una computadora es primitivo y muy poco agradable para el usuario. Se trata de operaciones de bajo nivel como:
- Configurar lecturas de disco
- Tratamiento de interrupciones
- Manejo de incidentes
- Cualquier otro tipo de manipulación de los componentes físicos de la computadora

Dicho entorno primitivo era ineficiente y por eso se decidió hacerlo invisible por medio de un software. Ese software que oculta la verdad acerca del hardware es el sistema operativo. Entonces, **la primera función** es brindarle al usuario un nivel de abstracción para hacer su entorno más cómodo.

Esta función da un concepto del sistema operativo que entra dentro de una visión de **abajo hacia arriba (bottom-up)**.

## Función 2 - El sistema operativo como un controlador de recursos

Una visión alternativa, de **arriba hacia abajo (top-down)**, define que el sistema operativo tiene la función de controlar los componentes físicos. Proporciona asignaciones ordenadas y controladas del hardware para los distintos softwares.

El sistema operativo es capaz de poner orden en un potencial caos. Un caos podría representarse como:
- Falta de recursos
- Saturación por exceso de programas ejecutándose simultáneamente
- Conflictos en el acceso a dispositivos

### Ejemplo práctico:
Imaginemos que el usuario manda a imprimir varios documentos simultáneamente en una misma impresora. Sabemos que:
- Las impresoras normalmente solo pueden trabajar con una hoja a la vez
- Si intentamos imprimir múltiples documentos a la vez, obtendríamos:
    - Hojas con fragmentos mezclados de diferentes documentos
    - Ningún documento completo
    - Resultados incomprensibles
    - Un proceso caótico

El sistema operativo resuelve este problema:
1. Organiza las solicitudes de impresión
2. Las procesa una por una
3. Mantiene el orden aunque el usuario haya enviado todos los documentos al mismo tiempo

Antes, el usuario tenía que esperar a que un documento se imprimiera completamente antes de enviar el siguiente. Ahora, el sistema operativo se encarga de esta gestión automáticamente.