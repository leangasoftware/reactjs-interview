
# Entrevista ReactJS

![](https://interacso.com/blog/wp-content/uploads/2019/05/React-post-interacso.png)

Bienvenido a tu prueba de __ReactJS__, a continuación encontrarás una serie de requerimientos con los cuales deberás realizar un ejercicio práctico.

La prueba general se divide en pequeños ejercicios con los cuales se evaluará en práctica:
- Pensamiento lógico.
- Resolución de problema.
- Tiempo de desarrollo.
- Entre otros.


Finalizada la prueba recuerda enviar link del proyecto o tu repositorio a [desarrollo@leangasoftware.es](mailto:desarrollo@leangasoftware.es) con tu información de contacto y en el asunto colocar: 
__REACT-JS-INTERVIEW__


> Recomendación: No importa terminar todos los ejercicios, lo más importante es la funcionalidad del ejercicio resuelto(s).

### Contexto:
Utilizando la api de [Youtube](https://developers.google.com/youtube/v3/docs/videos/list?hl=es)  construir una WebApp que permita obtener un listado de los videos mediante una búsqueda. Haciendo uso de "Drag & Drop" agregar los videos a una lista y ordenarlos, luego de ordenados poder reproducir los videos en el orden especificado o poder dar click para reproducir una canción en concreto.

### Antes de empezar:
- La data a consumir proviene de [Youtube](https://developers.google.com/youtube/v3/docs/videos/list?hl=es)

# Ejercicios

### 1. Home.
![](https://i.imgur.com/8Ezeakj.png)

__REQUERIMIENTO:__
Se requiere una vista "HOME" donde muestre en cuadrícula las canciones resultado de la búsqueda.

- Vista principal  __SEARCH_TRACKS_LIST__ 
	- RUTA: `/home` 
- Vista detalle __TRACK_DETAIL__
	- RUTA: `/play/{track}`
- Vista __404__
	- RUTA: `/404`
	- HTML: A tu gusto.
	- __NOTA:__ Debes poder re-direccionar rutas que no existan a `404`

___
### 2. Componentes.
![](https://i.imgur.com/9ICQnNu.png)

__REQUERIMIENTO:__
Se requiere hacer en componente la lista `Drag & Drop` y el reproductor para su uso práctico.
Ejemplo `  <favorite-list data="data"></favorite-list>`
___

### 3. LocalStorage
![](https://i.imgur.com/gwkZnxI.png)

__REQUERIMIENTO:__
No estamos usando una base de datos, vamos a usar el localStorage del navegador para almacenar los datos volátiles.

### 4. Compartir lista de reproducción

![](https://i.imgur.com/mga4cHi.png)

__REQUERIMIENTO:__
Como no tenemos una base de datos vamos utilizar el ingenio para compartir la data por la url, para ello recomiendo usar algún `package` que nos facilite el empaquetado de la data, puede ser ([object-hash](https://www.npmjs.com/package/object-hash)) o otro de su preferencia, o si lo desean pueden crear su propio `script`. La idea es que pueda compartir un url similar a la siguiente
`https://miproyecto.demo/playlist/{hash}` 

### Extra.
Si has llegado hasta este punto, y consideras que tienes tiempo se valora el hecho de que puedas desplegar tu proyecto en [Heroku](https://www.heroku.com/) o en cualquier servidor de tu gusto.

Gracias por participar!
