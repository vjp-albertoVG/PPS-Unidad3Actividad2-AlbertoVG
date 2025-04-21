# PPS-Unidad3Actividad2-AlbertoVG
Unidad 3 - Actividad 2. Detección de equipos, puertos, servicios,vulnerabilidades.

Tenemos como objetivo:

> Aprender y conocer comandos y herramientas para escanear y localizar equipos y recursos.
>
> Practicar y probar en el entorno de pruebas con dichas herramientas.
---
## ACTIVIDADES A REALIZAR
- Busca información de:
	- Como podemos obtener información pública con protocolo whois, web DoaminTools y DSNrecon.

El protocolo WHOIS permite obtener información registrada de dominios en Internet, como el propietario del dominio, los servidores de nombres, la fecha de creación y expiración, etc.

DomainTools es un servicio en línea que te permite buscar información sobre dominios, historial de registros, y más. Ofrece herramientas avanzadas de análisis de dominio y vigilancia.

DNSRecon es una herramienta que permite realizar consultas de DNS para obtener información sobre un dominio, como registros de tipo A, MX, NS, y más. Puede ayudarte a identificar la infraestructura de servidores y otros recursos asociados a un dominio.

	- Cómo podemos utilizar Nmap y nikto,   para buscar equipos, puertos abiertos, servicios, vulnerabilidades.

Nmap (Network Mapper) es una de las herramientas más utilizadas para escaneo de redes y auditoría de seguridad. Permite identificar hosts activos, puertos abiertos, servicios, y más.

Nikto es una herramienta de escaneo web que busca vulnerabilidades conocidas en servidores web. Detecta configuraciones incorrectas, fallos de seguridad, versiones vulnerables, y más.
 
	- Cómo utilizar Wfuzz, Dirb para localizar recursos web en servidores.

Wfuzz es una herramienta utilizada para realizar pruebas de fuzzing en aplicaciones web, identificando recursos ocultos como directorios y archivos. Utiliza diccionarios para realizar solicitudes HTTP masivas.

Dirb es una herramienta más simple que se utiliza para realizar ataques de fuerza bruta a directorios y archivos en aplicaciones web.

	- Que scripts que podemos utilizar con Nmap para la búsqueda de vulnerabilidades.

Algunos scripts comunes:

http-vuln-cve2006-3392: Detecta una vulnerabilidad en un servidor HTTP.

smb-vuln-ms17-010: Detecta la vulnerabilidad conocida como EternalBlue (CVE-2017-0144).

ftp-anon: Busca servidores FTP configurados de manera insegura (anónimos).

ssl-heartbleed: Detecta la vulnerabilidad Heartbleed en servicios SSL/TLS.
 
	- Cómo podemos buscar información de explotación de vulnerabilidades con searchsploit

Para buscar un exploit por nombre de CVE o término relacionado:

searchsploit <nombre_cve>

Buscar exploits para una vulnerabilidad conocida:

searchsploit apache

Mostrar detalles de un exploit:

searchsploit -x <exploit_path>

También puedes buscar y filtrar exploits por plataforma, como Linux, Windows, etc.

 
- Instala en tu navegador la extensión de Shodan y muestra la información que tenemos tanto de ip, como de dominio del sitio http://iesvalledeljerteplasencia.es

![](/Images/imagen1.png)
  
- Sobre la red del laboratorio PPS con kali, bWAPP, Multidillae y DVWA:<
	- Ayudándote del fichero docker-compose localiza las diferentes máquinas y puertos que deberían de tener abiertos.

	![](/Images/imagen2.png)

	- Identifica los equipos de la Red con Nmap.

	![](/Images/imagen3.png)

	- Realiza análisis de puertos en las MV.
  
	- Encuentra los Servicios y Sistemas Operativos de las MV.

	![](/Images/imagen4.png)

	- Inspecciona los puertos con nikto.

   	![](/Images/imagen5.png)
   
	- Busca las vulnerabilidades de las MV con los scripts de Nmap.

	![](/Images/imagen6.png)
  
	- Utiliza el comando searchsploit para buscar información de explotación de vulnerabilidades presentes en linux con kernel 5

   	![](/Images/imagen7.png)
  
---	
## ENTREGA

>__Realiza las operaciones indicadas__

>__Crea un repositorio  con nombre PPS-Unidad3Actividad2-Tu-Nombre donde documentes la realización de ellos.__

> No te olvides de documentarlo convenientemente con explicaciones, capturas de pantalla, etc.

>__Sube a la plataforma, tanto el repositorio comprimido como la dirección https a tu repositorio de Github.__
