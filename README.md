# TinySQLD
Datos I IIS2024

Para probar: 
1) corren la solucion en VS2022 o donde sea. El Proyecto ejecutable es APIInterface. 
2) abren en powershell el archivo en la carpeta Client
3) . .\tinysqlclient.ps1 -IP "127.0.0.1" -Port 11000
4) Ingresar progresivamente los comandos
   -CREATE DATABASE <NOMBRE>
   -SET DATABASE <NOMBRE>
   -CREATE TABLE <NombreTabla> (NombreVariable TipoVariable)
   Con la tabla creada ya se puede trabajar sobre ella:
   -INSERT INTO <NombreTabla> VALUES (NombreVariable TipoVariable)
   -DROP TABLE <NombreTabla>
