# Modelagem e Transformação de Dados com DAX no Power BI

# 1. Objetivo do Projeto
Este projeto descreve a implementação de inteligência de dados utilizando a linguagem DAX (Data Analysis Expressions). O foco é a criação de medidas calculadas e tabelas de suporte para análises financeiras avançadas, indo além das agregações básicas de soma e média.

# 2. Implementação de Inteligência de Dados
Para este cenário de vendas, a arquitetura lógica prevê a criação das seguintes métricas:
Medidas Implícitas vs. Explícitas: Substituição de campos automáticos por medidas DAX customizadas, garantindo maior controle sobre os filtros de contexto.

Cálculos de Performance: Implementação de funções como SUMX para cálculos linha a linha (Ex: Preço Unitário * Quantidade) e CALCULATE para modificar o contexto de filtro (Ex: Total de Vendas apenas para uma categoria específica).
Time Intelligence (Inteligência de Tempo): Planejamento de fórmulas como SAMEPERIODLASTYEAR e DATEADD para comparar o desempenho de vendas com períodos anteriores, essencial para análises sazonais.

# 3. Processamento de Transformação
Além das fórmulas, o planejamento inclui:
Criação de Tabelas Calculadas: Utilização de DAX para gerar tabelas de apoio, como tabelas de calendário customizadas.
Otimização de Medidas: Estruturação de fórmulas eficientes para reduzir o consumo de memória e aumentar a velocidade de resposta dos relatórios.

# 4. Justificativa Técnica
A entrega documenta a maturidade técnica no uso de expressões DAX. Devido à ausência de ambiente Windows para execução do Power BI Desktop, este repositório serve como prova de conceito da lógica matemática e estrutural aplicada ao desafio, demonstrando domínio sobre a sintaxe e aplicação de funções avançadas.
