Prefacio
========

Lee esto antes de empezar con Flask. Esto ojalá responda algunas preguntas
acerca del propósito y las metas del proyecto, y de cuándo usarlo
o cuándo no usarlo.

¿Qué significa "micro"?
-----------------------

"Micro" no significa que tu aplicación web deba recaer en un solo archivo de
Python (aunque ciertamente sí puede), ni significa que a Flask le falta
funcionalidad. El "micro" en microframework significa que Flask apunta a
mantener el núcleo simple pero extensible. Flask no quiere tomar muchas
decisiones por tí, tal como cúal base de datos utilizar. Aquellas deciciones
que hace, tales como qué motor de plantillas usar, son fáciles de cambiar.
Todo lo demás depende de tí, así que Flask puede ser todo lo que necesitas y
nada de lo que no.

Por defecto, Flask no incluye una capa de abstracción de base de datos,
validación de formularios o cualquier otra cosa que una librería diferente
pueda manejar. En su lugar, Flask soporta extensiones para agregar tales
funcionalidades a tu aplicación como si estuviera implementado en el propio
Flask. Numerosas extensiones proveen integración con bases de datos, validación
de formularios, manejo de carga, varias tecnologías de autenticación abiertas,
y más. Flask puede ser "micro", pero está listo para uso en producción en una
variedad de necesidades.

Configuración y convenciones
----------------------------

Flask tiene muchos valores de configuración, con valores predeterminados sencibles,
y unas pocas convenciones al empezar. Por convención, las plantillas y archivos
staticos se almacenan en subdirectorios dentro del árbol de trabajo de la aplicación,
con los nombres :file:`templates` y :file:`static` respectivamente. Mientras que esto
puede cambiarse, usualmente no tienes que hacerlo, especialmente cuando estás empezando.

Creciendo con Flask
-------------------

Una vez que tienes a Flask en funcionamiento, encontrarás una variedad de extensiones
disponibles en la comunidad para integrar a tu proyecto en producción.

Conforme tu código base crezca, eres libre de tomar las decisiones apropiadas de diseño
para tu proyecto. Flask continuará proveyendo una capa de unión muy simple a lo mejor
que Python tiene para ofrecer. Puedes implementar patrones avanzados en SQLAlchemy o
alguna otra herramienta de base de datos, introduce la persistencia de datos no
relacionales como sea apropiado, y toma ventaja de las herramientas agnósticas creadas
para WSGI, la interfaz web de Python.

Flask incluye muchos enganches para personalizar su comportamiento. Si necesitas más
personalización, la clase Flask está construída para subclases. Si estás interesado en
esto, revisa el capítulo :doc:`volviendosegrande`. Si sientes curiosidad sobre los
principios de diseño de Flask, ve a la sección acerca de :doc:`diseño`.