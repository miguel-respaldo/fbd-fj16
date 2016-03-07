# Primer parcial


## Conceptos de BD

* Campo (Field)
* Registro (Record)
* Archivo/Tabla (File/Tablas)

El conjunto de varios Archivos/Tablas hace una BD.

## Modelo de entidad relación

* Entidad (Cuadrado)
* Relación (Rombo)
* Atributos (Óvalos)
   - Clave primaria óvalo relleno
   - Clave foranea óvalo mitad relleno

### Carninalidad

* 1:1
* 1:N
* N:1
* M:M

#### Ejemplo

  Una escuela desea tener una base de datos, que almacene los datos
  principales de un alumno,la carrera que estudia las materias que cursa
  y los profesores que imparten clase.

  De igual manera se desea llevar un registro de las materias que imparte
  cada profesor.


## Modelo Relacional en SQL

* Entidades --> Tablas
* Atributos --> Campos
* Registro   -->  Tuplas
* Cardinalidad  --> Relaciones


## Normalización

Proceso de simplificación de los datos

* Tener almacenados con el menor espacio posible.
* Elimintar datos repetidos.
* Elimintar errores lógicos.
* Datos ordenados.

### Niveles

- Primer Forma Normal
  * Identificar los grupos de repetición
- Segunda Forma Normal
  * Dependencia Funcional
    + A-B  A-C
  * Dependencia Transitiva
    + A-B  B-C  C-A
- Tercer Forma Normal
  * Reducir espacio con claves primarias
- Forma Normal Boyce codd
- Cuarta Forma Normal
- Quinta Forma Normal


La **simplificación** se tiene que dar sin perdida de información



