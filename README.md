# Programas en c++ de Angulo Jean
## Informacion del autor
`Angulo Cedeño Jean Pierre`
## Correo electronico
`jean.angulo.cedeno@utelvt.edu.ec`
## Enlase de la Actividad B1
`https://youtu.be/agNW0XiCYtM`

##  Programas
###  Suma de varios numeros
#### Descripcion del problema
```
Una suma o adicion es una operación matemática que reune dos o más números llamados sumandos en un solo número llamado suma o total. Los sumandos son los valores que se desean combinar y la suma es el resultado de la operación.
```
#### Funcionalidad
```
 float aj_n,aj_cv,aj_c= 0 , aj_t = 0 ;
```
#### Salida
```
El resultado de la suma es aj_t;
```

### Compara dos numeros
#### Descripcion del problema
```
Consiste en ingresar dos valores y determinar cual es mayor y cual menor o si son iguales.
```
#### Funcionalidad
```
float aj_a,aj_c;
```
#### Salida
```
si aj_a==aj_c // son iguales
si aj_a<aj_c  // es menor
```
###  Punto venta
#### Descripcion del problema
```
Programa que ingresa el numero de productos, el iva, el descuento y que calcule el valor total a pagar.
```
#### Funcionalidad
```
float aj_p,aj_cp,aj_i,aj_vp,aj_c=0,aj_tp=0,aj_d,aj_vbr1,aj_vbr2,aj_vd,aj_vi;
```
#### Salida
```
aj_tp,aj_i,aj_d,aj_vp;
```
### La edad de una persona
#### Descripcion del problema
```
Programa que calcula la edad de una persona en el que ingresa el dia, mes, año actual y dia, mes y año de nacimiento.
```
#### Funcionalidad
```
int aj_aac,aj_mac,aj_dac,aj_ana,aj_mna,aj_dna,aj_anio,aj_mes,aj_dia;
```
#### Salida
```
si aj_dac<aj_dna       // aj_dac=aj_dac+30; aj_mac=aj_mac-1; aj_dia=aj_dac-aj_dna;
si no aj_dia=aj_dac-aj_dna;
si aj_mac<aj_mna       // aj_mac=aj_mac+12; aj_aac=aj_aac-1; aj_mes=aj_mac-aj_mna;
aj_mes=aj_mac-aj_mna
aj_aac-aj_ana
aj_dia
aj_mes
```
###  Cuenta Moneda
#### Descripcion del problema
```
Programa que calcule el numero de monedas de 0.10y0.25ctvs ingresando la cantidad, dando como resultado el numero y la suma de las monedas.
```
#### Funcionalidad
```
int aj_nm,aj_c=0,aj_c1=0, aj_c2=0;
float aj_x, aj_t=0,aj_t1=0, aj_t2=0, aj_mon=0.10;
```
#### Salida
```
si aj_x==aj_mon  // aj_c1=aj_c1+1;  aj_t1=aj_t1+aj_x;
si aj_x==0.25    // aj_c2=aj_c2+1;  aj_t2=aj_t2+aj_x;
aj_c1,aj_t1,aj_c2,aj_t2;
```
## Instalador
## Descargar el repositorio
```
git clone https://github.com/JeanPierreAC/ACTIVIDAD-E2.git
```
## Compilar y ejecutar
```
cd ACTIVIDAD-E2
```
```
AnguloJean-sumaN.cpp
```
```
g++ AnguloJean-sumaN.cpp -o sumaN-ejecutable
```
