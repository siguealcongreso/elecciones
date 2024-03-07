# elecciones

elecciones es una aplicación para leer y analizar los resultados de
las elecciones de diputados locales.

Fuentes: Instituto Electoral y de Participación Ciudadana del Estado
de Jalisco.

## Para contribuir a la aplicación

1. Copia este repositorio a tu cuenta (Crea un fork)

2. Clona de tu repositorio a tu computadora:

       git clone git@github.com:<tu-usuario>/elecciones.git

3. Crea una rama para las modificaciones

       git checkout -b agregar-mejora

4. Haz modificaciones

5. Empuja tus modificaciones a tu repositorio

6. Solicita que se incluyan tus cambios (Crea un Pull Request)


## Para generar la documentación

1. Crea un entorno virtual

       python3 -m venv env

2. Activa el entorno virtual

       . env/bin/activate

3. Instala la dependencia para la documentación

       pip install -e '.[doc]'

4. Genera la documentación

       cd docs
       make html

5. Navega a build/html/index.html
