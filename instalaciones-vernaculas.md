![Header](ryder_isologotipos.png)

***

# PIS - Instalaciones vernáculas (Clásicas)

## Índice

* [1. Descarga de los repositorios](#1-descarga-de-los-repositorios)
* [2. Setup pis-dash](#2-setup-pis-dash)

***


### 1. Descarga de los repositorios

La instalación requiere descargar los 3 repositorios.

```bash
$ cd example

example/:$ git clone https://github.com/reflejar/pis
example/:$ git clone https://github.com/reflejar/pis-dash
example/:$ git clone https://github.com/reflejar/pis-shiny
```

Una vez hecho, hay que hacer un "Setup" de cada una de los repositorios que acabamos de clonar.


### 2. Setup pis-dash

> #### ⚠️ Prerequisitos
> 
> Este entorno virtual requiere de:
> - [Python 3](https://www.python.org/)
> - [pip](https://www.pypi.org/)
> - [virtualenv](https://pypi.org/project/virtualenv/)

#### Instalación

Abrí una terminal del sistema en el directorio raiz del proyecto, creá el entorno virtual, activalo, instalá las dependencias del proyecto y ejecutá la plataforma

```bash
$ cd web
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ python main.py <tool>
```

tool puede ser alguna de las siguientes opciones:
- mapa_normativo
- indicadores_censos
- ranking_ambiental


#### Ejecución

Abrí una terminal del sistema en el directorio raiz del proyecto, activá el entorno virtual y ejecutá la plataforma

```bash
$ source env/bin/activate
$ python main.py <tool>
```
