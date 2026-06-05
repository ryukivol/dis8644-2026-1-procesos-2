# sesion-11b

# Trabajo en proyecto 

El dia de hoy estamos hablando de el capitulo 5 de el libro de fotografia. 

recitaron un poema de un poeta que esta funado, pero era vanguardista en su epoca, causo el despido de un profesor en su momento. Creo que es interesante como se conecta el arte con la poesia o la expresion humana, reflejada en diversos hambitos academicos. 

Apuntes de conexion realizadoa en la clase: 

CD4046 (PLL)
Pin 1
⚪ Blanco → Pin 2
Pin 2
⚪ Blanco → Pin 1
⚪ Blanco → Pin 3
Pin 3
⚪ Blanco → Pin 2
🔵 Azul → GND
Pin 4
⚪ Blanco → Pin 3 del TL072
🟡 Amarillo → Resistencia 100k
Pin 5
🔵 Azul → GND
Pin 6
⚪ Blanco → Pin 7
🟠 Naranja → Capacitor 1uF
Pin 7
⚪ Blanco → Pin 6
🟠 Naranja → Capacitor 1uF
Pin 8
🔵 Azul → GND
🟠 Naranja → Capacitor 104 (100nF) adicional hacia pin 14
Pin 9
🟣 Morado → Potenciómetro B1M pata 2
Pin 10
Sin conexión
Pin 11
🟣 Morado → Potenciómetro B500k pata 2
🟡 Amarillo → Resistencia 100k
🔵 Azul → GND
Pin 12
🟡 Amarillo → Resistencia 100k
🔵 Azul → GND
Pin 13
⚪ Blanco → Pin 14
🔵 Azul → GND
Pin 14
⚪ Blanco → Pin 13
🔵 Azul → GND
🟠 Naranja → Capacitor 104 (100nF) desde pin 8
Pin 15
🔵 Azul → GND
Pin 16
🔴 Rojo → VCC (+5V)
🟠 Naranja → Capacitor 104 (100nF)
Capacitor 104 (100nF) de desacople
🟠 Naranja → Una pata al pin 16
🔵 Azul → Otra pata a GND
TL072
Pin 1
🟠 Naranja → Capacitor 103 (10nF)
⚪ Blanco → Pin 2
🟢 Verde → Potenciómetro B250k pata 1
🟢 Verde → Potenciómetro B100k pata 1
⚪ Blanco → Pin 3 del LM386
Pin 2
🟠 Naranja → Capacitor 103 (10nF)
🟣 Morado → Potenciómetro B250k pata 2
🟡 Amarillo → Resistencia 10k
🔵 Azul → GND
Pin 3
🟡 Amarillo → Resistencia 100k
⚪ Blanco → Pin 4 del CD4046
🟠 Naranja → Capacitor 104 (100nF)
🔵 Azul → GND
Pin 4
🔵 Azul → GND
🟠 Naranja → Capacitor 104 (100nF)
Pin 5
Sin conexión
Pin 6
🟡 Amarillo → Resistencia 10k
⚪ Blanco → Pin 7
Pin 7
🟡 Amarillo → Resistencia 10k
⚪ Blanco → Pin 6
Pin 8
🔴 Rojo → VCC (+5V)
⚪ Blanco → Pin 6
⚪ Blanco → Pin 7

LM386
Pin 1
Sin conexión
Pin 2
🔵 Azul → GND
Pin 3
⚪ Blanco → Pin 1 del TL072
🟣 Morado → Potenciómetro B100k pata 2
Pin 4
🔵 Azul → GND
🟠 Naranja → Negativo capacitor 100uF
Pin 5
🟠 Naranja → Positivo capacitor 100uF
🟠 Naranja → Negativo capacitor de salida al parlante
⚪ Blanco → Pinza caimán
⚪ Blanco → Positivo del parlante
Pin 6
🔴 Rojo → VCC (+5V)
Pin 7
🟠 Naranja → Positivo capacitor 1uF
🔵 Azul → Negativo capacitor 1uF a GND
Pin 8
🟠 Naranja → Positivo capacitor 100uF conectado al pin 4
Potenciómetros
B1M (Control melodía)
🟣 Morado → Pata 2 al pin 9 del CD4046
B500k (Rango melodía)
🟣 Morado → Pata 2 al pin 11 del CD4046
B250k
🟢 Verde → Pata 1 al pin 1 del TL072
🟣 Morado → Pata 2 al pin 2 del TL072
B100k
🟢 Verde → Pata 1 al pin 1 del TL072
🟣 Morado → Pata 2 al pin 3 del LM386
Alimentación
VCC (+5V)
🔴 Rojo → Pin 16 del CD4046
🔴 Rojo → Pin 8 del TL072
🔴 Rojo → Pin 6 del LM386
GND común
🔵 Azul → CD4046: pines 3, 5, 8, 11, 12, 13, 14 y 15
🔵 Azul → TL072: pin 4
🔵 Azul → LM386: pines 2 y 4
🔵 Azul → Todos los negativos de capacitores indicados
🔵 Azul → Tierra común de la protoboard
Leyenda de colores
⚪ Blanco = conexión entre patas de chips
🔵 Azul = GND
🟡 Amarillo = resistencia
🟠 Naranja = capacitor ("lenteja")
🟣 Morado = potenciómetro pata 2
🟢 Verde = potenciómetro pata 1
🔴 Rojo = VCC (+5V)
  
