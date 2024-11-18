# Level Shifter

## Qué es

Un Level Shifter es un dispositivo electrónico utilizado para adaptar los niveles de voltaje entre dos sistemas que operan a diferentes voltajes. Su función principal es permitir la comunicación entre dispositivos que trabajan con distintas tensiones lógicas, como, en mi caso, un microcontrolador de 3.3V y una pantalla LCD de 5v.

## Características

**Voltajes de Suministro:**

Bajo Voltaje (LV): 1.5 V a 7 V

Alto Voltaje (HV): LV a 18 V

Canales: 4 canales bidireccionales

Dimensiones: Tamaño: 0.4″ × 0.5″ × 0.08″ (13 mm × 10 mm × 2 mm)

**Conexiones:**

Compatible con breadboards

Resistencias Pull-Up:

Se utilizan resistencias de 10 kΩ para cada canal, que ayudan a lograr tiempos de subida adecuados para señales rápidas (hasta 400 kHz para I²C). En mi caso utilizo la resistencia PULL-UP del ESP32.

Interfaz:

Compatible con interfaces digitales rápidas (I²C, SPI, TTL asíncrono).

## Funcionamiento

El principio básico de operación de un Level Shifter se basa en el uso de componentes electrónicos como transistores y resistencias para adaptar los niveles de voltaje de las señales digitales. Un ejemplo común es el uso de transistores MOSFET para cambiar el voltaje de las señales de un lado a otro, mientras que las resistencias controlan el flujo de corriente y la velocidad de conmutación.
