# Encoder

## Qué es

El encoder rotativo es un dispositivo de entrada ampliamente utilizado para controlar sistemas electrónicos. Funciona generando dos señales cuadradas (canales A y B) que permiten determinar el sentido de giro y el número de pasos. Adicionalmente, incluye un pulsador para implementar funcionalidades adicionales.

## Funcionamiento

Generación de Señales:

El encoder produce dos señales cuadradas (canales A y B) desfasadas 90 grados entre sí (Código Gray de 2 bits). Este desfase permite identificar la dirección de rotación:
Sentido horario (CW): A lidera a B.
Sentido antihorario (CCW): B lidera a A.
La señal se genera al girar el eje, y cada ciclo completo (un paso A y B) representa un pulso.

Conexiones Eléctricas:

Pin común: Conectado a GND.
Canales A y B: Conectados a resistencias pull-up hacia VCC, asegurando señales estables.
Pulsador: Proporciona una señal digital (pulso bajo al presionarlo).
