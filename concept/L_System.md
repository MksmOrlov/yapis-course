## Идентификатор

L-система (eng: L system)

## Определение

параллельная система переписывания и вид формальной грамматики

L-система состоит из алфавита символов, которые могут быть использованы для создания строк, набора порождающих правил, которые задают правила подстановки вместо каждого символа, начальной строки («аксиомы»), с которой начинается построение, и механизма перевода образованной строки в геометрические структуры

### Структура

L-системы определяются как кортеж

G = (V, ω, P),

где V - алфавит, ω - аксиома, P - множество порождающих правил

### Пример: Водоросли

Оригинальная L-система Линденмайера для моделирования роста водорослей.

* переменные : A B
* константы : нет
* аксиома  : A
* правила  : (A → AB), (B → A)

Система даёт

n = 0 : A

n = 1 : AB

n = 2 : ABA

n = 3 : ABAAB

n = 4 : ABAABABA

n = 5 : ABAABABAABAAB

n = 6 : ABAABABAABAABABAABABA

n = 7 : ABAABABAABAABABAABABAABAABABAABAAB

## Связь с другими понятиями

[грамматика](https://github.com/Dememedp/yapis-course/blob/main/concept/Grammar.md)

## Ссылка на библиографию

[Grzegorz Rozenberg, Arto Salomaa. The mathematical theory of L systems. — New York: Academic Press, 1980](https://github.com/Dememedp/yapis-course/blob/main/bibliography/Aho-Compilers-book.md)
