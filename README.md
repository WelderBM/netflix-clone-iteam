<h1 align="center">🎬 Netflix Clone - iTeam 🎬</h1>

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

<br>

> Clone fiel da interface da Netflix, desenvolvido com HTML, CSS e JavaScript puro como projeto de estudos práticos de frontend.

<br>

## Sumário

- [Preview do Projeto](#preview-do-projeto)
- [Status do Projeto](#status-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Como Rodar Localmente](#como-rodar-localmente)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [O que Aprendi](#o-que-aprendi)
- [Desenvolvedor](#desenvolvedor)

---

## Preview do Projeto

<p align="center">
  <em>Clone da interface da Netflix com seleção de perfis e página principal com carrosséis interativos.</em>
</p>

---

## Status do Projeto

🚀 **Concluído** ✅

O projeto está finalizado com as principais funcionalidades implementadas, fiel ao design original da Netflix.

---

## Funcionalidades

- ✅ **Tela de Seleção de Perfis** — Página inicial com múltiplos perfis de usuário, incluindo a opção de adicionar novo perfil e gerenciar perfis existentes.
- ✅ **Header Dinâmico** — Navbar que muda de aparência com fundo escuro ao rolar a página (efeito scroll).
- ✅ **Carrosséis de Filmes/Séries** — Múltiplas seções de conteúdo com rolagem horizontal:
  - 🔥 Populares na Netflix
  - ▶️ Continuar Assistindo (com barra de progresso individual)
  - 📈 Em Alta
  - 🎬 Filmes Originais da Netflix
  - 🏆 Top 10 (ranking com numeração)
  - 🔄 Assistir Novamente
  - 👤 Para Você
- ✅ **Navegação por Setas** — Botões de avançar/voltar que aparecem/desaparecem dinamicamente conforme a posição do scroll.
- ✅ **Arrastar para Rolar (Drag-to-Scroll)** — Interação de arrastar o mouse para navegar horizontalmente nos carrosséis.
- ✅ **Barras de Progresso** — Indicadores visuais de progresso para filmes/séries em andamento.
- ✅ **Poster Hero** — Banner principal com informações do filme em destaque, botões de "Assistir" e "Mais Informações".
- ✅ **Footer Completo** — Rodapé com ícones de redes sociais e links de navegação, fiel ao original.
- ✅ **Layout Responsivo** — Interface adaptada para diferentes tamanhos de tela.

---

## Estrutura de Pastas

```
netflix-clone-iteam/
│
├── assets/
│   ├── arrows-icons/       # Ícones de setas para navegação dos carrosséis
│   ├── generic-icons/      # Ícones gerais (lupa, sino, play, info, etc.)
│   ├── post-numbers/       # SVGs de numeração para o ranking Top 10
│   ├── posters/            # Imagens dos pôsteres de filmes e séries
│   ├── profiles/           # Avatares de perfil de usuário
│   ├── social-icons/       # Ícones das redes sociais (Facebook, Instagram, etc.)
│   ├── MovieName.svg       # Logo/título do filme em destaque (hero)
│   └── netflix-logo.svg    # Logotipo da Netflix
│
├── css/
│   ├── globals.css         # Variáveis e estilos globais (reset, fontes, utilitários)
│   ├── style.css           # Estilos da tela de seleção de perfis (index.html)
│   └── main.css            # Estilos da página principal (main.html)
│
├── fonts/                  # Fontes customizadas do projeto
│
├── js/
│   └── scripts.js          # Lógica de interatividade (scroll, drag, setas, header)
│
├── index.html              # Página de seleção de perfis
└── main.html               # Página principal com os carrosséis de conteúdo
```

---

## Como Rodar Localmente

Por ser um projeto em **HTML, CSS e JavaScript puro**, não há necessidade de instalação de dependências.

### Opção 1 — Abrir diretamente no navegador

1. Clone o repositório:
   ```bash
   git clone https://github.com/WelderBM/netflix-clone-iteam.git
   cd netflix-clone-iteam
   ```

2. Abra o arquivo `index.html` no seu navegador.

### Opção 2 — Usar o Live Server (Recomendado)

Para evitar possíveis problemas com o carregamento de arquivos locais:

1. Instale a extensão **Live Server** no VS Code.
2. Clique com o botão direito no `index.html` e selecione **"Open with Live Server"**.

### Opção 3 — Usar http-server via Node.js

```bash
npm install -g http-server
http-server .
```

Acesse `http://localhost:8080` no navegador.

---

## Tecnologias Utilizadas

| Tecnologia | Finalidade |
|---|---|
| [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML) | Estruturação semântica do conteúdo das páginas |
| [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) | Estilização, layout (Flexbox), animações e responsividade |
| [JavaScript (Puro)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) | Interatividade: drag-to-scroll, navegação por setas, efeito de scroll no header |

---

## O que Aprendi

Este projeto foi desenvolvido como um desafio prático de clone de interface, e durante o processo foram trabalhados e aprimorados os seguintes conceitos:

- 🧠 **Manipulação do DOM** com JavaScript puro
- 🖱️ **Eventos de mouse** (`mousedown`, `mousemove`, `mouseup`, `mouseleave`) para implementar o drag-to-scroll
- 📜 **Detecção de scroll** para controle dinâmico do header e visibilidade das setas nos carrosséis
- 🎨 **CSS Flexbox** para criar layouts complexos de múltiplas colunas e linhas
- 🔄 **Lógica de carrossel** com scroll horizontal controlado por botões e arrastar
- 📁 **Organização de projeto** com separação de responsabilidades entre arquivos HTML, CSS e JS

---

## Desenvolvedor

<div align="center">
  <a href="https://github.com/WelderBM">
    <img width="180" height="180" style="border-radius: 50%;" src="https://github.com/welderbm.png" alt="Foto de perfil de Welder Barroso"/>
    <br>
    <strong>Welder Barroso</strong>
  </a>
  <br><br>

  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/WelderBM)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/welderbm)

</div>

---

<p align="center">
  Feito com ❤️ por <a href="https://github.com/WelderBM">Welder Barroso</a>
</p>
