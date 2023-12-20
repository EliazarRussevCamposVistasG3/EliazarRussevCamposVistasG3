- Resume

The project consists of using bitrix24 which gives us access to a management web page which is a virtual tool that will give us access to all possible clients of a form, said form is there in Google sites which in turn is managed in bitrix24, Later we host the form page directly in Apaches2 which gives us direct access to its source code and edit it and these changes will be reflected in our bitrix24 page. In this way we can share the drive form having greater reach and control over it on our Apache server, being able to make deep changes to the code or more superficial ones using the tools provided by Google

Objetivo general:

El objetivo de este proyecto es probar nuestra capacidad en el manejo de los comandos y el manejo de servidores como muestra de su importancia en el mundo laborar 

Marco teórico

¿Qué es un servidor?

Un servidor web (server) es un ordenador de gran potencia que se encarga de “prestar el servicio” de transmitir la información pedida por sus clientes (otros ordenadores, dispositivos móviles, impresoras, personas, etc.)

Los servidores web (web server) son un componente de los servidores que tienen como principal función almacenar, en web hosting, todos los archivos propios de una página web (imágenes, textos, videos, etc.) y transmitirlos a los usuarios a través de los navegadores mediante el protocolo HTTP (Hipertext Transfer Protocol).

¿Para qué sirve un servidor web en Internet?

El rol principal de un servidor web es almacenar y transmitir el contenido solicitado de un sitio web al navegador del usuario.

Este proceso, para los internautas no dura más que un segundo, sin embargo, a nivel del web server es una secuencia más complicada de lo que parece.

Para cumplir con sus funciones el servidor deberá tener la capacidad de estar siempre encendido para evitar interrumpir el servicio que le ofrece a sus clientes. Si dicho servidor falla o se apaga, los internautas tendrán problemas al ingresar al sitio web.

¿Cómo funciona un servidor web?

La comunicación entre un servidor y sus clientes se basa en HTTP, es decir, en el protocolo de transferencia de hipertexto o en su variante codificada HTTPS.

Para saber cómo funciona, primero es necesario conocer que el web server está permanentemente en espera de una solicitud de información.

Además, ten en cuenta que toda computadora, smartphone o tablet tiene una dirección IP única e irrepetible que lo identifica de otro dispositivo en la red, así es como el servidor web envía la información exacta que el internauta está esperando.

Ahora bien, para que el web server pueda cumplir con su función es necesario que reciba la petición por parte de un navegador, en otras palabras, se envía un pedido desde una dirección IP hacia la dirección IP del servidor que aloja los archivos del sitio en cuestión.

A continuación, el servidor web busca en sus archivos la información que se le está solicitando, procede a interpretar las líneas de código y a enviar el resultado al navegador cuya dirección IP fue la solicitante.

Este resultado se le muestra a los internautas y es lo que siempre sucede cuando se navega en sitios de Internet. Cuando este proceso se completa podemos decir que el web server ha cumplido con su función.

CRM

La gestión o administración de relaciones con el cliente, más conocida por sus siglas en inglés CRM, puede tener varios significados: Administración o gestión basada en la relación con los clientes: un modelo de gestión de toda la organización, basada en la satisfacción del cliente.

Apaches: Apache es un servidor web dE código abierto, multiplataforma y gratuito.

Este web server es uno de los más utilizados en el mundo, actualmente el 43% de los sitios webs funcionan con él.

El nombre Apache se refiere a la tribu de los nativos americanos, conocidos por su gran resistencia en el combate y por sus estrategias de guerra.

Se ha vuelto muy popular entre los programadores debido a su modularidad y actualización constante por parte de la comunidad, la mayoría de servidores Apache los podemos encontrar en la mayoría de hosting a nivel mundial, funcionando sin problema con paneles como WePanel, Plesk, VestaCP, etc.

Una de las principales características de Apache es el uso del archivo .htaccess, muy utilizado entre todos los usuarios web.

Cómo funciona un servidor Apache

La función esencial del servidor Apache es servir las webs alojadas en el servidor a los diversos navegadores como Chrome, Firefox, Safari, etc

Apache consigue que la comunicación entre el servidor web y el cliente web (usuario que solicita la información) sea fluida y constante.

Haciendo que cuando un usuario haga una petición HTTP a través de navegador para entrar a una web o URL específica, Apache devuelva la información solicitada a través del protocolo HTTP.

