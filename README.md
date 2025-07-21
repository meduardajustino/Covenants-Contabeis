# Análise de Covenants Contábeis no Brasil (2010–2022)

Este repositório reúne os scripts e bases de dados utilizados na análise da presença de **covenants contábeis** em empresas listadas na B3, entre os anos de 2010 e 2022. A investigação tem como foco identificar padrões e frequência de cláusulas restritivas em contratos financeiros, com base em informações extraídas de notas explicativas.

## Objetivo

Mapear a incidência de covenants contábeis nas empresas brasileiras de capital aberto, identificando como essas cláusulas se distribuem ao longo do tempo e por setor econômico.

## Arquivos

- `Análise Covenants.ipynb`: Notebook principal contendo o processo de limpeza, análise exploratória e cruzamento dos dados.
- `Base Covenants Contabeis.xlsx`: Base consolidada com registros de cláusulas contábeis extraídas dos documentos analisados.
- `Empresas_com_covenants.xlsx`: Lista de empresas que apresentaram ao menos um covenant contábil no período analisado.
- `empresas_merge_final.xlsx`: Arquivo com informações unificadas das empresas, incluindo indicadores relevantes e presença de covenants.
- `Setores das empresas B3.xlsx`: Classificação setorial das empresas listadas na B3.
- `LICENSE`: Arquivo de licença do projeto (MIT).
- `README.md`: Este arquivo.

## Metodologia

A análise envolve:

- Coleta e padronização de dados extraídos de notas explicativas em PDF.
- Identificação de cláusulas com termos associados a covenants (e.g., índices financeiros, limites de endividamento, violação).
- Cruzamento com setores econômicos e demais características das empresas.
- Análise exploratória e síntese dos resultados por ano e setor.

## Requisitos

- Python 3.10+
- Bibliotecas: `pandas`, `numpy`, `openpyxl`, `matplotlib`, `seaborn`, `jupyter`

## Licença

Este projeto está licenciado sob os termos da Licença MIT.
