# Componente App que contiene los siguientes 3 componentes:

Un componente con un Form para crear nuevos usuarios
Un componente que muestra un listado de usuarios, cada usuario con un boton de Detalles de ese usuario y un boton para Eliminar ese usuario
Un componente que muestra los detalles de ese usuario cuando se presiona el boton de Detalles


## Scripts para ejecutar la App

En el directorio del proyecto se debe ejecutar los siguientes comandos:

### `npm install`

Para instalar o actualizar dependencias del proyecto 

### `npm start`

Corre la aplicacion en el modo de Desarrollo y se abre en http://localhost:3000 para verlo en el navegador de su preferencia

# Como funciona Redux y como interactua con una aplicacion React

Redux es una libreria de JavaScript que se puede utilizar con cualquier libreria-framework tales como React, Vue, etc. Su principal trabajo es el de manejar los estados de una aplicacion y su arquitectura es Flux que se encarga del manejo y flujo de datos en una aplicacion web (seria como un MVC). Redux contiene 3 componentes como son el Store (almacena el estado global de la aplicacion, da permiso al estado y permite la actualizacion de estados entre otras cosas), las Acciones (son objetos JavaScript que contienen al menos una propiedad que indica el tipo de accion) y los Reducers (se encargan de reaccionar a las acciones que se producen en nuestra aplicacion). Funciona mejor con un libreria-framework como React porque React utiliza la interfaz del usuario en funcion de estados y Redux es justamente lo que se utilizaria para manejar esos estados en respuesta a acciones.
