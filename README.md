# TinySQLD
Datos I IIS2024

Para probar: 
1) corren la solucion en VS2022 o donde sea. El Proyecto ejecutable es APIInterface. 
2) abren en powershell el archivo en la carpeta Client
3) . .\tinysqlclient.ps1 -IP "127.0.0.1" -Port 11000
4) Comandos de ejemplo:
CREATE DATABASE Minecraft
SET DATABASE Minecraft
CREATE TABLE Mobs (NUMERO INTEGER, NOMBRE VARCHAR(10), ESPECIE VARCHAR(10), NACIMIENTO DATETIME)
INSERT INTO Mobs VALUES (1, "Lila", "Vaca", '2023-12-02 10:22:23')
INSERT INTO Mobs VALUES (2, "Gustavo", "Pollo", '2022-12-02 10:22:23')
INSERT INTO Mobs VALUES (3, "Miguel", "Cerdo", '2021-12-02 10:12:12')
CREATE INDEX NumMob ON Mobs(NUMERO) OF TYPE BST
SELECT * FROM Mobs
UPDATE Mobs SET NOMBRE = "Pedro" WHERE NUMERO = 1
DELETE FROM Mobs
DROP TABLE Mobs
