  # Configuración para el Taller de Home Assistant en Celia Connect
 
 
 En este repositorio está la configuración de los dispositivos virtuales que se usarán durante el taller de Home Assistant en Celia Connect.
 
 Para instalar dicha configuración es  necesario ejecutar estos comandos en la terminal `ssh` de Home Assistant
 
 ```bash
 cd /config
 git clone https://github.com/miguelangellv/homeassistant-celia-demo
 mv homeassistant-celia-demo/* .
 rm -R homeassistant-celia-demo
 ```
 
 Después será necesario reiniciar Home Assistant