En Apache podemos aplicar una alta personalización a través de su sistema modular, de forma que podemos activar o desactivar diversas funcionalidades a través de los módulos de Apache.

Estos módulos de Apache hay que usarlos con cautela ya que pueden afectar a la seguridad y funcionalidades del servidor web.

Ventajas de Apache

Algunas de las ventajas que podemos encontrar en un servidor Apache son las siguientes:

Cuenta con una comunidad grande de desarrolladores en todo el mundo, que contribuyen a mejorar el software, ya que el código fuente original está disponible de forma gratuita para su visualización y colaboración.

Compatible con webs que usen WordPress y la mayor parte de los CMS más populares del mercado.

Estructura constituida por módulos.

Es multiplataforma. Puede ser usado en servidores Windows y Linux lo que amplía sus posibilidades de uso.

Es de código abierto y gratis.

Alto nivel de seguridad debido a sus actualizaciones constantes.

Podrás usar .htaccess lo que permite trabajar de forma más sencilla con los principales CMS.

Inconvenientes de Apache

El rendimiento puede verse afectado en páginas con alto tráfico, sobre todo a partir de las 10k conexiones.

Si no se hace un buen uso de los módulos se pueden generar brechas de seguridad.

Bitrix24

Es una herramienta online diseñada para ordenar las operaciones diarias, las tareas y los componentes de empresas u organizaciones sin fines de lucro. 

Desde el aspecto técnico, Bitrix24 es un servicio online en la nube al que puedes acceder a través del navegador o mediante una aplicación móvil o de escritorio. Cuenta con varios componentes distintos, como CRM, tareas y proyectos, chats, reuniones online, creador de sitios web, documentos online y mucho más, todos integrados y disponibles como parte de una única plataforma.

¿Para qué se utiliza Bitrix24?

Bitrix24 se puede utilizar para varios propósitos, los principales son ventas, marketing, comunicación, gestión de proyectos, servicio al cliente y colaboración online, especialmente para equipos remotos o híbridos.

Usando Bitrix24, tú y tu equipo pueden fácilmente:

comunicarse a través de chats y reuniones online

gestionar clientes y ventas a través de nuestro CRM

ejecutar proyectos utilizando nuestras herramientas de gestión de proyectos

administrar tareas de los empleados y realizar un seguimiento de sus horas de trabajo

editar de forma colaborativa documentos en tiempo real

generar y procesar prospectos

lanzar y rastrear e-mail marketing, SMM y otras campañas publicitarias

crear sitios web y landing pages

Desarrollo 

instalación de apaches en UBUNTU: se debe tener un non-root user normal con privilegios sudo configurado en su servidor. Además, deberá habilitar un firewall básico para que bloquee los puertos que no sean esenciales.

Paso 1: Instalar Apache

Apache está disponible en los repositorios de software predeterminados de Ubuntu, lo que permite instalarlo con las herramientas convencionales de administración de paquetes.

Comencemos actualizando el índice de paquetes locales para que reflejen los últimos cambios anteriores:

1.	sudo apt update

A continuación, instale el paquete apache2:

1.	sudo apt install apache2

Una vez confirmada la instalación, apt instalará Apache y todas las dependencias necesarias.

Paso 2: Ajustar el firewall

Antes de probar Apache, es necesario modificar los ajustes de firewall para permitir el acceso externo a los puertos web predeterminados. Suponiendo que siguió las instrucciones de los requisitos previos, debería tener un firewall UFW configurado para que restrinja el acceso a su servidor.

Durante la instalación, Apache se registra con UFW para proporcionar algunos perfiles de aplicación que pueden utilizarse para habilitar o deshabilitar el acceso a Apache a través del firewall.

Enumere los perfiles de aplicación ufw escribiendo lo siguiente:

1.	sudo ufw app list

Obtendrá una lista de los perfiles de aplicación:

Output

Available applications:

  Apache

  Apache Full

  Apache Secure

  OpenSSH

Como lo indica el resultado, hay tres perfiles disponibles para Apache:

•	Apache: este perfil abre solo el puerto 80 (tráfico web normal no cifrado)

•	Apache Full: este perfil abre el puerto 80 (tráfico web normal no cifrado) y el puerto 443 (tráfico TLS/SSL cifrado)

•	Apache Secure: este perfil abre solo el puerto 443 (tráfico TLS/SSL cifrado)

