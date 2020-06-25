# Entornos Virtuales de Python
El presente documento muestra los comandos más usados respecto a los entornos virtuales en **Python**.

### Programas necesarios para Entornos Virtuales
Se requiere es pip y python3-venv:
```
$ sudo apt-get install python3-pip
$ sudo apt-get install python3-venv
```

### Como crear un Entornos Virtuales
```
$ python3 -m nombre_EV directorio_destino/nombre_EV
```

### Como tratar las dependencias
Para ver las dependencias que tenemos en el entorno virtual debemos tenerlo activado, y luego usar:
```
$ pip3 freeze
```

Estos requerimientos los podemos incluir de manera automática en un archivo
```
$ pip3 freeze > requirements.txt
```

Para luego instalar los requerimientos
```
$ pip3 install -r requirements.txt
```

### Como manejar los entornos virtuales
Para activar un entorno virtual
```
$ source ruta/entorno_virtual/bin/activate
```

