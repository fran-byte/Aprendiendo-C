# <img src="images/C_Logo.png"/> Material didáctico  [ENGLISH - VERSION](README_en.md)


Este repositorio pretende ser una introdución a C.



## Palabras reservadas
| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
| auto     | break    | case     | char     | const    | continue | default  |
| do       | double   | else     | enum     | extern   | float    | for      |
| goto     | if       | int      | long     | register | return   | short    |
| signed   | sizeof   | static   | struct   | switch   | typedef  | union    |
| unsigned | void     | volatile | while    |          |          |          |

## Tipos de datos, modificadores de tipo y modificadores de acceso
- En C existen cinco tipos de datos:
(tipo de dato) (nombre de variable) (, nombre de variable);

|Tipo de dato| Descripción                              |
|------------|------------------------------------------|
|char        |Carácter o entero pequeño (byte)          |
|int         |Entero                                    |
|float       | Punto flotante                           |
|double      | Punto flotante (mayor rango quefloat)    |
|void        | Sin tipo (uso especial)                  |


- Existen, además, cuatro modificadores de tipo:
  
|Modificador| Tipos |de actuación |Descripción                |
|-----------|-------|-------------|---------------------------|
|signed     |  char |  int        |  Con signo (por defecto)  |
|unsigned   |  char |  int        |  Sin signo                |
|long       |  int  |  double     |  Largo                    |
|short      |  int  |             |  Corto                    |


- Es posible, además, aplicar dos modificadores seguidos a un mismo tipo de
datos, así, es posible definir una variable de tipo unsigned long int (entero largo sin
signo).


|                                    | Rango de valores posibles en (notación matemática)  |  Tipo de variable declarada 16 bits 32 bits  |
|------------------------------------|-----------------------------------------------------|----------------------------------------------|
|  char / signed char                |  (-128 , 127)                                       |  (-128 , 127)                                |
unsigned char [0 , 255] [0 , 255]
int / signed int [-32768 , 32767] [-2147483647 , 2147483648]
unsigned int [0 , 65535] [0 , 4294967295]
short int / signed short
int
[-32768 , 32767] [-32768 , 32767]
unsigned short int [0 , 65535] [0 , 65535]
long int / signed long
int
[-2147483647 , 2147483648] [-2147483647 , 2147483648]
unsigned long int [0 , 4294967295] [0 , 4294967295]
float [-3.4E+38 , -3.4E-38], 0 ,
[3.4E-38 , 3.4E+38]
[-3.4E+38 , -3.4E-38], 0 ,
[3.4E-38 , 3.4E+38]
double [-1.7E+308 , -1.7E-308], 0 ,
[1.7E-308 , 1.7E+308]
[-1.7E+308 , -1.7E-308], 0 ,
[1.7E-308 , 1.7E+308]
long double [-3.4E+4932 , -1.1E-4932], 0 ,
[3.4E-4932 , 1.1E+4932]
[-3.4E-4932 , -1.1E+4932], 0 ,
[3.4E-4932 , 1.1E+4932]
T
