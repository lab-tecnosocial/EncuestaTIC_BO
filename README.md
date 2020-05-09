# EncuestaTIC_BO
Datos en formato abierto de la Encuesta TIC de 2017 en Bolivia. 

Los datos se encuentran en la carpeta `csv`, con el siguiente contenido:

|Nombre|Contenido|Uso principal|
|------|---------|-------------|
|eti   | Datos etiquetados| Para Calc, Excel o Google Sheets|
|sem   | Datos con semántica vía asociación de base con diccionario| Para R o Python|
|val   | Datos con sólo valores, pero acompañados con tablas de etiqeutas de variables y valores| Para otros|

Estructura de la carpeta `csv`:
```
├── eti
│   └── datos_etiquetas_todo.csv
├── sem
│   ├── base.csv
│   └── dic.csv
└── val
    ├── datos_valores.csv
    ├── etiquetas_valores.csv
    └── etiquetas_variables.csv
```
