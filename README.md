# JAVASE
Los Objetos pueden ser
Físicos: User
Conceptuales: Session

Los objetos tendrán:
Propiedades (estado)
Métodos (comportamientos)

Las propiedades son características de los objetos y siempre serán de tipo sustantivo(nombre, tamaño, forma, estado).

-Los valores de las propiedes pueden ser sustantivos o adjetivos.
Por ejemplo: Juan, Alta, Azul, apagado.

Los comportamientos serán todas las operaciones del objeto, suele ser verbos o sustantivos y verbo.
ejemplos: login(), logout(), makeReport().


DIAGRAMA DE CLASES
------------------

Para entender qué es un diagrama de clases, lo primero que se debe tener claro es qué es una clase, pues bien, una clase es un elemento importante dentro del contexto de un sistema, que puede tener información o datos valiosos y realizar acciones que sean necesarias dentro del funcionamiento del sistema.

Por ejemplo, en un software para un supermercado, seguramente los elementos más importantes sobre los cuales sea significativo mantener información son los productos, los clientes, las ventas y los pedidos, en este caso se han encontrado las clases PRODUCTO, CLIENTE, VENTA y
PEDIDO.
Estas clases a su vez tienen atributos (datos) y métodos (funciones), porejemplo, la clase PRODUCTO tiene como uno de sus atributos, el atributo precio y uno de sus métodos puede ser incrementarPrecio. De esta forma, a través de los atributos se puede acceder a la información de la clase y a través de los métodos se pueden ejecutar acciones sobre la clase. Estas clases se unen a otras clases a través de relaciones y así se conforma el diagrama de clases.
Toda clases se compone de 3 elementos importantes así: Nombre de la clase, Atributos o propiedades también denominados miembros de la clase y los métodos (operaciones) o
acciones propias de la clase. (Estas acciones se identifican con verbos en infinitivo).
EjemploDeClases.png

Atributos:
------------------
Los atributos o características de una Clase pueden ser de tres tipos, definen la visibilidad:
  * Public (+): Indica que el atributo será visible tanto dentro como fuera de la clase, es decir, es accesible desde todos lados.
  * Private(-): Indica que el atributo sólo será accesible desde dentro de la clase (sólo sus métodos lo pueden acceder).
  * Protected (#): Indica que el atributo no será accesible desde fuera de la clase, pero si podrá ser accedido por métodos de la clase además de las subclases que se deriven (herencia).
Sin modificador de acceso ( ): Indica que el atributo será accesible desde cualquier clase que se encuentre en el mismo paquete de la clase que contiene al atributo sin modificador de acceso.
Métodos:
------------------
Los métodos u operaciones de una clase son la forma en cómo ésta interactúa con su entorno, éstos pueden tener las características:
• Public (+): Indica que el método será visible tanto dentro como fuera de la clase, es decir, es accesible desde todos lados.
• Private (-): Indica que el método sólo será accesible desde dentro de la clase (sólo otros métodos de la clase lo pueden acceder).
• Protected (#): Indica que el método no será accesible desde fuera de la clase, pero si podrá ser accedido por métodos de la clase además de métodos de las subclases que se deriven (herencia).
• Sin modificador de acceso ( ): Indica que el método será
accesible desde cualquier clase que se encuentre en el mismo
paquete de la clase que contiene al método sin modificador de
acceso.
Les comparto mis apuntes de esta Clase:

Modularidad
------------------
Es un concepto proveniente del diseño industrial y la arquitectura. Consiste en dividir un sistema en varios módulos independientes que unidos conforman todo el sistema completo.

Ventajas de la modularidad:
------------------
  * Reutilizar código.
  * Se evitan colapsos.
  * Código más mantenible.
  * Mejor legibilidad en el código
  * Rápida resolución de problemas
  * Mientras en las programación estructurada se tiene un sólo archivo muy grande en el que esta toda la lógica del sistema y en el que un error puede detener la ejecución de todo el programa, en la programación orientada a objetos las diferentes funciones de un sistema se dividen en módulos independientes, por lo que a la hora de solucionar bugs sólo hay que ubicar el módulo que esta fallando y repararlo sin tener que afectar al resto del código; y si se quieren añadir más funcionalidades al proyecto solo hay que crear nuevos módulos e integrarlos dentro del sistema.

Las Clases dentro de la modularidad

Las Clases juegan un papel fundamental dentro de la modularidad, pues permiten dividir el software en diferentes partes o módulos/Clases y a su vez separar dichas Clases en archivos diferentes.
