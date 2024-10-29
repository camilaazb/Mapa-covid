# Mapa-covid
HTML: https://camilaazb.github.io/Mapa-covid/MapeoCovid.html

DATA: https://www.datosabiertos.gob.pe/dataset/casos-positivos-por-covid-19-ministerio-de-salud-minsa/resource/690e57a6-a465-47d8-86fd

## Descripción 
Este proyecto es una visualización interactiva desarrollada en HTML que muestra datos de COVID-19 a través de un mapa. Utiliza un conjunto de variables claves para analizar la situación de la pandemia en diferentes regiones.

**Variables incluidas**:
FECHA_CORTE: Fecha de corte de la información disponible.
UUID: ID único de cada persona confirmada como caso positivo de COVID-19.
UBIGEO: Código de Ubicación Geográfica, representado como "DDppdd" (Departamento, Provincia, Distrito) de acuerdo a la clasificación del INEI.
DEPARTAMENTO: Departamento donde reside la persona con un caso positivo de COVID-19.
PROVINCIA: Provincia de residencia de la persona con un caso positivo.
DISTRITO: Distrito de residencia de la persona con un caso positivo.
METODODX: Método de diagnóstico de laboratorio utilizado para la prueba de COVID-19 (por ejemplo, prueba molecular o rápida).
EDAD: Edad de la persona confirmada como caso positivo de COVID-19.
SEXO: Sexo de la persona (Masculino/Femenino).
FECHA_RESULTADO: Fecha en la que se obtuvo el resultado de la prueba de COVID-19.

*Características*
Se pueden explorar y analizar los datos por departamento, provincia y distrito. Los datos permiten segmentar por edad, sexo y método de diagnóstico. En este caso, se segmento por metodo de diagnóstico, es decir por tipo de prueba de descarte. 

**Índice de Moran**: Calculamos el índice de Moran global, que reveló una débil autocorrelación espacial positiva ((I = 0.19)), sugiriendo que áreas con altas (o bajas) tasas de casos tienden a estar cerca, pero esta relación no es fuerte.

**Análisis LISA**: Identificamos patrones locales de autocorrelación:

HH (Alto-Alto): Clusters de alta incidencia, posibles focos de contagio.
LL (Bajo-Bajo): Zonas de baja incidencia.
HL (Alto-Bajo) y LH (Bajo-Alto): Outliers espaciales, áreas con tasas opuestas a sus vecinas.
Visualización de Clusters: Los mapas LISA ayudan a ubicar espacialmente estas áreas críticas para la toma de decisiones de salud pública.

![image](https://github.com/user-attachments/assets/2a56ee84-8284-4889-86aa-667d508e0dbc)


**LISA Bivariado**: Evaluamos la relación espacial entre los casos de COVID-19 en 2021 y 2022, identificando áreas donde la incidencia se mantuvo alta (HH) o baja (LL), lo cual es útil para estrategias de salud pública enfocadas en reducir la transmisión.

![image](https://github.com/user-attachments/assets/c819e204-6bee-4d8a-b4b8-dfcb94ceed69)
![image](https://github.com/user-attachments/assets/d37f1eba-357c-410c-9e5e-eb3983011bd6)




