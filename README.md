# Análisis de Asistencia de Personal

Proyecto de análisis de datos desarrollado en Python para evaluar indicadores de asistencia de personal durante marzo de 2024.

El objetivo es transformar un conjunto de datos operacionales en información útil para apoyar la toma de decisiones mediante limpieza de datos, análisis exploratorio, cálculo de indicadores y visualización de resultados.
NOTA: Se aleatorizaron los datos personales para poder presentarlo de manera pública, de esta manera no filtrar datos de empresas y/o trabajadores, cualquier parecido con la realidad es pura coincidencia.

---

## Objetivos
Responder las siguientes preguntas de negocio:
- ¿Cuál es el porcentaje total de ausentismo del mes?
- ¿Existe diferencia en el ausentismo entre los turnos 4x3 y 7x7?
- ¿Quiénes son los cinco trabajadores con mayor cantidad de ausencias?
- ¿Los conductores presentan un patrón de ausentismo distinto al resto del personal?

---

## Tecnologías utilizadas
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- OpenPyXL

---

## Dataset
El proyecto trabaja sobre un archivo Excel con registros diarios de asistencia correspondientes al mes de marzo de 2024.
Entre las variables analizadas se encuentran:

- ID del trabajador
- Nombre
- Estado de asistencia
- Turno
- Cargo
- Condición de conductor
- Fecha

> El dataset original no se incluye por motivos de privacidad.

---

## Proceso de análisis

### 1. Carga de datos
Se importa la información desde un archivo Excel utilizando Pandas.

### 2. Limpieza de datos
Durante esta etapa se realizaron tareas como:

- Identificación de valores nulos
- Corrección de inconsistencias en nombres de categorías
- Normalización de estados de asistencia
- Validación de registros

### 3. Análisis exploratorio
Se calcularon indicadores como:

- Porcentaje general de ausentismo
- Distribución por tipo de ausencia
- Comparación entre turnos
- Ranking de trabajadores con mayor ausentismo
- Comparación entre conductores y personal general

### 4. Visualización
Los resultados fueron representados mediante gráficos utilizando Matplotlib para facilitar la interpretación de los indicadores.

---

## Principales resultados
El análisis permitió identificar:

- Porcentaje total de ausentismo del período.
- Distribución de ausencias según su causa.
- Diferencias entre turnos de trabajo.
- Trabajadores con mayor frecuencia de ausencias.
- Comparación del comportamiento de conductores respecto del resto del personal.

---

## Estructura del proyecto

```
Analisis-Asistencia-RRHH
│
├── proyecto_01_rrll.ipynb
├── README.md
├── requirements.txt
├── images
│   ├── ausentismo_general.png
│   ├── ausentismo_turnos.png
│   ├── top5_ausencias.png
│   └── conductores.png
└── data
```

---

## Competencias demostradas

Este proyecto evidencia conocimientos en:
- Limpieza y preparación de datos
- Análisis Exploratorio de Datos (EDA)
- Manipulación de datos con Pandas
- Visualización de información
- Cálculo de indicadores (KPIs)
- Comunicación de resultados mediante gráficos

---

## Próximas mejoras
- Incorporar visualizaciones interactivas con Power BI.
- Automatizar el proceso de carga de datos.
- Exportar reportes en formato PDF.
- Integrar consultas SQL como fuente de datos.
