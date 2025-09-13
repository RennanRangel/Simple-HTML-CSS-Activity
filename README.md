# Projeto HTML e CSS – Exercício de Formatação de Texto

## Descrição
Este projeto é um **exercício prático de HTML e CSS**, focado em:

- Estruturação de conteúdo com `<div>`, `<h1>`, `<p>` e `<span>`.
- Estilização de textos e cores de fundo utilizando CSS.
- Centralização de textos e aplicação de fontes personalizadas.

O objetivo é **aprender a separar conteúdo (HTML) e estilo (CSS)**, aplicando boas práticas de marcação e visualização de textos.

---


## HTML

### Divisão do conteúdo:

1. **`<div class="div-1">`**
   - Contém o título principal `<h1 class="Texto-Principal">Lorem Ipsun</h1>`.
   - Três parágrafos `<p>` com trechos destacados usando `<span>`.
   - Fundo amarelo e texto preto.

2. **`<div class="div-2">`**
   - Três parágrafos `<p>` com texto informativo.
   - Texto na cor vermelha.

---

## CSS (`style.css`)

```css
.Texto-Principal {
    text-align: center;
}

p {
    font-family: 'Arial Black', Arial, Helvetica, sans-serif;
    text-align: center;
}

.div-1 {
    background-color: yellow;
    color: rgb(0, 0, 0);
}

.div-2 {
    color: red;
}


