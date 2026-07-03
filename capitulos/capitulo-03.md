# Capítulo 3 - Modularidade

## Resumo

O capítulo apresenta a modularidade como um dos princípios fundamentais da arquitetura de software. Os autores explicam que modularizar um sistema significa organizar elementos relacionados em módulos coesos e com baixo acoplamento, reduzindo a complexidade e facilitando a evolução do software. Também destacam a diferença entre modularidade e granularidade, introduzem os conceitos de coesão e acoplamento e mostram como medir a qualidade da modularização por meio de métricas.

## Ideias centrais

- Modularidade é um princípio de organização de software.
- Modularidade e granularidade são conceitos diferentes.
- Bons módulos possuem alta coesão e baixo acoplamento.
- A quantidade de modularidade pode ser avaliada por meio de métricas arquiteturais.

## Conceitos-chave
- Modularidade: organização lógica de elementos relacionados em módulos.
- Granularidade: tamanho dos módulos ou serviços.
- Coesão: grau em que os elementos de um módulo estão relacionaso entre si.
- Acoplamento: grau de dependência entre módulos.
- Entropia: tendência natural de um sistema perder sua organização ao longo do tempo.
- Acoplamento aferente (CA): quantidade de módulos que dependem de um módulo.
- Acoplamento eferente (CE): quantidade de dependências que um módulo possui.
- Instabilidade (I): métrica que indica a facilidade de mudança de um módulo.
- Abstração(A): proporção entre elementos abstratos e concretos de um módulo.
- Distância da Sequência Principal (D): mede o equilíbrio entre abstração e estabilidade.

## Exemplos e casos citados
- Comparação entre modularidade e granularidade: dividir um sistema em módulos é diferente de decidir o tamanho ideal desses módulos.
- Analogia com a entropia da física para explicar que arquiteturas exigem manutenção constante.
- Exemplos de arquiteturas problemáticas causadas por granularidade inadequada, como **Monólito Distribuído**, **Spaghetti Architecture** e **Big Ball of Distributed Mud**.
- Exemplos do uso das métricas de Robert C. Martin para avaliar a qualidade da modularização.

## Aplicações práticas
- Agrupar funcionalidades relacionadas no mesmo módulo.
- Evitar dependências desnecessárias entre módulos.
- Buscar alta coesão e baixo acoplamento durante o desenvolvimento.
- Revisar periodicamente a arquitetura para evitar a degradação causada pela entropia.
- Avaliar a modularização utilizando métricas, e não apenas percepção.
- Definir a granularidade considerando o contexto e evitando dividir componentes excessivamente.
