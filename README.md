
# Documentación del Proyecto Hospital

## Descripción general

Este ejecicio es para tener un primer acercamiento con lo que hace un departamento de QA, para esto desarrolle esta sencilla aplicacion que consta de un inicio de sesion y que se conecta a una base de datos donde almacena nombres de hospitales, con su direccion y numero de telefono.

Para su prueba se creo una imagen docker compose donde se integran postgres y todo el enviroment que se creo. 

## Tecnologias usadas:
- Python: 
    - version: 3.11
    Se uso para la creacion de backend de la aplicacion con Flask y    para la ejecucion de las pruebas automatizadas con Behave.
- Flask: Framework web minimalista para Python que perite car aplicaciones web rapidamente.

## Uso
1. Clonar el repositorio

```
git clone https://github.com/BenJameto/ejemploFEATURES
```

2. Posicionarse en la carpeta

```
cd <tu ruta>/ejemploFEATURES
```

3. Activar el entorno

```
souce test_selenium/bin/activate
```

4. Ejeutar la aplicacion

```
python3 app.py
```

5. Ingresar a http://127.0.0.1:5000

6. Credenciales de acceso
    - **Usuario:** hospitaluser
    - **contraseña** hospitaluser1234
**Nota:** Estas credenciales las puedes cambiar en el archivo *.env.local*

7. Apagar el entorno
```
source test_selenium/bin/deactivate
```