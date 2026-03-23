Capítulo 16-Aula 01
-Modelo de Caixas

#caixas dentro de caixas
*aninhamente*

<h1>Olá,mundo!</h1>

box:em volta do Olá,mundo!

tamanho:

height(Altura)

width(Largura)

outline=linha for do elemento
border=linha dentro do elemento que circula o conteúdo
padrão => grudado

*padding* => espaçamento(interno) borda e conteúdo
*margin* => espaçamento(externo)

*box-level* => linha nova, 100% da tela
tags ex:
<div>-Não sei ao certo ainda
<h1>-<h6>-Títulos e subtítulos
<p>-Parágrafos
<main>-corpo/conteúdo
<header>-cabeçario
<nav>-Não sei
<article>-Não sei
<aside>-Não sei
<footer>-Rodapé
<form>-Não sei
<video>-video 

*inline-level* => Continua linha, não ocupa 100%(divide a linha)
tags ex:
<span>-não sei
<a>-Hyperlink
<code>-codigos/monoespaço
<small>-pequeno
<strong>-negrito
<em>-sublinhado
<sup>-<sub>- termos de potência e de elementos quimicos
<label>-não sei
<button>-botão
<input>-não sei
<select>-não sei

Cápitulo 16- Aula 02
user-agent=navegador
display:block;=box-level
devtools => util
padding: distancia do elemento/texto da borda
part 02
margin: distancia da box da borda/outra borda
margin:auto => centraliza no meio para box, texto usa text-align:center
outline=borda

simplificação/shorthands
*border*: width style color;
*padding*: top right bottom left; top=right=bottom=left/ padding=all;, 2 valores top-bottom left-right

ex
*border:15px solid red;*
*padding:15px  16px 17px 18px;*-- todas diferentes
*padding:17px 20px;*--top=bottom right=left
*padding:20px;*--top=bottom=right=left

display:block,inline;

AGRUPAMENTO
caixas dentro de caixa, caixa caixada, que isso my dad

Grouping tags
<span>-inline
<div>-box


header-> usar h1 e nav
main-.section.article   
footer