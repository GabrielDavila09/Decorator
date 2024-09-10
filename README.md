## Elvirez Dávila Ulises Gabriel - 20211769
# Decorator
Decorator es un patrón de diseño estructural que te permite añadir funcionalidades a objetos 
colocando estos objetos dentro de objetos encapsuladores especiales que contienen estas funcionalidades.
El decorator hereda la interfaz de la misma clase que el objeto que decora, de esta forma permite que los objetos decorados puedan ser tratados como si fueran instancias del obejeto original. 

![DecoratorImage](https://refactoring.guru/images/patterns/content/decorator/decorator.png?id=710c66670c7123e0928d3b3758aea79e)

# Pros
### ✔ Es posible extender el comportamiento de un objeto sin crear una nueva subclase.
### ✔ Es posible combinar varios comportamientos envolviendo un objeto con varios decoradores.
### ✔ Es posible añadir o eliminar responsabilidades de un objeto durante el tiempo de ejecución.
### ✔ Es posible de responsabilidad única. Puedes dividir una clase monolítica que implementa muchas variantes posibles de comportamiento, en varias clases más pequeñas.

# Contras
### ❌ Resulta difícil eliminar un wrapper específico de la pila de wrappers.
### ❌ El código de configuración inicial de las capas pueden tener un aspecto desagradable.
### ❌ Es difícil implementar un decorador de tal forma que su comportamiento no dependa del orden en la pila de decoradores.

# Analogía en el mundo real
Vestir ropa es un ejemplo del uso de decoradores. Cuando tienes frío, te cubres con un suéter. Si sigues teniendo frío a pesar
del suéter, puedes ponerte una chaqueta encima. Si está lloviendo, puedes ponerte un impermeable. Todas estas prendas “extienden” 
tu comportamiento básico pero no son parte de ti, y puedes quitarte fácilmente cualquier prenda cuando lo desees.

![DecoratorImage](https://refactoring.guru/images/patterns/content/decorator/decorator-comic-1.png?id=80d95baacbfb91f5bcdbdc7814b0c64d)
