![image](https://user-images.githubusercontent.com/125910370/230785563-d11cb518-d000-4f5f-9907-ad42d9daff99.png)


🖥️ Aplicación de tareas con React 🖥️
Esta es una aplicación de tareas básica desarrollada con React, que utiliza varios conceptos importantes como hooks, estados, métodos como trim, filter, map, spread operator, e.target.value y .preventDefault. La aplicación te permite agregar, marcar y eliminar tareas.

Tecnologías utilizadas
React.js
HTML
CSS
JavaScript
Funcionalidades
La aplicación de tareas tiene las siguientes funcionalidades:

Agregar una nueva tarea: puedes agregar una nueva tarea a la lista de tareas ingresando un texto y presionando el botón "Agregar tarea" o presionando la tecla "Enter".
Marcar una tarea como completada: puedes marcar una tarea como completada haciendo clic en el botón de verificación junto a la tarea correspondiente.
Eliminar una tarea: puedes eliminar una tarea de la lista haciendo clic en el botón "Eliminar" junto a la tarea correspondiente.
Cómo utilizar la aplicación
Para utilizar la aplicación, sigue estos pasos:

Cuando se marca una tarea como completada, se actualiza el estado de la tarea correspondiente utilizando la función map para encontrar la tarea correcta en la lista y actualizar su propiedad completed. Cuando se elimina una tarea, se filtra la lista de tareas para excluir la tarea eliminada usando la función filter.

La aplicación también utiliza el método trim para eliminar espacios en blanco del texto de la tarea y e.target.value para obtener el valor del campo de entrada de la tarea. Además, utiliza e.preventDefault para evitar que el formulario se envíe cuando se presiona el botón "Agregar tarea" o la tecla "Enter".




