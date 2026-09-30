# SIGC - Comunicação Interplanetária

Projeto acadêmico desenvolvido para simular um Sistema Inteligente de Gerenciamento da Comunicação Interplanetária.

## Objetivo

Desenvolver um protótipo capaz de organizar, priorizar, transmitir e analisar mensagens entre diferentes pontos de comunicação, considerando falhas, ruídos e níveis de prioridade.

## Funcionalidades desenvolvidas

- Cadastro de mensagens
- Priorização utilizando fila de prioridade
- Processamento de mensagens
- Simulação de falhas de comunicação
- Histórico de transmissões
- Indicadores de sucesso e falha
- Busca de registros
- Estrutura Trie para busca eficiente
- Busca por prefixos
- Análise com Pandas
- Simulação de canal numérico com ruído
- Detecção de bits
- Cálculo da taxa de erro
- Avaliação em diferentes níveis de ruído
- Classificação inteligente de alertas
- Visualização de dados com gráficos
- Avaliação por matriz de confusão

## Tecnologias utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

## Arquivo principal

`SIGC_Comunicacao_Interplanetaria.ipynb`

## Autor

Hugo Camisotti Junior

## Evidências da implementação

O projeto contempla os principais requisitos por meio das seguintes implementações:

- **Estruturas de dados:** listas, dicionários e DataFrame.
- **Fila de prioridade:** uso do `heapq` para organização das mensagens.
- **Busca eficiente:** implementação de estrutura Trie e busca por prefixo.
- **Análise de dados:** uso de Pandas para organização do histórico.
- **Comunicação numérica:** simulação de sinal binário sujeito a ruído.
- **Detecção de erros:** comparação entre bits transmitidos e recebidos.
- **Métricas de desempenho:** MAE, MSE, RMSE e R².
- **Avaliação de classificação:** uso de matriz de confusão.
- **Sistema inteligente:** classificação automática dos alertas por nível de criticidade.
- **Visualização de dados:** gráficos de desempenho, transmissão e alertas.
