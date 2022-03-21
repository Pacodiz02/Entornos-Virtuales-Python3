## Entornos virtuales Python3
Nota: Entornos Virtuales de Python3 en Debian 11

1. Instalamos `apt install python3-venv`

2. Creamos un directorio en el `/home` de nuestro usuario sin privilegios, donde crearemos los entornos virtuales.

3. Nos movdemos al directorio que creamos en el paso anterior.

4. Para crear el entorno ejecutamos `python3 -m venv nombre_entorno_virtual`.

5. Para poder utilizarlo tenemos que activarlo con `source nombre_entorno_virtual/bin/activate`

    Una vez activo se cambiará el PATH del usuario y podremos instalar con `pip` las versiones que deseemos.
    
    Con la orden `pip list` podemos listar los paquetes instalados en dicho entorno. 

6. Para desactivarlo ejecutamos `deactivate`
