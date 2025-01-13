# ML_Classificação_de_Dados_Instituto_Nacional_de_Diabetes

## Introdução
Este projeto utiliza aprendizado de máquina para classificar dados de um conjunto fornecido pelo Instituto Nacional de Diabetes e Doenças Digestivas e Renais. O objetivo é treinar modelos de machine learning para prever a presença de diabetes em pacientes com base em características coletadas .

### 1. Introdução ao Dataset
O dataset utilizado contém informações de mulheres em período de gravidez e possui as seguintes variáveis:

 - PatientID: Identificador único para cada paciente.
 - Pregnancies: Número de gravidezes.
 - PlasmaGlucose: Concentração de glicose no sangue.
 - DiastolicBloodPressure: Pressão arterial diastólica.
 - TricepsThickness: Espessura da dobra cutânea no tríceps.
 - SerumInsulin: Nível de insulina sérica em 2 horas.
 - BMI: Índice de Massa Corporal.
 - DiabetesPedigree: Indicador de predisposição genética para diabetes.
 - Age: Idade do paciente.
 - Diabetic: Variável alvo (1 - diabético, 0 - não diabético).

### 2. Ferramentas e Tecnologias
Utilizamos as seguintes bibliotecas para construir e validar os modelos:

Pandas: Manipulação de dados em DataFrames.
Scikit-learn: Implementação dos algoritmos de classificação e métricas de avaliação.
Numpy: Operações matemáticas com arrays.
Jupyter Notebook: Ambiente interativo para codificação e visualização.

### 3. Processo de Desenvolvimento
    Passo 1: Carregamento e Análise dos Dados.
    Passo 2: Pré-processamento.
    Realizei o pré-processamento para garantir a integridade dos dados, removendo valores nulos e verificando os tipos de dados.
    Passo 3: Separação dos Dados
    Dividi o dataset em 70% para treinamento e 30% para validação, separando as variáveis independentes e a dependente.
    Passo 4: Treinamento dos Modelos
    Treinei dois modelos de machine learning.
    Passo 5: Avaliação dos Modelos
    Avaliei os modelos com as métricas de acurácia e matriz de confusão
    Resultados:
    Regressão Logística: Acurácia de 78.9%.
    SVM: Acurácia de 81.2%.

### 4. Consumo do Modelo
Simulei a entrada de um novo paciente para prever o diagnóstico

### 5. Conclusão
Esse projeto demonstrou como modelos de machine learning podem ser aplicados para problemas reais, como a classificação de pacientes diabéticos.
Regressão Logística: Simples, mas eficaz.
SVM: Melhor performance em dados mais complexos.


Este foi um projeto elaborado na Escola SENAI "Luiz Massa" - Botucatu 
