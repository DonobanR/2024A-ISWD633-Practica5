# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a uan red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO

![image](https://github.com/DonobanR/2024A-ISWD633-Practica5/assets/135273301/25759e57-f232-4d84-8e04-3adf4088c539)


# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube

![image](https://github.com/DonobanR/2024A-ISWD633-Practica5/assets/135273301/19e60a11-1343-4f12-a1fa-aed9d20023b6)

