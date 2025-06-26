# 🎓 Predição de Desempenho Escolar em Matemática (Ensino Médio)

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Sklearn-orange" alt="Machine Learning">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</div>

## 📌 Visão Geral

Projeto de análise e predição do desempenho final em matemática de estudantes do ensino médio, com base em dados públicos de Portugal (2005-2006). O objetivo é compreender os fatores que influenciam as notas finais e criar modelos preditivos para apoiar ações educacionais.

---

## 🎯 Objetivo

Analisar e prever a nota final (`G3`) dos alunos utilizando dados de notas parciais, características demográficas, hábitos de estudo e apoio familiar. Identificar padrões relevantes para a melhoria do aprendizado.

---

## 📊 Dados Utilizados

O dataset foi obtido do [UCI Machine Learning Repository - Student Performance](https://archive.ics.uci.edu/ml/datasets/Student+Performance) e contém informações como:

- Notas parciais (`G1`, `G2`)
- Dados demográficos (`age`, `sex`, `address`)
- Hábitos de estudo (`studytime`, `failures`)
- Apoio educacional (`schoolsup`, `famsup`)
- Nota final em matemática (`G3`)

---

## 🔍 Metodologia

1. **Importação e limpeza dos dados**: Tratamento de valores faltantes e conversão de tipos.
2. **Análise exploratória**: Visualização das distribuições, correlações e análise do tempo de estudo.
3. **Feature engineering**: Criação de novas variáveis para melhorar a predição.
4. **Modelagem preditiva**: Teste de modelos de regressão com validação cruzada.
5. **Avaliação e interpretação**: Métricas de performance e análise dos resultados.

---

## 📉 Principais Análises e Resultados

- Notas parciais `G1` e `G2` têm alta correlação com a nota final `G3` (até 0.90).
- Estudantes em áreas urbanas apresentam desempenho superior.
- O tempo ideal de estudo está em torno de 2 horas semanais.
- Reprovações anteriores impactam negativamente o desempenho.
- Criação de features relevantes como média das notas parciais e indicadores de declínio de desempenho.

---

## 🚀 Próximos Passos

- Implementar e comparar modelos preditivos: Regressão Linear, Random Forest, XGBoost.
- Aplicar validação cruzada para garantir robustez dos resultados.
- Explorar segmentação por clusters para entender perfis de estudantes.
- Refinar pré-processamento com tratamento de outliers e balanceamento de dados.

---

## 🔗 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais informações.

---

## ✉️ Contato

- **Email:** brunosuassuna.dev@gmail.com  
- **LinkedIn:** [linkedin.com/in/brunosuassuna](https://www.linkedin.com/in/brunosuassuna)

---

**Nota:** Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests.
