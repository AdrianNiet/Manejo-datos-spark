# Manejo-datos-spark

Realizada manipulación de una dataframe de apps de movil, analizandose y luego representando mediante graficas.

La primera tarea fue dividir los datos segun la categoria principal, estos datos se guardaron dentro de [Data Processed](https://github.com/AdrianNiet/Manejo-datos-spark/tree/main/data/processed), tenemos los archivos en 2 carpetas, [Datos_filtrados](https://github.com/AdrianNiet/Manejo-datos-spark/tree/main/data/processed/df_filtradas) contiene todos los CSV, cada uno dentro de una carpeta, la carpeta de [df_filtradas](https://github.com/AdrianNiet/Manejo-datos-spark/tree/main/data/processed/datos_filtrados) contiene todos los CSV dentro de la misma carpeta, ya que, asi queda mas limpio.

El proceso de manipulación de la DataFrame se realizo [operating_df](https://github.com/AdrianNiet/Manejo-datos-spark/blob/main/notebooks/operating_df.ipynb). Una vez realizada el guardado de los datos en una misma carpeta, se uso un bucle *__for__* para cojer todos los CSV de la carpeta y cargarlos uno a uno para poder representarlos, esta representación se realizo en [Visualizar_datos](https://github.com/AdrianNiet/Manejo-datos-spark/blob/main/notebooks/visualizar_datos.ipynb)

## Tareas realizadas.

- Repaso de los datos.
- Agrupación de sub-categorias segun categoria principal.
- Añadido de valores medios de reviews, rating e instalaciones segun sub-categoria.
- añadido version mas utilizada segun cada sub-categoria.
- Guardado de los datos en diferentes carpetas con el nombre de categoria.
- Guardado en una misma carpeta.
- Creacion de graficas segun los CSV guardados.
- Analisis de los datos una vez filtrados y visualizados.

### Pendiente:
Revisare en el futuro el trabajo para ver si se puede mejorar.
