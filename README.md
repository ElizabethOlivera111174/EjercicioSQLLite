# EjercicioSQLLite
Resolucion de ejercicio de sql Lite

CREATE TABLE curso (
codigo INT NOT NULL,
nombre VARCHAR NOT NULL,
descripcion VARCHAR,
Turno VARCHAR NOT NULL,
PRIMARY KEY(codigo)
);
ALTER TABLE curso ADD cupo Int;
INSERT INTO curso (codigo,nombre,descripcion,turno,cupo)VALUES(101, "Algoritmos","Algoritmos y Estructuras de Datos","Mañana",35);
INSERT INTO curso (codigo,nombre,descripcion,turno,cupo)VALUES(102, "Matemática Discreta","","Tarde",30);
INSERT INTO curso (codigo,nombre,descripcion,turno,cupo)VALUES(103,NULL,"","Tarde",30);
INSERT INTO curso (codigo,nombre,descripcion,turno,cupo)VALUES(102, "Matemática Discreta","","Tarde",30);
UPDATE curso SET cupo = 25
DELETE FROM curso WHERE nombre="Algoritmos";
DELETE FROM curso WHERE codigo=103;
SELECT * fROM curso;
