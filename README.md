# japones-coisas


## Objetivo:

Ter um projeto no ar para incluirmos nos nossos portifólios.

## O que ver hoje:

- Fazer um landing page, uma aula, um quiz e conectar a api do jisho.
- Trabalhar com git, fazer pelo menos 4 commits e 4 pull requests.
- Fazer deploy do projeto usando Netlify

## O que não vamos fazer mas ficar de olho:

- Usar o npm
- Fazer um mockup do projeto. Devo trazer pronto algo para trabalharmos
- Usar um framework como Angular, React ou Vue
- Conectar a um banco de dados

## Cronograma:

Introdução e Setup: 1h
Home e Aula + css: 1h
Api do Jisho: 1h
Quiz: 1h
Refatoração: 1h

## Nomes das branchs:

master
dev
HTML-001
CSS-001
JS-001

## Configurar Javascript no VSCode:

- Emmet
- Auto Close Tag
- Live Server

## Criar as seguintes páginas:

- index.html
- capitulo1.html
- quizz1.html
- sobre.html

## Como será feita a estilização da página?

- Bootstrap / MaterializeCSS / CSS Puro
- Flexbox / Grid Layout
- Mobile First??

## Detalhamento dos componentes:

Todas as páginas terão Sidebar/Navbar e um consultor de kanjis no rodapé

### Navbar:
- Início
- Aulas
- Testes
- Sobre

### Home e Aula serão uma landing page com imagens. Aula terá anchors. Sobre vai ser uma página da descrição do projeto.

### Teste
- A página teste vai pegar o JSON de exemplo e criar um formulário automaticamente. Provavelmente será a página mais difícil e demorada.
- Lógica do formulário: Cada questão vai ser gerada por um item do JSON, como se fosse um for. O titulo da questão pode ser feito hardcoded, A pergunta de cada questão vai ser o title, as questões vão estar em uma array e a resposta separada. A resposta vai ser comparada com o array e no final será gerado um score.

### Jisho
- A API do Jisho será usada em uma janela abaixo, que poderá ser minimizada.