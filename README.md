# EST46111 Fundamentos de Estadística (Ciencia de Datos)

## Análisis de datos

Este repositorio contiene los datos que analisamos en el curso Fundamentos de Estadística (Otoño 2016).

### Análisis en clase

En clase analizamos diferentes datos:
- **EST46111_NFLDraft_Data.RData**.- Datos acerca del desempeño de jugadores de la NFL
- **EST46111_DatosMexico_Data.RData**.- Datos de salarios e inflación en México (desagregado por entidades a través del tiempo)
- **EST46111_Donohue&Levitt_Data.RData**.- Datos acerca de la incidencia de la legalización de abortos sobre la incidencia criminal en los EEUU

### Proyecto Final

En el proyecto final, analizaremos los datos **EST46111_MEXBaseline_Data.RData**, los cuales corresponden a 

## Carga de datos en R

Para cargar los datos en R utiliza las siguientes líneas de comando:

```
library(repmis)

source_data("https://github.com/jcmartinezovando/est46111_datos/blob/master/EST46111_NFLDraft_Data.RData?raw=true")

source_data("https://github.com/jcmartinezovando/est46111_datos/blob/master/EST46111_DatosMexico_Data.RData?raw=true")

source_data("https://github.com/jcmartinezovando/est46111_datos/blob/master/EST46111_Donohue&Levitt_Data.RData?raw=true")

source_data("https://github.com/jcmartinezovando/est46111_datos/blob/master/EST46111_MEXBaseline_Data.RData?raw=true")
```

Para cargar las funciones en R usen:

```
source("https://raw.githubusercontent.com/jcmartinezovando/est46111_datos/master/BayLinReg.R")

source("https://raw.githubusercontent.com/jcmartinezovando/est46111_datos/master/BayHierLinReg.R")
```
