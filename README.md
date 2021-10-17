# ESP32_INORAY_Async_WiFi_Manager_OTA

Probando una ESP32 en la placa de Rubén:
----------------------------------------

Está basado en los ejemplos de https://github.com/khoih-prog/ESPAsync_WiFiManager

Tiene un WiFi Manager al estilo del de TZPAU, pero que funciona sin problemas con el Async Webserver, y los ejemplos de Rui Santos.

Hay que bajar este repositorio completo, descomprimirlo y abrirlo con VSCode y Platformio.

Recomiendo conectar el puerto serie al configurar (9600) y ver los datos de SSID y password, ya que son en base a la MAC de las placas ESP32.

Está pensado para un esp32doit-devkit-v1

El led 1 de la placa titila rápido al funcionar con el gestor de WiFi.
Luego pasa a un modo más lento indicando que está conectado y funcionando.

Se puede actualizar por OTA directamente, buscando en la red el dispositivo mDNS "esp32-IORAY"

Saludos y gracias!!!

Si esta información te resulta útil e interesante, invitame un cafecito!!!
https://cafecito.app/marce_ferra

Desde fuera de Argentina en:
https://www.buymeacoffee.com/marceferra

O podés colaborar comprando algunos de los objetos creados en los tutoriales del blog:
https://listado.mercadolibre.com.ar/_Envio_MercadoEnvios_CustId_13497891
