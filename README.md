# Satoshy — Restaurante Japonês

O Satoshy é um site escolar de restaurante japonês. Ele apresenta o restaurante, o cardápio, informações sobre o estabelecimento e uma página de contato. O visual usa tons de marrom inspirados na proposta do restaurante.

## Funcionalidade desta etapa

A página inicial possui uma busca de pratos. O JavaScript usa `fetch()` para carregar o arquivo `data/pratos.json`, converte a resposta com `response.json()` e atualiza a página sem recarregar. A busca considera somente os pratos e as categorias que já aparecem no cardápio do Satoshy. Também há tratamento de erros com `try/catch` e mensagens para quando não há resultados ou o arquivo não pode ser carregado.

> Nesta etapa, os dados vêm de um arquivo JSON do próprio projeto. A integração com uma API REST feita em Flask fica para a próxima etapa, conforme a apostila de DWS.

## Tecnologias

- HTML5 semântico
- CSS3 responsivo
- JavaScript (`async/await`, `fetch`, JSON, DOM e `try/catch`)
- GitHub e GitHub Pages

## Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta no Visual Studio Code.
3. Inicie o `index.html` com a extensão **Live Server**. O `fetch()` precisa que o site seja aberto por um servidor, e não diretamente como `file://`.
4. Pesquise, por exemplo, `salmão`, `temaki` ou `yakissoba`. Para testar o cenário sem resultados, digite um nome que não esteja no cardápio.

## Estrutura

```text
satoshy/
├── index.html
├── css/style.css
├── js/script.js
├── data/pratos.json
├── img/images.jpg
└── pages/
    ├── cardapio.html
    ├── sobre.html
    └── contato.html
```

## Publicação

O site estático pode ser publicado no GitHub Pages em **Settings → Pages**, selecionando a branch `main` e a pasta raiz (`/(root)`). Depois, aguarde a publicação e use o endereço exibido pelo GitHub.

## Entrega

- Repositório: https://github.com/luisaporcel2026/satoshy
- Site publicado: adicione aqui o link gerado pelo GitHub Pages.

Desenvolvido por Luisa Porcel — DWS, 2026.
