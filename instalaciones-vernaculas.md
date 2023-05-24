![Header](ryder_isologotipos.png)

***

# PIS - Instalaciones vernáculas (Clásicas)

## Índice

* [1. Descarga de los repositorios](#1-descarga-de-los-repositorios)
* [2. Setup pis-web](#2-setup-pis-web)
* [3. Setup pis-dash](#3-setup-pis-dash)

***


### 1. Descarga de los repositorios

La instalación requiere descargar los 3 repositorios.

```bash
$ cd example

example/:$ git clone https://github.com/DemocraciaEnRed/pis web
example/:$ git clone https://github.com/DemocraciaEnRed/pis-dash
example/:$ git clone https://github.com/DemocraciaEnRed/pis-shiny
```

Una vez hecho, hay que hacer un "Setup" de cada una de los repositorios que acabamos de clonar.

### 2. Setup pis-web

> #### ⚠️ Prerequisitos
> 
> Este entorno virtual requiere de:
> - [Python 3](https://www.python.org/)
> - [pip](https://www.pypi.org/)
> - [virtualenv](https://pypi.org/project/virtualenv/)

Abrí una terminal del sistema en el directorio raiz del proyecto, creá el entorno virtual, activalo, instalá las dependencias del proyecto y ejecutá la plataforma

```bash
$ cd web
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ python main.py
```

#### Ejecución

Abrí una terminal del sistema en el directorio raiz del proyecto, activá el entorno virtual y ejecutá la plataforma

```bash
$ source env/bin/activate
$ python main.py
```



### 3. Setup pis-dash

> #### ⚠️ Prerequisitos
> 
> Este entorno virtual requiere de:
> - [Python 3](https://www.python.org/)
> - [pip](https://www.pypi.org/)
> - [virtualenv](https://pypi.org/project/virtualenv/)

#### Instalación

Abrí una terminal del sistema en el directorio raiz del proyecto, creá el entorno virtual, activalo, instalá las dependencias del proyecto y ejecutá la plataforma

```bash
$ pis-dash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ python main.py
```

#### Ejecución

Abrí una terminal del sistema en el directorio raiz del proyecto, activá el entorno virtual y ejecutá la plataforma


```bash
$ source env/bin/activate
$ python main.py
```