# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba
![image alt](https://github.com/Estefano2001/2026A-ISWD633-practica5/blob/ea4a9687ed81ccb70cc41ede366382d36514cc45/descarga-compose.jpeg)
# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO
![image alt](https://github.com/Estefano2001/2026A-ISWD633-practica5/blob/ea4a9687ed81ccb70cc41ede366382d36514cc45/comprobacion-containers.jpeg)
# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
![image alt](https://github.com/Estefano2001/2026A-ISWD633-practica5/blob/ea4a9687ed81ccb70cc41ede366382d36514cc45/localhost.jpeg)
