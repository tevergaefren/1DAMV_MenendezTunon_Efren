# Ejercicio 01
## *¿Qué es un programa informático?*
Se trata de una secuencia ordenada de instrucciones, realizada para resolver un "problema" o para realizar una tarea especifica, y orientada para ser ejecutada por un ordenador.

## *Diferencia entre código fuente, código objeto y código ejecutable.*
###
- _Código fuente_

	Se trata de un texto plano que escribe un programador, empleando para ello un lenguaje de programación de alto nivel. Lo entienden los programadores y las herramientas de desarrollo, no puede ser ejecutado por la CPU directamente. Las extensiones típicas son .jav, .cpp, .py, .c.
- _Código objeto_
	Se trata del código resultante de pasar el código fuente por e compilador, este traduce el lenguaje de alto nivel a código binario (o de bajo nivel), pero este aún no se puede ejecutar, esta incompleto. Contiene las instrucciones del archivo, pero le faltan los enlaces a las librerías del sistema o a otros archivos del proyecto que el programa necesita para funcionar. Las extensiones típicas son .obj (Windows) o .o (Linux)
- _Código ejecutable_
	Es el "producto" final. Se obtiene utilizando una herramienta llamada enlazador (linker), une el código objeto con las librerías externas y los otros archivos del proyecto necesarios para funcionar. Este ya es "entendido" por el sistema operativo y la CPU, que puede cargarlo en la memoria RAM y ejecutarlo. Las extensiones típicas son .exe (Windows).


[Referencias 1] (https://www.studocu.com/es/document/instituto-de-educacion-secundaria-poligono-sur/matematicas-ii/13codigos-fuente-objeto-y-ejecutable/104853597?sid=f0645aa9-28b8-494e-8374-7a619f7f98b41790785437)

[Referencia 2] (https://prezi.com/cqq7pc8xhy45/coodigo-fuente-codigo-objeto-y-codigo-ejecutable/)

## Etapas del desarrollo del software.
Hay 6 etapas fundamentales del desarrollo de software
###
1. *Planificación y análisis de Requisitos*
	Es el punto en el que se define que debe hacer el software, se ven las necesidades y se redacta la ERS (Especificación de Requisitos del Software). De aquí obtenemos un documento con los requisitos funcionales (lo que hace el sistema) y no funcionales (rendimiento, seguridad)
1. *Diseño de la Arquitectura*
	Aquí se define cómo se va a construir el software, la arquitectura, la estructura de la base de datos, la interfaz con el usuario y los patrones de diseño. Obtenemos los diagramas de clases (UML), diagramas de entidad-relación y maquetas de pantallas
1. *Codificación*
	Es la fase de programación, donde se traducen los documentos anteriores a código fuente utilizando un IDE y el lenguaje de programación elegido. Tenemos de este modo el código fuente del software repartido en diferentes módulos o componentes
1. *Pruebas*
	Se trata de ejecutar el software en entornos controlados para buscar errores (bugs)y comprobar que cumple con lo que nos pedía el cliente. Se realizan pruebas unitarias, de integración y de sistema. con esto conseguimos tener informes corregido; y un software estable y de calidad.
1. *Despliegue o implantación*
	Es el momento en el que se pone el software en manos de los usuarios finales. Cuando se instala en los servidores de producción, se configuran las bases de datos reales y se realiza la migración de datos si es necesario. En este momento el programa ya está operativo para el cliente.
1. *Mantenimiento y evolución*
	Es la última etapa del ciclo, la más larga. Consiste en corregir errores, adaptar el sistema a nuevos sistemas operativos y añadir nuevas funcionalidades que vaya pidiendo el cliente. Esta es la fase de actualizaciones, parches y nuevas versiones del software.

[Referencia 3] (https://www.microsoft.com/es-es/power-platform/topics/phases-of-the-software-development-lifecycle)

[Referencia 4] (https://intelequia.com/es/blog/post/ciclo-de-vida-del-software-todo-lo-que-necesitas-saber)

![viedojuegos](images/videojuegos.jpg)


[enlace al repositorio Efren] (https://github.com/tevergaefren/1DAMV_MenendezTunon_Efren.git)