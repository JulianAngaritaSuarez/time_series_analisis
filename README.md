# Análisis de Series de Tiempo para Datos de Graduados

Este proyecto contiene el código para el análisis, la visualización, la exploración de datos y el modelo de propuesto para la serie de tiempo de graduados de la UNAL del programa de estadística - sede Bogotá.

## Estructura del Proyecto

```text
.
├── data/
│   └── data_graduados.csv
├── venv/
├── .git/
├── README.md
├── requirements.txt
└── *.py
```

## Conjunto de Datos

La aplicación utiliza el archivo:

```text
data/data_graduados.csv
```

Este conjunto de datos contiene la información necesaria para realizar los análisis y visualizaciones implementados en el proyecto.

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/JulianAngaritaSuarez/time_series_analisis.git
cd time_series_analisis
```

### 2. Crear un entorno virtual

```bash
python -m venv venv
```

### 3. Activar el entorno virtual

#### Linux

```bash
source venv/bin/activate
```

#### Windows

```bash
venv\Scripts\activate
```

### 4. Instalar las dependencias

```bash
pip install -r requirements.txt
```

## Directorio de Datos

```text
data/
└── data_graduados.csv
```

La aplicación espera encontrar el archivo `data_graduados.csv` dentro de la carpeta `data`.

## Requisitos

* Python 3.10 o superior.
* Dependencias especificadas en `requirements.txt`.

## Observaciones


* El archivo de datos debe mantenerse dentro de la carpeta `data`.

## Autor

Julian Angarita Suárez
Manuela Velasquez Zapata


## Licencia

Proyecto desarrollado con fines académicos y de investigación.
