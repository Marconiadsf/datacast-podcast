<p align="center">
  <img src="./assets/cover.png" width="320" alt="Capa do podcast DataCast">
</p>

# DataCast

Podcast sobre dados e tecnologia criado para o desafio **Criando um Podcast com IAs Generativas**, da DIO.

## Episódio

### Primeiros passos com Databricks

Uma introdução ao Databricks, ao conceito de lakehouse e à arquitetura medalhão.

🎧 [Ouvir o episódio](./output/podcast.mp3)

## Como foi produzido

- nome, estrutura e revisão do roteiro realizados com o Codex;
- informações técnicas conferidas na documentação oficial do Databricks;
- capa criada pelo gerador de imagens integrado ao Codex;
- narração produzida com Edge TTS e a voz masculina brasileira `pt-BR-AntonioNeural`;
- conteúdo revisado para usar linguagem acessível a iniciantes.

## Estrutura do projeto

- `assets/cover.png`: capa do podcast;
- `src/roteiro.md`: roteiro final do episódio;
- `src/roteiro-fonetico.md`: versão adaptada exclusivamente para síntese de voz;
- `src/prompts/texto.md`: prompts utilizados para criação do nome e do roteiro;
- `src/prompts/imagem.md`: prompt utilizado para criar a capa;
- `src/prompts/narracao.md`: instruções da síntese de voz;
- `output/podcast.mp3`: episódio final narrado por voz sintética masculina.

## Tecnologias utilizadas

- Codex para planejamento, redação, revisão e organização do projeto;
- gerador de imagens integrado ao Codex para a capa;
- Edge TTS com a voz `pt-BR-AntonioNeural` para a narração;
- Git e GitHub para versionamento e publicação.

## Contorno de uma limitação da síntese de voz

Na primeira versão do áudio, a voz em português pronunciou termos ingleses como
`lakehouse` usando fonemas inadequados. Para contornar essa limitação técnica, o
projeto mantém duas versões do texto:

- o roteiro editorial, com a grafia tecnicamente correta;
- o roteiro fonético, enviado ao sintetizador com aproximações em português.

Por exemplo, `lakehouse` é representado como `lêique-ráus` e `Apache Spark` como
`apáchi ispárque` somente na entrada do TTS. Esse recurso funciona como uma camada
de pré-processamento: melhora a pronúncia sem introduzir grafias incorretas no
conteúdo destinado à leitura. As substituições utilizadas estão documentadas em
[`src/roteiro-fonetico.md`](./src/roteiro-fonetico.md) e no
[`prompt de narração`](./src/prompts/narracao.md).

## Referências

- [O que é um data lakehouse?](https://docs.databricks.com/aws/en/lakehouse/)
- [Arquitetura medalhão](https://docs.databricks.com/aws/en/lakehouse/medallion)
- [Desenvolvimento em notebooks do Databricks](https://docs.databricks.com/aws/en/notebooks/notebooks-code)

## Projeto-base

Este trabalho foi desenvolvido a partir do repositório
[prompts-for-podcast-generate-by-ia](https://github.com/felipeAguiarCode/prompts-for-podcast-generate-by-ia),
de Felipe Aguiar. A estrutura foi disponibilizada como referência educacional pela
DIO. Capa, tema, roteiro, prompts e áudio deste projeto foram substituídos por
conteúdo autoral do DataCast.

## Aviso

Este conteúdo é introdutório, foi produzido com apoio de inteligência artificial e
passou por curadoria humana.

---

Projeto desenvolvido para fins educacionais durante a formação da DIO.
