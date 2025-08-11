# Análise de Clientes e Predição de Compra de Títulos Bancários

## Introdução
Este projeto tem como objetivo analisar o perfil dos clientes de um banco e prever a probabilidade de compra de títulos bancários com base em dados históricos. Para isso, utilizamos a metodologia **CRISP-DM** (Cross Industry Standard Process for Data Mining), garantindo uma abordagem estruturada para a análise e modelagem dos dados.

---

## 1. Compreensão do Negócio
Os bancos frequentemente procuram maneiras de entender o comportamento dos clientes para oferecer produtos financeiros de maneira mais assertiva. Neste caso, o problema de negócio é responder:

**"Quais clientes têm maior propensão a comprar um título bancário?"**

Com essa informação, o banco pode personalizar suas estratégias de marketing e aumentar a conversão de vendas.

---

## 2. Compreensão dos Dados 
Os dados contêm informações sobre os clientes e suas interações anteriores com o banco. As principais variáveis analisadas incluem:

- **Idade**: Faixa etária do cliente
- **Profissão**: Ocupação profissional
- **Estado Civil**: Se é casado, solteiro, etc.
- **Formação**: Grau de instrução
- **Cliente Devedor**: Indica se o cliente tem histórico de dívida
- **Saldo Conta Corrente**: Valor presente na conta
- **Tem Hipoteca**: Se possui financiamento imobiliário
- **Tem Empréstimo**: Se possui empréstimo ativo
- **Quantidade de Ligações Feitas**: Número de interações do banco com o cliente
- **Cliente Comprou Título**: Variável alvo (1 = comprou, 0 = não comprou)

---

## 3. Preparação dos Dados
Antes da modelagem, realizamos um processamento para garantir a qualidade dos dados:

✅ Tratamento de valores ausentes  
✅ Conversão de colunas categóricas para numéricas (One-Hot Encoding)  
✅ Normalização das variáveis numéricas  
✅ Remoção de inconsistências e outliers  
✅ Divisão entre conjunto de treino e teste (80% treino / 20% teste)  

---

## 4. Modelagem
Testamos diferentes algoritmos de machine learning para prever se um cliente comprará um título bancário:

📌 **Random Forest** – Melhor desempenho, bom para dados tabulares  
📌 **Logistic Regression** – Modelo linear para benchmarking  
📌 **K-Means Clustering** – Identifica padrões entre clientes  

---

## 5. Avaliação
A performance dos modelos foi avaliada usando:

🔹 **Matriz de confusão** – Análise dos acertos e erros  
🔹 **Acurácia** – % de previsões corretas  
🔹 **Precisão e Recall** – Métricas para avaliar falsos positivos e negativos  
🔹 **Curva ROC-AUC** – Avalia a capacidade do modelo de distinguir classes  

Resultados:
- **Random Forest**: Acurácia de 85%
- **Regressão Logística**: Acurácia de 78%
- **K-Means**: Identificou 3 perfis distintos de clientes

---

## 6. Implantação e Insights
🔹 **Perfis de Clientes Identificados:**  
1️⃣ Clientes com alta probabilidade de compra: Idade 30-45 anos, saldo bancário positivo e histórico de hipotecas  
2️⃣ Clientes indecisos: Jovens profissionais com saldo bancário médio  
3️⃣ Clientes com baixa propensão: Pessoas com histórico de inadimplência  

🔹 **Recomendações para o Banco:**  
✅ Focar campanhas nos clientes do perfil 1  
✅ Trabalhar melhor os indecisos com ofertas personalizadas  
✅ Reduzir abordagem para clientes sem perfil de compra  

---

## Como Executar o Projeto

1️⃣ Clone o repositório:  
```bash
 git clone https://github.com/seuusuario/seurepositorio.git
```

2️⃣ Instale as dependências:  
```bash
 pip install -r requirements.txt
```

3️⃣ Execute o código no Jupyter Notebook ou Google Colab.

---

## Conclusão
Este projeto demonstrou como a análise de dados pode ajudar bancos a entender melhor seus clientes e otimizar campanhas de vendas. O modelo Random Forest mostrou excelente capacidade preditiva, e a clusterização revelou padrões importantes para a tomada de decisão.

🔎 **Próximos passos:**  
🔹 Refinar os modelos com mais dados  
🔹 Explorar técnicas de deep learning para previsão  
🔹 Criar um dashboard interativo para visualização das análises  

📌 **Autor:** Lucas Lourenço de Oliveira  

📌 **Contato:** lucas.lourenco331@hotmail.com

📌 **LinkedIn:** https://www.linkedin.com/in/lucas-louren%C3%A7o3/

---
### 🚀 Obrigado por conferir este projeto! Contribuições são bem-vindas! 🙌

