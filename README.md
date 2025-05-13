#Ejemplos de programación orientada a objetos

##1. Crear el archivo **.gitignore**

Se crea el archivo **.gitignore** para configurar los archivos que no se sincronizarán en el repositorio

````shell







Se crea el ambiente virtual de trabajo de python

````shell
python3 -m venv .venv
````

## 3. Iniciar el **virtual enviroment**

Se activa el **virtual enviroment** para instalar las librerías necesarias para el proyecto

````shell
source .venv/bin/activate
````

## 4. Actualizar **pip** dentro del **virtual enviroment**

Se actualiza la versión instalada de **pip** para poder descargar las últimas versiones de las librerías.

````shell
pip install --upgrade pip
````

## 5. Verificar las librerías instaladas

Se verifica que librerías y versiones se tienen instaladas

````shell
pip freeze
````

## 6. Instalar librerías 

Se instalan las librerías que se van a ocupar en el proyecto.

````shell
pip install web.py
````