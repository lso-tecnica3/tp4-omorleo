# Trabajo Práctico 4: Archivos

> [!IMPORTANT]
> Entregar cada ejercicio en una carpeta diferente.

1. Crear páginas para realizar la preinscripción de un alumno a la escuela y almacenar los datos en un archivo CSV. Los datos en el archivo deben estar separados por comas y tener en la primera fila el siguiente encabezado: `id_preinscripcion,...,fecha_hora` donde el primer dato es el “código de preinscripción” y el ultimo sera “fecha/hora de preinscripción”. En el medio donde están los puntos suspensivos deben ir los datos del alumno. El `id_preinscripcion` comenzará en 1 si no hay datos cargados y, en caso contrario, se utilizará el máximo id utilizado hasta el momento, incrementado en uno. Si todo está correcto se debe mostrar los datos ingresados, el mensaje ”Preinscripción realizado con éxito, su número de orden es XX” (donde el número de orden se refiere al código de preinscripción) y una opción para volver a ingresar datos. Tener en cuenta de realizar las validaciones que crean necesarias sobre los datos ingresados.
    Además, agregar otra página para poder visualizar un tabla con los todos los datos de los alumnos preinscriptos hasta el momento.
    
2. Crear una página PHP que le permita a un usuario crear su propia trivia de 5 preguntas. Se desea crear una página para que un usuario pueda ingresar un **nombre** para la trivia, las **preguntas**, las **respuestas posibles** y la **respuesta correcta**. Las trivias se deben guardar en archivos CSV distintos. Además, agregar una página principal que liste todas las trivias que hay disponibles y permita resolver cualquiera de ellas.
