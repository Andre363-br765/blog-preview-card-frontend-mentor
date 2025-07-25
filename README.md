﻿# 📰 Blog Preview Card Frontend Mentor

Este projeto é um **Card de visualização de artigo** feito como desafio da plataforma **Frontend Mentor**, com foco em **HTML** e **CSS**.  
Ele simula a apresentação de um post de blog, com **título**, **data**, **descrição** e **autor**.  
É uma solução visual *simples e limpa*, mas com boas práticas de organização e responsividade.

---

## 🎯 Objetivos

- Praticar a construção de **layouts simples e bem organizados**.
- Trabalhar com **fontes externas** e **variáveis CSS**.
- Aplicar **responsividade** para melhorar a exibição em diferentes tamanhos de tela.
- Explorar efeitos visuais como **sombra com pseudo-elementos**.

---

## 🚀 Tecnologias utilizadas

- `HTML5`
- `CSS3`
  - `Reset` e `style`
  - Estilização principal
  - Estilos responsivos
  - Fontes customizadas (`Figtree`)
  - Variáveis CSS com `:root`
- Efeito de sombra com `::before`

---

## 🧠 Como foi feito

Comecei organizando as pastas como em outros projetos anteriores.  
Tive algumas dúvidas sobre qual fonte da `Figtree` usar (eram 4 opções), mas optei pelas versões `Medium` e `ExtraBold` da pasta `static/`.

Inicialmente, o layout já funcionava bem em tamanhos normais,  
mas ao testar no modo **inspecionar** percebi que alguns dispositivos não estavam com o layout tão ajustado, então decidi incluir o `responsivo.css`.

Outra novidade foi o uso do `:root` para definir **variáveis de cores**,  
algo que aprendi observando projetos anteriores do **Frontend Mentor** — e que funcionou muito bem.

Também usei um efeito de sombra com `::before`, que dá uma sensação de **profundidade** ao card.  
O resultado final lembra um pouco meu projeto anterior do **QR Code**, mas com estrutura e estilo diferentes.

---

## 🧩 Desafios enfrentados

- Escolher qual versão da fonte `Figtree` usar *(eram 4!)*.
- Decidir se adicionaria ou não um CSS para responsividade.
- Aprender como aplicar sombra com **`::before`**.

---

## 📚 O que aprendi

- Trabalhar com **variáveis CSS**.
- Criar efeitos visuais com **`::before`**.
- Melhorar responsividade com **media queries** simples.
- Organizar melhor pastas e fontes em projetos.

---

## 📁 Estrutura de pastas

```bash
blog-preview-card-frontend-mentor
├── docs/
├── src/     
│   ├── assets
│   │   ├── fonts/
│   │   │   ├── static/
│   │   │   │   ├── Figtree-Medium.ttf
│   │   │   │   └── Figtree-ExtraBold.ttf
│   │   │   └── variable/
│   │   │       ├── Figtree-VariableFont_wght.ttf
│   │   │       └── Figtree-Italic-VariableFont_wght.ttf
│   │   └── imagens/          
│   │       ├── favicon-32x32.png
│   │       ├── illustration-article.svg
│   │       └── image-avatar.webp               
│   └── css/
│       ├── reset.css
│       ├── estilos.css
│       └── responsivo.css              
├── index.html
├── README.md
└── .gitignore
```

---

## 🔗 Link do Projeto
[Veja o projeto aqui](https://andre363-br765.github.io/blog-preview-card-frontend-mentor/)
