# LM7805

## Qué es

El LM7805 es un regulador de voltaje lineal de tres terminales que proporciona una salida constante de 5V. Forma parte de la familia de reguladores de voltaje LM78xx, que están diseñados para convertir un voltaje de entrada superior a un valor específico y constante en la salida.

## Características

Salida: 5V (±2% de tolerancia).

Entrada: 7V a 35V (típicamente 9V a 12V).

Corriente de salida: Hasta 1A (dependiendo del modelo y la disipación térmica).

Regulación: Regulador de voltaje lineal, lo que significa que la energía no se convierte en energía de conmutación, pero tiene menos eficiencia en comparación con reguladores conmutados.

## Funcionamiento

El LM7805 regula el voltaje de entrada utilizando un transistor interno y un sistema de control de retroalimentación. El dispositivo mantiene la salida en 5V, ajustando automáticamente la corriente que pasa a través del transistor, de modo que la diferencia de voltaje entre la entrada y la salida se "descarta" como calor (por lo tanto, la eficiencia no es alta en comparación con los reguladores conmutados).

Entrada: Se conecta una fuente de voltaje que debe ser mayor que 5V, generalmente de 7V a 35V, pero el rango más común es entre 9V y 12V.
Salida: El regulador proporciona 5V constantes en su terminal de salida, adecuado para alimentar circuitos que operan con este voltaje.

## Uso dado

En mi caso es utilizado para regular una entrada de 9V de una batería, a los 5V necesitados para alimentar la pantalla LCD y el ESP32.
