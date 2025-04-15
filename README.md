# ADS 2025 DS Students Performance
Atividade da disciplina de Ciência de Dados - 5º termo ADS 2025

```
pip install -r requirements.txt
```

## Sobre a atividade

Para esta atividade, vamos utilizar o dataset [Students Performance](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset) e por meio das análises, identificar a performace dos alunos.

## Sobre o Dataset

Esse conjunto de dados contém informações abrangentes sobre 2.392 alunos do ensino médio, detalhando seus dados demográficos, hábitos de estudo, envolvimento dos pais, atividades extracurriculares e desempenho acadêmico. A variável de destino, GradeClass, classifica as notas dos alunos em categorias distintas, fornecendo um conjunto de dados robusto para pesquisa educacional, modelagem preditiva e análise estatística.

Traduzido com a versão gratuita do tradutor - [DeepL.com](https://www.deepl.com/pt-BR/translator#en/pt-br/This%20dataset%20contains%20comprehensive%20information%20on%202%2C392%20high%20school%20students%2C%20detailing%20their%20demographics%2C%20study%20habits%2C%20parental%20involvement%2C%20extracurricular%20activities%2C%20and%20academic%20performance.%20The%20target%20variable%2C%20GradeClass%2C%20classifies%20students'%20grades%20into%20distinct%20categories%2C%20providing%20a%20robust%20dataset%20for%20educational%20research%2C%20predictive%20modeling%2C%20and%20statistical%20analysis.)

### Variáveis categóricas

#### ParentalEducation (Escolaridade dos pais)
- 0: None (Não possui)
- 1: High School (Ensino médio)
- 2: Some college (Ensino técnico)
- 3: Bachelor's (Bacharelado)
- 4: Higher (Ensino superior)

#### Tutoring (Tutoria)
- 0: No (Não possui)
- 1: Yes (Possui)

#### ParentalSupport (Auxilio dos pais)
- 0: None (Não possui)
- 1: Low (Baixo)
- 2: Moderate (Moderado)
- 3: High (Alto)
- 4: Very High (Elevado)

#### Extracurricular
- 0: No (Não possui)
- 1: Yes (Possui)

#### Sports (Esportes)
- 0: No (Não possui)
- 1: Yes (Possui)

#### Music (Música)
- 0: No (Não possui)
- 1: Yes (Possui)

#### Voluteering (Voluntário)
- 0: No (Não possui)
- 1: Yes (Possui)

#### GradeClass (Nota)
- 0: 'A' (GPA >= 3.5)
- 1: 'B' (3.0 <= GPA < 3.5)
- 2: 'C' (2.5 <= GPA < 3.0)
- 3: 'D' (2.0 <= GPA < 2.5)
- 4: 'F' (GPA < 2.0)

## Análise Exploratória (EDA)

- [EDA](./notebooks/eda.ipynb)