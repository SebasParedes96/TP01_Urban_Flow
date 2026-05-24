
Dia 1:
- Se crearon las estructura de directorios.
- Se creo la branch Sprint_1.
- Se creo el archivo CHANGELOG.

Dia 2:
- Importamos los datos del dataset con pandas, y guardamos en tu carpeta local urban_flow/data/raw/
- Mostramos las 10 primeras lineas del dataset.
- Mostramos los tipos de datos.
- Contamos valores nulos.

Dia 3:
- Conversión y formateo de la columna "fecha" a 'YYYY-MM-DD'.
- Conversión y formateo de la columna "hora" a 00:00.
- Conversion columna "Ubicacion" a mayusculas y limpieza de caracteres especiales.
- Limpieza de filas con datos relevantes nulos.
- Adición de nuevas columnas para cálculo de exceso de velocidad y con 5% margen.
- Eliminación de filas sin infracción.
- Guardado del dataset limpio.

Dia 4:
- Creación de clase 'FineAnalyzer'.
- Consulta de Top 5 patentes mas multadas.
- Consulta de Top 5 horarios con mas multas.
- Consulta de Exceso promedio de velocidad (con margen de 5%).
- Consulta de Exceso real promedio de velocidad.
- Consulta de cantidad de multas por ubicación.

Dia 5:
- Vista y exportación de gráfico en barras top 10 Patentes mas Reincidentes.
- Vista y exportación de gráfico torta con porcentaje de infracciones por hora.
- Vista y exportación de gráfico barras horizontal de infracciones por mes.
- Vista y exportación de gráfico de líneas de excesos de velocidad agrupados por la hora `00:00`.
- Vista y exportación de gráfico de líneas de excesos de velocidad agrupados por la fecha `1931-01-01`.

Dia 6:

- Calculo de porcentaje de infracciones en la fecha `1932-01-01`.
- Calculo de porcentaje de infracciones en la hora `00:00`.

Dia 7:
- Creación de archivo `Data/Readme.md` con la conclusión.

Dia 8:
- iniciacion de herramienta de versionado.
- clonar repo.
- creamos rama Sprint_2

Dia 9:
- Listado de Imagenes y peso.
- Clasificacion de Imagenes segun resolucion.
- Mostrando imagenes aleatorias.

Dia 10:
- Conversión a escala de grises.
- Suavizado.
- Reconocimiento de Bordes.

Dia 11:
- Extraccion de Patente de las imagenes.
- Calculo de Ratio.
- Match de imagenes del dataset con nuestro CSV limpio.
