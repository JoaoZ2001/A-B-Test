# 📊 Análise A/B Para Dados de uma Webpage

## 📌 Descrição do Projeto
Este projeto tem como objetivo analisar os **cliques** de usuários em uma página web utilizando um **teste A/B**. A base de dados contém três colunas principais:
- **grupo**: identifica se o usuário pertence ao grupo de controle (versão atual) ou ao grupo de tratamento (nova versão).
- **views**: número de visualizações da página.
- **clicks**: número de cliques realizados.

A análise busca responder se há uma diferença estatisticamente significativa na **taxa de cliques** entre os grupos, auxiliando na tomada de decisões baseadas em dados.

---

## 🔧 Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**:
  - `random` → geração de dados aleatórios
  - `numpy` → operações matemáticas
  - `pandas` → manipulação de dados
  - `matplotlib` e `seaborn` → visualização de dados
  - `statsmodels` → modelagem estatística
  - `scipy.stats` → testes estatísticos

---

## 🛠 Etapas da Análise

Foram seguidos os seguintes passos:

1️⃣ **Carregamento dos Dados**  
2️⃣ **Análise Exploratória**  
3️⃣ **Análise com Teste T de Student**  
4️⃣ **Testes de Normalidade (Shapiro-Wilk e Mann-Whitney U)**  
5️⃣ **Conclusão sobre os resultados**  

---

## 📊 Resultados Esperados

✅ A nova versão da página aumentou significativamente a taxa de cliques?  
✅ As diferenças observadas são estatisticamente significativas?  
✅ Devemos adotar a nova versão ou manter a atual?  
