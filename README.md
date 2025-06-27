# Fundamentos da Lógica de Programação - Conectivos e Tabela Verdade


Cada seção abaixo apresenta uma frase, suas proposições atomicas, a representação lógica utilizando os conectivos apropriados e a tabela verdade completa.

### 1. Eu estudei para a prova e fiz todos os exercícios.

**Proposições:**
* **P**: Eu estudei para a prova.
* **Q**: Eu fiz todos os exercícios.

**Representação Lógica:** $P \land Q$ (Conjunção)

**Tabela Verdade:**

| **P** | **Q** | **$P \land Q$** |
| :---: | :---: | :----------: |
| V     | V     | **V** |
| V     | F     | F            |
| F     | V     | F            |
| F     | F     | F            |

---

### 2. Eu vou ao cinema ou fico em casa assistindo séries.

**Proposições:**
* **P**: Eu vou ao cinema.
* **Q**: Eu fico em casa assistindo séries.

**Representação Lógica:** $P \lor Q$ (Disjunção Inclusiva)

**Tabela Verdade:**

| **P** | **Q** | **$P \lor Q$** |
| :---: | :---: | :----------: |
| V     | V     | **V** |
| V     | F     | **V** |
| F     | V     | **V** |
| F     | F     | F            |

---

### 3. Se eu acordar cedo, então conseguirei pegar o ônibus.

**Proposições:**
* **P**: Eu acordar cedo.
* **Q**: Eu conseguirei pegar o ônibus.

**Representação Lógica:** $P \rightarrow Q$ (Condicional)

**Tabela Verdade:**

| **P** | **Q** | **$P \rightarrow Q$** |
| :---: | :---: | :---------------: |
| V     | V     | **V** |
| V     | F     | F                 |
| F     | V     | **V** |
| F     | F     | **V** |

---

### 4. Se eu estudar muito, então passarei na prova e ganharei um presente.

**Proposições:**
* **P**: Eu estudar muito.
* **Q**: Eu passarei na prova.
* **R**: Eu ganharei um presente.

**Representação Lógica:** $P \rightarrow (Q \land R)$

**Tabela Verdade:**

| **P** | **Q** | **R** | **$Q \land R$** | **$P \rightarrow (Q \land R)$** |
| :---: | :---: | :---: | :----------: | :-------------------------: |
| V     | V     | V     | V            | **V** |
| V     | V     | F     | F            | F                           |
| V     | F     | V     | F            | F                           |
| V     | F     | F     | F            | F                           |
| F     | V     | V     | V            | **V** |
| F     | V     | F     | F            | **V** |
| F     | F     | V     | F            | **V** |
| F     | F     | F     | F            | **V** |

---

### 5. Eu vou jogar videogame ou vou estudar lógica de programação.

**Proposições:**
* **P**: Eu vou jogar videogame.
* **Q**: Eu vou estudar lógica de programação.

**Representação Lógica:** $P \lor Q$ (Disjunção Inclusiva)

**Tabela Verdade:**

| **P** | **Q** | **$P \lor Q$** |
| :---: | :---: | :----------: |
| V     | V     | **V** |
| V     | F     | **V** |
| F     | V     | **V** |
| F     | F     | F            |

---

### 6. Eu comi pizza e tomei refrigerante.

**Proposições:**
* **P**: Eu comi pizza.
* **Q**: Eu tomei refrigerante.

**Representação Lógica:** $P \land Q$ (Conjunção)

**Tabela Verdade:**

| **P** | **Q** | **$P \land Q$** |
| :---: | :---: | :----------: |
| V     | V     | **V** |
| V     | F     | F            |
| F     | V     | F            |
| F     | F     | F            |

---

### 7. Se eu tiver dinheiro, então viajarei nas férias.

**Proposições:**
* **P**: Eu tiver dinheiro.
* **Q**: Eu viajarei nas férias.

**Representação Lógica:** $P \rightarrow Q$ (Condicional)

**Tabela Verdade:**

| **P** | **Q** | **$P \rightarrow Q$** |
| :---: | :---: | :---------------: |
| V     | V     | **V** |
| V     | F     | F                 |
| F     | V     | **V** |
| F     | F     | **V** |

---

### 8. Eu lerei um livro se e somente se terminar meu trabalho.

**Proposições:**
* **P**: Eu lerei um livro.
* **Q**: Eu terminar meu trabalho.

**Representação Lógica:** $P \leftrightarrow Q$ (Bicondicional)

**Tabela Verdade:**

| **P** | **Q** | **$P \leftrightarrow Q$** |
| :---: | :---: | :-------------------: |
| V     | V     | **V** |
| V     | F     | F                     |
| F     | V     | F                     |
| F     | F     | **V** |

---

### 9. Se estiver sol, então irei à praia ou ao parque.

**Proposições:**
* **P**: Estiver sol.
* **Q**: Irei à praia.
* **R**: Irei ao parque.

**Representação Lógica:** $P \rightarrow (Q \lor R)$

**Tabela Verdade:**

| **P** | **Q** | **R** | **$Q \lor R$** | **$P \rightarrow (Q \lor R)$** |
| :---: | :---: | :---: | :----------: | :------------------------: |
| V     | V     | V     | V            | **V** |
| V     | V     | F     | V            | **V** |
| V     | F     | V     | V            | **V** |
| V     | F     | F     | F            | F                          |
| F     | V     | V     | V            | **V** |
| F     | V     | F     | V            | **V** |
| F     | F     | V     | V            | **V** |
| F     | F     | F     | F            | **V** |

---

### 10. Eu farei um bolo se e somente se comprar os ingredientes.

**Proposições:**
* **P**: Eu farei um bolo.
* **Q**: Eu comprar os ingredientes.

**Representação Lógica:** $P \leftrightarrow Q$ (Bicondicional)

**Tabela Verdade:**

| **P** | **Q** | **$P \leftrightarrow Q$** |
| :---: | :---: | :-------------------: |
| V     | V     | **V** |
| V     | F     | F                     |
| F     | V     | F                     |
| F     | F     | **V** |

---
