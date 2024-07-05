# Sign Language

## Integrantes:
- MAYCOL ALEXANDER CANAVERI TACO
- JAIME MATEO GUTIERREZ MUÑOZ
- JHON BERLY TAYPE ALCCACCAHUA 
- LEONARDO ALONSO RAMIREZ QUIROZ

![Algoritmo_Genetico](https://hackster.imgix.net/uploads/attachments/953859/uploads2ftmp2f00dcd17f-b21e-4f3c-a696-e51994a927962fimages_abc1280x960_WFRTiqBVKE.png?auto=compress&w=900&h=675&fit=min&fm=jpg)

## Windows

Primero asegurarnos de tener instalado Python, para ello pueden recurrir a la pagina oficial para descargarlo e intalarlo.

![Python](https://www.python.org/)

## MacOS

No se, no tengo 

## Linux

De igual manera nos aseguramos primero de tener python instaldo, para ello usamos el siguiente comando:

```bash
python --version
```

Si nos da error, consideremos instalar python ya sea desde la pagina oficial ![Python](https://www.python.org/) o bien usando el siguiente comando dependiendo de la distribucion que use.

### Ubuntu / Debian

```bash
sudo apt-get update
sudo apt-get install python3 python3-pip
```

### Arch/Linux

```bash
sudo pacman -Syu
sudo pacman -S python3 python3-pip
```

Para ejecutar el proyecto se recomiendo hacer uso de un entorno virtual de python para mantener todo limpio y en caso de eliminar el el directorio, eliminarlo con todas las dependencias instaladas.

Para ello ejecutamos el siguiente comando dentro del directorio del repositoio clonado.

```bash
python3 -m venv .venv
```

Seguido activamos el entorno virtual, con el siguiente comando:

macOS/Linux
```bash
. .venv/bin/activate
```

Windows
```bash
.venv\Scripts\activate
```

Continuando usaremos el siguiente comando para instalar las dependencias
```bash
pip install -r requirements.txt
```

Ahora ejecutamos el codigo

```bash
python3 inference_classifier.py
```

y listo.
