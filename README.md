# Análisis de datos y modelos predictivos sobre rendimiento académico.
Análisis del rendimiento académico de estudiantes mediante técnicas de machine learning. Incluye limpieza de datos, modelos supervisados, clustering con K-Means y visualización de resultados.

Análisis del Rendimiento Académico — Proyecto de Ciencia de Datos
Descripción

Este proyecto aplica técnicas de Ciencia de Datos y Machine Learning para analizar los factores que influyen en el rendimiento académico de los estudiantes.
Incluye limpieza de datos, análisis exploratorio (EDA), creación de variables, escalamiento, codificación y desarrollo de modelos predictivos.

 Objetivo del Proyecto

El propósito es identificar patrones y variables clave que determinan si un estudiante aprueba o no, y construir modelos que permitan realizar predicciones precisas.

Tecnologías Utilizadas

Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook / VS Code

📁 Estructura del Proyecto
proyecto-ciencia-de-datos/
│── data/                  # Dataset utilizado (si aplica)
│── notebooks/             # Jupyter Notebook con análisis y modelos
│── src/                   # Código Python organizado
│── images/                # Gráficos generados
│── README.md              # Documentación del proyecto
│── requirements.txt       # Librerías necesarias
│── .gitignore             # Archivos ignorados por Git

Proceso del Proyecto
1. Limpieza de Datos

Eliminación de valores faltantes

Conversión de variables

Revisión de inconsistencias

2. Análisis Exploratorio (EDA)

Distribución de las variables

Correlaciones

Comparación entre categorías

Visualizaciones para entender patrones

3. Ingeniería de Variables

Creación de una variable binaria:

1 = Aprobado

0 = No aprobado

4. Codificación de Datos

Se usó LabelEncoder para codificar:

Género

Nivel Académico

Estrés Nivel

Uso de Biblioteca

5. Escalamiento

Se aplicó StandardScaler para mejorar el desempeño de los modelos.

6. Modelado

Se entrenaron tres modelos:

🔹 Regresión Logística

Exactitud: 0.78

Predice muy bien aprobados, pero tiene dificultad con reprobados.

🔹 Árbol de Decisión

Exactitud: 0.75

Mejor desempeño en aprobados, bajo en no aprobados.

🔹 Random Forest (opcional)

Mejora estabilidad y precisión general.

7. Evaluación

Se utilizaron:

Matriz de confusión

Precisión, Recall y F1-score

Exactitud (Accuracy)

Resultados Generales
Modelo	Exactitud
Regresión Logística	0.78
Árbol de Decisión	0.75

Cómo Ejecutar el Proyecto
1. Clonar el repositorio
git clone https://github.com/tu-usuario/proyecto-ciencia-de-datos.git

2. Instalar dependencias
pip install -r requirements.txt

3. Abrir el Notebook
jupyter notebook

📎 Autor

Fraimel Trinidad M.
Lic en Administracion|Analista de Datos 

🤝 Contribuciones

Las mejoras y sugerencias siempre son bienvenidas.
