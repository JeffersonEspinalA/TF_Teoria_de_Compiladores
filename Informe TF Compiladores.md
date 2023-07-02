
**Universidad Peruana de Ciencias Aplicadas**






**INFORME DEL TRABAJO FINAL**

CURSO TEORÍA DE COMPILADORES

Carrera de Ciencias de la Computación

Sección: CC61



|<a name="_gjdgxs"></a>Alumnos:|
| - |
|Código|Nombres y apellidos|
|U202019644|Eduardo Roman  Caballero Lara|
|U201816502|Ronaldo David Cornejo Valencia|
|U201919607|Jefferson William Espinal Atencia|



Junio 2023











1. <a name="_r7hz0htxdish"></a>**Introducción**

<a name="_be62sxxnlgqw"></a>La programación esotérica es una disciplina de la informática que utiliza lenguajes de programación que desafían las convenciones habituales sobre cómo se deben construir y utilizar los lenguajes de programación. En lugar de buscar la eficiencia o la facilidad de uso, los lenguajes esotéricos exploran los límites de lo que es posible en la programación y ofrecen una forma creativa y a menudo humorística de ver el arte de la programación.

<a name="_38jgygaexd33"></a>El lenguaje esotérico Brainfuck es un ejemplo extremo de minimalismo en la programación, con sólo ocho comandos simples. Este lenguaje es difícil de usar para realizar tareas complejas debido a su sintaxis única y su enfoque en la manipulación de una única cinta de memoria.

<a name="_eztcnpxwe9y9"></a>El objetivo de este trabajo es construir un compilador para el lenguaje Brainfuck utilizando C + + y LLVM. Este trabajo servirá para entender cómo funcionan los lenguajes de programación en un nivel fundamental y cómo se puede traducir un lenguaje de alto nivel a un lenguaje de máquina utilizando LLVM.

1. <a name="_9op0usd1envd"></a><a name="_9manznp639x4"></a>**Marco teórico: brevemente describe el lenguaje, llvm y teoría de compiladores**

<a name="_hnuj0o5pduw1"></a>Brainfuck es un lenguaje de programación minimalista diseñado por Urban Müller en 1993. Sólo tiene ocho comandos simples que operan en una matriz de memoria de 30,000 bytes, cada uno inicialmente establecido en cero. Los comandos son >, <, +, -, ., ,, [, ] que, respectivamente, mueven el puntero, incrementan y decrementan el valor en el puntero, imprimen y leen un carácter, y controlan el flujo del programa.

<a name="_enb1tzfcv1jf"></a>LLVM es un conjunto de tecnologías de compilador modulares y reutilizables. Incluye una colección de bibliotecas del compilador intermedio y herramientas de construcción de código que se pueden utilizar para crear compiladores para cualquier lenguaje de programación. LLVM permite la optimización en tiempo de compilación, enlace y ejecución, lo que lo hace ideal para la creación de compiladores modernos.

<a name="_ytscerwca3fl"></a>La teoría de los compiladores es la rama de la informática que se ocupa de la traducción de código de un lenguaje de programación (el lenguaje fuente) a otro lenguaje (el lenguaje de destino). Los compiladores son importantes para la informática porque permiten que el código de alto nivel que los humanos pueden leer y escribir se traduce a código de máquina que las computadoras pueden ejecutar. Al construir un compilador para Brainfuck, se puede obtener una comprensión más profunda de cómo funcionan los compiladores y cómo se pueden utilizar para traducir cualquier lenguaje de programación a código de máquina.

1. <a name="_4xta4bupzo4w"></a><a name="_5bous1b8k6e0"></a>**Desarrollo**
1. Diagrama de clases

Fuente: <https://lucid.app/lucidchart/028229c4-cd4c-4d93-8438-a75394c50755/edit?invitationId=inv_b08763da-b56a-4263-a8b9-56c12cd2ccfd&page=0_0#>

1. Diagrama de flujo

Fuente: <https://lucid.app/lucidchart/7a2b0a3d-571b-4758-8b1b-5eedf8df7abd/edit?viewport_loc=247%2C-21%2C2274%2C1094%2C0_0&invitationId=inv_fe839d1a-6bb8-44eb-ae6b-42ccc0834e2d>

1. <a name="_4p0j901qupu5"></a>**Pruebas**

Primero, debemos tener preparado los 4 archivos en nuestro entorno: 




A continuación, presentamos las pruebas:


1. <a name="_tqczo1cmboat"></a>**Conclusiones**
- Los lenguajes de programación esotéricos, aunque no son prácticos para aplicaciones de desarrollo comunes, representan un valioso campo de experimentación y aprendizaje en informática. A través del desarrollo de un compilador para el lenguaje esotérico Brainfuck, podemos adquirir una comprensión más profunda de los principios fundamentales de los lenguajes de programación y las estructuras de control de flujo, así como las operaciones de bajo nivel en la memoria.
- La implementación de un compilador usando tecnologías como LLVM permite la comprensión de los pasos de compilación, desde el análisis de la sintaxis del lenguaje fuente hasta la generación de código en el lenguaje objetivo. Este proceso es esencial para el funcionamiento de los sistemas informáticos modernos, ya que convierte el código de alto nivel escrito por los humanos en código de máquina que las computadoras pueden entender y ejecutar.
- Finalmente, el proyecto enfatiza la importancia de la modularidad y la reutilización en el diseño de software. La utilización de LLVM, una colección modular de tecnologías de compilador, resalta el valor de las herramientas que pueden ser utilizadas en una variedad de contextos para abordar una serie de problemas diferentes. En este caso, LLVM nos permite crear un compilador para un lenguaje tan inusual como Brainfuck, demostrando la versatilidad y la capacidad de estas herramientas.


