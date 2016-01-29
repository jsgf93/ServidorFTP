# ServidorFTP

Se implementó la siguiente estructura de red:

2 servidores FTP en máquinas virtuales de VMWare:
*IP Servidor 1: 192.168.254.155
*IP Servidor 2: 192.168.254.148
*Herramienta: vsftpd

1 balanceador de carga en una máquina virtual de VMWare:
*IP Balanceador: 192.168.254.147
*Herramienta: PEN

1 host con varios procesos de cliente en una máquina virtual de VMWare:
*IP Host: 192.168.254.159
*Herramientas: javac, eclipse mars (Apache Commons Net API) y archivos.sh

Peticiones:
*Código fuente: FTPDownloadFile.java 
*Scripts ejecutables

