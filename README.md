# Usuarios-y-grupos
"Mi primer repositorio en GitHub"
------------------------------------------------
Crear un grupo llamado casa
------------------------------------------------
groupadd Casa

--------------------------------------------------------------------------------------------------------------
Dentro del grupo casa crear 2 usuarios, uno con el nombre de su papá o mamá y el otro usuario seria su nombre.
--------------------------------------------------------------------------------------------------------------
--------->Creando 2 usuarios
useradd Rosa
useradd Williams

-------->Agregamos los usuarios a el grupo Casa
add user Rosa Casa
add user Williams Casa

-------------------------------------------------
Cambiamos el nombre del grupo Casa a Familia.
------------------------------------------------
groupmod -n Familia Casa
