# Projeto Seletor de Personagens - Marvel's Spider-Man 2

Este simples projeto foi baseado em um evento do canal [Dev em Dobro](https://www.youtube.com/c/devemdobro) que fizeram uma seleção de personagens usando HTML, CSS e JavaScript, como tema o anime One Piece. Tive a liberdade de me basear no projeto deles e personalizar ao meu gosto.

## Índice

- [Visão Geral](#Visão-Geral)
  - [Captura de Tela](#Captura-de-Tela)
- [Meu Processo](#Meu-Processo)
  - [Construído com](#Construído-com)
  - [O que eu aprendi](#O-que-eu-aprendi)
  - [Desenvolvimento Contínuo](#Desenvolvimento-Contínuo)
  - [Autor](#autor)

## Visão Geral

### Captura de Tela
![](/projeto-spider-man-2/src/imagens/screenshot.png)

Esta é uma captura de tela do meu projeto.

## Meu Processo

### Construído com

- HTML5
- CSS3
- JavaScript

### O que eu aprendi

Aprendi um pouco mais da lógica do JS e sua complexidade. 

```JS
const botoes = document.querySelectorAll(".botao");
const personagens = document.querySelectorAll(".personagem");

botoes.forEach((botao, indice) => {
	botao.addEventListener("click", () => {
		desselecionarBotao();
		desselecionarPersonagem();

		botao.classList.add("selecionado");
		personagens[indice].classList.add("selecionado");
	});
});

```

### Desenvolvimento Contínuo

Em busca de aperfeiçoar ainda mais meu conhecimento em CSS e principalmente JS, pois são fundamentais e bastante interessantes na linguagem que eu desejo seguir.

## Autor

- Instagram - [@xmauro.alvesx](https://www.instagram.com/xmauro.alvesx/)
- Linkedlin - [Maurílio Alves](www.linkedin.com/in/maurílio-alves-889b641a1)