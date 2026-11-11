# 👟 Nike Store

Site de vendas de tênis da Nike, desenvolvido como projeto da **N2 – Responsividade e Frameworks**. O projeto evolui o trabalho entregue na N1, com layout responsivo, visual reconstruído com um framework de front-end e animações.

## 🔗 Links

- **Repositório:** https://github.com/jhadylla/Nike-Store

## 🛠️ Tecnologias

- **HTML5**: estrutura das páginas
- **CSS3**: cores, detalhes e animações (`style.css`, carregado depois do framework)
- **JavaScript**: interações da página
- **Bootstrap 5.3**: framework de front-end (via CDN)

## 📱 Responsividade

O layout se adapta a três larguras de tela:

| Dispositivo | Largura | Comportamento |
|---|---|---|
| Celular | até 576px | Cards em 1 coluna e menu hambúrguer |
| Tablet | cerca de 768px | Cards em 2 colunas |
| Computador | 1200px ou mais | Cards em 3 colunas e menu completo |

- Meta tag `viewport` configurada no `<head>`
- Sem rolagem horizontal em nenhuma largura
- Imagens responsivas (não ultrapassam a largura da tela)

## ✨ Animações

- Efeito `hover` nos cards de produtos e nos botões
- Transições suaves (`transition`) em cores e tamanhos
- Animação com `@keyframes` em elementos de destaque

## 📁 Estrutura do projeto

```
Nike-Store/
├── index.html      # Página principal
├── css/
│   └── style.css   # CSS próprio (cores, detalhes e animações)
├── js/
│   └── main.js     # JavaScript
├── img/            # Imagens dos produtos
└── README.md
```

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/jhadylla/Nike-Store.git
   ```
2. Abra a pasta no VS Code.
3. Clique com o botão direito no `index.html` e escolha **Open with Live Server**
   (ou abra o arquivo direto no navegador).

> É necessário ter conexão com a internet para carregar o Bootstrap pelo CDN.

## 👥 Integrantes

| Nome | GitHub |
|---|---|
| Jhadylla (completar sobrenome) | [@jhadylla](https://github.com/jhadylla) |
| Daniel Felipe (completar sobrenome) | [@danielfelipelacerda09-hue](https://github.com/danielfelipelacerda09-hue) |
| (adicionar integrante) | (adicionar usuário) |

## 📚 Disciplina

N2 – Projeto: Responsividade e Frameworks
