# Visualización de Datos con PCA - Dataset Iris

## Objetivo  
Reducir la dimensionalidad del clásico dataset *Iris* mediante Análisis de Componentes Principales (PCA) para facilitar la exploración visual. Se busca proyectar los datos en un espacio bidimensional que preserve la mayor parte de la varianza y permita identificar relaciones entre especies de flores.

## Dataset  
- Fuente: [Kaggle - Iris Dataset](https://www.kaggle.com/uciml/iris)  
- Variables originales: largo y ancho de sépalo, largo y ancho de pétalo  
- Clases: *Iris-setosa*, *Iris-versicolor*, *Iris-virginica*

---

## Tecnologías utilizadas  
- **Python**  
- **NumPy** – operaciones numéricas  
- **Pandas** – manipulación y análisis de datos  
- **Matplotlib** – visualización de datos  
- **Seaborn** – gráficos estadísticos atractivos  
- **Scikit-learn**  
  - `StandardScaler` – normalización de características  
  - `PCA` – reducción de dimensionalidad  
  - `train_test_split` – división de conjuntos de datos

---

## Flujo de Trabajo

1. **Carga y exploración de datos**
   - Inspección de estructura y verificación de nulos  
   - Análisis preliminar de distribución por variable

2. **Preprocesamiento**
   - Normalización de variables para estandarizar escalas  
   - Visualización inicial con histogramas y scatter plots

3. **Aplicación de PCA**
   - Reducción de 4 características a 2 componentes principales  
   - Cálculo de varianza explicada (95.63%)  
   - Interpretación de coeficientes de componentes

4. **Visualización**
   - Gráfico 2D con color por especie floral  
   - Análisis de agrupamiento por clase en el nuevo espacio

5. **Interpretación**
   - PC1 dominado por características del pétalo (diferenciador clave)  
   - PC2 capturando principalmente el ancho del sépalo  
   - Evaluación de separación de clases en el plano PCA

## Resultados

- Los dos primeros componentes explican **el 95.63% de la varianza**, logrando una reducción dimensional altamente efectiva.  
- **PC1 (pétalo)** permite distinguir claramente entre especies.  
- **PC2 (sépalo)** complementa la separación aportando variabilidad adicional.  
- Las especies se **agrupan visiblemente** en el plano PCA, lo que sugiere que la estructura original del dataset se conserva.

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.





