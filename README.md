# Usuarios-y-grupos

---------------------------------
1- Crear un grupo llamado casa
---------------------------------
groupadd Casa

------------------------------------------------------------------------------------------------------------------
2- Dentro del grupo casa crear 2 usuarios, uno con el nombre de su papá o mamá y el otro usuario seria su nombre.
------------------------------------------------------------------------------------------------------------------
useradd Rosa
useradd Williams
--------------------
add user Rosa Casa
add user Williams Casa

-------------------------------------------------
3- Cambiamos el nombre del grupo Casa a Familia.
-------------------------------------------------
groupmod -n Familia Casa
