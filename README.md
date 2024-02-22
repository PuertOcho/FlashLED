# FlashLED

En este proyecto de la placa Nucleo-L476RG. El LED parpadea en un grupo de dos destellos rápidos cada segundo. Este tipo de flasheo se identifica como **GpFl(2)** en luces de faros marítimos. En este proyecto se utiliza el LED de usuario de la placa Nucleo-L476RG para simplificar. El LED parpadea en un grupo de dos destellos rápidos cada segundo. Se supone que la velocidad de parpadeo es de 200 ms. Este tipo de flasheo se identifica como **GpFl(2)** en luces de faros marítimos. El objetivo de este proyecto es mostrar cómo un LED se puede encender y apagar a diferentes velocidades. Por tanto, la secuencia de parpadeo requerida se puede expresar de la siguiente manera:

LED ON
Esperar 200 ms
LED OFF
Esperar 100 ms
LED ON
Esperar 200 ms
LED OFF
Esperar 100 ms
Esperar 400 ms

En la siguiente imagen muestra como es el conexionado del LED con el puerto PA5, con una resistencia para limitar la corriente del LED (Todo esto ya integrado dentro de la placa) 

![[20240222152414.png]]


## Test
![video test](https://github.com/PuertOcho/FlashLED/assets/57835621/35517888-6cf1-492d-b1e6-d211a2b5b65d)
