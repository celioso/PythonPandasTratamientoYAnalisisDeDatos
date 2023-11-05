# Python Pandas Tratamiento y análisis de datos

### Preparando el ambiente

En este curso utilizaremos **Google Colab** para escribir nuestro código Python y ejecutar los ejercicios. Para esto, necesitarás una cuenta de Google y acceder a [este enlace](https://colab.research.google.com/ "este enlace").

Además, descarga [aquí](https://github.com/alura-es-cursos/1792-introducao-python-pandas/raw/1792-Aula1/1792-Aula1.zip "aquí") el ZIP del proyecto inicial de nuestro entrenamiento, necesario para la continuidad del mismo.

### Haga lo que hicimos en aula

Llegó el momento de que tú mismo ejecutes todos los pasos que hemos realizado durante esta aula. Si ya lo has hecho, ¡excelente!. Si no, es importante que realices lo que enseñé en los videos para continuar con la próxima aula.

### Lo que aprendimos

En esta aula, aprendimos:

- Los ambientes de desarrollo para el lenguaje Python
- A crear **DataFrames** con el paquete **pandas**, utilizando datos externos
- Cómo obtener informaciones básicas de un `DataFrame`
- Cómo obtener estadísticas descriptivas de los datos de un `DataFrame`

### Haga lo que hicimos en aula

Llegó el momento de que tú mismo ejecutes todos los pasos que hemos realizado durante esta aula. Si ya lo has hecho, ¡excelente!. Si no, es importante que realices lo que enseñé en los videos para continuar con la próxima aula.

### Lo que aprendimos

En esta aula, aprendimos:

- Cómo importar la biblioteca (import pandas as pd)
- Cómo leer diferentes fuentes de datos:
 - Una base CSV (`pd.read_csv(...)`)
 - Una base JSON (`pd.read_json(...)`)
 - Una base TXT (`pd.read_table(...)`)
 - Un archivo EXCEL (`pd.read_excel(...)`)
 - Una página HTML (`pd.read_html(...)`)
- Varios métodos y atributos útiles de dataframes, como:
 - info()
 - head()
 - dtypes
 - columns
 - shape
Y sobre Colab, vimos cómo:

- Crear diferentes tipos de células dentro del notebook
- Acceder a la documentación
- Cómo re-ejecutar todas las células

### Proyecto del aula anterior

Si lo desea, puede descargar [aquí](https://github.com/alura-es-cursos/1792-introducao-python-pandas/raw/1792-Aula3/1792-Aula3.zip "aquí") el proyecto del curso en el punto donde paramos la clase anterior.

### Haga lo que hicimos en aula

Llegó el momento de que tú mismo ejecutes todos los pasos que hemos realizado durante esta aula. Si ya lo has hecho, ¡excelente!. Si no, es importante que realices lo que enseñé en los videos para continuar con la próxima aula.

### Lo que aprendimos

En esta aula, aprendimos:

- Cómo seleccionar una variable del Dataframe (por ejemplo, `datos['Tipo']` o `datos.Tipo`)
- Que un Dataframe está compuesto de varios Series
- Cómo eliminar duplicados (usando el método `drop_duplicates()`)
- Cómo redefinir el index de un Dataframe y Series (atributo `index`)
- Cómo concatenar Dataframes (recordando el `axis`)
- Cómo crear nuevos Dataframes basados en estructuras de datos Python (lista, diccionarios o tuplas)
¡En la próxima clase aprenderemos cómo filtrar nuestros datos! ¿Listo para continuar?

### Proyecto del aula anterior

Si lo desea, puede descargar [aquí](https://github.com/alura-es-cursos/1792-introducao-python-pandas/raw/1792-Aula4/1792-Aula4.zip "aquí") el proyecto del curso en el punto donde paramos la clase anterior.

### Haga lo que hicimos en aula

Llegó el momento de que tú mismo ejecutes todos los pasos que hemos realizado durante esta aula. Si ya lo has hecho, ¡excelente! Si no, es importante que realices lo que enseñé en los videos para continuar con la próxima aula.

### Lo que aprendimos

En esta aula, aprendimos como:

- Crear una Series booleana utilizando el método `isin(..)` a partir de un dataframe
- Filtrar los datos de un dataframe utilizando una Series booleana
- Exportar y guardar los datos de un dataframe(método `to_csv()`)
- Ordenar los datos de un dataframe (métodos `sort_values()` y `sort_index()`)

### Proyecto del aula anterior

Si lo desea, puede descargar [aquí](https://github.com/alura-es-cursos/1792-introducao-python-pandas/raw/1792-Aula5/1792-Aula5.zip "aquí") el proyecto del curso en el punto donde paramos la clase anterior.

### Dataframe para los próximos ejercicios

```python
import pandas as pd
alumnos = pd.DataFrame({
'Nombre': ['Ary', 'Katia', 'Denis', 'Beto', 'Bruna', 'Dara', 'Carlos', 'Alice'], 
'Sexo': ['M', 'F', 'M', 'M', 'F', 'F', 'M', 'F'], 
'Edad': [15, 27, 56, 32, 42, 21, 19, 35], 
'Notas': [7.5, 2.5, 5.0, 10, 8.2, 7, 6, 5.6], 
'Aprobado': [True, False, False, True, True, True, False, False]},
columns = ['Nombre', 'Edad', 'Sexo', 'Notas', 'Aprobado'])
```

Utilizando las técnicas de selección presentadas en esta aula, realice los conjuntos de selecciones propuestos en los siguientes ejercicios.


### Haga lo que hicimos en aula

Llegó el momento de que tú mismo ejecutes todos los pasos que hemos realizado durante esta aula. Si ya lo has hecho, ¡excelente!. Si no, es importante que realices lo que enseñé en los videos para continuar con la próxima aula.

### Lo que aprendimos

En esta aula, aprendimos:

- Métodos de selección y frecuencias
 - Selección con la condición **OR** (`|`)
 - Selección con la condición **AND** (`&`)
- Cómo crear un `Index` con `split()`
- Selección por línea y columna en un *dataframe*:
 - Usando índices numéricos y rótulos de las líneas
 
 ### Proyecto del aula anterior
 
 Si lo desea, puede descargar [aquí](https://github.com/alura-es-cursos/1792-introducao-python-pandas/raw/1792-Aula6/1792-Aula6.zip "aquí") el proyecto del curso en el punto donde paramos la clase anterior.