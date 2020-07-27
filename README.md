# AlexArduino
Repositorio que contiene código y guías para configurar módulos WiFi (como ESP8266) para funcionar con el asistente Virtual "Alexa".

Para usar las placas ESP8266 con Arduino IDE ir a Archivo (File) -> Preferencias (Preferences) y en la barra de "Gestor de URLs Adicionales a Tarjetas" colocar el siguiente URL. `http://arduino.esp8266.com/stable/package_esp8266com_index.json`. 
Después ir Herramientas (Tools), ir a Placa -> Gestor de Tarjetas..., buscar en la barra de búsqueda "esp8266" y **descargar la versión 2.5.0** (es importante que sea esta versión ya que si no es ésta hay un error que no permite subir código a la placa 01S). 

* Para ESP8266-01S hacer las conexiones tal como se muestra en el diagrama en la carpeta "imgs" y mantener apretado el *push button* para cargar código. 
