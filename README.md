# desafioTelecomX_BR
Projeto de Análise de Churn da Telecom X com foco na identificação dos fatores que influenciam a evasão de clientes. Envolve coleta de dados via API, processo de ETL, Análise Exploratória (EDA) e geração de insights estratégicos para apoiar decisões de retenção e futuros modelos preditivos.

(Relatório feito com IA)

# 📊 Análise de Evasão de Clientes (Churn Analysis)

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar o fenômeno de evasão de clientes (Churn) em uma base de dados contendo informações demográficas, contratuais e financeiras.

A evasão de clientes representa um dos principais desafios para empresas de serviços recorrentes, impactando diretamente receita, crescimento e previsibilidade financeira. Compreender os fatores associados ao cancelamento permite desenvolver estratégias mais eficazes de retenção.

A análise foi conduzida utilizando Python, com foco em Análise Exploratória de Dados (EDA) e visualizações que permitissem identificar padrões comportamentais.

---

## 🎯 Objetivos

* Identificar padrões associados ao cancelamento de clientes.
* Comparar características de clientes que ficaram vs. clientes que saíram.
* Explorar variáveis categóricas e numéricas relacionadas ao churn.
* Gerar insights estratégicos para redução da evasão.

---

## 🧰 Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 📂 Estrutura da Análise

A análise foi dividida nas seguintes etapas:

### 1️⃣ Limpeza e Tratamento de Dados

* Verificação de inconsistências.
* Conversão de tipos de dados.
* Padronização da variável **Churn** (0 = Ficou | 1 = Saiu).
* Conversão da variável **Total geral** para formato numérico.
* Criação de faixas estratégicas para a variável **Meses de contrato**.

---

### 2️⃣ Análise Exploratória – Variáveis Categóricas

Foram analisadas as taxas de evasão por:

* Gênero
* Tipo de contrato
* Forma de pagamento
* Suporte técnico

A taxa de churn foi calculada utilizando a média da variável binária (0/1), representando a proporção de clientes que cancelaram em cada categoria.

Principais padrões identificados:

* Contratos mensais apresentam maior taxa de evasão.
* Clientes sem suporte técnico apresentam maior probabilidade de cancelamento.
* Algumas formas de pagamento estão associadas a maior churn.

---

### 3️⃣ Análise Exploratória – Variáveis Numéricas

Foram analisadas:

* Meses de contrato
* Total geral (valor acumulado gasto)

A variável **Meses de contrato** foi segmentada em faixas estratégicas:

* 0–12 meses
* 12–24 meses
* 24–36 meses
* 36–60 meses
* 60–72 meses

Essa segmentação permitiu observar que:

* A maior taxa de evasão ocorre nos primeiros 12 meses.
* O risco de churn diminui conforme o tempo de permanência aumenta.
* Clientes antigos apresentam maior estabilidade.

Além disso, foi observado que clientes que cancelaram possuem, em média, menor valor total acumulado.

---

## 📊 Principais Insights

* O tempo de contrato é o fator mais fortemente associado à evasão.
* Contratos de curta duração apresentam maior risco.
* A retenção nos primeiros 12 meses é crítica.
* Clientes com maior tempo de permanência acumulam maior valor financeiro.
* A ausência de suporte técnico aumenta a probabilidade de churn.

---

## 💡 Recomendações Estratégicas

Com base na análise, recomenda-se:

* Implementar estratégias de retenção nos primeiros meses de contrato.
* Incentivar contratos de maior duração.
* Monitorar clientes com contrato mensal.
* Fortalecer suporte técnico como ferramenta de retenção.
* Desenvolver programas de fidelização.

---

## 🚀 Possíveis Extensões

* Construção de modelo preditivo de churn.
* Análise de importância de variáveis.
* Segmentação de clientes por risco.
* Aplicação de técnicas de Machine Learning.

---

## 📎 Conclusão

A análise exploratória permitiu identificar padrões consistentes associados à evasão de clientes. Os resultados demonstram que o churn está fortemente relacionado ao ciclo de vida do cliente e ao tipo de vínculo contratual.

Os insights obtidos fornecem base estratégica para desenvolvimento de políticas de retenção mais eficazes.
