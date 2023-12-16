# CH340G

Este es un simple CI para construir un USB 2.0 a Serial de muy bajo coste, diseñado y fabricado en china por [Jiangsu Heng Qin Ltd. (WCH)](http://www.wch-ic.com). Para usar el CI conectado a un ordenador/computadora, necesitas tener instalado el driver. De momento nos vamos a centrar en el CH340G que tiene unas prestaciones muy versátiles, entre ellas destacan las siguientes:

- USB 2.0 a Serial, compatible con RS232, RS485, RS422.
- Usa el protocolo UART para comunicarse con el MCU.
- Soporta 5v y 3.3v.

![](https://github.com/nstrappazzonc/CH340/blob/main/img/minimal_protoboard.jpg?raw=true)

En la imagen mostramos el circuito básico y la conexión con un ATMega328P, en el [siguiente enlace](https://github.com/nstrappazzonc/atmega32x/tree/main/atmega328p/examples/cdc) tenemos varios ejemplos de cómo integrar ambos circuitos integrados.

## Esquema minimo del circuito

![](https://github.com/nstrappazzonc/CH340/blob/main/img/minimal_schematic.jpg?raw=true)

## Driver

- [Linux](https://www.wch-ic.com/downloads/CH341SER_LINUX_ZIP.html)
- [MacOS](https://www.wch-ic.com/downloads/CH341SER_MAC_ZIP.html)
- [Windows](https://www.wch-ic.com/downloads/CH341SER_ZIP.html)
