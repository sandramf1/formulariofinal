# formulariofinal
En este repositorio se incluye el código con respecto al formulario que se pide hacer en la tarea de laboratorio del curso.

En cuanto a la validación de los campos del formulario, se hace, por así decirlo en dos niveles (y usando las imágenes y los estilos de validación que se pedían). Por un lado, siempre que se pulsa una tecla en un campo determinado se llama a la función JS que valida ese campo y por otro lado, cuando se pulsa el botón enviar se vuelve a validar. Se ha optado por hacer las validaciones con JS dado que el trabajo con REGEX es más sencillo.

En cuanto al campo nombre, solo se permiten letras mayúsculas o minúsculas que no sean la Ñ y espacios.

En cuanto al email, se buscó una expresión regular en Internet tal y como se comentaba en el laboratorio.

En cuanto a la contraseña, en el primer campo se valida que no tenga más de 8 caracteres y en el segundo campo se valida, además de eso mismo, que la contraseña de confirmación y la anterior que se ha introducido sean iguales.

El estilo de los errores y de los aciertos en las validaciones del campo se hace a través de una función JavaScript que añade código con la función innerHTML, y después se formatea en CSS.
