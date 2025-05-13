## Ejemplos de programación orientada a objetos

## 1. Crear el archivo **.gitignore**

Se crea el archivo **.gitignore** para configurar los archivos que no se sincronizarán en el repositorio

````shell

## 2. 





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

## 7. Crear el archivo **requirements.txt**

Se crea el archivo **requirements.txt** con las librerías y el número de versión utilizadas.

````shell
pip freeze > requirements.txt
````

## 8. Crear el archivo **runtime.txt**

Se crea el archivo

````shell
python3 -V > runtime.txt
````

## 9. Indexar los archivos creados con **git**

Se indexan los archivos y cambios realizados en el proyecto

````shell
git add .
````

## 10. Generar un **commit**

Se realiza un **commit** con un texto que describa los camb8ios realizados en el proyecto

````shell
git commit -m "created configuración básica"
````

## 11. Realizar un **push**

Se realiza un **push** para subir los cambios realizados al repositorio de **GitHub**

````shell
git push -u origin main
````