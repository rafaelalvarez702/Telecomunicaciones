Proyecto Individual - 02-Telecomunicaciones
Introducción⚠️🚧
Este proyecto se realizó simulando ser un Analista de Datos de una empresa prestadora de servicios de telecomunicaciones; que me encarga  la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considerando que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.


Para cumplir con ello, los datos iniciales que se utilizan son derivados de un dataset con información sobre homicidios de siniestro viales en la Ciudad de Buenos Aires, durante los años 2016-2021, que es de píblico acceso en la página oficial de CABA. Podemos acceder a ellos desde Datos oficiales

Contexto⚠️🚧
Las telecomunicaciones en Argentina experimentaron un crecimiento significativo en las últimas décadas. El aumento en la demanda de servicios de comunicación, como telefonía móvil e internet, contribuyó a la expansión del mercado. Dicha expansion a contibuido a que las empresas prestadoras de servicios inviertieran en infraestructura, implementaran tecnologias y de esta forma ofrecer mayor y mejor calidad de servicio a sus usuarios.


Desarrollo⚠️🚧
Datos⛔
Para este proyecto se trabajó con la API de ENACOM, para extraer los datos pero dado que la API prsentaba muchos errores a la hora de descargar la informacion los datos se extrajeron directo de la Página oficial de ENACOM en formato csv y exel.


- Proceso de ETL (Extracción, limpieza y carga de datos)se realiza la extracción y limpieza de los datos de los dos dataset obtenidos, a través de la utilización de Pandas y Jupyter Netbook. ETL Eliminando nulos, duplicados, con transformaciones necesarias como cambio en los tipos de datos, eliminación de columnas y unión de las tablas.

- Proceso de EDA (Análisis Exploratorio de los datos)una vez que los datos están limpios, es momento de revisar las relaciones que existen entre las variables numéricas y categóricas de los datasets, encontrar si hay presencia de valores atípicos o anomalías (que no tienen que ser errores necesariamente), y se verificó si hay algún patrón o conocimiento que sirva en un análisis posterior. EDA

Análisis de los datos⛔




![image](https://github.com/rafaelalvarez702/Telecomunicaciones/assets/104017553/2c81383e-f6bc-4688-8be2-5dece807f77f)


















