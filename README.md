# VirtualEnv
Práctica de entornos virtuales con VENV, opciones (PIPENV) (POETRY)

## Steps to create an virtual environment on Python

1. Create repository on GITHUB, add `.gitignore Python`
2. Clone repository
3. Execute the following command to create the virtual environment:

```bash
python -m venv <Name>
```

4. Activate virtual environment en windows(en terminal de bash):
```bash
source env/Scripts/activate
```
`source` ejecuta scripts de bash fuera de los entornos normales 

.bash para Linux 
.bat para Windows
.ps1 para PowerShell 

4.1 Deactivate virtual environment
```bash
deactivate
```

5. Install ipython dependency(library):
```bash
pip install ipython

pip --version
```

5.1. Uninstall ipython
```bash
pip uninstall ipython
```

6. Execute ipyhton
```bash
ipython
```

7. Show project dependencies 
```bash
pip freeze
```

8. Share dependencies of the project
```bash
pip freeze > requeriments.txt
```

> `ipython` crea bloques de codigo o celdas de codigo. 

9. Install dependencies from file, first `python -m venv env` then `source env/Scripts/activate`
```bash
pip install -r requierements.txt 
```

`-r` Va especificar que instale de un archivo.

`Homework` write in a python program: "El profe rifa, lo quiero mucho ❤" con:
    1. asc (ASCII drawings)
    2. colorama (color in console)