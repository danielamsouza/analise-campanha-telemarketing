# Análise Exploratória de Dados: Otimização de Campanha de Telemarketing Bancário 🎯

## 1. Contexto e Problema de Negócio

O desafio deste projeto é identificar o perfil de cliente com maior probabilidade de aderir a um produto bancário, focando na análise da variável profissão. O objetivo de negócio é otimizar os custos da campanha de telemarketing da empresa, direcionando o orçamento e os recursos da equipe para os grupos com maior taxa de conversão.

## 2. Base de Dados e Ferramentas

* **Linguagem e Ambiente:** Python (Google Colab).
* **Bibliotecas:** Pandas para estruturação, limpeza e análise estatística dos dados.
* **Base de Dados:** Dataset "Bank Marketing" (Kaggle), contendo o histórico de campanhas telefônicas.

## 3. Metodologia (Limpeza e Análise)

* **Importação e Estruturação:** Leitura da base de dados ajustando o separador padrão (`;`) para a correta divisão das colunas.
* **Verificação de Dados Ausentes:** Avaliação da coluna de profissões (`job`), confirmando a categorização de dados não informados como `"unknown"` para preservar a integridade das demais informações financeiras da linha.
* **Transformação de Variáveis:** Conversão da coluna de resposta da campanha (`y`) de texto (`"yes"`/`"no"`) para formato numérico binário (`1`/`0`), permitindo cálculos estatísticos.
* **Análise de Conversão:** Agrupamento dos clientes por profissão e cálculo da média de adesão para descobrir a taxa de conversão exata de cada grupo.

## 4. Principais Descobertas e Recomendações

* **Descoberta:** A análise revelou que **estudantes** e **aposentados** apresentam as maiores taxas de conversão de todo o dataset.
* **Recomendação Estratégica:** A equipe de telemarketing deve priorizar o contato com clientes pertencentes a esses dois perfis. Essa ação focada visa maximizar os resultados da campanha e reduzir o custo de aquisição de clientes (CAC).
