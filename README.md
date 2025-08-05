# Classificação de Notícias com Big Data e Deep Learning (AG News)
*Projeto de classificação de texto utilizando Spark, MLlib e modelos de Deep Learning para categorizar artigos do dataset AG News.*

---

### 🚩Visão Geral

Este repositório contém o desenvolvimento de um pipeline completo de ML e Deep Learning para a tarefa de classificação de texto. O objetivo principal é categorizar notícias em quatro classes distintas (Mundo, Esportes, Negócios, Sci/Tech) e comparar o desempenho de modelos Machine Learning Spark MLlib com Deep Learning.

---

#### 📋Lista de Conteúdos

- [Visão Geral](#-visão-gearal)
- [Dataset](#-dataset)
- [Tecnologias Utilizadas](#-Tecnologias Utilizadas)
- [Resultados e Análise](#-Resultados-e-análise)
- [Otimização](\#-otimização)
- [Licença](#-Licença)
- [Autor](#-Autor)

---

#### 📦 Dataset

O *dataset* citado é o **AG News**, uma coleção de >120.000 artigos de notícias públicas, divisíveis em 4 classes. Os dados foram obtidos do repositório [Hugging Face Datasets](https://huggingface.co/datasets/sh0416/ag_news).

Encoraja-se que se obtenha os arquivos pela plataforma [Hugging Face](https://huggingface.co/datasets/sh0416/ag_news). Eles se encontram no formato JSON:

-  `train.jsonl`: Contém 120.000 amostras para treinamento.
- `test.jsonl`: Contém 7.600 amostras para teste.

Cada linha no arquivo é um objeto JSON com a seguinte estrutura:

\```json {"text": "Wall St. Bears Claw Back Into the Black (Reuters) Reuters - Short-sellers, Wall Street's dwindling\\band of ultra-cynics, are seeing green again.", "label": 2}``

Onde `label` corresponde a:

- `0`: World (Mundo)

- `1`: Sports (Esportes)
- `2`: Business (Negócios)
- `3`: Sci/Tech (Ciência/Tecnologia)

---

#### :gear: Tecnologias Utilizadas





