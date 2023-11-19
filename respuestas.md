## Respuestas

### La diferencia entre clase y objeto es que la clase es la definición de una abstracción mientras que el objeto es una entidad que tiene un estado y un comportamiento. El estado de un objeto es el conjunto de valores de sus atributos en un momento dado. El comportamiento de un objeto es el conjunto de operaciones que puede realizar.

### La diferencia entre clase e interfaz es que la clase define una abstracción y la interfaz define comportamientos.

### El polimorfismo es la propiedad de una referencia de ser referida a objetos de tipos distintos, y durante la ejecución, invocar el método de la clase a la que pertenece el objeto referenciado.

### En nuestro proyecto podemos ver implementado el polimorfismo en la clase 'Experiencia' y sus subclases 'ExperienciaSimple' y 'ExperienciaCompuesta'. En la clase 'Experiencia' se define el método 'getDatos' que es sobreescrito en las subclases.

### Las asociasiones en un diagrama de clases representan la relación entre las clases. Pueden representar relaciones de dependencia, agregación, composición, herencia, y pueden indicar la naturaleza y la multiplicidad de la relación entre las instancias de las clases.

### Ejemplo de esto es la asociación entre las clases 'Experiencia' y 'ExperienciaCompuesta'. La clase 'ExperienciaCompuesta' es una subclase de la clase 'Experiencia', por lo que la clase 'ExperienciaCompuesta' hereda los atributos y métodos de la clase 'Experiencia'.

### La diferencia entre la agregación y la composición es que en la agregación la clase que representa el todo no es responsable de la creación y destrucción de las instancias de la clase que representa la parte, mientras que en la composición la clase que representa el todo es responsable de la creación y destrucción de las instancias de la clase que representa la parte.

### En nuestro proyecto se puede apreciar esta diferencia al tener una clase EgresadoInfo la cual en su constructor recibe como parámetro una instancia de la clase LinkEgresados de manera que la clase EgresadoInfo es responsable de la creación de la instancia de la clase LinkEgresados ya que debe existir previamente una instancia de esta para poder crear una instancia de la clase EgresadoInfo viendo así la composición. Por otra parte se puede ver la agregación en la clase EgresadoInfo ya que esta puede recibir como parámetro una instancia de la clase ExperienciaCompuesta, pero la clase EgresadoInfo no es responsable de la creación de la instancia de la clase ExperienciaCompuesta, ya que esta puede existir sin que exista una instancia de la clase EgresadoInfo.

### El encapsulamiento es la propiedad de los objetos que les permite controlar el acceso a sus atributos y métodos. Esto implica agrupar los atributos y métodos de un objeto en una unidad, y especificar qué atributos y métodos son accesibles desde fuera de la clase. Esto permite que los objetos puedan ocultar su estado y comportamiento, y que puedan cambiar su estado sin que se modifique el comportamiento de otros objetos. Entre las principales ventajas del encapsulamiento se encuentran la modularidad, la ocultación de la información, y la reutilización del código, la integridad de los datos, etc.

### Un ejemplo de esto es la clase 'EgresadoInfo' la cual tiene como metodo 'setExperiencia' el cual recibe como parámetro una instancia de la clase 'Experiencia' y este método se encarga de validar los datos y asignarle a la instancia de la clase 'EgresadoInfo' el valor del parámetro recibido. De esta manera se puede ver que la clase 'EgresadoInfo' valida los datos y oculta la información de la clase 'Experiencia' y solo se le asigna el valor del parámetro recibido.

### La modularidad en POO se representa mediante la creación de clases, ya que estas permiten agrupar atributos y métodos en una unidad teniendo una responsabilidad unica, también se representa mediante el encapsulamiento ya que este permite proporcionar una interfaz clara para interactuar con la funcionalidad encapsulada, de igual forma se representa mediante la creación de paquetes ya que estos permiten agrupar clases relacionadas con responsabilidades unicas.

### En el polimorfismo la diferencia entre usar herencia o interfaces radica en que utilizar el polimorfismo con herencia implica que las subclases tengan una relación contextual entre ellas, mientras que utilizar el polimorfismo con interfaces implica que las clases que implementan la interfaz no tienen una relación contextual entre sí, sino que solo comparten comportamientos.

