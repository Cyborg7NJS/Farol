# Farol (Semáforo) — Projeto simples

Um pequeno exemplo de semáforo feito com HTML, CSS e JavaScript.

## O que é

Esta é uma página estática que mostra um semáforo com três luzes (vermelha, amarela e verde). Ao clicar no botão "Mudar" o semáforo avança para a próxima luz.

## Como funciona (resumido)

- Arquivo principal: `index.html` — contém todo o HTML, CSS e JavaScript em um único arquivo.
- As luzes têm a classe `.luz` e opacidade padrão menor (`opacity: 0.3`).
- A classe `.acesa` torna a luz visível (`opacity: 1`).
- O JavaScript controla a variável `estado`:
  - `0` = vermelho
  - `1` = amarelo
  - `2` = verde
- A função `mudarFarol()` é chamada pelo botão e alterna a classe `.acesa` entre as três luzes.

## Arquivos

- `index.html` — interface, estilos e script.

## Como testar

1. https://cyborg7njs.github.io/Farol/

Feito para demonstração e estudo.
