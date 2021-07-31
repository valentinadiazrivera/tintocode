# TintoCode

Aquí vamos a trabajar todos juntos, en este lugar vamos a tener nuestras biografías



                      Pasos:

- Hazme Fork

- Hacer clone de tu repositorio al cual hiciste fork
$ git clone URL-REPO

- Crear la rama con el nombre de lo que vas a hacer, en este caso usaremos el formato: add-bio-nombreapellido
En este caso add-bio-julianleon ya que vamos a agregar la biografía
$ git checkout -b add-bio-julianleon

- Crea un archivo con tu nombre, en él pones tu biografía
$ touch nombre-apellido.txt

- Hazle commit a los cambios

- Envía los nuevos cambios de la rama creada hacia la rama remota con el mismo nombre al repositorio forkeado de tu cuenta
$ git push origin add-bio-julianleon:add-bio-julianleon

- Haces un pull-request

- Si queremos mantener actualizados con el repositorio original, establecemos una conexión con
$ git remote add update URL-REPO  // En este caso le queremos poner update a la conexión porque de este remoto solo vamos a actualizar (hacer fetch)