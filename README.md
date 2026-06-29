# Clique na Aula — Landing page

Página "one page" do app **Clique na Aula** — fotografe o quadro da sala e organize automaticamente em cadernos digitais por matéria.

## Estrutura

```
site/
├── index.html        Página (HTML)
├── css/
│   └── styles.css    Estilos
├── js/
│   └── main.js       Scroll suave dos links
└── img/
    ├── icon.png      Ícone do app
    ├── home.png      Screenshots…
    ├── camera.png
    ├── edit.png
    └── grade.png
```

## Editar

Abra a pasta `site/` no VSCode. Todo o texto está em `index.html`; cores, espaçamentos e layout em `css/styles.css` (as cores ficam nas variáveis `:root` no topo). Troque as imagens em `img/` mantendo os mesmos nomes.

## Publicar no GitHub Pages

1. Suba o conteúdo da pasta `site/` para o repositório (pode ser na raiz ou na pasta `/docs`).
2. Em **Settings → Pages**, escolha a branch e a pasta.
3. Acesse em `https://SEU_USUARIO.github.io/SEU_REPO/`.
