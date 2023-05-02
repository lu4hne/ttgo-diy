# ttgo-diy
Create your ttgo lora with parts.

Two models of plates to assemble a ttgo in long format, With its elements one after another.
Or the mini version, with the esp32 on the back side and Lora and oled display on the front.


Este proyecto es una copia con componentes discretos del modelo ttgo-lora, enfocado para quienes no tienen la posibilidad de adquirir un original.

Funcionamiento:
El dispositivo tiene grabado un firmware que informa en la web https://sondehub.org/ las sondas meterologicas detectadas. Brinda información de altitud, temperatura, humedad, y cordenadas muy precisas de latitud y longitud.
En el mapa se pueden observer dos estados, el de ascenso y descenso, cambiando de color el globo. Al momento des descenso calcula por prediccion la zona de caida con un error menor a 100mtrs.

![image](https://user-images.githubusercontent.com/100592663/235674420-163f5969-a0d4-40b0-904b-3ea78a7bb011.png)

Configuración:
El dispositivo se configuran los datos de la sonda a rastrear, licencia del radioaficionado que hace la captura y otros datos como se ve en este video. https://youtu.be/HP3r6paxjF8

Importante:
Las sondas trabahan en la banda de UHF entre 402Mhz y 405Mhz segun el modelo de sonda y la ubicación de donde se lanza. Esta banda no está autorizada para usarse, solo pueden usarlas los sistemas metereologicos.
Tampoco ponga en funcionamiento Sondas cerca de la zona de lanzamiento ya que informaria datos falsos.


Version mini, doble side

![pcb](https://user-images.githubusercontent.com/100592663/221630061-26c77171-9630-4d0a-a9fe-9d4487af65e8.png)

Version large, single side

![pcb long](https://user-images.githubusercontent.com/100592663/221630958-b474b4ca-ff23-4841-bbe9-71283537c87c.png)


https://youtube.com/shorts/UzUDJ2xq2zk
