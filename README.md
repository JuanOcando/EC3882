# EC3882
Basic Firmware of DEMOQE for Projects Laboratory 2 (EC3882). Examples and sample code.


# Instrucciones

Deben comenzar con los mismos pasos del prelaboratorio del lunes, empezando con su propio código desde cero y tomando como referencia los ejemplos que coloqué en este repositorio.

Recuerden que deben usar processor expert, agregar los componentes y realizar los ajustes de cada uno. Eso no está reflejado en ninguno de estos documentos.

La secuencia en la que deben trabajar su primer proyecto funcional es la siguiente:

1.- Encender y apagar conjuntos de LEDs de acuerdo a una interrupción periódica: componentes TimerInt y BitIO.

2.- Enviar por serial un byte de su elección (en el prelaboratorio yo lo hice con 0xAA). Ver en la pantalla de realterm u otro programa de puerto serial. Componente AsynchroSerial.

3.- Trabajar en el esqueleto de la máquina de estados. Definir las constantes en el header. Hasta ahora sólo 2 estados: Esperar y enviar.

4.- Enviar por serial un bloque de su elección, que sea de 4 o 5 bytes. Se usa el método SendBlock.

5.- Hacer la medición del ADC del pin del potenciómetro (PTA0). Hacerla primero a 8 bits. Componente ADC.

6.- Incluir un tercer estado en la máquina de estados. Ahora serán: sperar, medir y enviar.

7.- Hacer la medición del potenciómetro a 12 bits y enviar por serial como bloque.

Tengan en cuenta que este código es sólo de referencia, y que no funcionará si lo queman directo sin configurar todos los componentes. Por eso es preferible que inicien todo desde cero y repitan lo que yo hice en el prelaboratorio del lunes.

OT
