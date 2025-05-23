---
title: Instalación
---

<Intro>

React se ha diseñado desde un inicio para una adopción gradual. Puedes usar tan poco o mucho de React como necesites. Ya sea que quieras probar de qué va React, agregar interactividad a una página HTML o crear una aplicación compleja con React, los enlaces de esta sección te ayudarán a comenzar.

</Intro>

<YouWillLearn isChapter={true}>

* [Cómo iniciar un nuevo proyecto de React](/learn/start-a-new-react-project)
* [Cómo agregar React a un proyecto existente](/learn/add-react-to-an-existing-project)
* [Cómo configurar el editor](/learn/editor-setup)
* [Cómo instalar las Herramientas de Desarrollo de React](/learn/react-developer-tools)

</YouWillLearn>

## Prueba React {/*try-react*/}

No necesitas instalar nada para jugar con React. ¡Prueba editar este ejemplo de código!

<Sandpack>

```js
function Greeting({ name }) {
  return <h1>Hola, {name}</h1>;
}

export default function App() {
  return <Greeting name="mundo" />
}
```

</Sandpack>

Puedes editarlo directamente o abrirlo en una nueva pestaña presionando el botón "Bifurcar" en la esquina superior derecha.

La mayoría de las páginas de la documentación de React contienen ejemplos interactivos como este. Fuera de la documentación de React, también existen muchos *sandboxes* en línea que permiten usar React: por ejemplo, [CodeSandbox](https://codesandbox.io/s/new), [Stackblitz](https://stackblitz.com/fork/react), o [CodePen](https://codepen.io/pen?template=QWYVwWN).

### Probar React localmente {/*try-react-locally*/}

Para probar React de forma local en tu computadora, [descarga esta página HTML](https://gist.githubusercontent.com/gaearon/0275b1e1518599bbeafcde4722e79ed1/raw/db72dcbf3384ee1708c4a07d3be79860db04bff0/example.html). ¡Ábrela en tu editor y en tu navegador!

## Iniciar un nuevo proyecto React {/*start-a-react-project*/}

Si quieres crear una aplicación o un sitio web completamente con React, [inicia un nuevo proyecto React](/learn/start-a-new-react-project).

## Construir una aplicación React desde cero {/*build-a-react-app-from-scratch*/}

Si un framework no se ajusta bien a tu proyecto, prefieres construir tu propio framework, o simplemente quieres aprender los conceptos básicos de una aplicación React, puedes [construir una aplicación React desde cero](/learn/build-a-react-app-from-scratch).

## Añadir React a un proyecto existente {/*add-react-to-an-existing-project*/}

Si quieres probar usando React en tu aplicación existente o en un sitio web, [añade React a un proyecto existente](/learn/add-react-to-an-existing-project).

<Note>

#### ¿Debería usar Create React App? {/*should-i-use-create-react-app*/}

No. Create React App ha sido descontinuado. Para más información, consulta [Descontinuación de Create React App](/blog/2025/02/14/sunsetting-create-react-app).

</Note>

## Próximos pasos {/*next-steps*/}

Dirígete a la guía de [Inicio rápido](/learn) para un recorrido de los conceptos más importantes de React que encontrarás en el día a día.
