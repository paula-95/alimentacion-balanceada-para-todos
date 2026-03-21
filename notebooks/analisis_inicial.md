# Análisis inicial de los datos FAOSTAT (CoAHD)

Este documento contiene el análisis paso a paso del archivo FAOSTAT sobre el costo y la asequibilidad de una dieta saludable en Colombia.

## 1. Cargar y revisar el archivo CSV

En esta sección revisaremos:
- Número de filas
- Columnas disponibles
- Tipos de datos
- Primeras observaciones
## 2. Descripción del archivo FAOSTAT

El archivo contiene información del dominio CoAHD (Costo y asequibilidad de una dieta saludable). 
Incluye indicadores como:

- Número de personas que no pueden pagar una dieta saludable (NUA)
- Prevalencia de no asequibilidad (PUA, %)
- Costo de una dieta saludable en moneda local (CoHD)
- Costo de una dieta saludable en dólares internacionales PPP
- Año de referencia
- País (Colombia)

Este paso permite entender qué variables están disponibles antes de comenzar el análisis.

## 3. Columnas del archivo

En esta sección se listarán las columnas presentes en el archivo CSV y una breve descripción de cada una. Esto permitirá entender qué información está disponible para el análisis.


Las columnas presentes en el archivo FAOSTAT son: 
-Scope Code
-Scope	
-Area Code (M49)
-Area	
-Element Code
-Item	
-Product Code
-Product Year Code
-Year	
-Edition	
-Unity	
-Value	
-Symbol	
-Description of the Symbol
## 4. Indicadores disponibles

Los indicadores presentes en el archivo FAOSTAT (columna Product) son:

- Cost of a healthy diet (CoHD), LCU per person per day
- Cost of a healthy diet (CoHD), PPP dollar per person per day
- Prevalence of unaffordability (PUA), percent
- Number of people unable to afford a healthy diet (NUA), million

Estos indicadores permiten analizar el costo y la asequibilidad de una dieta saludable en Colombia.

## 5. Revisión de los valores reportados

En esta sección se revisarán los valores numéricos asociados a cada indicador, según la columna *Value*. 
Esto permitirá identificar:

- El costo de una dieta saludable en moneda local (LCU)
- El costo en dólares internacionales PPP
- La prevalencia de no asequibilidad (PUA)
- El número de personas que no pueden pagar una dieta saludable (NUA)

En el siguiente paso se listarán los valores exactos presentes en el archivo.

## 6. Análisis inicial de los indicadores

En esta sección se realizará una interpretación de los valores reportados, con el fin de comprender:

- El nivel de costo de una dieta saludable en Colombia
- La asequibilidad para la población
- La magnitud del número de personas afectadas
- La relación entre los indicadores (CoHD, PUA, NUA)

Este análisis permitirá contextualizar los resultados y preparar el terreno para visualizaciones y conclusiones posteriores.

