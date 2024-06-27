Primero hacer un: npm i
Y luego npm start

para ver todos los usuarios:
(GET) http://localhost:5000/users

Para eliminar usuario: 
(DELETE) http://localhost:5000/users/21cc34cc-0657-4fdf-96c5-cbca6a025c27

Para editar usuario: 
(PATCH) http://localhost:5000/users/21cc34cc-0657-4fdf-96c5-cbca6a025c27

con un raw: 
{

        "nacimiento": "2002-08-27"
      
    }

Para registrar un usuario:
(POST) http://localhost:5000/users

con el raw
{
    "first_name": "Deelvin",
    "last_name": "Johnson",
    "email": "delvin.larez@ieee.org",
    "trabajo": false,
    "nacimiento": "20/08/2002"
}