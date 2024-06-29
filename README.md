# PYTHON-FINAL
## Crearemos un entorno virtual

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Windows.
2. Creamos una carpeta o directorio:

        mkdir python-final
   
3. Entramos en ella:

        cd python-final
   
4. Iniciamos el repositorio:

        git init
   
5. Creamos un archivo:

        touch finales.py
   
6. Abrimos VSC:

         code .
   
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

        python --version o python -V
   
8. Creamos el entorno virtual en Python:

        python3 -m venv venv
   
9. Activamos el entorno virtual:
    * En Linux:
   
          source venv/bin/activate
     * En Windows:

           venv/Scripts/activate

10. Hacemos actualización del pip de Python:

        python -m pip install --upgrade pip o python3 -m pip install --upgrade pip

> ¿Qué es el pip y por qué lo actualizamos?
> `pip` es el gestor de paquetes para Python. Permite instalar, actualizar y desinstalar paquetes y librerías de Python, que son colecciones de módulos y herramientas que puedes usar en tus proyectos para añadir funcionalidades sin tener que escribir todo el código desde cero.
> Actualizar pip es importante porque las versiones más recientes suelen incluir mejoras, nuevas características, y correcciones de errores o vulnerabilidades de seguridad. Mantener pip actualizado te asegura que estás utilizando la versión más segura y eficiente posible.

[REPOSITORIO REMOTO](https://github.com/AFRIAULAR/python-final)
