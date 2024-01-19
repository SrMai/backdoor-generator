# Backdoor Generator

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)

## Preview
![Preview](https://i.imgur.com/5H7LepV.png)
Mas screenshots abajo

## Descripción

Este proyecto es un generador de backdoors en Python con el objetivo de educar y facilitar la comprensión de conceptos relacionados con la seguridad informática y el hacking ético. Es importante destacar que el uso de este script está estrictamente limitado a entornos autorizados y con propósitos educativos.

## Funcionalidades

- Generación de backdoors para diversos sistemas operativos (Windows, Mac, Linux, Android, iOS)
- Creación de reverse shells con comandos de reverse shells, bind shells, msfvenom, y shell hoax.
- Guardado de scripts generados como sesiones, permitiendo la administración y eliminación de sesiones.
- Funciones adicionales para activar listeners y crear ejecutables con código inyectado para el cliente (Disponibles en las siguientes actualizaciones).
- Se incluye soporte para los siguientes listeners (ncat, nc freebsd, busybox nc, ncat, ncat.exe, ncat (TLS), rlwrap + nc, rustcat, pwncat, windows ConPty, socat, socat (tty), powercat, msfconsole, hoaxshell).
- Compatibilidad con las siguientes shells (sh, /bin/sh, bash, /bin/bash, cmd, powershell, pwsh, ash, bsh, csh, ksh, zsh, pdksh, tcsh, mksh, dash).
- De momento solo genera y gestiona codigos de reverses funcionales como se aprecia en las screenshots, cuanto tenga inyectables para todos los sistemas operativos se subira la funcion de crear backdoors y gestionarlas

## Requisitos

- Python 3.x
- [Instala las dependencias](#instalación) con `pip install -r requirements.txt`

## Uso

1. Clona el repositorio: `git clone https://github.com/SrMai/backdoor-generator.git`
2. Navega al directorio: `cd backdoor-generator`
3. Ejecuta el script: `python3 main.py` **¡Importante!** Para la función de activar una backdoor o crear un ejecutable necesitas ejecutar con permisos de super usuario `sudo python3 main.py`
4. Navega por el Menú de opciones
.

**Lee cuidadosamente las advertencias y condiciones de uso antes de utilizar el script en cualquier entorno.**

## Instalación

Para instalar las dependencias, ejecuta el siguiente comando:

```bash pip install -r requirements.txt```

## screenshots
Utilizando una sesión ya creada en una red externa
![0](https://i.imgur.com/0zvuI4v.png)

Creando una nueva sesión:
![1](https://i.imgur.com/tc3FUJY.png)
windows

![2](https://i.imgur.com/8PQMywO.png)
reverseShell

![3](https://i.imgur.com/e6X8CJp.png)
powershell

![4](https://i.imgur.com/1pyuBVg.png)
powershell #1

![5](https://i.imgur.com/5WVbQLH.png)
ncat

![6](https://i.imgur.com/N9ivqSD.png)
Activador de sesiones ( 1) es la que creamos)

![6](https://i.imgur.com/3wPgkU2.png)
Datos de la sesión

## Contribuciones

Las contribuciones son bienvenidas. Siéntete libre de abrir un problema o enviar un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para preguntas o comentarios, no dudes en ponerte en contacto con el autor:

- [Correo Electrónico](mailto:opensource@carlosayala.cloud)
- [Discord](https://discordapp.com/users/691847137297694731)
- [Linkedin](https://www.linkedin.com/in/carlosayala04/)

