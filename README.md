# Super Mario Galaxy

Uma landing page estática inspirada em um filme de aventura cósmica do Super Mario.

## Visão geral

Este projeto apresenta uma página responsiva com:
- seção hero com vídeos em loop de Mario, Yoshi e um planeta 3D
- navegação flutuante com âncoras internas
- letreiro em movimento de personagens
- seção de personagens com imagens e figcaption
- carrossel de trailers incorporados
- efeitos de paralaxe e animação ao rolar a página
- fundo animado de estrelas em canvas

## Estrutura do projeto

- `index.html` — marcação principal da página
- `css/styles.css` — estilos e layout do projeto
- `js/script.js` — inicialização do canvas, navegação e outras interações
- `js/scroll-animations.js` — lógica de paralaxe e animações de rolagem
- `assets/` — imagens e vídeos usados na página

## Como visualizar

1. Abra `index.html` diretamente no navegador.
2. Opcional: use uma extensão ou servidor local para servir o site, por exemplo:
   - VS Code Live Server
   - `python -m http.server` na pasta do projeto

## Observações

- O projeto não depende de bibliotecas externas.
- Os vídeos e imagens são carregados localmente a partir da pasta `assets`.
- Para melhor performance, o site usa `loading="lazy"` em imagens e animações reduzidas quando o usuário prefere movimento reduzido.
