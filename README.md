# Proyecto-Final-IA-2023
# Aplicación de SVM y ANN para clasificar cultivos a partir de características de suelo 😁

En el presente proyecto se usa un data set de la entidad AGROSAVIA que contiene características de diferentes cultivos plantados alrededor de Colombia. Estas características son tanto categóricas como numéricas. El objetivo es entrenar modelos con diferentes técnicas de aprendizaje de maquina supervisado para determinar a partir de características numéricas de suelo, cual es el cultivo optimo a plantar.

### 1. Datos a utilizar 

[Data set cultivos](NIRSdata.csv)

De este data set se utilizan unicamente datos numéricos, y estos corresponden a porcentajes de nutrientes en el suelo del cultivo y el espectro del mismo. Por ende, en la limpieza de datos del código, verán como se separan los datos numéricos útiles de los categóricos y adicional de usa PCA como técnica de reducción dimensional para reducir el numero de datos usados para entrenar.

### 2. Técnicas de entrenamiento

Principalmente de aplicaron 2 técnicas de entrenamiento de aprendizaje de maquina supervisado y fueron Maquinas de Soporte Vectorial (SVM) y Redes Neuronales Artificiales (ANN). Como métricas de evaluación se uso Correlación de Matthews y F1 Score.

### 3. Resultados obtenidos 🫠

Al final, con los resultados obtenidos de las métricas, se encontró que las características no tienen una alta correlación con las etiquetas. Es decir, no se puede decidir que cultivo es mejor plantar en un suelo, solo teniendo el espectro y nutrientes de este. Se requieren mas características para obtener un modelo con mejores resultados.

### Pre-requisitos 📝

Instalar **pandas**, **numpy** y **scikit-learn**

```python
import sys
!{sys.executable} -m pip install pandas
!{sys.executable} -m pip install numpy
!{sys.executable} -m pip install scikit-learn
```
### Autores 👀
    - Alfredo Cuellar
    - Valentina Forero

#### Adicional

**Link del código en Colab**
<https://colab.research.google.com/drive/1DDBFfDsjAFH2eEzvO1seQ6NCQ_FEpVSo?usp=sharing>

**Link del video**
<https://youtu.be/VJGYN0Gm9ls>
