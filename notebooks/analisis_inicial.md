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

En esta sección se identificarán los indicadores presentes en el archivo FAOSTAT según la columna *Product*. 
Estos indicadores incluyen, por ejemplo:

- Cost of a healthy diet (CoHD)
- Cost of a healthy diet in PPP dollars
- Prevalence of unaffordability (PUA)
- Number of people unable to afford a healthy diet (NUA)
