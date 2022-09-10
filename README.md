# Usuarios-y-grupos

---------------------------------
1- Crear un grupo llamado casa
---------------------------------
groupadd Casa

------------------------------------------------------------------------------------------------------------------
2- Dentro del grupo casa crear 2 usuarios, uno con el nombre de su papá o mamá y el otro usuario seria su nombre.
------------------------------------------------------------------------------------------------------------------
Creamos 2 usuarios
--------------------------
useradd Franklin

useradd Nahun

-----------------------------
Agregamos usuarios a un grupo
-----------------------------
adduser Franklin Casa

adduser Nahun Casa

-------------------------------------------------
3- Cambiamos el nombre del grupo Casa a Familia.
-------------------------------------------------
groupmod -n Familia Casa
