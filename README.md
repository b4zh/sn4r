# SN4R
Este un pequeño script que escribí para automatizar **mi uso** de 👁️ nmap al realizar un escaneo activo hacia máquinas de 🚩 CTF.

## Uso
El script recibe como argumento al host objetivo.

## Escaneo inicial
Nmap escanea todos los puertos, nmap solo muestra los puertos en estado abierto, nmap guarda resultados del primer escaneo en los ficheros **ports.txt** e **init.nmap**.

## Escaneando servicios.
Nmap lanza los scripts de la categoría default y escanea los servicios de los puertos abiertos, nmap guarda el resultado en el fichero **services.nmap**.

## Errores
Nmap guarda los errores del escaneo en el fichero **errors.txt**.
