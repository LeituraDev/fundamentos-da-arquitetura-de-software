# Fundamentos da Arquitetura de Software

Repositório de referência do **Clube Leitura Dev** para a leitura do livro _Fundamentos da Arquitetura de Software - 2ª edição_, de Mark Richards e Neal Ford.

Este projeto faz parte da rotina de leitura do **Clube Leitura Dev**. A programação oficial dos encontros pode ser acompanhada em `https://leitura.dev/encontros`.

Se alguém quiser usar esta organização como base para criar anotações próprias, há uma versão voltada para esse uso na branch `organizacao-leitura`.

## Objetivo

Este repositório existe para servir como **material de referência do próprio clube** durante a leitura, reunindo resumos, notas e registros produzidos ao longo dos estudos e dos encontros.

O objetivo é centralizar, em um só lugar:

- leitura por capítulo;
- notas de encontro;
- conceitos importantes;
- aplicações práticas e dúvidas.

## Estrutura do repositório

```text
.
|-- README.md
|-- capitulos/
|   |-- README.md
|   |-- capitulo-01.md
|   |-- capitulo-01-discussao.md
|   |-- capitulo-02.md
|   |-- capitulo-02-discussao.md
|   `-- templates/
|       |-- capitulo-discussao.md
|       `-- capitulo.md
|-- encontros/
|   |-- README.md
|   `-- templates/
|       `-- encontro.md
`-- referencias/
    `-- README.md
```

## Como o repositório é construído

O conteúdo deste repositório é alimentado ao longo da leitura e dos encontros do clube.

- `capitulos/` reúne os resumos e as anotações de estudo por capítulo;
- cada capítulo pode ter um arquivo principal e um arquivo separado para as perguntas de discussão do fim do capítulo;
- `encontros/` registra os principais pontos discutidos em cada encontro;
- `referencias/` concentra materiais complementares que ajudam a aprofundar os temas.

## Linha editorial

Para manter o repositório útil como referência coletiva do clube:

- `capitulos/` responde: o que o livro apresenta e quais pontos merecem destaque;
- `capitulos/*-discussao.md` responde: como as perguntas finais do capítulo foram trabalhadas;
- `encontros/` responde: o que foi discutido no clube e o que ficou mais claro;
- `referencias/` reúne materiais complementares que ajudam a aprofundar os temas;
- os resumos e observações são incorporados como parte do registro de estudo do clube.

## Convenções

- `capitulos/capitulo-02.md`, `capitulos/capitulo-03.md`, etc.
- `capitulos/capitulo-02-discussao.md`, `capitulos/capitulo-03-discussao.md`, etc.
- `encontros/2026-07-08.md`, `encontros/2026-07-15.md`, etc.
- Escreva em português, mas preserve termos técnicos em inglês quando fizer sentido.
- Prefira notas curtas e cumulativas a textos longos difíceis de revisar.

As perguntas de discussão presentes ao fim dos capítulos devem ser respondidas em arquivos separados, vinculados ao respectivo capítulo.

## Fluxo de manutenção

- a `main` concentra o material oficial e consolidado do clube;
- a branch `organizacao-leitura` pode ser usada por quem quiser clonar, baixar e adaptar a estrutura para anotações próprias;
- branches temporárias podem ser usadas apenas para mudanças estruturais maiores antes de integrar tudo na `main`.

## Critérios para boas notas

- Resumo: o que o autor quis explicar.
- Interpretação: como você entendeu o conceito.
- Aplicação: onde isso aparece em software real.
- Debate: o que vale levar para o encontro.

## Para quem este repositório é útil

- participantes do Clube Leitura Dev que querem revisar capítulos e encontros;
- pessoas que estão acompanhando a leitura do livro junto ao clube;
- futuras leituras e revisões desse ciclo de estudos.

## Estado atual

- capítulos `01` e `02` já possuem arquivos de resumo e discussão;
- a estrutura está pronta para receber os próximos capítulos e os registros de encontro.
