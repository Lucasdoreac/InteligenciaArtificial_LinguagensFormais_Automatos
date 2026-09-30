# Máquina de Turing para 0ⁿ1ⁿ (n ≥ 1)

- Alfabeto de entrada: `{0, 1}`
- Alfabeto da fita: `{0, 1, X, Y, ␣}` (`␣` = branco)
- Estado inicial: `q0` · Estado de aceitação: `qA`
- Rejeição: falta de regra para o símbolo lido

## Ideia

Marca o primeiro `0` livre com `X`, anda até o primeiro `1` livre e marca com `Y`, volta ao último `X` e repete. Quando não sobra `0`, confere se restaram só `Y`.

## Transições (lê → escreve, move, próximo estado)

| Estado | `0` | `1` | `X` | `Y` | `␣` |
|---|---|---|---|---|---|
| `q0` (procura um 0) | `X`, R, `q1` | — | — | `Y`, R, `q3` | — |
| `q1` (anda até um 1) | `0`, R, `q1` | `Y`, L, `q2` | — | `Y`, R, `q1` | — |
| `q2` (volta) | `0`, L, `q2` | — | `X`, R, `q0` | `Y`, L, `q2` | — |
| `q3` (só Y?) | — | — | — | `Y`, R, `q3` | `␣`, R, `qA` |
