# 👟 Nike Store

Site de vendas de tênis, meias e roupas da Nike, desenvolvido como projeto da **N2 – Responsividade e Frameworks** (IFMA). O projeto evolui o trabalho da N1 com foco em layout responsivo, design system próprio (Paleta Editorial: Preto, Creme e Dourado) e animações performáticas sem dependência de JavaScript.

## 🔗 Links

* **Repositório:** [https://github.com/jhadylla/Nike-Store](https://github.com/jhadylla/Nike-Store)
* **Deploy (GitHub Pages):** *(Adicione o link aqui se publicar)*

## 🛠️ Tecnologias

* **HTML5 Semântico**: Estrutura com `<header>`, `<main>`, `<section>`, `<article>` e `<footer>`.
* **CSS3 Avançado**: Variáveis (Design System), Flexbox, Grid (via Bootstrap), animações (`@keyframes`) e transições.
* **Bootstrap 5.3 (CDN)**: Framework base para grid, navbar e utilitários.
* **JavaScript (Vanilla)**: Interações de UI (menu mobile e feedback de botões).
* **Google Fonts**: Tipografia editorial (`Limelight` para títulos e `Libre Caslon Condensed` para texto).

## 📱 Responsividade

O layout foi construído com a abordagem *Mobile First* (via Bootstrap) e testado para se adaptar a três larguras principais:

| Dispositivo | Largura | Comportamento |
| :--- | :--- | :--- |
| **Celular** | até 576px | Cards em 1 coluna, menu hambúrguer, hero adaptado (texto centralizado). |
| **Tablet** | ~768px | Cards em 2 colunas, menu expandido, hero com texto alinhado à esquerda. |
| **Desktop** | 1200px+ | Cards em 3 colunas, layout full-screen no Hero e carrossel lateral. |

* **Sem rolagem horizontal** em nenhuma largura (`overflow-x: clip`).
* **Imagens responsivas** (`img-fluid`) e com `loading="lazy"`.
* **Menu Sticky** com compensação de âncora (`scroll-padding-top`).

## ✨ Animações e Design System

* **Carrossel CSS Puro**: Animação infinita no Hero usando `@keyframes` e `transform: translateX`, sem JavaScript.
* **Micro-interações**: Hover nos cards (elevação e zoom na imagem), botões com efeito *pulse* e transições suaves de cores.
* **Acessibilidade**: Respeito à preferência de movimento reduzido (`prefers-reduced-motion`), `alt` descritivo em todas as imagens e contraste de cores validado (WCAG).
* **Paleta**: Preto (`#0a0a0a`), Creme (`#f4f1ea`) e Dourado (`#d4af37`).

## 📁 Estrutura do projeto

```text
Nike-Store/
├── index.html          # Página principal (Hero + Categorias)
├── css/
│   └── style.css       # Design System, animações e overrides do Bootstrap
├── js/
│   └── main.js         # Lógica do menu e estado dos botões
├── img/                # Imagens dos produtos (.avif, .webp)
├── produtos/
│   ├── sapatos.html    # Catálogo de tênis
│   ├── meia.html       # Catálogo de meias
│   └── roupa.html      # Catálogo de roupas
└── README.md