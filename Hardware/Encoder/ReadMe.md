# Encoder

## Qué es

El encoder rotativo es un dispositivo de entrada ampliamente utilizado para controlar sistemas electrónicos. Funciona generando dos señales cuadradas (canales A y B) que permiten determinar el sentido de giro y el número de pasos. Adicionalmente, incluye un pulsador para implementar funcionalidades adicionales.

## Características

Tipo: Encoder incremental y absoluto.

Tamaño del Eje: 11 mm.

Número de Pulsos: 20pulsos

Vida Útil:
15,000 ciclos para la mayoría de los modelos.

Torque: Entre 1.5 y 12 mN·m, dependiendo del modelo.

Switch de Presión: Con función de switch de presión (viaje de 1.5 mm).

Voltaje de Operación: 5V DC.

Corriente de Operación: 10 mA.

Conectividad: Terminales de salida A y B, con señal proporcional a la diferencia de fase.

Especificaciones Adicionales

Temperatura de Operación: -40 °C a +85 °C.

Rango de Humedad: 90-95% RH a 60 °C.

Resistencia a la Insulación: Mínimo 100 MΩ a 250V DC.

Protección: A prueba de voltaje de 300V AC durante 1 minuto.

## Funcionamiento

Generación de Señales:

El encoder produce dos señales cuadradas (canales A y B) desfasadas 90 grados entre sí [(Código Gray de 2 bits)](https://angelmicelti.github.io/4ESO/EDI/cdigo_gray.html). Este desfase permite identificar la dirección de rotación:
Sentido horario (CW): A lidera a B.
Sentido antihorario (CCW): B lidera a A.
La señal se genera al girar el eje, y cada ciclo completo (un paso A y B) representa un pulso.

Conexiones Eléctricas:

Pin común: Conectado a GND.
Canales A y B: Conectados a resistencias pull-up hacia VCC, asegurando señales estables.
Pulsador: Proporciona una señal digital (pulso bajo al presionarlo).
