# 🤖 Telecom X - Modelo Predictivo de Cancelación

[![una-imagen-estilo-publicitario-para-la-compa-a.jpg](https://i.postimg.cc/Jhw2KRyc/una-imagen-estilo-publicitario-para-la-compa-a.jpg)](https://postimg.cc/w1V2j8Q7)
![Static Badge](https://img.shields.io/badge/status-completed-green)

---
## 📑 Índice
- [🧾 Descripción del proyecto](#-descripción-del-proyecto)
- [🔧 Funcionalidades del análisis](#-funcionalidades-del-análisis)
- [📊 Resultados y hallazgos](#-resultados-y-hallazgos)
- [📂 Acceso al proyecto](#-acceso-al-proyecto)
- [🛠️ Abre y ejecuta el proyecto](#️-abre-y-ejecuta-el-proyecto)
- [🧰 Tecnologías utilizadas](#-tecnologías-utilizadas)
- [👨‍💻 Autor](#-autor)
- [🪪 Licencia](#-licencia)

---

## 🧾 Descripción del proyecto
Este proyecto corresponde a la **Parte 2** del desafío **Telecom X** dentro del curso **Estadística y Machine Learning** de la formación ONE (Oracle Next Education) en conjunto con Alura LATAM.  

En esta fase se avanzó hacia la construcción de **modelos predictivos de cancelación de clientes (churn)**, buscando identificar los factores más determinantes en la pérdida de usuarios y comparar el desempeño de diferentes algoritmos de Machine Learning.

El dataset procesado en la *Parte 1* sirvió como base para la creación de modelos, su evaluación y la interpretación de resultados, lo que permitió generar estrategias de retención basadas en evidencia.

---

## 🔧 Funcionalidades del análisis
- `División en entrenamiento y prueba`: Separamos los datos en proporción 70/30 asegurando el balance de clases.
- `Modelos predictivos`: Entrenamiento y evaluación de **Decision Tree** y **Random Forest**, con ajuste de hiperparámetros.
- `Optimización con GridSearchCV`: Búsqueda de los parámetros más eficientes para maximizar el rendimiento de los modelos.
- `Evaluación con métricas clave`: Exactitud, Precisión, Recall, F1-score y Matriz de Confusión.
- `Comparativa visual`: Gráfico comparativo de métricas entre modelos para facilitar la interpretación.
- `Importancia de variables`: Identificación de los factores más relevantes que explican la cancelación.
- `Recomendaciones prácticas`: Estrategias de retención basadas en los resultados obtenidos.

---

## 📊 Resultados y hallazgos
- **Random Forest optimizado** alcanzó la mejor exactitud global (≈79.4%) y un mejor equilibrio entre métricas que el Decision Tree.  
- **Factores clave en la cancelación**:  
  - **Meses contratados** y **facturación total** fueron las variables más determinantes en Random Forest.  
  - **Tipo de contrato mensual** y el uso de **fibra óptica** destacaron fuertemente en Decision Tree.  
- **Patrón identificado**: Los clientes con contratos mensuales y altos niveles de facturación tienen mayor propensión a cancelar, lo que indica la necesidad de reforzar programas de fidelización en este segmento.

📊 Se generaron gráficos de comparación de métricas y de importancia de variables para apoyar la interpretación.

---

## 📂 Acceso al proyecto
Puedes acceder al código fuente y a los archivos generados directamente en este repositorio. 

Las estapas y los pasos a seguir para esta segunda parte se describen en este [tablero](https://trello.com/b/y1FQQnc7/telecomxparte2latam).

💡 *El desarrollo fue realizado en Google Colab y Jupyter Notebook, con visualizaciones en Matplotlib y Seaborn.*

---

## 🛠️ Abre y ejecuta el proyecto
1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/telecom-x-parte2.git
```
2. Accede a la carpeta:
```bash
cd telecom-x-parte2
```
3. Instala las dependencias (requiere Python 3 y pip):
```bash
pip install pandas matplotlib seaborn scikit-learn
```
4. Abre el proyecto en Google Colab o Jupyter Notebook.

---

## 🧰 Tecnologías utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 👤 Autor
[<img src="https://avatars.githubusercontent.com/u/157757330?v=4" width=115><br><sub>Jetsael Villegas</sub>](https://github.com/JetsaelVillegasMendoza)

---

## 📝 Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
