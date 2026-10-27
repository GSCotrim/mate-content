## Arranjos, permutações e combinações

Quando escolhemos *p* elementos de um conjunto de *n*, a pergunta decisiva é: **a ordem importa?**

- **Arranjo** — a ordem **importa** (pódio, senha, cargos diferentes).

```formula
A(n,p) = n! / (n − p)!
```

- **Permutação** — arranjo usando **todos** os elementos (ordenar *n* pessoas em fila): *Pₙ = n!*.
- **Combinação** — a ordem **não** importa (escolher uma comissão, uma equipe, números da loteria).

```formula
C(n,p) = n! / [p! · (n − p)!]
```

*Exemplo:* escolher 2 entre 5 pessoas para uma **comissão** (ordem não importa) → *C(5,2) = 10*. Mas escolher entre elas um **presidente e um vice** (ordem importa) → *A(5,2) = 20*.

```diagram
diagrama · comparação entre arranjo (ordem importa) e combinação (ordem não importa)
```

**Regra prática:** "comissão, grupo, equipe" → combinação; "ranking, ordem, cargos distintos, senha" → arranjo ou permutação.
