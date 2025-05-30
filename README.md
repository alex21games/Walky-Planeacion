# Walky - Un chat seguro y ligero para tu empresa
___
## ¿Qué es walky?

Walky será una aplicación de escritorio desarrollada en Python que planea ser lo mas segura y funcional para el beneficio de tu empresa y empleados.

Contara con conectividad exclusiva a una red LAN, puesto no se esta planeado para su uso fuera de la empresa, mas como herramienta con la que los trabajadores y desarrolladores puedan mejorar su flujo de trabajo dentro de la compañía, con la capacidad de subir archivos de varios formatos: PNG, JPEG, MP3, MP4, DOCX, PDF, MD, RAR, carpetas, código crudo, etc.

Con códigos únicos para cada trabajador, que los demás tendrán que añadir puesto creemos que cada persona debería tener la opción de elegir quien puede contactarlo y/o tener su contacto.

También una interfaz sencilla pero agradable para el ojo programador, tema oscuro cálido pero fuerte a la vez con tonos resaltantes en las funcionalidades importantes y un tema blanco para aquellos que prefieren lo de la vieja escuela con un parecido a eclipse o NetBeans ¡que tiempos aquellos!

## Objetivos
___
Tenemos una filosofía de que el programador se sienta cómodo con sus herramientas, que no tarden años en abrir o tengan muchos botones que no se usan ni la mitad, que el programador pueda concentrarse en trabajar y no en optimizar su flujo de trabajo con otra herramienta mas que le impide trabajar cómodamente.

Por eso, ¿Cuáles son nuestros principales objetivos?

1. Ser directos: Un programa sin complicaciones, listo para usarse de entrada y con opciones que serian mas que suficientes para un buen flujo de trabajo.
2. Seguro: No queremos a otra gente metida en nuestros asuntos internos, todos los chats son privados y solo por lado del cliente se guarda información de los chats y archivos.
3. Utilidad: Queremos proveer la mayor cantidad de herramientas que puedan ser necesarias para el día a día del programador o trabajador que use el programa, siempre estamos dispuestos a incluir nuevas funcionalidades.


## Funcionalidades
Muchas de las funcionalidades ya las comentamos anteriormente pero las principales tenemos que dejarlas claras:

1. - Enviar mensajes de texto a un usuario (sin esto no se le podría decir chat)
2. - Enviar documentos, archivos y código crudo a una conversación
3. - Añadir gente a tus contactos
4. - Bandeja de notificaciones
5. - Notificaciones en pop up y de dos tipos: urgentes y no urgentes
6. - Tener los archivos que envías y se te envían de manera local

Para que quede de manera mas visual como funcionara el programa a continuación se mostrara un diagrama de flujo con formato C4 con todo las funciones que mencionamos y como se comunican entre si.





![Diagrama](diagrama-sistema.svg)


## Herramientas
___
Para este proyecto usaremos únicamente Python con Tkinter y SQLite ya que la base de datos no será muy compleja o grande, solo almacenara información básica, Tkinter siendo la librería que usaremos para la interfaz grafica y Python pues el lenguaje que usaremos para hacer el programa.


## Roles
___
Entrando mas en el repartimiento de las tareas que se encomendaran a lo largo del proyecto solo seremos dos los encargados del proyecto:

Yo (Efraín De Jesús) me encargare de gran parte del área técnica, como crear la mayor parte del programa y de esta planeación.

Mi compañero (Yahel Soto) se encargara de realizar los manuales y las pruebas del programa.

Y entre los dos realizaremos la presentación del programa total.
