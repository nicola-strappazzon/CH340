# CH340

Este es un simple CI para construir un USB 2.0 a Serial de muy bajo coste, diseñado y fabricado en china por [Jiangsu Heng Qin Ltd. (WCH)](http://www.wch-ic.com). Para usar el CI conectado a un ordenador/computadora, necesitas tener instalado el driver. De momento nos vamos a centrar en el CH340C/B que tiene unas prestaciones muy versátiles, entre ellas destacan las siguientes:

- Las versiones CH340C/N/K/E/X/B tiene reloj integrado, no requiere cristal externo. CH340B también integra una EEPROM utilizada para configurar el número de serie, etc.
- USB 2.0 a Serial, compatible con RS232, RS485, RS422.
- Usa el protocolo UART para comunicarse con el MCU.
- Soporta 5v y 3.3v.

También podemos configurar el UART para Unified Program and Debug Interface (UPDI) que es habitual para programar MCU.

![](https://github.com/nicola-strappazzon/CH340/blob/main/img/minimal_protoboard.jpg?raw=true)

En la imagen mostramos el circuito básico y la conexión con un ATMega328P.

Puedes conseguir los IC en la tienda oficial de [AliExpress](https://wchofficialstore.es.aliexpress.com/store/1100367542) o en [LCSC](https://www.lcsc.com).

## Componentes

Use los siguientes componentes para construir el circuito mínimo:

- Un IC CH340C.
- Condensador de 0.1uF (Código: 104, Cantidad: 2).
- Condensador de 10nF.
- Condensador de 100nF.

## Esquema minimo del circuito

![](https://github.com/nicola-strappazzon/CH340/blob/main/img/minimal_schematic.jpg?raw=true)

## Driver

- [Linux](https://www.wch-ic.com/downloads/CH341SER_LINUX_ZIP.html)
- [MacOS](https://www.wch-ic.com/downloads/CH341SER_MAC_ZIP.html)
- [Windows](https://www.wch-ic.com/downloads/CH341SER_ZIP.html)

## Proyectos relacionados

- [CH334 - HUB USB 2.0](https://github.com/nicola-strappazzon/CH334)
- [CH552 - 8-bits MCU - 8051](https://github.com/nicola-strappazzon/CH552)
- [CH9141 - Bluetooth Serial Transparent](https://github.com/nicola-strappazzon/CH9141)