Se recomienda habilitar el perfil más restrictivo, que de todos modos permitirá el tráfico que configuró. Debido a que en esta guía aún no configuramos SSL para nuestro servidor, solo deberemos permitir el tráfico en el puerto 80:

1.	sudo ufw allow 'Apache'

Puede verificar el cambio escribiendo lo siguiente:

1.	sudo ufw status

El resultado proporcionará una lista del tráfico de HTTP que se permite:

Output

Status: active



To                         Action      From

--                         ------      ----

OpenSSH                    ALLOW       Anywhere                  

Apache                     ALLOW       Anywhere                

OpenSSH (v6)               ALLOW       Anywhere (v6)             

Apache (v6)                ALLOW       Anywhere (v6)

Como lo indica el resultado, el perfil se activó para permitir el acceso al servidor web Apache.

Paso 3: Comprobar su servidor web

Al final del proceso de instalación, Ubuntu 20.04 inicia Apache. El servidor web ya debería estar activo.

Realice una verificación con el sistema init systemd para saber si se encuentra en ejecución el servicio escribiendo lo siguiente:

1.	sudo systemctl status apache2

Output

● apache2.service - The Apache HTTP Server

     Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: enabled)

     Active: active (running) since Thu 2020-04-23 22:36:30 UTC; 20h ago

       Docs: https://httpd.apache.org/docs/2.4/

   Main PID: 29435 (apache2)

      Tasks: 55 (limit: 1137)

     Memory: 8.0M

     CGroup: /system.slice/apache2.service

             ├─29435 /usr/sbin/apache2 -k start

             ├─29437 /usr/sbin/apache2 -k start

             └─29438 /usr/sbin/apache2 -k start



Como lo confirma este resultado, el servicio se inició correctamente. Sin embargo, la mejor forma de comprobarlo es solicitar una página de Apache.

Puede acceder a la página de destino predeterminada de Apache para confirmar que el software funcione correctamente mediante su dirección IP: Si no conoce la dirección IP de su servidor, puede obtenerla de varias formas desde la línea de comandos.

Intente escribir esto en la línea de comandos de su servidor:

1.	hostname -I

Obtendrá algunas direcciones separadas por espacios. Puede probar cada uno en el navegador web para determinar si funcionan.

Otra opción es utilizar la herramienta Icanhazip, que debería proporcionarle su dirección IP pública como aparece en otra ubicación en Internet:

1.	curl -4 icanhazip.com

Cuando tenga la dirección IP de su servidor, introdúzcala en la barra de direcciones de su navegador:

http://your_server_ip

Debería ver la página web predeterminada de Apache en Ubuntu 20.04:

 

Esta página indica que Apache funciona correctamente. También incluye información básica sobre archivos y ubicaciones de directorios importantes de Apache.

Paso 4: Administrar el proceso de Apache

Ahora que el servidor web está listo y en funcionamiento, repasemos algunos comandos de administración básicos con systemctl.

Para detener su servidor web, escriba lo siguiente:

1.	sudo systemctl stop apache2

Para iniciar el servidor web cuando no esté activo, escriba lo siguiente:

1.	sudo systemctl start apache2

Para detener y luego iniciar el servicio de nuevo, escriba lo siguiente:

1.	sudo systemctl restart apache2

Si solo realiza cambios de configuración, Apache a menudo puede recargarse sin cerrar conexiones. Para hacerlo, utilice este comando:

1.	sudo systemctl reload apache2

Por defecto, Apache está configurado para iniciarse automáticamente cuando el servidor lo hace. Si no es lo que quiere, deshabilite este comportamiento escribiendo lo siguiente:

1.	sudo systemctl disable apache2

Para volver a habilitar el servicio de modo que se cargue en el inicio, escriba lo siguiente:

1.	sudo systemctl enable apache2

Ahora, Apache debería iniciarse de forma automática cuando el servidor lo haga de nuevo.

Paso 5: Configurar hosts virtuales (recomendado)

Al emplear el servidor web Apache, puede utilizar hosts virtuales (similares a bloques de servidor de Nginx) para encapsular detalles de configuración y alojar más de un dominio desde un único servidor. Configuraremos un dominio llamado your_domain, pero debería cambiarlo por su propio nombre de dominio. Si va a configurar un nombre de dominio con DigitalOcean, consulte nuestra Documentación de red.

