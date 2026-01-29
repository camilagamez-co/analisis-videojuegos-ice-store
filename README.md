# 🎮 Análisis de Patrones de Éxito en Videojuegos - Ice Store

📋 Descripción del Proyecto
Análisis de datos históricos de videojuegos para la tienda online Ice con el objetivo de identificar patrones que determinan el éxito comercial y optimizar campañas publicitarias para 2017. Se analizan 16,715 videojuegos evaluando ventas globales, plataformas, géneros y comportamiento regional.

🎯 Objetivos
Identificar plataformas con mayor potencial comercial para 2017
Analizar géneros más rentables y eficientes
Evaluar impacto de reseñas de críticos y usuarios en ventas
Crear perfiles de usuario por región (NA, EU, JP)
Determinar influencia de clasificaciones ESRB por mercado
🛠️ Tecnologías Utilizadas
Python 3.8+
Pandas
Manipulación y análisis de datos
NumPy
Operaciones numéricas y estadísticas
Matplotlib
Visualización de datos
Seaborn
Visualizaciones estadísticas avanzadas
SciPy
Pruebas de hipótesis estadísticas
Jupyter Notebook
Entorno de desarrollo interactivo
📊 Estructura de Datos
Dataset principal con 16,715 registros y variables clave:

name
Nombre del videojuego
platform
Plataforma (PS4, Xbox One, PC, etc.)
year_of_release
Año de lanzamiento
genre
Género (Action, Shooter, RPG, etc.)
na_sales/eu_sales/jp_sales/other_sales
Ventas por región (millones USD)
critic_score
Puntuación críticos (0-100)
user_score
Puntuación usuarios (0-10)
rating
Clasificación ESRB (E, E10+, T, M)
⚙️ Funcionalidades Implementadas
### 🔍 Preprocesamiento
- Estandarización de nombres de columnas
- Conversión de tipos de datos (user_score a float64)
- Tratamiento estratégico de valores ausentes
- Creación de variable total_sales
- Filtrado temporal (2012-2015) para análisis predictivo

### 📈 Análisis Exploratorio
- Análisis temporal: Evolución de lanzamientos por año
- Análisis de plataformas: Ciclo de vida y ventas por plataforma
- Análisis de géneros: Distribución y rentabilidad por género
- Correlaciones: Impacto de puntuaciones en ventas

### 🌍 Perfiles Regionales
- Top 5 plataformas por región (NA, EU, JP)
- Top 5 géneros más populares regionalmente
- Análisis ESRB: Impacto de clasificaciones por mercado
- Comparativas: Diferencias culturales en preferencias

### 🧪 Pruebas de Hipótesis
- H1: Calificaciones Xbox One vs PC (α = 0.05)
- H2: Calificaciones géneros Acción vs Deportes (α = 0.05)
- Aplicación de t-tests bilaterales
- Verificación de supuestos estadísticos y normalidad
- Interpretación de p-valores para toma de decisiones

## 🚀 Instalación y Uso

### Prerrequisitos

```bash
Python 3.8+
Jupyter Notebook
