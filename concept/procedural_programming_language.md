## Идентификатор

процедурный_язык_программирования (eng: procedural_programming_language)

## Определение

Процедурный язык программирования - императивный язык программирования, в котором последовательно выполняемые операторы можно собирать в подпрограммы с помощью механизмов самого языка.

## Пояснение

Основным концептом процедурного языка программирования является подпрограмма. Любая подпрограмма может быть вызвана в любой момент выполнения программы, включая вызов из других подпрограмм, также подпрограмма может вызывать саму себя.

## Пример

Программа для нахождения минимального числа из трех на Pascal.

~~~Pascal
program exProcedure;
var
   a, b, c,  min: integer;
procedure findMin(x, y, z: integer; var m: integer); 

begin
   if x < y then
      m:= x
   else
      m:= y;
   
   if z < m then
      m:= z;
end; { end of procedure findMin }  

begin
   writeln(' Enter three numbers: ');
   readln( a, b, c);
   findMin(a, b, c, min); (* Procedure call *)
   
   writeln(' Minimum: ', min);
end.
~~~

## Связь с другими понятиями

1. язык_программирования
2. императивный_язык_программирования

## Библиография

1. Joseph C. Giarratano, Gary Riley, Expert Systems Principles and Programming