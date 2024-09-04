Checkpoint 17

¿Qué significa CRUD?

"CRUD es el acrónimo de Create (Crear), Read (Leer), Update (Actualizar) y Delete (Borrar). Este concepto se utiliza para describir las cuatro operaciones básicas que pueden realizarse en la mayoría de las bases de datos y sistemas de gestión de información.

Estas operaciones permiten a los usuarios crear nuevos datos (Create), leer los existentes (Read), actualizarlos (Update) y eliminarlos (Delete). 

CRUD es una función esencial para muchos sistemas de información, ya que permite a los usuarios realizar tareas básicas de mantenimiento y gestión de datos.

El concepto de CRUD surge en el contexto del desarrollo de software y de la gestión de bases de datos relacionales. 

La idea es que cualquier sistema de información que interactúe con datos debe proporcionar funcionalidades para crearlos, leerlos, actualizarlos y eliminarlos.

Las ventajas del CRUD son que: Facilita la creación y gestión de datos. Proporciona una estructura coherente y fácil de entender para su manipulación. Ayuda a minimizar los errores y garantiza la integridad de los datos. Proporciona una base sólida para el desarrollo de aplicaciones. 

Y las desventajas del CRUD son que: Puede ser demasiado simplista para aplicaciones complejas. En ocasiones, es menos eficiente para aplicaciones de alta velocidad o de gran escala. A veces, requiere una gran cantidad de código y configuración para implementarlo completamente. 

CRUD se utiliza cuando se está desarrollando una aplicación que maneja datos almacenados en una base de datos. Es un concepto fundamental en el desarrollo de software, especialmente en aplicaciones que interactúan con bases de datos, como aplicaciones web, sistemas de gestión de contenido (CMS), y sistemas de información empresarial.

La razón para utilizar CRUD es que estas operaciones cubren prácticamente todas las interacciones básicas que una aplicación puede tener con una base de datos. Permiten crear, acceder, modificar y eliminar


¿Qué es un operador ternario?

