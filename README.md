# Lanudo
La herramienta "Lanudo" es un script de fortalecimiento de seguridad para sistemas Linux. 

# ¿Qué es y qué hace?

Su objetivo es aplicar una serie de medidas avanzadas para mejorar la seguridad de un sistema.

Algunas de las acciones que realiza esta herramienta incluyen:

Actualizar el sistema y los paquetes instalados.
Configurar políticas de firewall para permitir conexiones establecidas y relacionadas, así como tráfico SSH, HTTP, HTTPS y DNS.
Configurar reglas de SELinux para reforzar la seguridad del sistema (si SELinux está instalado).
Aplicar reglas de seguridad adicionales, como deshabilitar el inicio de sesión de root a través de SSH, deshabilitar el inicio de sesión de usuarios con contraseña en SSH, limitar los permisos del directorio /tmp y configurar límites de recursos para usuarios.
Configurar la auditoría de eventos para registrar cambios en archivos sensibles como /etc/passwd, /etc/shadow y /etc/sudoers.
Actualizar las políticas de contraseñas para requerir una longitud mínima y recordar las últimas contraseñas utilizadas.
Habilitar la ejecución de comandos SUID y SGID.
Reiniciar los servicios pertinentes para aplicar los cambios.

# ¿Cómo se ejecuta? 

git clone del link del repositorio
chmod +x lanudo.sh
ejecutar con bash el script 


