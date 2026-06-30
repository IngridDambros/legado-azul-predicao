# 🏥 Legado Azul — Da Invisibilidade à Predição

> MVP desenvolvido para aplicação de técnicas de Machine Learning na triagem do Transtorno do Espectro Autista (TEA), transformando dados em conhecimento para apoiar pesquisas e futuras soluções tecnológicas.

---

## 📖 Sobre o projeto

O **Legado Azul – Da Invisibilidade à Predição** nasceu da reflexão sobre um dos maiores desafios enfrentados pelas famílias de pessoas autistas:

> **Como garantir continuidade, suporte e qualidade de vida quando os cuidadores não estiverem mais presentes?**

Embora esse problema seja amplo e envolva fatores sociais, econômicos e de saúde pública, este MVP propõe uma primeira etapa tecnológica: demonstrar como técnicas de **Machine Learning** podem ser utilizadas para identificar padrões associados ao risco de TEA a partir de dados de triagem.

O projeto utiliza um conjunto de dados público da **UCI Machine Learning Repository**, permitindo construir uma prova de conceito para aplicação de algoritmos supervisionados em apoio à triagem do transtorno.

---

# 🎯 Objetivos

- Desenvolver um modelo de classificação para triagem do TEA.
- Comparar diferentes algoritmos de Machine Learning.
- Avaliar o desempenho dos modelos utilizando métricas clássicas.
- Demonstrar a viabilidade da aplicação de IA como ferramenta de apoio à triagem.
- Evidenciar a importância da disponibilidade de dados públicos para pesquisas na área da saúde.

---

# 📊 Dataset

**Nome:**

Autism Screening Adult Dataset

**Fonte:**

UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/426/autism+screening+adult

### Contextualização

Como referência para o cenário brasileiro, também foram considerados dados do **Censo Demográfico 2022 (IBGE)**, utilizados exclusivamente para contextualização do problema, não participando do treinamento do modelo.

---

# 🧠 Modelos avaliados

Durante o desenvolvimento foram comparados diferentes algoritmos supervisionados, incluindo:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

O modelo de melhor desempenho foi selecionado após comparação das métricas de avaliação.

---

# 📈 Métricas utilizadas

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de Confusão

---

# 🛠 Tecnologias

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Estrutura do projeto

```
📦 LegadoAzul
│
├── MVP.ipynb
├── README.md
├── requirements.txt
└── imagens/
```

---

# ⚖ Aspectos éticos

Este projeto utiliza exclusivamente dados públicos e anonimizados.

O modelo desenvolvido possui finalidade **acadêmica** e constitui uma **prova de conceito**, não devendo ser utilizado para diagnóstico clínico nem para tomada de decisão individual.

---

# 🚧 Limitações

- Dataset internacional.
- Não representa especificamente a população brasileira.
- Base destinada à triagem inicial.
- Não substitui avaliação realizada por profissionais especializados.

---

# 🚀 Trabalhos futuros

Entre as possíveis evoluções do projeto destacam-se:

- utilização de bases nacionais;
- ampliação do conjunto de dados;
- validação clínica do modelo;
- integração com aplicações voltadas ao apoio à triagem;
- desenvolvimento de ferramentas para acompanhamento longitudinal de pessoas neurodivergentes.

---

# 👩‍💻 Autora

**Ingrid Nogueira Dambros**

Projeto desenvolvido como MVP da Pós-Graduação em Ciência de Dados e Analytics.

---

# 💙 Sobre o Legado Azul

Mais do que um projeto de Machine Learning, o **Legado Azul** busca estimular a discussão sobre a importância da identificação precoce do TEA, da disponibilidade de dados públicos para pesquisa e do desenvolvimento de soluções tecnológicas que contribuam para uma sociedade mais inclusiva.

A invisibilidade não está apenas no diagnóstico tardio, mas também na escassez de informações capazes de impulsionar pesquisas, políticas públicas e inovação em benefício das pessoas neurodivergentes.