Ubuntu 20.04 tiene habilitado un bloque de servidor por defecto, que está configurado para proporcionar documentos del directorio /var/www/html. Si bien esto funciona bien para un solo sitio, puede ser difícil de manejar si aloja varios. En vez de modificar /var/www/html, vamos a crear una estructura de directorios dentro de /var/www para un sitio your_domain y dejaremos /var/www/html como directorio predeterminado que se suministrará si una solicitud de cliente no coincide con otros sitios.

Cree el directorio para your_domain de la siguiente manera:

1.	sudo mkdir /var/www/your_domain

A continuación, asigne la propiedad del directorio con la variable de entorno $USER:

1.	sudo chown -R $USER:$USER /var/www/your_domain

Los permisos de los roots web deberían ser correctos si no modificó el valor umask, que establece permisos de archivos predeterminados. Para asegurarse de que sus permisos sean correctos y permitir al propietario leer, escribir y ejecutar los archivos, y a la vez conceder solo permisos de lectura y ejecución a los grupos y terceros, puede ingresar el siguiente comando:

1.	sudo chmod -R 755 /var/www/your_domain

A continuación, cree una página de ejemplo index.html utilizando nano o su editor favorito:

1.	sudo nano /var/www/your_domain/index.html

Dentro de ella, agregue el siguiente ejemplo de HTML:

/var/www/your_domain/index.html

<html>

    <head>

    <title>Welcome to Your_domain!</title>

    </head>

    <body>

    <h1>Success!  The your_domain virtual host is working!</h1>

    </body>

</html>

Guarde y cierre el archivo cuando termine.

Para que Apache proporcione este contenido, es necesario crear un archivo de host virtual con las directivas correctas. En lugar de modificar el archivo de configuración predeterminado situado en /etc/apache2/sites-available/000-default.conf directamente, vamos a crear uno nuevo en /etc/apache2/sites-available/your_domain.conf:

1.	sudo nano /etc/apache2/sites-available/your_domain.conf

Péguelo en el siguiente bloque de configuración, similar al predeterminado, pero actualizado para nuestro nuevo directorio y nombre de dominio:

/etc/apache2/sites-available/your_domain.conf

<VirtualHost *:80>

    ServerAdmin webmaster@localhost

    ServerName your_domain

    ServerAlias www.your_domain

    DocumentRoot /var/www/your_domain

    ErrorLog ${APACHE_LOG_DIR}/error.log

    CustomLog ${APACHE_LOG_DIR}/access.log combined

</VirtualHost>

Tenga en cuenta que cambiamos DocumentRoot por nuestro nuevo directorio y ServerAdmin por un correo electrónico al que pueda acceder el administrador del sitio your_domain. También agregamos dos directivas: ServerName, que establece el dominio de base que debería coincidir para esta definición de host virtual, y ServerAlias, que define más nombres que deberían coincidir como si fuesen el nombre de base.

Guarde y cierre el archivo cuando termine.

Habilitaremos el archivo con la herramienta a2ensite:

1.	sudo a2ensite your_domain.conf

Deshabilite el sitio predeterminado definido en 000-default.conf:

1.	sudo a2dissite 000-default.conf

A continuación, realizaremos una prueba para ver que no haya errores de configuración:

1.	sudo apache2ctl configtest

Debería obtener el siguiente resultado:

Output

Syntax OK

Reinicie Apache para implementar sus cambios:

1.	sudo systemctl restart apache2

Con esto, Apache debería ser el servidor de su nombre de dominio. Puede probarlo visitando http://your_domain, donde debería ver algo como esto:

 

Instalación de bitrix24: Para instalar bitrix24 se debe ingresar a la página oficial de bitrix24 y buscar la instancia para Linux y verificar que esta sea compatible con nuestra SO

La aplicación de Bitrix24 para Linux admite distribuciones:

DEB

•	Ubuntu 20,21,22

•	Kubuntu 20,22

•	Mint 20, 21

•	Astra Linux 2.12

RPM

•	Fedora 35, 36

•	ALT Workstation 10

•	Rosa 21.1

•	OpenSuse Leap 15.4

Bibliografía 

https://httpd.apache.org/docs/trunk/es/install.html apaches 

https://helpdesk.bitrix24.es/open/16173006/ bitrix24

https://www.salesforce.com/mx/crm/ 

https://sites.google.com/view/importadora-fa/p%C3%A1gina-principal formulario drive




<!---
EliazarRussevCamposVistasG3/EliazarRussevCamposVistasG3 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