Un operador ternario es un operador que toma tres [argumentos](https://es.wikipedia.org/wiki/Operando "Operando"). Este operador ternario puede pasar varias líneas de código a una sola línea en lenguajes que puedan usarlo tales como JavaScript, o Java. Los argumentos y el resultado puede ser de diferentes tipos. 

Muchos lenguajes de programación que utilizan la sintaxis del [lenguaje C](https://es.wikipedia.org/wiki/Lenguaje_de_programaci%C3%B3n_C "Lenguaje de programación C") utilizan un operador ternario,?:, que define una [sentencia condicional](https://es.wikipedia.org/wiki/Sentencia_condicional "Sentencia condicional"). Dado que este operador es a menudo el único operador ternario existente en el lenguaje de programación, a veces es referido simplemente como "el operador ternario". 

La sintaxis del operador ternario (?:) se utiliza como sigue:[<sup>2</sup>](https://es.wikipedia.org/wiki/Operador_ternario#cite_note-kwista-2)​

expresión boleana ? valor si cierto : valor si falso

La condición es evaluada verdadera o falsa como una expresión [booleana](https://es.wikipedia.org/wiki/Booleano "Booleano"). Sobre la base de la evaluación de la condición de Booleana, la expresión entera devuelve valor si cierto si la condición es verdadera, pero valor si falso en caso contrario. Por lo general, las dos sub-expresiones valor si cierto y valor si falso deben tener el mismo tipo, lo cual determina el tipo de toda la expresión. 

La importancia de este tipo de control se encuentra en el uso más común del operador --en declaraciones de asignación condicional. En este uso aparece como una [expresión](https://es.wikipedia.org/wiki/Expresi%C3%B3n_\(programaci%C3%B3n\) "Expresión (programación)") en el lado derecho de una sentencia de asignación, de la siguiente manera:

variable = condición ? valor si cierto : valor si falso

El operador ?: es similar a la manera como funcionan las expresiones condicionales (if-then-else) en lenguajes de [programación funcional](https://es.wikipedia.org/wiki/Programaci%C3%B3n_funcional "Programación funcional"), como [Scheme](https://es.wikipedia.org/wiki/Scheme "Scheme"), ML y [Haskell](https://es.wikipedia.org/wiki/Haskell "Haskell"), puesto que if-then-else forma una expresión en lugar de una declaración en esos idiomas.

El uso más común de este operador ternario es hacer una breve sentencia condicional. Por ejemplo, si queremos desarrollar código en C para cambiar las horas de apertura de una tienda a 12:00 del mediodía los fines de semana y 9 en punto entre semana, podemos usar:

int tiempo\_de\_apertura = (día == FIN\_DE\_SEMANA) ? 12 : 9;

en lugar del código más detallado

int tiempo\_de\_apertura;

if (día == FIN\_DE\_SEMANA)

`    `tiempo\_de\_apertura = 12;

else

`    `tiempo\_de\_apertura = 9;

Las dos formas son casi equivalentes. Tenga en cuenta que el ?: es una expresión y if-then-else una declaración. También hay que tomar en cuenta que ni el valor si es verdadero ni valor si falso pueden ser omitidos en el operador ternario, lo cual resultaría en un error por el [compilador](https://es.wikipedia.org/wiki/Compilador "Compilador"). Esto contrasta con sentencias de if..else, donde se puede omitir la cláusula else.

Los beneficios que tiene utilizar un operador ternario son que permite escribir condiciones simples en una sola línea, haciendo el código más compacto.

En casos donde la condición es sencilla, puede hacer que el código sea más fácil de leer al reducir el número de líneas.

Evita la necesidad de escribir una estructura condicional más larga, como un if-else.

El operador ternario se utiliza mejor en situaciones donde la lógica condicional es simple y se puede expresar claramente en una sola línea. Por ejemplo, al asignar un valor a una variable en función de una condición sencilla.



¿Qué tipo de solicitud de API hacemos cuando queremos eliminar datos?

Cuando queremos eliminar datos a través de una API, hacemos una solicitud de tipo DELETE

Una solicitud DELETE es un método HTTP que se utiliza para eliminar un recurso específico del servidor. Generalmente, se especifica el recurso a eliminar mediante su identificador único en la URL de la solicitud.
### Los beneficios que tiene utilizar una solicitud DELETE son que El método DELETE es simple y directo para eliminar recursos. No requiere un cuerpo extenso en la solicitud, solo la identificación del recurso.
Se utiliza cuando se necesita eliminar un recurso en particular, como un registro de usuario, un artículo, una publicación, etc.

Utilizar el método DELETE deja claro que la operación tiene como objetivo la eliminación de un recurso, reduciendo el riesgo de malentendidos o errores en la interpretación de la solicitud.

¿Qué tipo de solicitud de API hacemos cuando queremos actualizar los datos?

Cuando queremos actualizar datos a través de una API, utilizamos una solicitud de tipo PUT o PATCH. Ambos métodos son utilizados para modificar recursos, pero tienen diferencias importantes en su comportamiento y uso.

Una solicitud PUT es un método HTTP utilizado para actualizar un recurso existente en el servidor o crear uno nuevo si no existe. Cuando se realiza una solicitud PUT, se envía un recurso completo al servidor, y este reemplaza completamente el recurso existente con el nuevo contenido proporcionado.

Una solicitud PATCH es otro método HTTP utilizado para actualizar parcialmente un recurso existente. A diferencia de PUT, que requiere enviar todo el recurso, PATCH solo necesita los cambios específicos que deseas realizar.

Los beneficios de la solicitud PUT son que asegura que el recurso en el servidor sea exactamente igual al enviado en la solicitud, lo que puede ser útil cuando se requiere que los datos sean coherentes y completos.

Además, simplifica el manejo de datos, ya que el servidor siempre puede esperar un recurso completo.

Los beneficios de la solicitud PATCH son que solo actualiza los campos necesarios, lo que puede ser más eficiente en términos de ancho de banda y procesamiento.  Es ideal para situaciones en las que solo una parte del recurso necesita ser actualizada, sin alterar el resto de los datos.
### Utilizaría la solicitud PUT Cuando necesito actualizar todos los campos de un recurso y asegurarme de que el servidor tenga una versión completa y coherente de ese recurso. 
En el caso de PATCH, es preferible cuando deseas hacer cambios pequeños y específicos sin enviar datos innecesarios.

¿Qué es el código dinámico?

El código dinámico es como si pudieras escribir o cambiar las instrucciones de un programa mientras este se está ejecutando, en lugar de hacerlo todo antes de que empiece a funcionar.

El código se puede crear o modificar mientras la aplicación está en ejecución, lo que permite una gran flexibilidad en la manera en que se comporta el programa.

El código puede ser evaluado o ejecutado en tiempo real, lo que permite al programa adaptarse a diferentes condiciones o datos que no estaban disponibles al momento de escribir el código original.

Permite a los desarrolladores o usuarios interactuar con el programa de manera más avanzada, como ejecutar comandos personalizados, cargar scripts adicionales, o ajustar el comportamiento del software sin necesidad de recompilar o reiniciar la aplicación.

Tiene como beneficio que permite modificar el comportamiento de un programa sin necesidad de cambiar el código base, lo que es útil para situaciones donde las necesidades del programa pueden cambiar.

Tiene como riesgo que puede ser más difícil de mantener y depurar que el código estático, ya que puede resultar en comportamientos impredecibles si no se gestiona cuidadosamente.







