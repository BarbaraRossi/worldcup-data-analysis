# Etapa 1 - Extração de dados

Esta pasta reúne os datasets brutos utilizados no projeto de análise da Copa do Mundo FIFA, cobrindo o período de 1930 a 2022.

## Origem dos dados

Os arquivos foram obtidos no Kaggle, no dataset:

- [FIFA Football World Cup (1930–2022)](https://www.kaggle.com/datasets/piterfm/fifa-football-world-cup?resource=download)

## Arquivos incluídos

- `world_cup.csv`
- `matches_1930_2022.csv`
- `fifa_ranking_2022-10-06.csv`

## Situação atual da etapa

Neste momento, os dados foram apenas extraídos e organizados nesta pasta.
Ainda não foi realizada uma validação completa de qualidade, portanto:

- não há confirmação de que os dados estejam totalmente limpos;
- ainda será verificado se os arquivos estão fragmentados em informações redundantes;
- também será analisado se os três arquivos se complementam para ampliar as possibilidades de análise.

## Próximos passos

Na segunda etapa do projeto (limpeza), serão executadas as seguintes atividades:

1. Inspeção da estrutura de cada arquivo (colunas, tipos e granularidade).
2. Verificação de valores ausentes, duplicidades e inconsistências.
3. Padronização de nomes, formatos e chaves de relacionamento.
4. Avaliação de integração entre os datasets para compor uma base analítica consistente.
5. Documentação das decisões de limpeza para garantir rastreabilidade no GitHub.
