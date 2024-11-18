# LM7805

## Qué es

El LM7805 es un regulador de voltaje lineal de tres terminales que proporciona una salida constante de 5V. Forma parte de la familia de reguladores de voltaje LM78xx, que están diseñados para convertir un voltaje de entrada superior a un valor específico y constante en la salida.

## Características

**Voltaje de Entrada (VI)**

Para VO = 5V a 18V: 35V

Para VO = 24V: 40V

**Corriente de Salida (IO)**

Hasta 1A

**Voltaje de Salida (VO)**

4.75V a 5.25V (con 5.0mA ≤ IO ≤ 1.0A, PO ≤ 15W)

Típicamente 5.0V a 25°C

**Regulación de Línea (Regline)**

VI = 8V a 12V: -1.6 mV a 50 mV

**Regulación de Carga (Regload)**

IO = 5mA a 1.5A: -9 mV a 100 mV

IO = 250mA a 750mA: -4 mV a 50 mV

**Caída de Voltaje (VDrop)**

IO = 1A, TJ = +25°C: -2V

**Rango de Temperatura**

Temperatura de Operación (TOPR): 0°C a +125°C


## Funcionamiento

El LM7805 regula el voltaje de entrada utilizando un transistor interno y un sistema de control de retroalimentación. El dispositivo mantiene la salida en 5V, ajustando automáticamente la corriente que pasa a través del transistor, de modo que la diferencia de voltaje entre la entrada y la salida se "descarta" como calor (por lo tanto, la eficiencia no es alta en comparación con los reguladores conmutados).

Entrada: Se conecta una fuente de voltaje que debe ser mayor que 5V, generalmente de 7V a 35V, pero el rango más común es entre 9V y 12V.
Salida: El regulador proporciona 5V constantes en su terminal de salida, adecuado para alimentar circuitos que operan con este voltaje.

## Uso dado

En mi caso es utilizado para regular una entrada de 9V de una batería, a los 5V necesitados para alimentar la pantalla LCD y el ESP32.
