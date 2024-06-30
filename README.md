# AnomaliasLST-EE

En este repositorio se encuentra todos los elementos necesarios para la Aplicación del api de Google Earth Engine para Python para el cálculo de Anomalías de Temperatura Superficial Terrestre parte del Seminario Internacional sobre Monitoreo Satelital de Incendios Forestales.
- Se recomienda descargar [Miniconda](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe) aunque el Anaconda también es buena opción
- Se puede usar cualquier IDE pero en el Seminario se usará el [Visual Studio Code](https://code.visualstudio.com/download)
## Configuración del Entorno

### Creación de un Nuevo Ambiente de Trabajo

Abre Anaconda Prompt y crea un nuevo ambiente con el siguiente comando:
```bash
conda create -n <nombre_de_ambiente>
```
Ejemplo:
```bash
conda create -n sig
```
Presiona `y` y `ENTER` para confirmar la creación del ambiente.

### Activación del Ambiente de Trabajo

Activa el ambiente recién creado:
```bash
conda activate <nombre_de_ambiente>
```

### Instalación de Librerías Necesarias

Para instalar todas las librerías requeridas, ejecuta el siguiente comando:
```bash
conda install -c conda-forge earthengine-api geopandas seaborn ipykernel
```

### Instalación desde requirements.txt

Si prefieres usar un archivo `requirements.txt` para crear el ambiente, como el que se encuentra en este repositorio:
```bash
conda create --name <nombre_de_ambiente> -c conda-forge --file requirements.txt
```
Asegúrate de que `requirements.txt` contenga todas las dependencias necesarias.

---
