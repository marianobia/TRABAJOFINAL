TRABAJO FINAL - PROGRAMA

El programa arranca presentando 3 opciones:

1-ACTUALIZAR DATOS
2-VISUALIZAR DATOS
3-ULTIMO CIERRE

Al utilizarse por primera vez se debe iniciar por la opción 1.

1- ACTUALIZAR DATOS

Primero el programa solicitará que ingrese el codigo del ticker.
Seguidamente la fecha dónde se inicará el rango a guardar y luego la fecha final para el período.
Seguidamente el programa consultará a la API Polygon.io, creará la base de datos y guardará la información solicitada.
Tener en cuenta que están disponibles para cada ticker los datos de cada jornada bursátil hasta dos años hacía atrás contado desde la fecha actual.
Siempre considerando estos períodos no hay limitación para la solicitud. En caso de que ya hubiera guardado datos del ticker requerido y el nuevo pedido incluyera datos de un lapso ya guardado para el mismo ticker, el programa solo almacenará en la base de datos la información que no posee y descartará la ya contenida.

2- VISUALIZAR DATOS

Esta opción lleva a otras dos subopciones

2.1 - VISUALIZAR DATOS GUARDADOS

Primero aparecerá la lista de la informacion correspondiente a cada ticker y período de tiempo ya guardado en la base de datos.
Luego el programa solicitará que elija un ticker y un período de tiempo que deberá seleccionarse siempre respetando los parámetros de los datos guardados.
Finalmente el programa entregará un listado de los valores de cada jornada bursátil para el ticker y período solicitado.

2.2 - GRAFICAR UN TICKER

Primero aparecerá la lista de la informacion correspondiente a cada ticker y período de tiempo ya guardado en la base de datos.
Luego el programa solicitará que elija un ticker y un período de tiempo que deberá seleccionarse siempre respetando los parámetros de los datos guardados.

En ese momento el programa brindará 3 subopciones

2.2.1 - COTIZACIONES

El programa graficará los datos del valor del ticker para los parámetros PROMEDIO, APERTURA, CIERRE, MÁXIMO Y MÍNIMO para cada jornada bursátil dentro del período solicitado.

2.2.2 - VOLÚMEN OPERADO

El programa graficará los datos del VOLÚMEN OPERADO para cada jornada bursátil dentro del período solicitado.

2.2.3 - CANT. TRANSACCIONES

El programa graficará los datos de CANTIDAD DE TRANSACCIONES DIARIAS para cada jornada bursátil dentro del período solicitado.

IMPORTANTE: Tener en cuenta que como las solicitudes pueden en dos años superar las 500 jornadas bursátiles el programa cuanto más grande sea el rango del período solicitado más espacia en el eje correspondiente a las fechas los datos mostrados. Esto es debido a que de otra manera 500 fechas escritas en un eje terminarían imprimiéndose una arriba de la otra resultando ilegibles.

3 - ÚLTIMO CIERRE

Está opción es en tiempo real, está siempre disponible ya que no depende de la base de datos.
Proporciona el último cierre de la cotización del ticket en U$D.

 





