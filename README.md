
# Computer Vision – CEIA UBA

### Trabajos Prácticos de la materia Computer Vision (CEIA - UBA)

## Integrantes del Grupo
- Agustin Maglione  
- Juan Cruz Becerra  

Este repositorio contiene las entregas de los Trabajos Prácticos (TP1, TP2 y TP3) de la materia Computer Vision del posgrado CEIA (UBA).  
Cada trabajo práctico se encuentra organizado en su propio directorio, mientras que las dependencias del proyecto se administran de manera centralizada utilizando uv.

---

## Estructura del Repositorio

    COMPUTER_VISION/
    ├── TP_1/
    │   ├── assets/               
    │   └── tp1_cv.ipynb       
    ├── TP_2/
    │   └── ...                  
    ├── TP_3/
    │   └── ...                  
    ├── pyproject.toml           
    ├── uv.lock                  
    └── README.md                

---

## Instalación y Configuración del Proyecto con `uv`

Para preparar el entorno del proyecto, ejecutar en la raíz del repositorio:

    uv sync

Esto instalará todas las dependencias definidas en el archivo pyproject.toml.

Si es necesario agregar nuevas dependencias:

    uv add nombre-paquete

Ejemplo:

    uv add opencv-python

---
