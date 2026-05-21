
Conclusión del dataset **'speeding_fines'**:
- **Análisis de datos iniciales**: Al importar y analizar los datos nos enontramos
con que hay muchos registros que contienen fechas y horas con formatos diferentes
 asi como registros con datos escenciales nulos.
- **Depuración inicial**: Se normalizó los registros de fechas y horas a un formato
común y se remplazo los datos invalidos de ambos campos a `1931-01-01` y
a `00:00`. Tambien se eliminaron los registros nulos tomando en cuenta las columnas
relevantes (`patente`, `fecha`, `hora`, `velocidad_registrada`,
`velocidad_maxima`). Se depuraron en total 1982 filas por registros con datos
nulos y 0 uotliers.
- **Resultados obtenidos**: Una vez con el dataset limpio se analizaron los datos
dandonos varios resultados relevantes como la patente con mas
infracciones obtenidas siendo `WE FLYN` con **38 infracciones**. Tambien el
exceso real promedio de velocidad fue de `42.35 km/h`. La avenida donde se
produjeron mas infracciones fue **AV LIBERTADOR** con 708 infracciones.

- La resultande de las fechas y horas invalidas se obtubieron el porcentaje de
infracciones en la fecha `1932-01-01` fue del 26.44% y el porcentaje de infracciones
a la hora `00:00` fue del 19.79%.
