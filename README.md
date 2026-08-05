<h1 align="center">
  🛼 Snitap Patins — Landing Page Animada
</h1>

<p align="center">
  Landing Page responsiva de uma marca fictícia de patins, com animações e transições feitas em <strong>HTML e CSS puro</strong>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages" />
</p>

<p align="center">
  <a href="https://cesar-seixas.github.io/patins-animation/"><strong>🔗 Ver deploy ao vivo</strong></a>
</p>

<p align="center">
  <img src="https://cesar-seixas.github.io/patins-animation/assets/hero/patins-image.png" width="380" alt="Preview do patins Snitap" />
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-demonstração">Demonstração</a> •
  <a href="#-tecnologias">Tecnologias</a> •
  <a href="#-estrutura-do-projeto">Estrutura</a> •
  <a href="#-como-rodar-localmente">Como rodar</a> •
  <a href="#-o-que-eu-pratiquei">O que pratiquei</a> •
  <a href="#-autor">Autor</a>
</p>

<br>

## 📌 Sobre o projeto

Este projeto foi desenvolvido durante a formação **Full-stack**, em uma aula de especialização focada em **animações e transições em CSS**. A proposta era construir a Landing Page responsiva de uma marca de patins ("Snitap"), explorando o máximo possível de efeitos visuais: animações de entrada, transições em scroll/viewport, hover states e uma galeria de fotos dinâmica.

O projeto foi construído em duas frentes:

| Versão | Como foi desenvolvida |
|---|---|
| 🖥️ **Desktop** | Em aula, junto com o professor, seguindo a formação Full-stack |
| 📱 **Mobile** | De forma independente, adaptando o layout e as animações para telas menores |

> O layout é único e responsivo: a adaptação para mobile acontece via `@media` queries dentro de cada arquivo CSS (exceto `index.css`), e não em pastas separadas.

<br>

## 🎬 Demonstração

<details>
<summary><strong>🖥️ Clique para ver a versão Desktop</strong></summary>
<br>

<p align="center">
  <img src="./assets/docs/desktop-demo.gif" width="700" alt="Demonstração da versão desktop" />
</p>

</details>

<details>
<summary><strong>📱 Clique para ver a versão Mobile</strong></summary>
<br>

<p align="center">
  <img src="./assets/docs/mobile-demo.gif" width="300" alt="Demonstração da versão mobile" />
</p>

</details>

<br>

## ✨ Destaques

- 🎞️ Animações de entrada nos elementos do herói (título, botões, imagem do patins)
- 🌀 Transições suaves ao interagir com botões e cards
- 🖼️ Galeria de fotos (`#usesnitap por aí`) com efeitos de hover
- 📱 Layout responsivo, com media queries dedicadas em cada arquivo CSS
- ⚡ Deploy publicado via GitHub Pages

<br>

## 🛠 Tecnologias

<p align="center">
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

Projeto construído com **HTML e CSS puro** — sem frameworks, sem bibliotecas de JavaScript para as animações. Todas as transições e animações foram feitas com recursos nativos do CSS (`@keyframes`, `transition`, `transform`, media queries para responsividade, etc).

<br>

## 📂 Estrutura do projeto

```
patins-animation/
├── assets/               # Imagens, ícones, SVGs e os prints/gifs deste README
├── styles/
│   ├── banner.css        # + media queries (responsivo)
│   ├── footer.css        # + media queries (responsivo)
│   ├── gallery.css       # + media queries (responsivo)
│   ├── global.css        # + media queries (responsivo)
│   ├── header.css        # + media queries (responsivo)
│   ├── hero.css          # + media queries (responsivo)
│   └── index.css         # estilos base, sem media queries
└── index.html
```

> Cada arquivo CSS cuida do seu próprio bloco da página (header, hero, gallery, footer...) e já traz as `@media` queries responsáveis pela versão mobile — só o `index.css`, com os estilos globais/base, fica sem media query.

<br>

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/cesar-seixas/patins-animation.git

# Entre na pasta do projeto
cd patins-animation

# Abra o index.html no navegador
# (ou use a extensão Live Server no VS Code)
```

<br>

## 🧠 O que eu pratiquei

<details>
<summary>Clique para expandir</summary>
<br>

- Criação de animações e transições em CSS puro (`@keyframes`, `transition`, `transform`)
- Animações disparadas por scroll/viewport
- Responsividade para diferentes tamanhos de tela, com adaptação própria da versão mobile
- Organização de assets (ícones, SVGs, imagens) em um projeto real de Landing Page
- Fluxo de trabalho com Git/GitHub, incluindo deploy via GitHub Pages

</details>

<br>

## 👨‍💻 Autor

Desenvolvido por **César Seixas**, durante a formação Full-stack.

<p align="center">
  <a href="https://github.com/cesar-seixas">GitHub</a>
</p>
