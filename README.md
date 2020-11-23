    1. Instalar pyenv

    2. Con pyenv, instalar python 3.7.5

    3. Dentro de la carpeta del proyecto, ejecutar ```pyenv local 3.7.5```

    4. Instalar pipenv utilizando pip.

    5. Ejecutar ```pipenv --python 3.7.5```

    6. Ejecutar ```pipenv install```

    7. Ejecutar ```pipenv run install_modules```
    
    8. Ejecutar ```pipenv run python -m ipykernel install --user --name=`pipenv run basename '$VIRTUAL_ENV'` ```
