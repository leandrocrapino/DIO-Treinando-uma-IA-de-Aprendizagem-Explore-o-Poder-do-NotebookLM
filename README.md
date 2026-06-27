# Roteiro de Treinamento: Introdução Prática ao Power BI

Este projeto tem como objetivo criar um roteiro teórico e prático para um treinamento nível iniciante de Power BI, desenvolvido para capacitar os colaboradores da empresa.

## Contexto e Objetivos
Nesse projeto, foi abordado o tema "Roteiro de Treinamento de Power BI", com o objetivo de criar um roteiro teórico e prático para um treinamento nível iniciante da plataforma. A escolha desse tema foi por necessidade, pois estou sendo responsável por montar e apresentar esse treinamento para os colaboradores da empresa em que trabalho.

---

## Curadoria de Fontes
* [Microsoft Learn: Power BI](https://learn.microsoft.com/pt-br/training/powerplatform/power-bi)
* [Alura: Artigos sobre Power BI](https://www.alura.com.br/artigos/power-bi)
* [Microsoft Power Platform](https://www.microsoft.com/pt-br/power-platform/products/power-bi)
* [Quero Bolsa: Carreira de Especialista em BI](https://querobolsa.com.br/carreiras-e-profissoes/especialista-em-business-intelligence)
* [InfoJobs: Analista de Treinamento](https://www.infojobs.com.br/cargo/analista-treinamento)

---

## Engenharia de Prompts e "Cicatrizes"
**Pergunta:** "Preciso que você crie um roteiro de treinamento de Power BI para os colaboradores da minha empresa..."

**Resposta da IA:**
Como Analista Especialista em Treinamentos, elaborei este roteiro estruturado para capacitar os colaboradores da sua empresa a darem os primeiros passos no Power BI.

| Módulo | Duração | Objetivo Principal | Tópicos e Conteúdo |
| :--- | :--- | :--- | :--- |
| **1. Abertura: O "Porquê"** | 0-5 min | Apresentar o valor do Power BI | O que é, para quem é e o fluxo de trabalho (obter, transformar, carregar). |
| **2. O Power Query** | 5-20 min | Limpador de Dados | Conexão com fontes, processo de ETL e limpeza prática. |
| **3. Modelagem** | 20-30 min | O Coração do BI | Estruturação de modelos e introdução à linguagem DAX. |
| **4. O Visual** | 30-50 min | Criando o Painel | Construção de relatórios, exemplos setoriais e IA. |
| **5. Dúvidas** | 50-60 min | Próximos Passos | Sessão de Q&A e fontes de aprendizado contínuo. |

> **Dica para o Instrutor:** Pergunte aos participantes de quais setores eles são (RH, Financeiro, Vendas, etc.) e exemplifique o uso da ferramenta no contexto deles para manter o engajamento.

---

## Roteiro de Exercício Prático
Como Especialista em Inteligência de Negócios (BI) e Instrutor Corporativo, preparei este exercício para consolidar o aprendizado.

### 1. Contexto do Case
Vocês são Analistas de Dados na empresa fictícia "TechStore". O objetivo é criar um **Dashboard de Vendas** para o primeiro trimestre.

### 2. Base de Dados
*   **CSV:** Copie os dados abaixo para um bloco de notas e salve como `vendas_techstore.csv`.
*   **Excel:** Copie a tabela e cole na célula A1 do Excel, salvando como `vendas_techstore.xlsx`.

| Data_Venda | Vendedor | Categoria | Produto | Quantidade | Valor_Unitario |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 01/02/2026 | Ana | Eletrônicos | Smartphone | 5 | 2000,00 |
| 05/02/2026 | Carlos | Acessórios | Fone Bluetooth | 15 | 150,00 |
| 10/02/2026 | Ana | Eletrônicos | Notebook | 2 | 4500,00 |
| 15/02/2026 | Mariana | Acessórios | Cabo USB | 50 | 30,00 |
| 20/02/2026 | Carlos | Eletrônicos | Tablet | 4 | 1800,00 |
| 25/02/2026 | Mariana | Eletrodomésticos | Cafeteira | 3 | 250,00 |

### 3. Passo a Passo no Power BI Desktop
1.  **Obter Dados:** Importar arquivo e selecionar "Transformar Dados".
2.  **O Limpador de Dados (Power Query):** Verificar tipos e criar coluna "Faturamento Total" ([Quantidade] * [Valor_Unitario]).
3.  **Fechar e Aplicar:** Carregar os dados tratados.

### 4. Construção Visual (UX)
*   **Cartão:** Faturamento Total (Canto superior esquerdo).
*   **Gráfico de Colunas:** Faturamento por Categoria (Canto superior direito).
*   **Matriz:** Vendedor x Produto (Base do relatório).

### 5. Perguntas para Análise
1. Qual o valor total do faturamento (Cartão)?
2. Qual categoria gerou a maior receita (Gráfico)?
3. Ao filtrar "Eletrônicos", qual Vendedor mais faturou (Matriz)?

---

## Miniguia de Estudo (Entrega Final)

### 📝 Resumo do Processo de BI
O fluxo de trabalho no Power BI segue três pilares fundamentais:
1.  **ETL (Extração, Transformação e Carga):** O uso do Power Query para limpar e preparar dados brutos.
2.  **Modelagem:** Estabelecer relacionamentos entre tabelas para garantir que os cálculos façam sentido em conjunto.
3.  **Visualização:** Criação de interfaces (Dashboards) que contam uma história e facilitam a tomada de decisão rápida.

### 📖 Glossário de Conceitos
*   **Power Query:** Ferramenta de transformação de dados; o "limpador".
*   **ETL:** Sigla para Extrair, Transformar e Carregar.
*   **DAX:** Linguagem de fórmulas do Power BI (Data Analysis Expressions).
*   **Modelo Semântico:** A estrutura de dados e relacionamentos por trás do relatório.
*   **KPI (Key Performance Indicator):** Indicadores chave de desempenho exibidos em Cartões.
*   **Matriz:** Visual que permite analisar dados cruzados (linhas e colunas), similar a uma Tabela Dinâmica.

### 🤖 Prompts Reutilizáveis
Utilize estes prompts para continuar seus estudos com IAs:

> **Para criar novos exercícios:** "Atue como um Especialista em BI. Crie um desafio prático de nível iniciante em Power BI contendo um dataset pequeno de [INSERIR SETOR, ex: RH] e 3 perguntas de análise para testar a interatividade."

> **Para aprender fórmulas DAX:** "Atue como um instrutor de Power BI. Explique a função [INSERIR FUNÇÃO, ex: CALCULATE] de forma simples, com um exemplo prático aplicado a uma tabela de vendas."

> **Para revisão de conceitos:** "Crie um resumo de 5 pontos principais sobre [INSERIR TÓPICO, ex: Modelagem de Dados no Power BI] focado em boas práticas para iniciantes."
