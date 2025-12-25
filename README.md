# Python Data Pipeline: Automated Cleaning & Reporting

## Descripción
Este proyecto es una solución de automatización diseñada para optimizar el flujo de trabajo entre la captura de datos crudos y la generación de reportes listos para la toma de decisiones. 

Como Ingeniero con experiencia en sistemas críticos, he diseñado este script enfocándome en la **robustez, el manejo de errores y la integridad de los datos**, asegurando que procesos administrativos u operativos manuales se reduzcan de horas a segundos.

## Funcionalidades Clave
- **Ingesta Automatizada:** Lectura masiva de archivos CSV desde directorios configurables.
- **Validación de Integridad:** Identificación de archivos vacíos, columnas faltantes y gestión de valores nulos (NaN).
- **Limpieza y Normalización:** - Estandarización de formatos de texto (Case normalization).
  - Conversión inteligente de tipos de datos (Parsing de fechas y números).
  - Eliminación de registros duplicados o corruptos.
- **Motor de Métricas:** Cálculo automático de promedios, totales y conteos específicos según reglas de negocio.
- **Generación de Entregables:** Salida dual de un dataset limpio (CSV) y un informe ejecutivo resumen (TXT/CSV).

## Stack Tecnológico
- **Lenguaje:** Python 3.x
- **Librerías principales:** - `Pandas`: Para la manipulación y análisis de estructuras de datos.
  - `Logging`: Para el rastreo de eventos y depuración profesional.
  - `Os/Pathlib`: Para la gestión eficiente del sistema de archivos.

## 📁 Estructura del Proyecto
```text
auto-data-engine/
│
├── data/
│   ├── input/          # Archivos CSV crudos a procesar
│   └── output/         # Resultados: CSV limpio y Reportes
│
├── src/
│   ├── main.py         # Punto de entrada del script
│   └── utils.py        # Funciones auxiliares de limpieza y cálculo
│
├── requirements.txt    # Dependencias del proyecto
└── README.md           # Documentación
