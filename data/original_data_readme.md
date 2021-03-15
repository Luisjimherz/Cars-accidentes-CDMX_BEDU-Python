Content
The data set has the following columns:

folio: a unique ID for each register
fecha_creacion: creation date
hora_creacion: creation time
dia_semana: day of the week when incident happens
codigo_cierre: internal classification. The column could contain the following codes.
A: Affirmative, if the incident is confirmed by emergencies team.
N: Negative, if the emergencies team doesn't confirm the incident at the location point.
I: Informative, in case attention teams want to add extra information.
F: False, if initial report doesn't match with the real events
D: Duplicated, records with closing code affirmative, negative or false but operators identify them
fecha_cierre: close date, the date when the incident was resolved
año_cierre: close year
mes_cierre: close month
hora_cierre: close time
delegacion_inicio: entity inside Mexico City where the incident was registered
incidente_c4: a brief explanation about the incident.
latitud: accident latitude
longitud: accident longitude
clasconf_alarma: code identifying the situation's severity
tipo_entrada: how the incident was reported
delegacion_cierre: entity inside Mexico City where the incident was closed
geopoint: latitude and longitude columns combined
mes: month when the incident was reported