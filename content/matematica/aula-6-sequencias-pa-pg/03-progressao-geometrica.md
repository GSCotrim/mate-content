## Progressão geométrica (PG)

Numa **PG**, cada termo é o anterior **multiplicado** por um valor fixo, a **razão** *q*.

*Exemplo:* 3, 6, 12, 24, … tem razão *q = 2*.

**Termo geral:**

```formula
aₙ = a₁ · q^(n−1)
```

**Soma dos n primeiros termos** (q ≠ 1):

```formula
Sₙ = a₁ · (qⁿ − 1) / (q − 1)
```

**Comportamento conforme q:**

- *q > 1* → **crescente** (explode, como juros compostos).
- *0 < q < 1* → **decrescente** (decai, como depreciação ou meia-vida).

```diagram
diagrama · termos de uma PG em pontos sobre uma curva exponencial
```

Assim como a PA corresponde à função afim, a **PG é a versão discreta da função exponencial** — seus termos seguem uma curva exponencial. Por isso *montante de juros compostos é uma PG*.
