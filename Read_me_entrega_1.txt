Data Set 1 - Prediccion de precio de celulares
Descripción:
El archivo csv contiene 21 columnas. La descripción de cada columna es la siguiente:

   - BATTERY POWER: Duración en mA/h
   - Blue: Si tiene o no Blueth
   - Clock speed: Velocidad del microprocesador
   - Dual SIM: Si tiene o no dual SIM
   - FC: Mega pixeles de la camara frontal
   - four_g: Si tiene 4G o no
   - int_memory: Memoria interna en GB
   - M_deep: grosor en cm
   - mobile_wt: Peso
   - n_cores: Cantidad de cores del proesador
   - pc: Mega pixeles Camara trasera 
   - px_heght: resolucion de altura en pixeles
   - px_width: resolucion de ancho en pixeles
   - RAM: memoria RAM en MB
   - sc_h: alto de la pantalla en cm
   - sc_w: ancho de la pantalla en cm
   - talk_time: duración de la bateria
   - three_g: si tiene o no 3g
   - touch_screen: si tiene touch o no
   - wifi: si tiene o no Wifi
   - Price_Range: Rango de Precios

Posibles Aplicaciones
1. Clasificación de gama de celulares (Rango de precios) segun caracteristicas:

Pixeles cámara / Nucleos / Resolución de pantalla / Velocidad del procesador / Dual sim / RAM. 

Debería hacerse una selección de variables para ver cuales son las mas representativas.

-----------------------------------------------------------------------------------------------------------------------

Data Set 2 - Predicción de potencia generada por celdas solares
Descripción:
El archivo csv contiene 16 columnas. La descripción de cada columna es la siguiente:
- Day or Year: Día del año (0-365)
- Year: Año
- Mounth: Mes
- Day: Día
- First Hour of Period: Hora del día
- is day light: Si hay luz solar (Bool)
- Distance to solar noon: distancia al mediodia solar
- Average temperature (day): Temperatura promedio
- Average wind direction (day): Promedio de direccion del viento
- Average wind speed (day): Pomedio de velocidad del viento
- Sky Cover: Cobertura del cielo
- Visibility: Visibilidad
- Relative Humedity: Humedad Relativa
- Average Wind Speed Period: Promedio de velocidad del viento en ese periodo
- Average Barometric presure: Promedio de presion atmosferica
- Power Generated: Potencia generada

Posibles Aplicaciones
1. Predicción de potencia generada a partir de las siguientes columnas:

Año / Dia del año / Pediodo / y todas las variables climaticas. 

Debería hacerse una selección de variables para ver cuales son las mas representativas.

-----------------------------------------------------------------------------------------------------------------------

Data Set 4 - Clasifición de tweets sobre desastres
Descripción:
El archivo csv contiene 5 columnas. La descripción de cada columna es la siguiente:
- id: Identificador único del tweet
- text: Texto del tweet
- location: Ubicación del tweetero
- keyword: Palabra clave del tweet
- target: Determina si el tweet se refiere a un desastre (accidente, desastre natural, etc.) o no. Valor 1 o 0, respectivamente. 

Posibles Aplicaciones
1. Clasificación de los tweets en desastres o no desastres basado en Procesamiento de Lenguaje Natural (Natural Language 
Processing (NLP)):

Las columnas a utilizar son:

text / target

NOTA: Si bien se requería que las bases de datos tuvieran al menos 15 columnas, en este caso con las columnas text 
y target es sufieicnet para realizar la clasificación. Siendo una aplicación típica de NLP, me pareció pertinente 
agregarla para poder abordar dicho tema. 