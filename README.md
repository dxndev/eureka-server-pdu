# eureka-server-pdu
 Servidor Eureka - Proyecto Sistema Educativo


-------------------------------------------------------------------------------------------
INTRUCCIONES PARA CREAR LAS BASES DE DATOS

1. Creamos la base de datos para el ms-profesores
   
create database db_profesores;

-------------------------------------------------------------------------------------------
2. Creamos la base de datos para el ms-cursos
   
create database db_cursos;

-------------------------------------------------------------------------------------------
3. Creamos la base de datos para el ms-alumnos;
   
create database db_alumnos;

-------------------------------------------------------------------------------------------
4. Creamos la base de datos para el ms-auth y luego
   
   create database db_auth;
   
-------------------------------------------------------------------------------------------
5. insertamos los datos(no es necesario crear la tabla, esta se crea al ejecutar el servicio)

INSERT INTO usuarios (username, password, rol) VALUES ('admin', 'admin123', 'ADMIN');

-------------------------------------------------------------------------------------------
