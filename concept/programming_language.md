## Идентификатор

язык_программирования (eng: programming_language)

## Определение

Язык программирования - формальный язык, предназначенный для записи компьютерных программ. 

## Пояснение

Язык программирования определяет набор синтаксических, лексических и семантических правил, определяющих внешний вид программы и действия, которые выполнит исполнитель под ее управлением.

Язык программирования задается перечислением всех текстов языка, порождающей грамматикой или программой-распознавателем.

## Пример

Программа, которая проверяет, является ли число, введенное пользователем, четным, на языке программирования C++.

~~~C++
#include <iostream>
using namespace std;

int main() {
  int n;

  cout << "Enter an integer: ";
  cin >> n;

  if ( n % 2 == 0) cout << n << " is even.";
  else cout << n << " is odd.";
  
  return 0;
}
~~~

## Связь с другими понятиями

1. [семантика_языка_программирования](programming_language_semantics.md)
2. [синтакс_языка_программирования](programming_langiage_syntax.md)
3. [компилируемый_язык_программирования](compiled_programming_language.md)
4. [интерпретируемый_язык_программирования](interpreted_programming_language.md)
5. [декларативный_язык_программирования](declarative_programming_language.md)
6. [императивный_язык_программирования](imperative_programming_language.md)

## Библиография

1. ISO/IEC/IEEE 24765:2010 Systems and software engineering — Vocabulary
2. Friedman, Daniel P.; Mitchell Wand; Christopher T. Haynes (1992). Essentials of Programming Languages (1st ed.). The MIT Press.