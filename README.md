# CHECKLIST PARA LA INSTALACIÓN DE DEBIAN
En este repositorio se muestra una checklist para una pre-instalación, durante instalación, y post-instalación de el sistema operativo Debian12 

Es importante hacer una cheklist para llevar a cabo una correcta instalación del sistema operativo el cual queramos instalar en algún equipo de cómputo, conocer desde su software como su hardware.

------------
#### PRE-INSTALL CHECKLIST
Para conocer los requirimientos indispensables que requiere nuestro equipo de cómputo para poder instalar la ISO hay que consultar la documentación oficial de Debian [https://wiki.debian.org/es/DebianBookworm](https://wiki.debian.org/es/DebianBookworm) .
- [x] Conocer si nuestro equipo es de 64 o 32 bits.
- [x] Comprobar de compatibilidad del CPU.
- [x] Conocer nuestra tarjeta de red.
- [x] Verificar la compatibilidad de periféricos y otro hardware.
- [x] Conocer nuestro espacio en disco para crear el particionado del mismo.
- [x] Hacer un respaldo previo del contenido de nuestro disco.
- [x] Conocer la memoria minima y recomendada.
- [x] Preparar el medio de instalación (disco, memoria USB,etc).
- [x] Conocer si el equipo soporta BIOS o UEFI.
------------
#### CHECKLIST DURANTE INSTALACIÓN

- [x] Desactivar el Secure Boot en la BIOS/UEFI.
- [x] Indicar el medio de arranque del sistema.
- [x] Durante la instalación elegir el idioma.
- [x] Durante la instalación elegir la zona horaria o ubicación.
- [x] Durante la instalación configurar el tipo de teclado del equipo de cómputo.
- [x] Elegir la interfaz de red primaria a configurar.
- [x] Al llegar al particionado de discos hacerlo manualmente.
- [x] Crear las particiones primarias (máximo 4) ext y reservar espacio para crear la memoria swap (área de intercambio).
- [x] Elegir el dispositivo (nuestra maquina) donde se instalará el cargador de arranque.
- [x] Completar demás información durante la instalación.
------------
#### POST-INSTALATION CHECKLIST
- [x] Verificar que el equipo esté conectado a internet (vía alámbrica o inalámbrica). 
- [x] Agregar los repositorios necesarios en el archivo de **sources.list** en el directorio de **apt**.
- [x] Creación o modificación de cuentas de usuario y asignación de permisos.
- [x] Instalación, configuración y personalización del nuevo sistema operativo.

