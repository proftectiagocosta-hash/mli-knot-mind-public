# Padrão Visual de Repositórios — MLI-Knot / Tendoshk

Este documento registra o padrão visual recomendado para repositórios do ecossistema **MLI-Knot / Tendoshk**.

## Banner padrão

Todo novo repositório do ecossistema deve incluir, no topo do `README.md`, o banner visual compartilhado:

```md
<div align="center">

<img src="https://raw.githubusercontent.com/proftectiagocosta-hash/mli-knot-mind-public/main/assets/matrix-inspired-banner.gif" width="100%" alt="Cyber banner" />

</div>
```

## Forma alternativa simples

Quando a renderização HTML ou alguma ferramenta bloquear o bloco acima, use a forma Markdown simples:

```md
![Cyber banner](https://raw.githubusercontent.com/proftectiagocosta-hash/mli-knot-mind-public/main/assets/matrix-inspired-banner.gif)
```

## Regra de estabilidade

O arquivo central do banner deve permanecer estável em:

```text
mli-knot-mind-public/assets/matrix-inspired-banner.gif
```

Outros repositórios devem referenciar esse arquivo central, em vez de duplicar o GIF em cada projeto.

## Escopo

Este padrão é visual e documental. Ele não autoriza alteração de código, workflows, segredos, governanças privadas, checkpoints reais ou material sensível.

## Objetivo

Criar unidade visual entre os repositórios do ecossistema sem quebrar a separação entre camadas públicas, privadas, sensíveis, pausadas e experimentais.
