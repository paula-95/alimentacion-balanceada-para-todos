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

### Interpretación de los indicadores

Los valores reportados por FAOSTAT para Colombia en 2024 permiten realizar un análisis preliminar sobre el costo y la asequibilidad de una dieta saludable:

1. **Costo en moneda local (7561 pesos por persona por día)**  
   Este valor indica que, para que una persona pueda acceder a una dieta saludable, necesita aproximadamente 7561 pesos diarios. Para un hogar de cuatro personas, esto equivaldría a más de 900 000 pesos mensuales solo en alimentación saludable. Esto sugiere que el costo puede representar una carga significativa para muchos hogares.

2. **Costo en dólares internacionales PPP (4.67 Int$ por persona por día)**  
   Esta medida permite comparar el costo de una dieta saludable entre países. Un valor de 4.67 Int$ ubica a Colombia en un nivel de costo moderado-alto dentro de la región. Aunque el valor parece bajo en dólares, la capacidad adquisitiva interna es lo que determina la asequibilidad real.

3. **Prevalencia de no asequibilidad (36.1%)**  
   Más de un tercio de la población colombiana no puede pagar una dieta saludable. Este porcentaje refleja una brecha importante entre el costo de una alimentación adecuada y los ingresos disponibles de los hogares.

4. **Número de personas que no pueden pagar una dieta saludable (19.1 millones)**  
   Este valor cuantifica la magnitud del problema: casi 20 millones de personas en Colombia no tienen los recursos económicos suficientes para acceder a una dieta saludable. Esto tiene implicaciones directas en nutrición, salud pública y desigualdad.

En conjunto, estos indicadores muestran que, aunque el costo absoluto de una dieta saludable puede parecer moderado, la asequibilidad es un desafío significativo para una parte importante de la población colombiana.

## 7. Visualizaciones

En esta sección se incluirán gráficos que permitan representar de manera clara los indicadores analizados. 
Las visualizaciones ayudarán a:

- Comparar los costos en LCU y en dólares PPP
- Observar la magnitud de la prevalencia de no asequibilidad (PUA)
- Representar el número de personas que no pueden pagar una dieta saludable (NUA)
- Facilitar la interpretación de los resultados para audiencias no técnicas

Los gráficos se generarán en pasos posteriores.

### Gráfico 1: Comparación del costo de una dieta saludable (LCU vs PPP)

Este gráfico mostrará la diferencia entre:

- Cost of a healthy diet (CoHD), LCU per person per day
- Cost of a healthy diet (CoHD), PPP dollar per person per day

El objetivo es visualizar cómo cambia el costo dependiendo de la unidad de medida.

