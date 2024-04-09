# O que é HTML e sua estrutura básica

HTML, ou HyperText Markup Language (Linguagem de Marcação de Hipertexto), é a linguagem padrão utilizada para criar e estruturar conteúdo em páginas da web. Desenvolvido inicialmente por Tim Berners-Lee em 1991, HTML é uma linguagem de marcação que utiliza uma sintaxe especial para definir a estrutura e o conteúdo de uma página web.

Em termos simples, o HTML é composto por uma série de elementos ou "tags" que são usados para marcar diferentes partes do conteúdo de uma página da web. Cada elemento tem uma função específica e pode conter ou envolver outros elementos para formar a estrutura da página.

## Tipos de Tag

| Tipo                  | Exemplos                                           | Descrição                                                                                     |
|-----------------------|----------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Tag de Par            | `<p>...</p>, <div>...</div>,< span>...</span>, etc.` | Tags que abrem e fecham, usadas para agrupar e estilizar blocos de conteúdo. Por exemplo, `<p>` define um parágrafo de texto. |
| Tag sem fechamento   | `<br>, <img src="...">, <input type="text">, etc.` | Tags que não possuem uma forma de fechamento explícita. Elas são usadas para inserir elementos individuais na página, como quebras de linha, imagens e campos de entrada em formulários. |
| Tags de Bloco        | `<div>, <p>, <h1> a <h6>, <ul>, <ol>, <table>, etc.` | Elementos que começam em uma nova linha e ocupam toda a largura disponível de seu contêiner pai. |
| Tags de Comportamento Inline | `<span>, <a>, <strong>, <em>, <img>, <input>, etc.` | Elementos que não começam em uma nova linha e ocupam apenas a largura necessária para exibir seu conteúdo. |

## Tags de Estrutura

- `<html>`: Define o início e o fim do documento HTML.
- `<head>`: Contém informações sobre o documento, como o título da página, links para estilos CSS, scripts JavaScript, etc.
- `<body>`: Contém todo o conteúdo visível da página, como texto, imagens, vídeos, etc.

## Tags de Título e Cabeçalho

- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`: São usadas para definir títulos e subtítulos, com `<h1>` sendo o título mais importante e `<h6>` o menos importante.
- `<title>`: Define o título da página que é exibido na barra de título do navegador.

## Tags de Texto

- `<p>`: Define parágrafos de texto.
- `<span>`: Usada para aplicar estilo a partes específicas de um texto.
- `<strong>`: Define texto importante, geralmente exibido em negrito.
- `<em>`: Define texto enfatizado, geralmente exibido em itálico.
- `<br>`: Cria uma quebra de linha.
- `<hr>`: Cria uma linha horizontal.

## Tags de Listas

- `<ul>`: Define uma lista não ordenada.
- `<ol>`: Define uma lista ordenada.
- `<li>`: Define um item de lista dentro de `<ul>` ou `<ol>`.

## Tags de Links e Imagens

- `<a>`: Define um hyperlink para outra página ou recurso.
- `<img>`: Define uma imagem a ser exibida na página.

## Tags de Tabelas

- `<table>`: Define uma tabela.
- `<tr>`: Define uma linha em uma tabela.
- `<td>`: Define uma célula de dados em uma tabela.

## Tags de Formulários

- `<form>`: Define um formulário para coletar dados do usuário.
- `<input>`: Define um campo de entrada em um formulário.
- `<button>`: Define um botão de envio em um formulário.

## Tags Semânticas

- `<article>`: Define um conteúdo independente e autocontido, como um post de blog ou um artigo.
- `<aside>`: Define um conteúdo relacionado, mas não essencial para o conteúdo principal da página, como barras laterais ou notas explicativas.
- `<footer>`: Define o rodapé da página ou de uma seção.
- `<header>`: Define o cabeçalho da página ou de uma seção.
- `<main>`: Define o conteúdo principal da página.
- `<nav>`: Define uma seção de navegação.
- `<section>`: Define uma seção da página.

[A Estrutura básica de uma página HTML](estrutura.html)
