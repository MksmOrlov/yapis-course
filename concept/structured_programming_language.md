## Идентификатор

структурный_язык_программирования (eng: structured_programming_language)

## Определение

Структурный язык программирования - императивный язык программирования, в основе которого лежит представление программы в виде иерархической структуры блоков.

## Пояснение

В структурных языках программирования программа состоит из трех базовых управляющих конструкций: последовательность, ветвление и цикл. Также могут использоваться подпрограммы.

В структурных языках программирования особый акцент сделан на использовании оператора goto. В структурном программировании данный оператор рассматривается как крайне нежелательный.

## Пример

Пример расчета чисел Фибоначчи на языке ALGOL68.

~~~Algol68
PROC print fibo = (INT n) VOID:
  BEGIN
     INT a:= 0, b = 1;
     FOR i FROM 1 TO n DO
        print((whole(i,0), "==>", whole(b,0), new line));
        INT c = a + b;
        a := b;
        b := c

     OD
 END;

  INT k = 40;
  print("Compute fibonacci");
  print((whole(k,0), new line));
  print fact(k)
~~~

## Связь с другими понятиями

1. [язык_программирования](programming_language.md)
2. [императивный_язык_программирования](imperative_programming_language.md)

## Библиография

1. O.J. Dahl, E. W. Dijkstra, C. A. R. Hoare Structured Programming, Academic Press, London, 1972.
2. Edsger W. Dijkstra. "Go To Statement Considered Harmful".