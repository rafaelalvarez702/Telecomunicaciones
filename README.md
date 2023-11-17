# Proyecto Individual - 02-Telecomunicaciones #

## Introducción⚠️🚧##

Este proyecto se realizó simulando ser un Analista de Datos de una empresa prestadora de servicios de telecomunicaciones; que me encarga  la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considerando que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.


Para cumplir con ello, los datos iniciales que se utilizan son derivados de la API de ENACOM  [Data](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/),  

Contexto⚠️🚧
Las telecomunicaciones en Argentina experimentaron un crecimiento significativo en las últimas décadas. El aumento en la demanda de servicios de comunicación, como telefonía móvil e internet, contribuyó a la expansión del mercado. Dicha expansion a contibuido a que las empresas prestadoras de servicios inviertieran en infraestructura, implementaran tecnologias y de esta forma ofrecer mayor y mejor calidad de servicio a sus usuarios.


Desarrollo⚠️🚧
Datos⛔
Para este proyecto se trabajó con la API de ENACOM, para extraer los datos pero dado que la API prsentaba muchos errores a la hora de descargar la informacion los datos se extrajeron directo de la Página oficial de ENACOM en formato csv y exel. Dataset usados en ETL  [Data](https://github.com/rafaelalvarez702/Telecomunicaciones/tree/main/Datos),  



- Proceso de ETL (Extracción, limpieza y carga de datos)se realiza la extracción y limpieza de los datos de los dos dataset obtenidos, a través de la utilización de Pandas y Jupyter Netbook. ETL Eliminando nulos, duplicados, con transformaciones necesarias como cambio en los tipos de datos, eliminación de columnas y unión de las tablas.

- Proceso de EDA (Análisis Exploratorio de los datos)una vez que los datos están limpios, es momento de revisar las relaciones que existen entre las variables numéricas y categóricas de los datasets, encontrar si hay presencia de valores atípicos o anomalías (que no tienen que ser errores necesariamente), y se verificó si hay algún patrón o conocimiento que sirva en un análisis posterior.
- Datos para el EDA [Data](https://github.com/rafaelalvarez702/Telecomunicaciones/tree/main/Datos_EDA),

Análisis de los datos⛔




![image](https://github.com/rafaelalvarez702/Telecomunicaciones/assets/104017553/2c81383e-f6bc-4688-8be2-5dece807f77f)

Vemos como ha sido la penetracion del internet por provincias notando que Capital federal lidera tanto por habitantes como por hogares seguido por la Pampa y Tierra del Fuego, pero tambien es muy notaria la brecha que existe con respecto a Formos, Chaco, San Juan y Santa Cruz, ya que mientras en Capital Federal la penetracion por hogares supera la medida maxima planteada que es un indicativo que hay hogares que tienen mas de una conexion a internet laas otras estan por debajo de la media. 


![image](https://github.com/rafaelalvarez702/Telecomunicaciones/assets/104017553/ce1b7e79-d704-46ed-abf0-895c58e5f80a)


Podemos apreciar el incremento experimentado por cablemodem y Fibra óptica en los ultimos años, estas tecnologias ofrecen mayor eficiencia para conexion a internet por lo que no es de extrañar que los usuarios las escojan de igual forma vemos como ADSL una tecnologia mas antigua a perdido terreno experimentando una contracion en su uso. Es importante señalar que la Fibra óptica es la que ofrece mayor eficiencia y velocidad; su crecimiento puede llegar a superar a cable modem ya que el mismo ENACOM a destinada para el Proyecto de Despliegue y Extensión de la Red Federal de Fibra Óptica (Refefo) en las provincias de Jujuy, Salta y Tucumán a $ 2.500 millones, a través de la Resolución 1550/2023, para incrementa el monto del programa, lanzado en agosto de 2022 y ejecutado por Arsat. Además busca fomentar la inversión pública y privada en la expansión de los servicios.



![image](https://github.com/rafaelalvarez702/Telecomunicaciones/assets/104017553/9e1545e1-8e5a-4e2b-a781-9c934eb68db0)


Las graficas nos muestran la evolucion de la velocidad con el paso del tiempo, destacando que el aumento de conexiones a velocidades mayores en los ultimos años y esto no es de extrañar debido a la observacion del grafico anterior donde las tecnologias nuevas han ganado terreno aumentando de esta forma la velocidad de conexion.

![image](https://github.com/rafaelalvarez702/Telecomunicaciones/assets/104017553/bc53deed-59c7-4eec-adc3-3862d53816f7)


Este grafico se busca establecer una relacion entre los accesos a internet y los servicios conexos, en este sentido podemos notar como el ingreso a internet por cada 100 hogares muestra una fuerte relacion con el ingreso a tv por suscripcion siendo estos dos servicios conjuntos y que dado el crecimiento de conexion cable modem a incrementado su penetracion es un resultado esperado.


![image](https://github.com/rafaelalvarez702/Telecomunicaciones/assets/104017553/03a07c96-4e05-42fb-a7b4-f9a7a0a7fbde)

Al comparar los ingresos por servicios de telecomunicaciones notamos el aumento sostenido en todos los servicios resaltando los ingresos por telefonia movil seguido por los de internet y Tv por suscripcion estando estos dos ultimos ligados a la tecnologia Cable Modem que pudimos apreciar su crecimiento a lo largo del periodo estudiado, con relacion a los ingresos por telofinia movil se resalta que. En el cuarto trimestre de 2022, se registró que el 62,6% de los hogares urbanos tiene acceso a computadora y el 92,1% a internet. Además, los datos muestran que, en la Argentina, 89 de cada 100 personas usan teléfono celular y 88 de cada 100 utilizan internet. Esto segun datos del Instituto Nacional de Estadistica y Censo (INDEC).

Indicadores de Rendimiento Clave KPI⛔
Una vez finalizado el Análisis Exploratorio, se utiliza los dataset 
Propuestas de KPI

incremento de 2% trimestral cada 100 hogares:este KPI me permitiría ver cómo ha cambiado la penetración de internet en los hogares a lo largo del tiempo.

Irecimiento de tecnologias: Este KPI mide el crecimiento en el uso de diferentes tecnologías de internet en Argentina, esto me permitiría ver cómo está evolucionando la infraestructura de internet en la región.



TECNOLOGIAS
![image](https://camo.githubusercontent.com/c55baa119025272015a13e035fdac21ae2544b47d9665dbb0b1a93c84ecb7290/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f56697375616c5f53747564696f5f436f64652d677261793f7374796c653d666c6174266c6f676f3d76697375616c25323073747564696f253230636f6465266c6f676f436f6c6f723d7768697465), ![image](https://camo.githubusercontent.com/143df000a83ba7f1665291aa3fdd254e45dddc7cbf66d63de15812fdbde36058/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d677261793f7374796c653d666c6174266c6f676f3d707974686f6e), 



















