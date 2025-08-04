# Introduccion al conjunto de datos

El presente análisis se basa en un conjunto de datos de reservas de vuelos de varias aerolíneas, extraído de la plataforma Kaggle. Según la descripción proporcionada, los datos fueron recolectados mediante técnicas de web scraping desde una página web reconocida del sector, y luego organizados en un formato estructurado y ordenado cronológicamente.

El conjunto de datos contiene registros detallados de vuelos entre distintas ciudades de la India. Incluye información sobre la aerolínea, horarios, duración del vuelo, escalas, clase del asiento y precios, entre otros aspectos relevantes para el análisis del comportamiento de los vuelos y la variación de precios.

En total, el conjunto cuenta con 300,153 registros distribuidos en 12 campos. A continuación se describen brevemente cada uno de ellos:

index: Identificador único de cada vuelo (clave primaria).

airline: Nombre de la aerolínea que opera el vuelo.

flight: Código identificador del avión.

source_city: Ciudad de origen desde donde parte el vuelo.

departure_time: Categoría derivada que agrupa la hora de salida en intervalos o franjas horarias. Tiene 6 valores distintos.

stops: Número de escalas entre la ciudad de origen y el destino. Es una variable categórica con 3 valores posibles.

arrival_time: Categoría derivada que agrupa la hora de llegada en intervalos o franjas horarias. También tiene 6 valores distintos.

destination_city: Ciudad de destino donde aterriza el vuelo. Se registran 6 ciudades únicas.

class: Clase del asiento reservada; puede ser Business o Economy.

duration: Tiempo total de viaje entre ciudades, expresado en horas (variable continua).

days_left: Número de días entre la fecha de reserva y la fecha del vuelo, calculado como la diferencia entre ambas fechas.

price: Precio del pasaje (variable objetivo del análisis).

Este conjunto de datos permite realizar un análisis exploratorio enfocado en entender cómo varían los precios de los vuelos en función de características como la aerolínea, la antelación con que se reserva, la duración del vuelo, las escalas y otros factores clave. El objetivo será extraer patrones relevantes y potencialmente útiles para modelos predictivos o para apoyar decisiones informadas sobre reservas aéreas.

