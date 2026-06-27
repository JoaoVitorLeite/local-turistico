# Busan | Local turístico

> **Idioma:** Português (BR) · [English](README.en.md)

Landing page de turismo sobre Busan, Coreia do Sul, construída apenas com HTML e CSS.

## Sobre o projeto

Página estática que apresenta Busan como destino turístico, com destaque para três atrações históricas. O layout foi baseado em um design do Figma e implementado sem frameworks ou JavaScript.

## Estrutura do projeto

```
local-turistico/
├── assets/
│   ├── busan.png       # Imagem principal da seção hero
│   ├── icone.png       # Ícone do rodapé
│   ├── parque.png      # Imagem do Parque Yongdusan
│   ├── templo1.png     # Imagem do Templo Haedong Yonggungsa
│   └── templo2.png     # Imagem do Templo Beomeo-sa
├── index.html          # Estrutura e conteúdo da página
├── styles.css          # Estilos e layout
├── LICENSE
├── README.md           # Documentação em português
└── README.en.md        # Documentação em inglês
```

## Como executar

Como o projeto é composto apenas por arquivos estáticos, não é necessário instalar dependências.

**Opção 1 — Abrir diretamente no navegador**

Abra o arquivo `index.html` no seu navegador preferido (duplo clique ou arraste o arquivo para a janela do navegador).

**Opção 2 — Servidor local com Python**

```bash
python -m http.server 8080
```

Acesse [http://localhost:8080](http://localhost:8080) no navegador.

**Opção 3 — Extensão Live Server (VS Code / Cursor)**

Instale a extensão **Live Server**, clique com o botão direito em `index.html` e selecione **Open with Live Server**.

## O que foi aprendido

- Estruturação semântica de HTML com seções, hierarquia de títulos (`h1`–`h3`) e listas.
- Estilização com CSS puro: reset de margens, variáveis em `:root` e tipografia com Google Fonts.
- Aplicação de cores, espaçamentos e alinhamentos a partir de um layout no Figma.
- Seletores CSS como pseudo-elementos (`::marker`), pseudo-classes (`:nth-child`) e combinadores adjacentes (`.divider + p`).
- Estilização de imagens, divisores e rodapé para compor uma landing page completa.

## Projeto no Figma

👉 [Acessar o layout original no Figma](https://www.figma.com/community/file/1384542229391733447/local-turistico)

## Tecnologias utilizadas

- HTML5
- CSS3
