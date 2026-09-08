# Roteiro fonético para síntese de voz

Este arquivo registra o texto efetivamente enviado ao sintetizador. Ele não
substitui o roteiro editorial: sua função é contornar pronúncias inadequadas de
termos ingleses por uma voz configurada para português brasileiro.

## Mapeamento aplicado

| Grafia original | Entrada fonética do TTS |
| --- | --- |
| Databricks | dêita bríques |
| lakehouse | lêique-ráus |
| data lake | dêita lêique |
| data warehouse | dêita uér-ráus |
| Apache Spark | apáchi ispárque |
| Delta Lake | délta lêique |
| notebook | noute-búque |
| notebooks | noute-búques |
| SQL | ésse-quê-éle |
| Python | páiton |

As aproximações foram usadas apenas para controlar a pronúncia. A grafia correta
permanece em `src/roteiro.md`, no README e nas referências técnicas.

## Texto enviado ao sintetizador

Olá! Este é o DataCast.

No episódio de hoje, vamos entender o que é dêita bríques e conhecer três ideias
que aparecem logo no início dos estudos: lêique-ráus, arquitetura medalhão e
noute-búque.

Dêita bríques é uma plataforma unificada de dados e inteligência artificial
baseada na arquitetura lêique-ráus. Ela combina tecnologias como apáchi ispárque,
para processamento, e délta lêique, para armazenamento confiável de tabelas, além
de recursos para importar, analisar e governar dados em um mesmo ambiente.

O primeiro conceito importante é o lêique-ráus. O nome combina dêita lêique e
dêita uér-ráus. Um dêita lêique é usado para armazenar grandes volumes de dados
em diferentes formatos. Já um dêita uér-ráus organiza dados para consultas,
indicadores e relatórios. A arquitetura lêique-ráus procura reunir as vantagens
dessas duas abordagens, reduzindo a necessidade de manter cópias separadas dos
mesmos dados.

O segundo conceito é a arquitetura medalhão. Ela organiza o tratamento dos dados
em camadas.

Na camada bronze ficam os dados brutos, próximos de como chegaram da fonte. Na
camada prata ficam os dados limpos, validados e padronizados. Na camada ouro ficam
os dados preparados para relatórios, análises e decisões de negócio.

O terceiro conceito é o noute-búque. No dêita bríques, noute-búques permitem
combinar explicações, consultas e código. É possível trabalhar com linguagens como
ésse-quê-éle e páiton, observar os resultados e compartilhar o trabalho com outras
pessoas da equipe.

Um fluxo inicial pode ser resumido assim: carregar um arquivo, armazenar os dados
na camada bronze, corrigir tipos e valores na camada prata e criar uma tabela
resumida na camada ouro. Depois, essa tabela pode alimentar um relatório ou uma
análise.

Se você está começando, não tente aprender a plataforma inteira de uma vez.
Comece com um conjunto pequeno de dados e acompanhe o caminho dele entre as três
camadas.

Este foi o DataCast. Até o próximo episódio.
