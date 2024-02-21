# CLEAN CODE

Before starting, it's important to understand what clean code is and why its practice is important.
Clean code refers to good practice; as its name suggests, to code in a clean manner that is easy to understand, modify, and maintain. The purpose of clean code is for it to be readable and comprehensible for developers when reading and interpreting it.


1. What is code optimization?

Code optimization aims to improve a specific characteristic of the code, such as its execution speed, memory usage, resource consumption, executable file size, or even its maintainability and readability.


3. What is code refactoring?

In short, code refactoring alludes to the process of restructuring existing code, with the goal of improving its internal structure, whether with the purpose of simplifying the code, enhancing readability, increasing efficiency, among others. All of this, without affecting the external functionality of the code itself, maintaining the goal and functionality of it.


4. What is Continuous Integration/Continuous Deployment (CI/CD) or continuous integration?

These are practices that focus on the automation of processes and tests in software development to improve the quality of the code, accelerate the delivery of new features, and reduce the risk of errors in production.

CI (Continuous Integration): as the name suggests, refers to continuous integration where developers constantly merge changes and updates of code into a central repository, after which automated builds and tests are executed.

CD (Continuous Deployment): Continuous deployment is the automation of the software delivery process, covering from integration to the final delivery to a client. It is automatically deployed in a pre-production or testing environment, where it is subjected to additional user acceptance or performance tests, all in an automated way.


5. What is DRY (Don't Repeat Yourself)?

It is a software design principle that promotes the reduction of code duplication in a software system, thus seeking for programmers to write modular and reusable code instead of repeating similar logic in multiple places.
The DRY principle seeks for every piece of knowledge in a software system to have a unique, unambiguous, and authoritative representation in the source code.
This means, instead of repeating the same logic in different parts of the code, we should create a unique representation of that logic and reuse it throughout the system. This involves grouping that logic into functions, classes, or modules that can be easily invoked from anywhere in the program, instead of writing the same code over and over again.


Some benefits of the DRY principle are:
- Maintainability
- Readability
- Reusability
- Reduction of errors

In conclusion, the DRY principle is an essential rule in software development that seeks to improve the efficiency and quality of code by avoiding unnecessary repetitions. This leads to clearer, easier-to-maintain code and less prone to errors.

---------------------------------

# CLEAN CODE

Antes de iniciar es importante entender que es clean code y por qué es importante su práctica.
Clean code hace referencia a la buena práctica, como su nombre lo dice, codificar de forma
limpia, que sea fácil de entender, modificar y mantener. La finalidad del clean code es que sea
legible y comprensible para los desarrolladores a la hora de leerlo e interpretarlo.


1. ¿Qué es optimización de código?
   
La optimización de código busca mejorar alguna característica específica del código, como su
velocidad de ejecución, uso de memoria, consumo de recursos, tamaño del archivo ejecutable,
o incluso su mantenibilidad y legibilidad.


3. ¿Qué es la refactorización del código?
   
En pocas palabras la refactorización de código hace alusión al proceso de reestructuración de
un código existente, con el fin de mejorar su estructura interna, ya sea con el propósito de
simplificar el código, mejorar la legibilidad, aumentar la eficiencia, entre otros. Todo esto, sin
afectar el funcionamiento exterior del código mismo, manteniendo el objetivo y funcionalidad de
este.


4. Que es Continuous Integration/Continuous Deployment (CI/CD) o integracion continua?
   
Son prácticas que se enfocan en la automatización de procesos y pruebas en el desarrollo de
software para mejorar la calidad del código, acelerar la entrega de nuevas funcionalidades y
reducir el riesgo de errores en producción.

CI (Continuous Integration): como su nombre lo indica hace referencia a la integración
continua donde los desarrolladores fusionan constantemente los cambios y actualizaciones de
un código en un repositorio central, tras lo cual se ejecutan compilaciones y pruebas
automatizadas.

CD (Continuous Deployment): La entrega continua es la automatización del proceso de
entrega de un software, este abarca desde la integración, hasta la entrega final a un cliente. Se
despliega automáticamente en un entorno de preproducción o de pruebas, donde se somete a
pruebas adicionales de aceptación por parte del usuario o de rendimiento, todo esto de forma
automatizada.


5. Que es DRY (Don't Repeat Yourself)?
   
Es un principio de diseño de software que promueve la reducción de la duplicación de código
en un sistema de software, buscando así que los programadores escriban código modular y
reutilizable en lugar de repetir lógica similar en múltiples lugares.
El principio DRY busca que cada pieza de conocimiento en un sistema de software tenga una
representación única, no ambigua y autoritativa en el código fuente.
Esto quiere decir, en lugar de repetir la misma lógica en diferentes partes del código,
deberíamos crear una única representación de esa lógica y reutilizarla en todo el sistema. Esto
implica agrupar esa lógica en funciones, clases o módulos que puedan ser fácilmente
invocados desde cualquier parte del programa, en lugar de escribir el mismo código una y otra
vez.

Algunos beneficios del principio DRY son:

- Mantenibilidad
- Legibilidad
- Reutilización
- Reducción de errores

En conclusión, el principio DRY es una regla esencial en el desarrollo de software que busca
mejorar la eficiencia y la calidad del código al evitar repeticiones innecesarias. Esto conduce a
un código más claro, fácil de mantener y menos propenso a errores.
