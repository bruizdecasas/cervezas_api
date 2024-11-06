# Cervezas API

Este proyecto permite manejar y analizar datos sobre cervezas, guardando información en un archivo CSV para disponer de un backup si es necesario.

## Archivos de Proyecto

- `cervezas.ipynb`: Contiene el código principal para el análisis y manipulación de datos de cervezas.
- `cervezas_final.csv`: Archivo de backup donde se guarda la información procesada en formato CSV.

## Funcionalidades

1. **Carga de Datos**: 
   - Se cargan los datos desde diversas fuentes, y se realiza una limpieza inicial.

2. **Manipulación de Datos**: 
   - A través de `pandas`, los datos de cervezas se filtran, transforman y analizan, para obtener información útil.

3. **Guardado de Resultados**:
   - El DataFrame resultante se guarda en `cervezas_final.csv`, con el fin de tener un backup accesible en cualquier momento.

## Requisitos

- **Python 3.x**
- **Librerías**:
  - `pandas`
  - `numpy`
  
Puedes instalarlas ejecutando:
```bash
pip install pandas numpy
```
Si deseas contribuir a este proyecto, por favor, realiza un fork del repositorio, crea una rama para tus cambios y abre un Pull Request.

