## Идентификатор

продукция_графовой_грамматики (eng: graph_grammar_production)

## Определение

Правило графовой грамматики - тройка (g1, g2, E), где g1 и g2 - графы, а E - правило преобразования

## Пояснение

Письменно правило может задаваться в форме
~~~
g1 -> g2 (E)
~~~

Но в большинстве случаев правило задается в графической форме

## Пример

Правило в письменной форме:
~~~
A -> B ({ (1, 1'), (2, 2'), (3, 3'), (1, 4') })
~~~

Правило в графической форме: 
<img src="images/production.png">

Преобразование включения для правила:
<img src="images/embedding.png">

## Связь с другими понятиями

1. [правило_преобразования](embedding_transformation.md)

## Библиография

1. A survey of graph grammars: theory and applications, Hoda Fahmy, University of Toronto.