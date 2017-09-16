RMarkdown: O devir revolucionário da Estatística/Ciência de Dados
========================================================
css: custom.css
class: fundo
autosize: true
class: illustration
font-import: http://fonts.googleapis.com/css?family=Risque
font-family: 'Risque'
author: 
Steven Dutt-Ross<br>
Thiago de Araujo Severo dos Santos

ROTEIRO
========================================================
navigation: section

- Introdução (exemplos de Rmarkdown)
- Texto.
- Aprendendo ênfase e estilo (tamanho, negrito e itálico) com Game of Thrones.
- Colocando hiperlink.
- Para fazer tópicos/bullets.
- Como colocar citação.
- Como colocar imagem.
- Quebra de linhas (HTML).
- YAML (word e pdf).

***

- Bootstrap.
- Programando em R dentro do Markdown.
- Gráficos.
- Matriz de Correlação.
- Mapa do Rio de Janeiro.
- Nuvem de palavras.
- Colocar equações do LaTeX no RMarkdown.
- REVEAL.JS, Flexdashboard, Bookdown, Blogdown, Pkgdown e Mindmap.



R Markdown
========================================================

Vou pedir para vocês escreverem um texto com três parágrafos<br>
<br>
(pode ser qualquer coisa. um relatório que você estava escrevendo ontem, uma poesia ou até mesmo o hino do flamengo)

R de REVOLUCIONÁRIO
========================================================

#### Fatos sobre o crescimento do R

[Fonte 2014](http://blog.revolutionanalytics.com/2014/04/seven-quick-facts-about-r.html)

<!-- utilizar somente se o publico do minicurso for de SI-->
1. R é a habilidade de TI mais bem paga (pesquisa Dice.com, janeiro de 2014)<br>
2. R a linguagem de ciência de dados mais utilizada após o SQL (pesquisa O'Reilly, janeiro de 2014)<br>
3. R é usado por 70% dos mineradores de dados (Rexer survey, outubro de 2013)<br>
4. R crescendo mais rápido do que qualquer outra linguagem de ciência de dados (pesquisa KDNuggets, agosto de 2013)<br>
5. R é o software # 1 do Google Search for Advanced Analytics (Google Trends, março de 2014)<br>
6. R tem mais de 2 milhões de usuários em todo o mundo (estimativa Oracle, fevereiro de 2012)


R Markdown
========================================================

![](C:/Users/Steven/Documents/GitHub/UNIRIO_JIC/rmarkdown0.png)

Slides com códigos
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slides com gráficos
========================================================

![plot of chunk unnamed-chunk-2](REVEALJS-figure/unnamed-chunk-2-1.png)


R Markdown
========================================================

![](C:/Users/Steven/Documents/GitHub/UNIRIO_JIC/rmarkdown1.png)

R Markdown
========================================================

![](C:/Users/Steven/Documents/GitHub/UNIRIO_JIC/rmarkdown2.png)

R Markdown
========================================================

![](C:/Users/Steven/Documents/GitHub/UNIRIO_JIC/rmarkdown3.png)

R Markdown
========================================================

Markdown é uma linguagem de marcação simples para escrever textos<br>
O texto pode ser lido sem nenhum processamento, ou seja, da maneira como está escrito
Outras linguagens de marcação como HTML e LATEX<br>
requerem um grande número de tags para formatar o texto, muitas vezes dificultando a leitura do código-fonte<br>
A proposta do Markdown é que o escritor se concentre no texto e não na formatação<br>
Pode ser convertido para vários outros formatos além de HTML<br>
fonte: Fernando Mayer (UFPR)

========================================================