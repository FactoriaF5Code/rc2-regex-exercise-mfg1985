[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/aRQGnba4)
# Expresiones Regulares (regex)

## Investiga: 

- qué son las expresiones regulares?
 una expresión regular es una herramienta poderosa para realizar operaciones de búsqueda y manipulación de texto. Puedes especificar patrones complejos que coincidan con ciertos patrones de caracteres, lo que facilita tareas como validar direcciones de correo electrónico, buscar palabras clave en un texto o realizar operaciones avanzadas de manipulación de cadenas.

- Qué problema resuelven? Por qué es importante conocerlas?
 Los  relacionados con el procesamiento y manipulación de cadenas de texto.
 Búsqueda y Extracción de Patrones: Permiten buscar patrones específicos en una cadena de texto, como direcciones de correo electrónico, números de teléfono, fechas, etc. Esto es útil para extraer información estructurada de grandes conjuntos de datos.

Validación de Formatos: Se utilizan para validar si una cadena de texto cumple con un formato específico. Por ejemplo, verificar si una cadena representa un número de teléfono válido o una dirección de correo electrónico bien formada.

Reemplazo de Texto: Facilitan la tarea de buscar y reemplazar texto en un documento o cadena de texto según ciertos patrones. Esto es útil para realizar cambios masivos y precisos en grandes conjuntos de datos.

Análisis de Texto: Ayudan en la tarea de analizar y procesar texto de manera más eficiente y precisa. Pueden utilizarse para dividir una cadena en partes significativas o para realizar operaciones más avanzadas de manipulación de texto.

Automatización de Tareas: Permiten automatizar tareas relacionadas con el manejo de cadenas de texto en programación y scripting. Esto puede incluir la manipulación de archivos de texto, la generación de informes o la transformación de datos.
## Ejercicio 1:

Escribe las expresiones regulares correctas para validar:

- un email: ^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$

- un número de teléfono (español): ^(\+34|0034|34)?[6789]\d{8}$

- un DNI: ^\d{8}[A-HJ-NP-TV-Z]$


## Ejercicio 2:

Crea un formulario de contacto y utiliza el atributo `pattern` de los elementos `input` para validar los campos usando expresiones regulares. El formulario debe incluir: nombre, apellidos, dni, número de teléfono, email, dni y dirección.

Nota: puedes hacerlo añadiendo un archivo `index.html` en este repositorio.


## Referencias

- [Expresiones Regulares en Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions)
- [Online Regex Editor](https://regex101.com/)