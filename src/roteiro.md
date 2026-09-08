# DataCast - Primeiros passos com Databricks

## Roteiro

Olá! Este é o DataCast.

No episódio de hoje, vamos entender o que é Databricks e conhecer três ideias que aparecem logo no início dos estudos: lakehouse, arquitetura medalhão e notebook.

Databricks é uma plataforma unificada de dados e inteligência artificial baseada na arquitetura lakehouse. Ela combina tecnologias como Apache Spark, para processamento, e Delta Lake, para armazenamento confiável de tabelas, além de recursos para importar, analisar e governar dados em um mesmo ambiente.

O primeiro conceito importante é o lakehouse. O nome combina data lake e data warehouse. Um data lake é usado para armazenar grandes volumes de dados em diferentes formatos. Já um data warehouse organiza dados para consultas, indicadores e relatórios. A arquitetura lakehouse procura reunir as vantagens dessas duas abordagens, reduzindo a necessidade de manter cópias separadas dos mesmos dados.

O segundo conceito é a arquitetura medalhão. Ela organiza o tratamento dos dados em camadas.

Na camada bronze ficam os dados brutos, próximos de como chegaram da fonte. Na camada prata ficam os dados limpos, validados e padronizados. Na camada ouro ficam os dados preparados para relatórios, análises e decisões de negócio.

O terceiro conceito é o notebook. No Databricks, notebooks permitem combinar explicações, consultas e código. É possível trabalhar com linguagens como SQL e Python, observar os resultados e compartilhar o trabalho com outras pessoas da equipe.

Um fluxo inicial pode ser resumido assim: carregar um arquivo, armazenar os dados na camada bronze, corrigir tipos e valores na camada prata e criar uma tabela resumida na camada ouro. Depois, essa tabela pode alimentar um relatório ou uma análise.

Se você está começando, não tente aprender a plataforma inteira de uma vez. Comece com um conjunto pequeno de dados e acompanhe o caminho dele entre as três camadas.

Este foi o DataCast. Até o próximo episódio.

## Fontes consultadas

- [O que é um data lakehouse? - Databricks](https://docs.databricks.com/aws/en/lakehouse/)
- [O que é a arquitetura medalhão? - Databricks](https://docs.databricks.com/aws/en/lakehouse/medallion)
- [Desenvolvimento em notebooks do Databricks](https://docs.databricks.com/aws/en/notebooks/notebooks-code)
