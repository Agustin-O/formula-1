# 🏁 Desafio Fullstack: Portal Interativo Fórmula 1

## 📖 Sobre o Projeto
O **Portal Interativo Fórmula 1** é um projeto prático de Desenvolvimento de Sistemas focado na criação de uma *Landing Page* de alto impacto para a temporada da Fórmula 1. O objetivo é desenvolver uma interface dinâmica, imersiva e interativa utilizando exclusivamente a tríade fundamental da web: **HTML5**, **CSS3** e **JavaScript Vanilla**.

> **🛑 Regra de Ouro:** Para a resolução deste projeto, **não é permitido** utilizar inteligência artificial (ChatGPT, Copilot, etc.) ou fóruns de respostas prontas. A única fonte de consulta permitida é a documentação oficial do **W3Schools**.

## 📂 Estrutura do Projeto
O projeto deve seguir rigorosamente a seguinte organização de arquivos e diretórios:

```text
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── background-1.jpg
│   ├── background-2.jpg
│   ├── background-3.jpg
│   ├── background-4.jpg
│   └── icon.webp
├── pages/
│   ├── index.html
│   ├── f1-circuits.html
│   └── squads.html
├── .gitignore
├── index.html
└── README.md
```

## 🛠️ Requisitos Técnicos e Funcionalidades

### 1. Estrutura (HTML5 Semântico)
O layout deve ser limpo e utilizar as tags semânticas corretas: `<header>`, `<nav>`, `<main>` e `<section>`.
*   No canto superior direito, crie um menu de navegação (`<nav>`) contendo os links: **Home**, **Equipes** e **Pistas**.

### 2. Estilização e Impacto Visual (CSS3)
*   **Background Tela Cheia:** O container de fundo deve ocupar exatamente `100vw` e `100vh` e possuir um efeito de transição suave (`transition`) para que a troca de imagens não seja brusca.
*   **Menu de Navegação:** Alinhado à direita utilizando **Flexbox**. Use efeitos de `hover` nos links para indicar interatividade.
*   **Tipografia:** Importe uma fonte esportiva/moderna via Google Fonts (sugestões: *Orbitron*, *Poppins* ou *Inter*).

### 3. Dinamismo e Lógica (JavaScript Vanilla)
O JavaScript será o motor do sistema, responsável por dar vida à tela:
*   **Troca de Background Automática:** Crie um `Array` com os caminhos das imagens de fundo. O JavaScript deve alterar a propriedade `backgroundImage` do CSS a cada **5 segundos** de forma cíclica.
*   **Navegação Inteligente (Single Page Application - SPA):** Ao clicar nos links do menu (Home, Equipes, Pistas), o JavaScript deve interceptar o clique, esconder a seção atual e mostrar apenas a seção selecionada pelo usuário, **sem recarregar a página**.   
