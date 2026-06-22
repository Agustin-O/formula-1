# 🏁 Desafio Fullstack: Portal Interativo Fórmula 1#
###Seja bem-vindo ao projeto prático de Desenvolvimento de Sistemas!###
 O seu desafio será construir uma Landing Page de alto impacto para a temporada da Fórmula 1. 
 O objetivo é criar uma interface dinâmica, imersiva e interativa utilizando apenas a tríade fundamental da web: HTML5, CSS3 e JavaScript Vanilla.
 🛑 Regra de Ouro: Para a resolução deste projeto, você não poderá utilizar inteligência artificial (ChatGPT, Copilot, etc.) ou fóruns de respostas prontas. A sua única fonte de consulta permitida será a documentação oficial do <b>W3Schools</b>.🎨 

├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── backgroun-1.jpg
│   ├── backgroun-2.jpg
│   ├── backgroun-3.jpg
    ├── backgroun-4.jpg
│   └── icon.webp
├── pages/
    ├── index.html
    ├── f1-circuits.html
    ├── squads.html
├── .gitignore
├── index.html
└── README.md

# 🛠️ Requisitos Técnicos e Funcionalidades1. 
Estrutura (HTML5 Semântico)O layout deve ser limpo e utilizar as tags semânticas corretas: <header>, <nav>, <main>, e <section>.
No canto superior direito, crie um menu de navegação (<nav>) contendo os links: Home, Equipes e Pistas.2. 
Estilização e Impacto Visual (CSS3)Background Tela Cheia: O container de fundo deve ocupar exatamente 100vw e 100vh e possuir um efeito de transição suave (transition) para que a troca de imagens não seja brusca.Menu de Navegação: Alinhado à direita utilizando Flexbox. 
Use efeitos de hover nos links para indicar interatividade.Tipografia: Importe uma fonte esportiva/moderna via Google Fonts (sugestões: Orbitron, Poppins ou Inter).3. 
Dinamismo e Lógica (JavaScript Vanilla)O JavaScript será o motor do sistema, responsável por dar vida à tela:Troca de Background Automática: Crie um Array com os caminhos das imagens de fundo. O JavaScript deve alterar a propriedade backgroundImage do CSS a cada 5 segundos de forma cíclica.Navegação Inteligente (Single Page Application - SPA): Ao clicar nos links do menu (Home, Equipes, Pistas), o JavaScript deve interceptar o clique, esconder a seção atual e mostrar apenas a seção selecionada pelo usuário, sem recarregar a página.
🔍 Guia de Sobrevivência no W3SchoolsFicou travado na sintaxe? Aqui estão os termos exatos que você deve digitar na barra de pesquisa do W3Schools para encontrar a solução:O que você quer fazer?Termo de busca no W3SchoolsAlinhar o menu no topo direito"CSS Flexbox" ou "CSS Navigation Bar"Fazer a imagem cobrir a tela toda"CSS background-size Property"Criar a lista de imagens no JS"JS Arrays"Fazer o fundo mudar sozinho por tempo"JS Timing Events" (setInterval)Mudar o estilo CSS usando o JS"JS HTML DOM Style"Esconder ou mostrar seções da página"CSS display Property"