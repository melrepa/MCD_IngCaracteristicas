# Descripción de fuentes de datos.

Estos son los tidy DataFrames que se utilizarán en el proyecto final del curso de Ingeniería de Características. La pregunta es: Cuando se comete un feminicidio, ¿la víctima ha sido reportada como desaparecida anteriormente?

Se encontraron tres fuentes de información que dan datos de diferente origen, los cuales son:

* [Datos abiertos de Incidencia delictiva (SESNSP)](https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva) se presentan los registros de las averiguaciones previas y/o carpetas de investigación de delitos y subtipo de delito  por entidad federativa y de forma mensual. En estos datos hay una sección de feminicidios los cuales se presentan registrados de forma mensual por cada estado de 2015 a septiembre de 2022. Se presenta en la tabla Femtidy.csv. 

* [DataMexico API Explorer](https://dev-api.datamexico.org/ui/?cube=sesnsp_crimes&cuts%5B0%5D=Type.Crime+Type%2C502&debug=false&distinct=false&drilldowns%5B0%5D=Date.Year&drilldowns%5B1%5D=Geography.State&drilldowns%5B2%5D=Type.Crime+Type&locale=es&measures%5B0%5D=Value&nonempty=true&parents=false&sparse=false) se presentan los registros de las averiguaciones previas y/o carpetas de investigación de feminicidios por entidad federativa de forma anual de 2015 a septiembre de 2022. Se presenta en la tabla Delitidy.csv
* [Datos Abiertos del Gobierno](https://datos.gob.mx/busca/dataset/estadistica-de-personas-desaparecidas-no-localizadas/resource/a42be713-6cc3-4339-88c3-0e70d1089baa?inner_span=True) se presentan las Estadísticas de Personas Desaparecidas no localizadas (EPDNL) hasta 2018. Se presenta en la tabla Desaptidy.csv
