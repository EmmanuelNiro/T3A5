Fase 1: Descripcion

Desarrolla una aplicación de cajero automático en Java en la cual se muestre un menú para 
seleccionar la operación requerida por el usuario:

- El usuario debe ingresar su tarjeta (número y NIP) para ingresar al menú principal,
en caso de que no coincida con sus datos entonces deberá mostrar una alerta donde le 
indique que sus datos son erróneos.

- El menú principal debe tener las siguientes opciones:
~~~
  1. Consultar saldo
  2. Consultar estado de cuenta
  3. Retirar efectivo
  4. Otras opciones
    a. Seguros
    b. Créditos
  5. Salir
~~~
Fase 2: Diseño de la solucion


1. Entrada
  ~~~
  -String numeroDeTarjeta
  -int pin
  -float saldo
  -Adicionales: nombre, telefono, email
  ~~~
2. Procesos
  ~~~
  -Validar los datos ingresados: numero de tarjeta y pin
  -Mostrar el menu de opciones del cajero
  -Mostrar el nombre ususario
  ~~~
3. salida

Diseño de la interfaz

~~~
+-----------------------------------------------------------+
|         Bienvenido/Buen dia, (ingrese nombre aqui)        |
+-----------------------------------------------------------+
| Menu (¿Que desea realizar hoy?)                           |
|  1. Consultar saldo                                       |
|  2. Consultar estado de cuenta                            |
|  3. Retirar efectivo                                      |
|  4. Otras opciones                                        |
|   a. Seguros                                              |
|   b. Créditos                                             |
|                                                           |
|   5. Salir                                                |
+-----------------------------------------------------------+
~~~


Etapa 3: Diseño de la solucion


![](https://github.com/EmmanuelNiro/T3A5/blob/main/Cajero.png)
