<h1>Desarrollo backend con NodeJs - UTN - FRC</h1>

<h3>Objetivo:</h3>  
<h4>Desarrollar una API RESTful utilizando Express.js para la gestión de libros, almacenando los datos en una base de datos con MongoDB. La API permitirá realizar operaciones básicas como crear, leer, actualizar y eliminar libros, así como
obtener una lista de todos los libros disponibles.</h4>

<h4>Consigna</h4> 
<ol>
  <li>La API debe seguir los principios de arquitectura RESTful y utilizar los métodos HTTP
adecuados para cada operación.</li>
  <li>La API debe implementar las siguientes rutas y funcionalidades:
   <ul>
    <li>GET /libros: Devuelve la lista completa de libros.</li>
    <li>GET /libros/:id: Devuelve los detalles de un libro específico según su ID.</li>
    <li>POST /libros: Crea un nuevo libro con la información proporcionada.</li>
    <li>PUT /libros/:id: Actualiza la información de un libro específico según su ID.</li>
    <li>DELETE /libros/:id: Elimina un libro específico según su ID.</li>
   </ul>
  </li>
  <li>La API debe utilizar una estructura de archivos y carpetas organizada para separar las rutas y
los controladores de libros.</li>
  <li>La API debe manejar adecuadamente los errores y devolver respuestas JSON apropiadas en
caso de errores.</li>
  <li>Se debe implementar mediante el ORM Mongoose el acceso a una base de datos de libros</li>
</ol>
