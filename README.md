# 🎓 Predição do Desempenho Escolar em Matemática (Ensino Médio) — Análise e Modelagem Preditiva

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue" alt="Python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange" alt="Machine Learning" />
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen" alt="Status" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
</div>

---

## 📖 Resumo do Projeto

Este projeto tem como objetivo analisar e prever o desempenho final dos estudantes do ensino médio em matemática, utilizando um conjunto de dados públicos provenientes de escolas portuguesas (ano letivo 2005-2006). Através de técnicas avançadas de análise exploratória, engenharia de atributos e modelagem preditiva, busca-se identificar os principais fatores determinantes da performance acadêmica e construir modelos robustos que possam auxiliar educadores e gestores em intervenções pedagógicas.

---

## 🎯 Objetivos Específicos

- **Analisar** as variáveis sociodemográficas, hábitos de estudo e histórico escolar que influenciam a nota final em matemática (`G3`).
- **Construir modelos preditivos** capazes de estimar o desempenho dos alunos com base em dados parciais (`G1`, `G2`) e outras características.
- **Avaliar e comparar** a performance dos modelos para garantir precisão e generalização.
- **Gerar insights** que possam fundamentar estratégias educacionais visando a melhoria do aprendizado.

---

## 📚 Dataset

Os dados foram obtidos do repositório público UCI Machine Learning Repository — [Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/Student+Performance) — e contemplam:

| Tipo de Variável       | Exemplos                                    |
| --------------------- | ------------------------------------------ |
| **Notas parciais**    | `G1` (1º período), `G2` (2º período)       |
| **Demográficas**      | `age` (idade), `sex` (sexo), `address` (urbano/rural) |
| **Hábitos de estudo** | `studytime` (tempo semanal dedicado), `failures` (reprovações anteriores) |
| **Apoio educacional** | `schoolsup` (apoio escolar extra), `famsup` (apoio familiar) |
| **Nota final**        | `G3` (nota final em matemática)             |

---

## 🔍 Metodologia

1. **Pré-processamento dos dados**
   - Tratamento de valores ausentes e inconsistências.
   - Conversão e codificação de variáveis categóricas para formatos adequados.
   - Detecção e tratamento de outliers.

2. **Análise Exploratória de Dados (EDA)**
   - Visualização das distribuições das variáveis e identificação de padrões.
   - Análise de correlação entre variáveis preditoras e `G3`.
   - Investigação do impacto do tempo de estudo e histórico escolar no desempenho.

3. **Engenharia de Atributos**
   - Criação de variáveis derivadas, como média entre `G1` e `G2`.
   - Indicadores de tendência de desempenho (melhora ou declínio entre os períodos).
   - Transformações para normalização e escalonamento.

4. **Modelagem Preditiva**
   - Implementação de modelos de regressão linear e ensemble (Random Forest, XGBoost).
   - Utilização de validação cruzada k-fold para avaliação robusta.
   - Otimização de hiperparâmetros via Grid Search.

5. **Avaliação e Interpretação**
   - Métricas principais: R², RMSE, MAE.
   - Análise da importância das variáveis no modelo.
   - Visualização de resíduos e análise de erros.

---

## 📊 Principais Resultados

- **Correlação alta** entre notas parciais (`G1`, `G2`) e a nota final `G3` (coeficiente ~0.90), indicando forte preditividade.
- Estudantes residentes em áreas urbanas tendem a apresentar desempenho superior em matemática.
- **Tempo ideal de estudo** identificado em torno de 2 horas semanais para melhor rendimento médio.
- Histórico de reprovações anteriores (`failures`) impacta negativamente o desempenho final.
- Features criadas como média das notas parciais e indicadores de tendência temporal aumentaram a capacidade preditiva dos modelos.

---

## 🚀 Próximos Passos

- Expandir a modelagem para incluir técnicas avançadas de aprendizado de máquina, como Gradient Boosting e Redes Neurais.
- Implementar análise de segmentação (clusterização) para identificar perfis distintos de estudantes e personalizar recomendações.
- Aplicar técnicas de tratamento de dados desbalanceados e outliers para maior robustez.
- Desenvolver dashboards interativos para visualização dinâmica dos resultados e insights.
- Realizar análises de sensibilidade para testar a estabilidade do modelo frente a variações nos dados.

---

## 📁 Estrutura do Repositório

A organização dos arquivos e diretórios deste projeto segue o padrão abaixo, facilitando a navegação e manutenção do código e dados:

| Diretório / Arquivo | Descrição                                         |
|--------------------|--------------------------------------------------|
| `/data`            | Dados brutos originais e dados tratados após o pré-processamento. |
| `/notebooks`       | Notebook interativo (Google Colab) contendo análises exploratórias, visualizações e experimentos de modelagem. |
| `/scripts`         | Scripts Python para pré-processamento, limpeza e construção dos modelos preditivos. |
| `/outputs`         | Resultados gerados, como gráficos, relatórios e modelos treinados. |
| `/LICENSE`         | Arquivo com a licença MIT que rege o uso e distribuição do projeto. |
| `/README.md`       | Documentação principal do projeto, contendo descrição, instruções e informações gerais. |



---

## ⚖️ Licença

Este projeto está licenciado sob a **Licença MIT**. Consulte o arquivo [LICENSE](LICENSE) para detalhes.

---

## 📬 Contato

Caso tenha dúvidas, sugestões ou queira contribuir, entre em contato:

- **Email:** brunosuassuna.dev@gmail.com  
- **LinkedIn:** [linkedin.com/in/brunosuassuna](https://www.linkedin.com/in/brunosuassuna)

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, propor melhorias e enviar pull requests.



