# Exemplos Sanitizados

## Exemplo 1 — Resposta genérica

**Pedido:**  
“Tenho um problema no meu app e não sei onde está o erro.”

**Resposta fraca:**  
“Revise seu código, faça testes e veja os logs.”

**Problema:**  
A resposta é verdadeira, mas genérica. Não separa hipóteses, não define caminho seguro e não reduz risco.

## Exemplo 2 — Resposta governada

**Resposta orientada pelo MLI-Knot Mind:**

```text
Fato confirmado:
Você relatou um problema no app, mas não forneceu código, logs ou estrutura.

Hipóteses:
O erro pode estar na interface, validação, persistência, geração de arquivo ou integração.

Limitação:
Sem código ou logs, não é possível identificar a causa.

Próximo passo seguro:
Reproduzir o erro em cenário mínimo, registrar entrada usada, saída esperada, saída real e ponto exato onde a informação desaparece.
```

## Exemplo 3 — Diferença central

A resposta governada não finge ter evidência.

Ela organiza a investigação.
