# Site de Currículo Pessoal — Adelina Jorge

## Sobre o Projeto
Site pessoal de currículo (portfólio), desenvolvido em HTML5 e CSS3 puro, sem frameworks nem JavaScript, como Trabalho Prático I da disciplina de Programação de Design Web, 2º ano de Licenciatura em Informática, Universidade Licungo.

**Estudante:** Adelina Jorge
**Turma:** 1

## Como Visualizar
Basta abrir o ficheiro `index.html` num navegador (Chrome, Edge, Firefox, etc.).

## Páginas do Site
- **index.html** — Home: apresentação pessoal, foto, vídeo de apresentação e chamada para contacto.
- **about.html** — Currículo: formação académica e tabela de competências técnicas.
- **portfolio.html** — Portfólio: grelha de projetos, organizada com CSS Grid.
- **hobbies.html** — Hobbies: interesses pessoais organizados com Flexbox, e uma faixa de áudio.
- **contact.html** — Contacto: formulário completo com validação nativa HTML5.

## Principais Tags e Técnicas Utilizadas

### HTML
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` — estrutura semântica da página, em vez de `<div>` genéricos.
- `<figure>`/`<figcaption>` — usados para o certificado na página Currículo, associando imagem e legenda.
- `<table>` com `<thead>`/`<tbody>` — organiza as competências técnicas de forma tabular.
- `<iframe>` (YouTube) — incorpora o vídeo de apresentação.
- `<audio controls>` com `<source>` — reproduz uma faixa na página Hobbies.
- `<form>` com `<fieldset>`/`<legend>` e atributos `required`, `pattern`, `minlength`, `min`/`max`, `accept` — validação nativa do formulário, sem JavaScript.

### CSS
- **Variáveis (`:root`)** — cores e espaçamentos definidos uma vez e reutilizados em todo o site.
- **Flexbox** — usado no header (alinhar nome e menu) e na página Hobbies (cartões organizados).
- **CSS Grid** — usado na página Portfólio para a grelha de projetos, com `repeat(auto-fit, minmax())` para se adaptar ao ecrã.
- **`position: sticky`** — mantém o header fixo no topo ao fazer scroll.
- **Pseudo-classes** (`:hover`, `.active`) — destacam o link da página atual e dão feedback visual ao passar o rato.
- **Pseudo-elemento (`::before`)** — adiciona um símbolo decorativo antes do título da Home.
- **`@keyframes`** — anima suavemente o botão de destaque.
- **`transition`** — suaviza a mudança de cor dos botões e links ao passar o rato.
- **Media queries** (`responsivo.css`) — adaptam o layout a tablet (768px) e telemóvel (480px), com abordagem mobile-first.

## Estrutura de Pastas
```
meu-curriculo/
├── index.html
├── about.html
├── portfolio.html
├── hobbies.html
├── contact.html
├── css/
│   ├── estilo.css
│   └── responsivo.css
└── assets/
    ├── img/
    ├── audio/
    └── ficheiros/
```