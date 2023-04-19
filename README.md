# PreworkMacOS
Este repositorio sirve de consejo para las personas que quieren hacer un Prework y tener algunas herramientas instaladas en su equipo MacOS.

### ¿Qué es el navegador?
Es la ventana que tenemos hacia el mundo para la web. Un navegador es un software que nos permite el acceso a la web, interpreta la información para que estos puedan ser vistos. Los navegadores existen gracias a la interacción de Javascript. 
- HTML: nos permite estructurar el contenido de los sitios webs, permite visualizar y diseñar todo el contenido sin estilo.
- CSS: es todo el css que nos permite crear estilos al HTML, para que se pueda visualizar con estilos y mejor presentable. 
- Javascript: es todo lo funcional dentro de un sitio web.

### Escoge e instala el navegador y conoce sus DevTools.
**************************Chrome DevTools************************** es un conjunto de herramientas que nos permiten hacer depuración en el desarrollo de aplicaciones web. Este se encuentra en Chrome y en navegadores basados en Chromium. 

Existen diferentes versiones de Google Chrome:
- Canary: la que trae las versiones más recientes construidas por los devs. 
- Dev: es la versión que desarrollan los devs.
- Stable: es la versión estable que se da al publico general. 

Se pueden abrir las DevTools para poder visualizar la pantalla de modo desarrollador. 
Los siguientes comandos nos sirven para:
- cmd + opt + i: abre los DevTools.
- cmd + opt + j: abre la consola.
- cmd + shift + c: abre el inspector de elementos.

### Instalando nuestro editor de texto. 
Los editores de texto nos permite crear archivos para el código y tiene muchas funcionalidades extras, como auto complementar el código, mostrar mensajes de error, etc.
- WebStorm: es un editor de código de pago que nos permite desplazar por el código de forma más eficiente.
- Atom: es un lienzo libre que nos permite usar a nuestro gusto.
- Visual Studio Code: es para mi gusto el mejor editor de texto, que nos permite instalar extensiones para mejorar el código. 

### Extensiones y personalización de VSCode
- Prettier: es un formateador de código con reglas específicas y se le de un formato de una manera más legible. 
- Color highlight: cuando escribamos colores de css esto nos coloca los colores en un cuadrito para ver si es el mismo que estamos escribiendo. 
- Live server: los cambios se hacen de manera automáticamente cada vez que guardamos el archivo que estamos editando.
- Path intellisense: nos ayuda a navegar a una ruta de un archivo, es aun auto completado de la ruta. 
- Auto Rename Tag: nos ayuda a auto complementar todas las etiquetas de html.
- Material Icon: nos ayuda a colocar iconos más visuales para nuestro proyecto. 

### Uso de Live Server en proyectos reales de HTML y CSS 
Todos los proyectos que se corran con la extensión de Live Server nos permite crear un servidor interno en el localhost del equipo que nos ayuda a evitar el realoader dentro de los sitios webs.

### Instalación de Homebrew y Node.js
- Homebrew: maneja software o paquetes para la mac.
- NPM: maneja softwares o paquetes para los proyectos que estemos desarrollando.

Para poder instalar homebrew hacemos el siguiente comando: 

` /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" `

Para poder instalar Node.JS
 
` brew install node `

Para poder actualizar nuestros paquetes instalados en la mac, se hace con: 

`brew install node`

### Comandos básicos de la terminal
- cd (Change Directory): moverte entre las carpetas de tu mac.
- ls (List): Lista todas las carpetas y archivos que hay dentro de tu carpeta actual
- code . puedes usarlo para abrir un archivo en Visual Studio Code
- open: abre un archivo con el programa determinado.
- sudo: permite ejecutar cualquier comando como super administrador
- clear: Manda para arriba todos los comandos anteriores para que de la impresión de que se limpió la pantalla
- reset: resetea la terminal
- ctrl + c: mata cualquier proceso que se este ejecutando en ese momento de la terminal. 

### Primer proyecto con React.js
Para poder crear una aplicación con React.Js se tiene que hacer con el siguiente comando: 
` npx create-react-app name-app `
- Es importante que para crear este proyecto se tiene que declarar con guiones y no con la nomenclatura de camelCase.

### ¿Qué es Git y Github? 
Git es una herramienta que te permite manejar todo el versionado de tu código, ya no existe de eso “versión final”, “versión final final”, “versión final final esta sí”. Ahora con git puedes llevar un control de versiones donde puedes organizar todos los features nuevos que vayas agregando a tu aplicación. 

Con git puedes crear ramas (un universo paralelo de tu proyecto), puedes juntar esas ramas, puedes ver quién tuco la culpa de qué en cada línea de código, puedes volver atrás en el tiempo, etc. 

Con Github puedes alojar todo ese código y sus cambios en un servidor en la nube, así como ver el código de otras personas que tienen sus repositorios públicos. Github es como tu portafolio de proyectos como programador.
