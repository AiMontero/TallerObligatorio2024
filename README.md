# Taller Obligatorio Linux Julio-2024
Esto muestra las lineas generales de como trabajamos y configuramos paso a paso cada directorio y archivo para cumplir las exigencias del trabajo entregable

Instalación
Se hizo uso e instalación de Git y Ansible para poder llevar a cabo el proceso de automatismos deseados.

Configuración General de Playbooks

#Hardening.yml

-Configuracion de app ToDo en Ubuntu

-Copiar archivo WAR de la aplicacion todo

-Reiniciar tomcat

#database.yml

- Instalar pyMysql para soporte MYsql/mariaDB en Python
- Cambiar la configuracion para escuchar en todas las interfases de red
- Habilitamos en ufw la conexion a mariadb
- Creo la DB todo
- Creo un handler para restartear el servicio
- Reiniiciar MariaDB

#tomcat.yml
- Configurar Todo
- Actualizar lista de paquetes
- Instalar Java
- Descargar Tomcat
- Crear directorio de instalación de Tomcat
- Extracción de Tomcat
- Configurar permisos para Tomcat
- Recargar systemd para incluir tomcat
- Iniciar y habilitar servicio Tomcat
- Instalar MariaDB
- Copiar archivo WAR de app todo
- Reiniciar tomcat


#ufwmariadb

-Configurar el firewall para MariaDB
-UFW instalado
- Permitir puerto 22 en ufw
- Defino politicas de tráfico entrante
- Servicio UFW levantado y activo
- MariaDB instalado
- Instalar PyMySQL para soporte MySQL/mariaDB en Python
- Cambiar configuracion para escuchar todas las interfases
- Habilitamos en ufw la conexion a MariaDB
- Creo base de datos todo
- Reiniciar MariaDB

#todo.yml

- Configurar todo en ubuntu
- Copiar archivo war de app todo
- Reiniciar tomcat

Archivo files:

-todo.sql
-virtualhost.conf

Archivo inventory:

hardening.yml
servidores.toml
group_vars

Archivo templates:

app.properties.j2
containerfile.j2
index.j2




Contribuciones
# Se obtuvo ayuda de las clases grabadas y de documentación online
