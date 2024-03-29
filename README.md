# AE_2_XML_DTD_XSD

Este es una tarea realizada para el ciclo formativo grado superior de Desarrollo de Aplicaciones Multiplataforma.

Enunciado

Vamos a elaborar una estructura de base de datos en XML que permita almacenar los datos de una biblioteca en la red con las siguientes características:

Existen tres tipos de documentos almacenados en la biblioteca: libros, revistas y periódicos. Todos los documentos están identificados por el atributo Id.
Para los libros este atributo empieza con la letra “L” seguido de 4 dígitos identificativos.
Para los periódicos este atributo empieza por la letra “P” seguido de los 4 dígitos identificativos.
En el caso de las revistas empieza por la letra “R”.
Los libros a su vez son clasificados en novela, infantil o didáctico. Cada libro contiene un atributo identificativo de su clase denominado tipo_clase. Dentro de cada libro se tiene un título, varios capítulos con el título en su interior, un índice y una sinopsis. Tanto en libro como en capítulo existe un atributo que contiene el número de páginas del libro o del capítulo, según corresponda. Cada capítulo contiene un elemento denominado contenido, en el que se tiene un atributo con el enlace a la información.
Las revistas a su vez son clasificadas en: informática, corazón, coches, investigación y otras. Cada revista tiene el atributo tipo_clase identificativo de la clase a la que pertenece. Dentro de cada revista tenemos el título, el número de la revista, un índice de contenido y las secciones. En cada sección y en la revista se tiene un atributo que contiene el número de páginas. Además, en cada sección se tiene la parte denominada contenido, en la que se tiene un atributo con un enlace a la información.
Los periódicos se clasifican en nacionales e internacionales. Cada periódico contiene el atributo tipo_clase identificativo de la clase a la que pertenece y un atributo que incluye la fecha de publicación. Dentro de los periódicos tenemos secciones y un índice. Cada sección debe contener un atributo identificativo del tipo de sección, que puede ser: económica, opinión, deportes, nacional o internacional. Las secciones se dividen en artículos, en donde se define en un atributo el autor. Finalmente, el contenido será el último elemento del árbol, que necesita un atributo que referencie a la información.
Requerimiento 1

Crear un XML con el modelo de datos indicado en el enunciado.

Elaborar un DTD que permita validar el documento XML.

Validar el documento con alguna aplicación externa e incluir capturas de pantalla.

IMPORTANTE: Cada alumno propondrá una solución de XML y DTD. Una vez todos los alumnos hayan puesto todas sus soluciones, se cotejará con el resto para poner la solución final.

Valoración: 5 puntos sobre 10

Requerimiento 2

Elaborar un XSD que permita validar el documento XML.

Validar el documento con alguna aplicación externa e incluir capturas de pantalla.

IMPORTANTE: Cada alumno propondrá una solución de XML y XSD. Una vez todos los alumnos hayan puesto todas sus soluciones, se cotejará con el resto para poner la solución final.

Valoración: 5 puntos sobre 10
