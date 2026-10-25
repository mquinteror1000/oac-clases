### Octubre 24

Procesador:



Para el 404

2^20 = 1048576

5 en hexadecimal



### Modos de direccionamiento

- Inherente ( implicito ): No requiere un operando o está implícito en el código de operación

- Inmediato: El operando está incluido en la instrucción, después del código de operación.

- Directo: La instrucción contiene la dirección del operando. No el operador mismo.

- Indexado: La dirección del operando se obtiene sumando el desplazamiento al contenido del registro índice.

- Relativo: La dirección de destino se obtiene sumando la cantidad relativa al contenido del contador del programa ( PC )

#### Inherente

Primer ciclo: Empieza con la dirección 

Segundo ciclo:  Empieza a ejecutar la operación





#### Indexado

Primer ciclo: Empieza con la dirección

Segundo ciclo: Empieza a ejecutar la operación load indexada

contado se incrementa en 1

en la alu se suma registro indice mas registro de esplazamiento para obtener - 5+7 = 12

pasa 12 al registro de dirección

Tercer ciclo: Con la dirección de la ALU ( 12 )

En la dirección 12 se encuentra el operando

registro de datos

llega al acumulador

#### Relativo (salto)

##### Primer ciclo ( determinar que va a jacer )

Contador del programa obtiene dirección de la instrucción



-> Se va a realizar un salto relativo

##### Segundo ciclo

contenido del PC se transfiere al ALU y al registro de direcciones



ALU suma [ Direccion relativa ][2] + [Direcciuón del contador del programa][5] -> 7

Entonces regustro de direcciones apunta al salto [7]

##### Tercer ciclo










































