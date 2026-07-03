# Capítulo 3 - Perguntas para Discussão

## Perguntas do capítulo

### Pergunta 1
Descreva a diferença entre modularidade e granularidade e forneça um exemplo de cada uma.

**Resposta:**
A modularidade trata da divisão de sistemas em partes menores, já a granularidade, está relacionada com o tamanho dessas partes.

**Exemplo de modularidade:** separar um sistema em módulos de Clientes, Pedidos e Pagamentos.

**Exemplo de granularidade:** decidir se o módulo de Pagamentos será um único serviço ou dividido em serviços menores, como Cobrança, Estorno e Conciliação.

### Pergunta 2
Qual a diferença entre acoplamento e coesão?

**Resposta:**
Coesão mede o quanto os elementos de um mesmo módulo estão relacionados entre si. Quanto maior a coesão, melhor.
Acoplamento mede o grau de dependência entre módulos. Quanto menor o acoplamento, melhor.
Um bom projeto busca alta coesão e baixo acoplamento.

### Pergunta 3
O que significa o termo conascência?

**Resposta:**
Conascência é uma forma de medir o grau de dependência entre elementos de um sistema. Ela indica quanto uma mudança em uma parte do código exige alterações em outra para que o sistema continue funcionando corretamente.

### Pergunta 4
Qual a diferença entre conascência estática e dinâmica?

**Resposta:**
A **conascência estática** pode ser identificada por meio da análise do código-fonte, como dependências entre classes, métodos e tipos.

A **conascência dinâmica** depende da execução do sistema e está relacionada à ordem de execução, sincronização ou comunicação entre componentes.

### Pergunta 5
Qual a forma mais forte de conascência?

**Resposta:**
A forma mais forte é a **Conascência de Identidade (Identity)**, pois dois elementos precisam compartilhar exatamente a mesma instância de um objeto para funcionar corretamente.

### Pergunta 6
Qual a forma mais fraca de conascência?

**Resposta:**
A forma mais fraca é a **Conascência de Nome (Name)**, em que dois elementos apenas precisam concordar sobre um mesmo identificador, como o nome de uma variável, método ou atributo.

### Pergunta 7
O que é preferível dentro de um codebase: conascência estática ou dinâmica?

**Resposta:**
Dentro de um mesmo módulo ou codebase, a **conascência estática** é preferível, pois é mais fácil de identificar, compreender e refatorar.

Quando a dependência ocorre entre módulos ou serviços diferentes, é preferível reduzir a conascência estática e aceitar algum nível de **conascência dinâmica**, diminuindo o acoplamento entre os componentes.