# Fundamentos de IA y Machine Learning

Este proyecto contiene tres ejercicios prácticos que cubren los **Fundamentos de Inteligencia Artificial y Machine Learning** utilizando **Python** y **Jupyter Notebooks**. Cada uno de los ejercicios se centra en un tipo de problema diferente:

1. **Regresión Lineal**.
2. **Red Neuronal**.
3. **Clustering Jerárquico**.

## Instalación

Para ejecutar los notebooks en este proyecto, es recomendable utilizar un entorno virtual y asegurarse de instalar las dependencias necesarias. Sigue los siguientes pasos:

### 1. Clonar el repositorio

```bash
git clone https://github.com/Zhanya001/fund_IA_Master
cd mi_proyecto
```
### 2. Crear un entorno virtual (opcional pero recomendado)

En Linux/MacOS:
```bash
python3 -m venv venv
source venv/bin/activate
```

En Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```

### 3. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 4. Ejecutar los notebooks
```bash
jupyter notebook
```

___

## Problema 1: Regresión Lineal
En este problema se busca estimar el valor Y de unas zapatillas dada su valoración X1 y el número de reseñas X2. El notebook prob1.ipynb incluye los siguientes pasos:

- Regresión lineal simple de Y en función de X1.
- Regresión lineal múltiple de Y en función de X1 y X2.
- Evaluación de ambos modelos utilizando un conjunto de test.

| Valor `Y` | `X1` (Valoración) | `X2` (Reseñas) |
|-----------|--------------------|-----------------|
| 140       | 6.5                | 18              |
| 150       | 8.5                | 20              |
| 130       | 7.5                | 10              |
| 120       | 6.0                | 15              |
| 125       | 6.2                | 15              |
| 135       | 8.0                | 18              |
| 100       | 5.0                | 8               |
| 150       | 10.0               | 25              |
| 150       | 9.5                | 25              |
| 110       | 5.5                | 10              |

___

## Problema 2: Red Neuronal
Este ejercicio entrena una Red Neuronal Artificial para clasificar patrones según dos características (X1 y X2). El notebook prob2.ipynb incluye:

Entrenamiento de una red neuronal para clasificación.
Predicciones y evaluación del rendimiento de la red en un conjunto de test.
La red neuronal se representa como sigue:

| Patrón | `X1` | `X2` | Clase |
|--------|------|------|-------|
| 1      | 3.50 | 1.40 | 1     |
| 2      | 3.40 | 1.50 | 1     |
| 3      | 3.20 | 1.20 | 2     |
| 4      | 3.20 | 1.60 | 3     |
| 5      | 3.20 | 4.70 | 2     |
| 6      | 2.90 | 4.30 | 2     |
| 7      | 3.00 | 4.20 | 1     |
| 8      | 3.20 | 5.30 | 3     |
| 9      | 2.80 | 5.60 | 3     |
| 10     | 3.00 | 6.10 | 1     |

___

## Problema 3: Clustering Jerárquico
En este ejercicio se aplica clustering jerárquico utilizando el método de enlace simple para agrupar patrones según una matriz de distancias. El notebook prob3.ipynb incluye:

Aplicación de clustering jerárquico con enlace simple.
Visualización de los grupos mediante un dendograma.

|     | A  | B  | C  | D  | E  |
|-----|----|----|----|----|----|
| **A** | 0  | 1.5  | 2.5  | 3  | 10 |
| **B** |    | 0    | 2.25 | 6  | 4  |
| **C** |    |      | 0    | 8  | 7.5|
| **D** |    |      |      | 0  | 3.62|
| **E** |    |      |      |    | 0  |

___

## .gitignore

El archivo `.gitignore` está configurado para ignorar archivos innecesarios que no deben ser incluidos en el repositorio, tales como:

- Entornos virtuales (`venv/`)
- Cachés de Python (`__pycache__/`)
- Archivos de configuración locales (`.vscode/`, `.idea/`)
- Checkpoints de Jupyter (`.ipynb_checkpoints/`)


## Contacto
Si tienes preguntas o deseas más información, puedes contactarme a través de [LinkedIn: Ariet Michal](https://www.linkedin.com/in/ariet-michal)
