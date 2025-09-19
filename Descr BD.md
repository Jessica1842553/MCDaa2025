# Conjunto de Datos: Student Performance

## Introducción

El conjunto de datos **"Student Performance"** proviene del repositorio de aprendizaje automático de la Universidad de California en Irvine (UCI Machine Learning Repository). Este dataset fue recopilado con el propósito de analizar los factores que pueden influir en el rendimiento académico de los estudiantes de secundaria en Portugal.

Información detallada sobre estudiantes de la asignatura: **Matemáticas** (`student-mat.csv`), contiene datos de aproximadamente **395 estudiantes**, con un total de **33 variables**, estas variables abarcan aspectos personales, familiares, escolares y académicos.

---

## Descripción de las columnas

Las variables están agrupadas en las siguientes categorías:

### Datos Personales del Estudiante

| Columna   | Descripción                                               | Tipo        |
|-----------|-----------------------------------------------------------|-------------|
| `sex`     | Género del estudiante (`F` = femenino, `M` = masculino)   | Categórica  |
| `age`     | Edad del estudiante (de 15 a 22 años)                     | Numérica    |
| `address` | Tipo de residencia (`U` = urbana, `R` = rural)            | Categórica  |
| `famsize` | Tamaño de la familia (`LE3` = ≤3, `GT3` = >3 miembros)   | Categórica  |
| `Pstatus` | Situación de convivencia de los padres (`T` = juntos, `A` = separados) | Categórica  |

---

### Contexto Familiar

| Columna   | Descripción                                              | Tipo              |
|-----------|----------------------------------------------------------|-------------------|
| `Medu`    | Nivel educativo de la madre (0: ninguno, 4: universitario) | Numérica ordinal  |
| `Fedu`    | Nivel educativo del padre (0: ninguno, 4: universitario)  | Numérica ordinal  |
| `Mjob`    | Trabajo de la madre (`teacher`, `health`, etc.)          | Categórica        |
| `Fjob`    | Trabajo del padre                                        | Categórica        |
| `guardian`| Tutor principal del estudiante (`mother`, `father`, `other`) | Categórica     |

---

### Información Escolar

| Columna     | Descripción                                                   | Tipo             |
|-------------|---------------------------------------------------------------|------------------|
| `school`    | Escuela a la que asiste el estudiante (`GP` o `MS`)           | Categórica       |
| `studytime` | Tiempo de estudio semanal (1: <2h, 4: >10h)                   | Numérica ordinal |
| `failures`  | Número de materias reprobadas (0–3)                           | Numérica         |
| `schoolsup` | Apoyo educativo adicional en la escuela (`yes` o `no`)       | Categórica       |
| `famsup`    | Apoyo educativo familiar (`yes` o `no`)                       | Categórica       |
| `internet`  | Acceso a internet en casa (`yes` o `no`)                      | Categórica       |

---

### Factores de Comportamiento y Hábitos

| Columna     | Descripción                                                 | Tipo             |
|-------------|-------------------------------------------------------------|------------------|
| `activities`| Participa en actividades extracurriculares (`yes` o `no`)  | Categórica       |
| `goout`     | Frecuencia con la que sale con amigos (1–5)                 | Numérica ordinal |
| `Dalc`      | Consumo de alcohol entre semana (1–5)                       | Numérica ordinal |
| `Walc`      | Consumo de alcohol en fin de semana (1–5)                   | Numérica ordinal |
| `health`    | Estado de salud autoevaluado (1–5)                          | Numérica ordinal |

---

### Rendimiento Académico

| Columna | Descripción                                  | Tipo     |
|---------|----------------------------------------------|----------|
| `G1`    | Nota obtenida en el primer periodo (0–20)    | Numérica |
| `G2`    | Nota obtenida en el segundo periodo (0–20)   | Numérica |
| `G3`    | Nota final (tercer periodo) (0–20)           | Numérica |


---
