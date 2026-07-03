## Prompt

Analise o código-fonte abaixo e calcule a métrica **LCOM96** para cada classe.

### Considere

- **m** = quantidade de métodos da classe
- **a** = quantidade de atributos da classe
- **μ(Aj)** = quantidade de métodos que acessam diretamente o atributo **Aj**

### Utilize a fórmula

\[
LCOM96 = \frac{1}{a} \times \sum \left( \frac{m - \mu(A_j)}{m} \right)
\]

### Para cada classe

1. Liste todos os atributos.
2. Liste todos os métodos.
3. Monte uma matriz mostrando quais métodos utilizam quais atributos.
4. Calcule **μ(Aj)** para cada atributo.
5. Mostre o cálculo detalhado da fórmula.
6. Informe o valor final do **LCOM96**.
7. Classifique a coesão conforme a tabela:

| Faixa do LCOM96 | Classificação |
|----------------:|---------------|
| 0.0 – 0.2       | Excelente     |
| 0.2 – 0.4       | Boa           |
| 0.4 – 0.6       | Média         |
| 0.6 – 0.8       | Ruim          |
| 0.8 – 1.0       | Muito Ruim    |

### Ao final

- Crie um ranking das classes ordenadas pelo maior **LCOM96**.
- Identifique possíveis violações do **Single Responsibility Principle (SRP)**.
- Sugira possíveis extrações de classes quando houver baixa coesão.