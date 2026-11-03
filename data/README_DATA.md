# Dados

Esta pasta é reservada para arquivos de dados locais eventualmente utilizados no projeto.

Na versão atual do Tech Challenge, **os dados não são versionados diretamente neste repositório**. As bases utilizadas são consumidas principalmente a partir do ambiente Databricks e de fontes externas, como BigQuery/Base dos Dados, além das tabelas persistidas nas camadas Silver e Gold do projeto.

Essa decisão evita:

- versionamento de arquivos volumosos;
- duplicação de dados já disponíveis nas fontes oficiais;
- inclusão acidental de credenciais ou informações sensíveis;
- aumento desnecessário do tamanho do repositório.

## Principais fontes utilizadas

- Indicador Criança Alfabetizada;
- INSE;
- Censo Escolar;
- IBGE;
- IDEB / SAEB;
- metas educacionais estaduais e municipais.

As etapas de leitura, tratamento, enriquecimento e persistência estão documentadas nos notebooks da pasta `notebooks/` e no `README.md` principal do projeto.

> A pasta `data/` permanece no repositório para manter uma estrutura organizada e permitir futuras extensões com arquivos de apoio, amostras ou dados locais devidamente documentados.