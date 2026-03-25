# App Internet

Projeto de estudos de desenvolvimento web com HTML e CSS, organizado em aulas progressivas.

## Estrutura do projeto

```
app_internet-main/
├── aula_3/
│   ├── index.html      # Portal de Notícias — HTML semântico e CSS inline
│   └── lighthouse.jpg
└── aula_4/
    ├── index.html      # Portal de Notícias — HTML refatorado
    └── style.css       # CSS externo com design system próprio
```

## Aulas

### Aula 3
Introdução ao HTML semântico com elementos como `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>` e `<footer>`.
Estilização feita com CSS interno (dentro da tag `<style>`).

**Conteúdo abordado:**
- Estrutura semântica de página
- Navegação acessível com `aria-label` e `aria-current`
- Formulários com validação nativa (`required`, `pattern`, `minlength`)
- Elementos de mídia: `<figure>`, `<picture>`, `<video>`, `<audio>`
- Acessibilidade: skip link, `aria-live`, `aria-describedby`

### Aula 4
Separação entre estrutura (HTML) e apresentação (CSS), movendo todo o estilo para um arquivo `style.css` externo.

**Conteúdo abordado:**
- Arquivo CSS externo vinculado via `<link rel="stylesheet">`
- Remoção de estilos inline
- Design system com paleta de cores consistente
- Cards com `box-shadow` e `border-radius`
- Responsividade com `@media`
- Preferência de acessibilidade `prefers-reduced-motion`

## Como visualizar

Abra o arquivo `index.html` de qualquer aula diretamente no navegador — não é necessário servidor.

## Tecnologias

- HTML5
- CSS3 (sem frameworks)
