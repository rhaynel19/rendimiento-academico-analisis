Análisis de Rendimiento Académico — Proyecto de Ciencia de Datos

Este proyecto realiza un análisis completo del rendimiento académico de estudiantes utilizando herramientas de Ciencia de Datos y Machine Learning.
Incluye limpieza de datos, análisis exploratorio, ingeniería de características, preparación del dataset y entrenamiento de múltiples modelos predictivos.

🎯 Objetivo del Proyecto

Identificar qué factores influyen en que un estudiante apruebe o no apruebe,
y construir modelos capaces de predecir este resultado con un nivel adecuado de exactitud.

🧠 Tecnologías Utilizadas

Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

📁 Estructura del Proyecto
rendimiento-academico-analisis/
│── data/                  # Dataset utilizado
│── notebooks/             # Jupyter Notebook con el análisis y modelos
│── images/                # Gráficos generados durante el análisis
│── README.md              # Documentación del proyecto
│── requirements.txt       # Dependencias necesarias
│── .gitignore             # Archivos ignorados por Git

📊 Proceso del Análisis
1️⃣ Limpieza de Datos

Manejo de valores nulos

Revisión de tipos de datos

Corrección de inconsistencias

Normalización de nombres y categorías

2️⃣ Análisis Exploratorio (EDA)

Distribución de variables

Relación entre factores académicos

Visualización de correlaciones

Identificación de patrones y tendencias

3️⃣ Ingeniería de Características

Creación de una variable objetivo binaria:

1 = Aprobado

0 = No aprobado

Codificación de variables categóricas (LabelEncoder)

Escalamiento de variables numéricas (StandardScaler)

4️⃣ División de Datos

70% Entrenamiento

30% Prueba

🤖 Modelos Entrenados y Desempeño
🔹 Regresión Logística

Exactitud: 0.78

Buen desempeño prediciendo estudiantes aprobados

Menor precisión en casos de no aprobación

🔹 Árbol de Decisión

Exactitud: 0.75

Alta precisión en aprobados

Baja capacidad para no aprobados

(Puedes agregar Random Forest si lo integras más adelante)

📈 Resumen de Resultados
Modelo	Exactitud
Regresión Logística	0.78
Árbol de Decisión	0.75
🚀 Cómo Ejecutar el Proyecto
1️⃣ Clonar el repositorio
git clone https://github.com/rhaynel19/rendimiento-academico-analisis.git

2️⃣ Instalar las dependencias
pip install -r requirements.txt

3️⃣ Ejecutar el análisis
jupyter notebook

👨‍💻 Autor

Fraimel (Rhayner) Trinidad
Lic. en Administración | Analista de Datos | Estudiante de Ciencia de Datos e Inteligencia Artificial

📧 Abierto a colaboraciones, mejoras o sugerencias.

Cualquier sugerencia o mejora es bienvenida.
