# Predicción de GRD en Pacientes

Este proyecto utiliza modelos de **aprendizaje automático** para predecir el **Grupo Relacionado al Diagnóstico (GRD)** de pacientes utilizando datos médicos tanto **estructurados** como **no estructurados**. Los datos incluyen información sobre la **edad**, **sexo** y **texto clínico** de los pacientes, con el objetivo de asignar los pacientes a las clases correspondientes del GRD.

## Modelos Entrenados

- **Regresión Logística**
- **Random Forest**
- **SVM (Máquinas de Vectores de Soporte)**
- **KNN (K-Nearest Neighbors)**

## Descripción del Dataset

El dataset contiene información sobre **10,000 registros** de pacientes hospitalarios, con las siguientes características:
- **Edad**: Edad en años de cada paciente.
- **Sexo**: Sexo de cada paciente (0 = Hombre, 1 = Mujer).
- **Texto Clínico**: Descripción del diagnóstico del paciente.

## Requisitos

Este proyecto requiere las siguientes bibliotecas de Python:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

Puedes instalar todas las dependencias necesarias utilizando el archivo `requirements.txt`.

```bash
git clone https://github.com/joqvan/proyecto1ml.git
pip install -r requirements.txt
