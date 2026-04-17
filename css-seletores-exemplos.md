# Exemplos de seletores em `assets/css/main.css`

Este arquivo lista seletores reais do código e identifica o tipo de cada um.

## 1. Seletores simples
- Linha 63: `body {`
- Linha 69: `a {`
- Linha 80: `h1,` (parte do grupo `h1, h2, h3, h4, h5, h6 {`)
- Linha 92: `.php-email-form .error-message {` (classe)
- Linha 145: `.header {` (classe)
- Linha 386: `#preloader:before {` (ID + pseudo-elemento, mas usa ID como seletor simples)

## 2. Seletores pseudo-classes
- Linha 75: `a:hover {`
- Linha 186: `.header .social-links a:hover {`
- Linha 252: `.navmenu a:focus {`
- Linha 295: `.navmenu .active:focus {`
- Linha 432: `.scroll-top:hover {`

## 3. Seletores combinadores
- Linha 186: `.header .social-links a:hover {` (descendente)
- Linha 343: `.navmenu .dropdown>.dropdown-active {` (filho direto)
- Linha 481: `.page-title .breadcrumbs ol li+li {` (irmão adjacente)
- Linhas 193-194: `.header~main,` e `.header~#footer {` (irmão geral)

## 4. Seletores pseudo-elementos
- Linha 120: `.php-email-form .loading:before {`
- Linha 540: `.section-title h2:before,` e `.section-title h2:after {`
- Linha 485: `.page-title .breadcrumbs ol li+li::before {`

## 5. Seletores de atributos
- Linha 447: `[data-aos-delay] {`

## Observações
- O arquivo `index.html` usa classes e IDs que correspondem a esses seletores, por exemplo `class="header"`, `id="preloader"`, `class="navmenu"`, `data-aos-delay="100"`.
- Não há seletor universal (`*`) em `assets/css/main.css`.
