# Usuarios
En Linux, un usuario es una persona o entidad que utiliza el sistema operativo. Cada usuario tiene su propio nombre de usuario y contraseña para acceder al sistema. Los usuarios pueden tener diferentes permisos y niveles de acceso a los archivos y programas del sistema.

Linux es como una casa y cada usuario es una persona que vive en esa casa. Cada persona tiene su propia habitación y puede acceder a sus propias cosas, pero no puede acceder a las cosas de otras personas sin permiso.

# Grupos
Un grupo es una colección de usuarios que comparten ciertos permisos y características. <br> <br>Los grupos se utilizan para facilitar la administración de usuarios y asignar permisos de manera más eficiente.

Los grupos son como clubes en la casa de Linux. Cada club tiene sus propias reglas y solo los miembros del club pueden acceder a ciertas áreas o realizar ciertas actividades.

## Crear usuarios y grupos
Para crear un usuario en Linux, se utiliza el comando **useradd**.<br><br> Por ejemplo, si quisieras crear un usuario llamado "juan", puedes ejecutar el siguiente comando en la terminal:

`useradd juan`

Para crear un grupo, se utiliza el comando **groupadd**.

Por ejemplo, si quisieras crear un grupo llamado "amigos", puedes ejecutar el siguiente comando:

`groupadd amigos`

# Asignar usuarios a grupos
Una vez que tienes usuarios y grupos creados, puedes asignar usuarios a grupos utilizando el comando **usermod**. Por ejemplo, si quisieras agregar al usuario "juan" al grupo "amigos", puedes ejecutar el siguiente comando:

`usermod -aG amigos juan`

Esto permitirá que el usuario "juan" tenga acceso a los permisos y características asignados al grupo "amigos".