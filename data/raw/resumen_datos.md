# Análisis de Datos Primitivos del Archivo: Paper1_WebData_Final.csv

Este documento resume el análisis de los datos primitivos extraídos del archivo `Paper1_WebData_Final.csv`.

## 1. Información General del Archivo

*   **Ruta del Archivo:** `C:\Users\USUARIO\ing_datos\data\raw\Paper1_WebData_Final.csv`
*   **Tamaño del Archivo:** Aproximadamente 117.89 MB

## 2. Estructura del Conjunto de Datos

*   **Número de Filas:** 1,114,966
*   **Número de Columnas:** 21

### Columnas y Tipos de Datos

| Nombre de Columna | Tipo de Dato Inferido                               |
| :---------------- | :-------------------------------------------------- |
| `test_date`       | Fecha (en formato `DD-MON-YYYY`)                    |
| `nid`             | Numérico (Entero)                                   |
| `L500k` - `R8k`   | Numérico (Entero)                                   |
| `gender`          | Categórico (Texto, ej: 'M')                         |
| `naics`           | Categórico (Puede ser Numérico o un Código)         |
| `age_group`       | Categórico (Numérico)                               |
| `region`          | Categórico (Texto, ej: 'MA')                        |
| `NAICS_descr`     | Texto (Descripción de la categoría NAICS)           |

## 3. Rango de Fechas

*   **Fecha Mínima:** 01 de enero de 2000
*   **Fecha Máxima:** 31 de diciembre de 2008

## 4. Distribución de Datos Categóricos

### Distribución de Género (`gender`)
| Género | Cantidad |
| :--- | :--- |
| M | 864,130 |
| F | 247,592 |
| (vacío) | 3,244 |

### Distribución por Grupo de Edad (`age_group`)
| Grupo de Edad | Cantidad |
| :--- | :--- |
| 3 | 289,422 |
| 2 | 269,652 |
| 4 | 250,762 |
| 1 | 190,897 |
| 5 | 114,233 |

### Distribución por Región (`region`)
| Región | Cantidad |
| :--- | :--- |
| MW | 525,090 |
| MA | 203,117 |
| WE | 181,887 |
| SO | 151,734 |
| (vacío) | 28,056 |
| SW | 16,689 |
| NE | 8,393 |

## 5. Muestra de Datos

A continuación se muestran las primeras 20 líneas del archivo:

```csv
test_date,nid,L500k,L1k,L2k,L3k,L4k,L6k,L8k,R500k,R1k,R2k,R3k,R4k,R6k,R8k,gender,naics,age_group,region,NAICS_descr
12-FEB-2007,1,10,5,5,15,5,0,20,20,20,10,10,25,30,45,M,331512,4,MA,Steel Investment Foundries
29-FEB-2008,2,15,5,15,20,20,15,15,10,0,10,15,30,20,15,M,331512,3,MA,Steel Investment Foundries
08-FEB-2006,3,25,20,15,20,35,25,15,20,20,10,15,40,30,30,M,331512,3,MA,Steel Investment Foundries
29-FEB-2008,6,10,10,10,35,50,30,10,10,10,5,30,35,25,20,M,331512,4,MA,Steel Investment Foundries
08-FEB-2006,8,15,15,5,15,45,30,20,15,15,5,40,50,20,5,M,331512,3,MA,Steel Investment Foundries
29-FEB-2008,9,10,5,0,5,15,15,15,5,0,5,5,5,5,20,M,331512,3,MA,Steel Investment Foundries
29-FEB-2008,10,5,0,5,5,5,10,0,10,5,5,5,5,5,0,M,331512,2,MA,Steel Investment Foundries
29-FEB-2008,11,30,20,25,60,60,60,30,25,20,35,65,65,70,50,M,331512,5,MA,Steel Investment Foundries
29-FEB-2008,12,15,10,5,5,35,20,5,10,15,5,25,40,10,20,M,331512,3,MA,Steel Investment Foundries
08-FEB-2005,13,10,5,10,45,50,35,30,10,10,10,10,20,5,20,M,331512,5,MA,Steel Investment Foundries
29-FEB-2008,14,15,5,10,55,60,75,75,15,5,20,65,65,75,80,M,331512,5,MA,Steel Investment Foundries
29-FEB-2008,15,15,15,15,30,60,45,15,20,10,5,35,45,60,25,M,331512,4,MA,Steel Investment Foundries
29-FEB-2008,17,15,10,5,10,40,20,10,15,5,0,20,5,25,5,M,331512,2,MA,Steel Investment Foundries
08-FEB-2006,18,10,10,5,35,40,35,10,10,5,0,10,20,30,10,M,331512,2,MA,Steel Investment Foundries
12-FEB-2007,20,15,5,10,50,50,15,20,15,10,10,35,50,15,10,M,331512,4,MA,Steel Investment Foundries
22-FEB-2006,21,5,0,5,20,10,25,0,5,0,0,5,5,15,10,M,331512,4,MA,Steel Investment Foundries
29-FEB-2008,22,15,5,5,15,15,40,15,10,10,5,10,15,20,20,M,331512,4,MA,Steel Investment Foundries
29-FEB-2008,23,10,10,5,5,20,20,15,10,5,0,5,30,10,15,M,331512,4,MA,Steel Investment Foundries
22-FEB-2006,24,5,0,0,0,5,10,0,0,0,0,0,10,0,5,M,331512,3,MA,Steel Investment Foundries
```