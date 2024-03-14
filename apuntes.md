¿Qué hace un analista de datos?

Los analistas de datos buscan determinar cómo se pueden usar los datos para responder preguntas y resolver problemas de negocio.


Algunas tareas involucradas:

-Analizar e interpretar resultados utilizando herramientas y técnicas estadísticas.

-Identificar tendencias y patrones en conjuntos de datos.

-Trabajar con equipos de tecnología para establacer metas y objetivos en común.

-En algunas ocasiones, se deberán de encargar de limpiar los datos para la eliminación de información irrelevante.

-Identificar nuevas oportunidades de acción para la mejora de procesos.

-Generar informes de datos para la gestión.



Herramientas de visualización de datos

Excel es una herramienta "entry level", es decir, es una de las primeras herramientas que has de aprender para dedicarte a los datos.

Power Bi

Tableau

QlikView

Data Studio

Cognos



¿Qué es Excel?

Es una hoja de cálculo que nos permite manipular datos numéricos y de texto en tablas formadas por la unión de filas y columnas.
Excel ofrece datos estructurados de manera tabular.


Artículo sobre la historia de Excel: 

https://aula10formacion.com/blog/la-historia-de-excel/


Para trabajar con Excel en Mac hay una aplicación descargable.

Para usar Excel con Microsoft 365 hay una prueba gratuita de un mes.

También hay una versión web desde:

https://www.microsoft365.com/template/excel



Creamos un libro en blanco.

Hay un espacio que será muy importante, el espacio de fórmula. Se puede ampliar para mayor comodidad.

Las columnas de las tablas vienen definidas por letras.

Las filas de las tablas vienen definidas por números.

La intersección de una columna y una fila es una celda.

Referenciar celdas es nombrarla con la columna + fila, por ejemplo B2, H16, etc.

A través de la referenciación de celdas logramos la automatización.

Las celdas son punteros hacia un valor o un dato.

Excel tiene muchas opciones. Una importante es cambiar tipos de datos, por ejemplo.



¿Cómo proteger un archivo de Excel?

Existen tres niveles de protección:

-Celda

-Hoja

-Libro

Se hace en el apartado "Revisar", y es muy útil si no quieres que nadie pueda modificar tu documento.


Es recomendable tener activado el autoguardado.

Y con el historial de versiones podemos ver quién ha hecho cada cambio (si lo usamos de modo colaborativo).
Para compartir el archivo hay una pestaña arriba a la derecha, y desde ahí también podemos definir qué permisos le damos a esa persona.

Existe también la posibilidad de exportar el archivo.


Hay que tener en cuenta cuando guardemos el trabajo hacerlo con la extensión  .xlsx



Error de desbordamiento.

Ocurre cuando tienes alguna casilla ocupada donde quieres pegar algo.


Rellenar celdas con valores o fórmulas.

3 formas:

-comandos

-controlador

-atajos


Autocompletar.

Se usa para rellenar las celdas en base a un patrón.


Referencias en Excel

Existen dos tipos de referencias, las relativas y las absolutas.


Para leer más sobre referencias en Excel:

https://exceltotal.com/referencias-absolutas-y-relativas/


Listas desplegables, validación de datos

Se usa para restringir los valores que se pueden introducir entre un rango de datos, o ajustandose a una lista de valores. (está en la pestaña Datos)


Dividir texto en columnas


Formato condicional

Sirve para aplicar una regla lógica y a partir de los registros que cumplen ese criterio, aplicar un formato concreto.


Clase dos

Comparativa entre la versión desktop y la versión online de Excel.

Por lo general, la versión online puede ser más cómoda para trabajos ligeros, y te da la libertad de que puedas usarla en cualquier pc.

La versión desktop es mejor para trabajos más pesados, y cuanta con algunas funicionalidades exclusivas. También hay que tener en cuenta las prestaciones de tu propia computadora cuando se trata de velocidad de procesamiento de datos, etc.


FORMULAS Y FUNCIONES


¿Qué son las fórmulas de Excel?

 Son instrucciones o expresiones matemáticas que se utilizan para realizar cáculos, manipular datos y realizar diversas operaciones en una hoja de cálculo.

 Permiten realizar una amplia gama de tareas, desde operaciones matemáticas simples hasta cálculos complejos y análisis de datos.

 Las fórmulas en Excel siempre comienzan con el signo igual (=) y pueden incluir referencias a celdas, valores constantes, funciones predefinidas de Excel y operadores matemáticos.

 Algunos ejemplos comunes de fórmulas en Excel incluyen:

 -Resta de valore: =B2-B3

 -Multiplicación de valores: =C4*D4

 -División de valores: =E5/F5

Excel incluye funciones predefinidas que cubren diversas áreas, como matemáticas, estadísticas, finanzas, fecha y hora, texto, búsqueda y referencias, entre otras.


¿Qué son las funciones en Excel?

Son fórmulas predefinidas que realizan cálculos específicos o ejecutan operaciones sobre los datos en una hoja de cálculo.


Las funciones:

-Tienen nombre

-Pueden recibir parámetros

-Devuelven un resultado


=nombre_de_la_función(argumento1,argumento2,...)

Función dinámica: La que recibe parámetros.

Función estática: La que no recibe parámetros.


Para ver la lista de todas las funciones de Excel existentes: http://exceltotal.com/funciones/


Diferencia entre fórmula y función

FÓRMULA: 

-Expresión matemática o lógica que comienza con el signo igual (=) y puede incluir operadores matemáticos, referencias a otras celdas, valores constantes y funciones.

-Se crean escribiendolas manualmente.

-Pueden realizar cálculos simples o complejos.


FUNCIÓN:

-Es una función predefinida que realiza una tarea específica.

-Tienen nombre y una sintaxis específica.

-Se utilizan para realizar cáculos más complejos.

-Se utilizan escribiendo el nombre de la función seguido de paréntesis que contienen los argumentos de la función.

-Se utiliza para simplificar y automatizar cálculos comunes, y permiten realizar una amplia gama de tareas sin la necesidad de escribir expresiones matemáticas complejas manualmente.



Los operadores de Excel


Concatenar con el operador ampersand (&)

-Concatenar referencia a celdas

-Concatenar valores y texto

-Concatenar fórmulas y texto


Listas personalizadas
Cuando tenemos por ejemplo una fila con varias celdas, y en la primera pone "lunes", y yo arrastro hacia la derecha, me lo rellena con los demás días de la semana. 
O si pone en la primera celda "Enero" y lo arrastro hacia la derecha me lo rellena con los demás meses del año.
Esto es por las listas personalizadas que Excel tiene precargadas.

¿Cómo crear tu propia lista personalizada?

seccion archivo, opciones, solapa "avanzadas", general, modificar listas pesonalizadas.
En mac esta opción está en "preferencias de Excel".


Administración de celdas y rangos

Podemos seleccionar un rango de celdas y asignarles un nombre, y luego usar éste pata referenciar dichas celdas.



Funciones lógicas

-SI

-Y y O

-SI anidada