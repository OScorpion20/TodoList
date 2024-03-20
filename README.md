# Todo List en React

Este proyecto es un simple Todo List desarrollado utilizando React. Permite a los usuarios agregar, marcar como completadas y eliminar tareas de su lista de quehaceres.

## Funcionalidades

- Agregar nuevas tareas.
- Marcar tareas como completadas.
- Eliminar tareas de la lista.

## Componentes

El código es una aplicación de lista de tareas (Todo List) desarrollada utilizando React. Aquí hay una descripción de sus componentes principales:

Importaciones de React y Hooks:
Importa React y los hooks useState y useEffect de la biblioteca "react". Estos hooks se utilizan para manejar el estado y los efectos secundarios en componentes funcionales de React.

Estilos CSS:
Importa los estilos CSS desde el archivo "App.css". Esto permite aplicar estilos a la aplicación.

Componente Funcional App:
Define un componente funcional llamado App, que representa toda la aplicación de lista de tareas.

Estado de los Todos:
Utiliza el hook useState para gestionar el estado de los todos. Inicialmente, el estado todos se establece como un array vacío.

Estado de Edición de Todo:
Utiliza otro estado, todoEditing, para rastrear el todo que se está editando actualmente. Se inicia como null.

Efecto para Cargar los Todos:
Utiliza el hook useEffect para cargar los todos desde el almacenamiento local después de la primera renderización. Si hay datos guardados, los carga en el estado todos.

Efecto para Guardar los Todos:
Utiliza otro efecto useEffect para guardar los todos en el almacenamiento local cada vez que el estado todos cambia.

Funciones de Manipulación de Datos:
Define funciones como handleSubmit, deleteTodo, toggleComplete y submitEdits para agregar, eliminar, marcar como completado y editar los todos respectivamente.

Renderizado de la Interfaz de Usuario:
Renderiza la interfaz de usuario de la lista de tareas utilizando JSX. Muestra los todos, permitiendo la edición y eliminación de cada uno.

Exportación del Componente:
Exporta el componente App para que pueda ser utilizado en otros archivos de la aplicación.

## Instalación

1. Clona este repositorio en tu máquina local:

## bash
git clone https://github.com/OScorpion20/TodoList.git

## Instala las dependencias del proyecto:

cd TodoList
npm install

## Uso
Para ejecutar la aplicación localmente, utiliza el siguiente comando:

npm start
Esto abrirá la aplicación en tu navegador web predeterminado.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, siéntete libre de hacer un fork y enviar un pull request. Asegúrate de seguir las pautas de contribución antes de enviar cambios.

## Licencia

Este proyecto está bajo la Licencia APACHE. Para más detalles, consulta el archivo [LICENSE](LICENSE).

## Contacto
Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto conmigo a través de mi correo electrónico 20460044@colima.tecnm.mx.

¡Gracias por tu interés en este proyecto!


Este README proporciona una descripción general del proyecto, instrucciones de instalación, cómo usarlo, cómo contribuir, información sobre la licencia y cómo ponerse en contacto con el desarrollador. Puedes personalizarlo según tus necesidades específicas. Recuerda que en Markdown, puedes utilizar sintaxis como `#` para encabezados, listas con `-`, código con triple comilla invertida (\`\`\`) y enlaces `[texto](URL)`, entre otros.

