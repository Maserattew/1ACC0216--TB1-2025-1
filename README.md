# 1ACC0216--TB1-2025-1

![image](https://github.com/user-attachments/assets/61a731be-baf1-42a2-87e1-b8e63343da40)


1ACC0216-2510-256 - Fundamentos de Data Science · TB1

2025 · Ciencia de la Computación

Profesora: Nérida Isabel Manrique Tunque

Alumnos:

Alzamora Gonzales Leonel - U20231c427@upc.edu.pe

Fabian Marcelo, Rojas Cuadros - U202218498@upc.edu.pe

Avalos Sánchez, César Gabriel - U202310307@upc.edu.pe

Rivas Pinto, Piero Aldair - U202122405@upc.edu.pe

# Análisis Exploratorio de Datos (EDA): Hotel Booking Demand
## Índice
1. [Objetivo del proyecto](#objetivo-del-proyecto)  
2. [Descripción del dataset](#descripción-del-dataset)  
   2.1. [Variables categóricas](#variables-categóricas)  
   2.2. [Variables numéricas](#variables-numéricas)  
   2.3. [Variables de fecha](#variables-de-fecha)  
3. [Conclusiones clave](#conclusiones-clave)  
4. [icencia](#licencia)

## 1. Objetivo del proyecto

El objetivo de este proyecto es llevar a cabo un análisis exploratorio de datos (EDA) utilizando un conjunto de datos que recopila información sobre reservas en hoteles de ciudad y resorts. Mediante este análisis, se pretende identificar patrones relevantes, detectar tendencias importantes y examinar posibles relaciones entre las distintas variables incluidas en los datos.

---
## 2. Descripción del dataset

El dataset reúne información detallada sobre reservas de hotel, incluyendo datos del cliente, categoría de habitación, fechas de ingreso, duración de la estancia y otros elementos clave de cada transacción. Cada fila corresponde a una reserva individual e incluye múltiples atributos que permiten analizar los factores que afectan la demanda en el sector hotelero.

### 2.1. Variables categóricas

Incluyen datos como:
- Tipo de hotel
- Canal de reserva
- Tipo de habitación
- País de origen, etc.

### 2.2. Variables numéricas

Incluyen:
- Número de adultos y niños
- Días de estancia
- Número de reservas canceladas, etc.

### 2.3. Variables de fecha

Incluyen:
- Fecha de llegada
- Año, mes y día
- Semana del año

---

## 3. Conclusiones clave

- La mayoría de los clientes prefieren el City Hotel, con 53,422 reservas, frente a las 33,522 del Resort Hotel. Por lo que podemos decir que existe una preferencia por los hoteles en ubicaciones urbanas, probablemente por la cercanía a más servicios.
- De los datos se observa una demanda con sostenido crecimiento en el tiempo, y con esto la evolución del negocio hotelero. Lo que muestra que las estrategias de negocios, ajustes en logística o mejora de la atención, aplicadas por los hoteles están funcionando.
- Durante los meses de verano(Junio, Julio,Agosto) hay una alta demanda, mientras que invierno y primavera/otoño por otro lado muestran una demanda baja y media respectivamente. Las promociones y estrategias se ajustan a la estación del año.
- La duración de las estancias varían dependiendo el tipo de hotel, en los resorts son más prolongadas, 4.5 días en promedio, y en city hotel 3 días en promedio.
- El city hotel atrae mayor cantidad de familias, si bien los resort también las reciben, probablemente en el city hotel las familias encuentran más accesibilidad para viajes cortos, esto se ve en que el city hotel has recibido entre 5000 y 5300 reservas versus resort que recibe entre 3700 y 400 reservas de familias.
- La alta demanda que se ve en agosto también puede generar cancelaciones en las reservas debido a cambios de planes o sobre reservas.
- Los canales de distribución influyen en las cancelaciones, se ha notado que canales como Corporate, Direct Y GDS tienen bajas tasas de cancelación mientras que TA/TO y los undefined presentan mayor riesgo.

---

## Licencia

El presente trabajo está publicado bajo la licencia [MIT](LICENSE).
