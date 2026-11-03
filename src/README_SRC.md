# Código-fonte reutilizável

A pasta `src/` foi mantida como referência para uma possível evolução da arquitetura do projeto, porém **não é utilizada na versão atual da solução**.

Neste Tech Challenge, o fluxo foi desenvolvido integralmente em notebooks Databricks, que concentram as etapas de:

- preparação e enriquecimento dos dados;
- engenharia de atributos;
- treinamento e validação dos modelos;
- avaliação e interpretabilidade;
- aplicação estratégica e geração dos produtos analíticos.

Por esse motivo, optou-se por **não criar módulos artificiais apenas para preencher a estrutura do repositório**, evitando duplicação de código e alterações tardias em um pipeline já validado.

## Evolução futura

Em uma próxima versão, a solução poderá ser refatorada para extrair funções reutilizáveis dos notebooks e organizá-las em módulos como:

```text
src/
├── preprocessing/
├── modeling/
├── evaluation/
└── visualization/
```

Essa modularização facilitaria testes unitários, reutilização de componentes, manutenção e execução em ambientes produtivos.

> Esta limitação foi mantida de forma intencional e documentada. A modularização em `src/` fica registrada como melhoria para as próximas fases dos projetos.
