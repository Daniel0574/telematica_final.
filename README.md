# telematica_final.
principalme y para comenzar, clonaremos el repositorio con el comando acontinuacion: git clone https://github.com/Daniel0574/telematica_final..git

 -pasos
 
 
 -Para iniciar el contenedor se ejecuta el siguiente comando: sudo docker build -t proyectofinal:01 .

- Para ejecturar el servicio se usa el siguiente comando: sudo docker run -it -p 80:80 proyectofinal:01 python3 app.py
