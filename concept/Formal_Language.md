## Идентификатор

формальный язык (eng: formal language)

## Определение

множество конечных слов (строк, цепочек) над конечным алфавитом.

### Способы задания

* Перечисление слова, входящих в язык
  применим к:
    * конечные языки
    * языки простой структуры
* Слова, порожденные некоторой формальной грамматикой
* Слова, порожденные регулярными выражениями
* Слова, распознаваемые конечным автоматом
* Слова, порожденные БНФ-конструкцией

### Пример

если алфавит задан как {a,b}, а язык L включает в себя все слова над ним, то слово **ababba** принадлежит L. **Пустое слово**(то есть строка нулевой длины) допускается и часто обозначается как *e*, *epsilon* или *Lambda*.

### Операции 

При помощи операций из двух и более языков можно порождать новые. Возьмем два языка L1 и L2, причем они определены над общим алфавитом.

* Конкатенация (L1L2 содержит все слова формы *ас*, где *а* - слово из L1, а *с* - из L2)
* Пересечение (L1/\L2 содержит все слова из L1 **и** L2)
* Объединение (L1\/L2 содержит все слова из L1 **или** L2)
* Дополнение (дополнение языка L1 содержит все слова, которых нет в L1)
* Правое отноешение (L1/L2 содержит все слова *а*, для оторых существует слово *с* в L2 такое, что *ас* находится  L1) и т.д.

## Связь с другими понятиями

[множество](https://github.com/Dememedp/yapis-course/blob/main/concept/Set.md)

[слово](https://github.com/Dememedp/yapis-course/blob/main/concept/Formal_Word.md)

[алфавит символов](https://github.com/Dememedp/yapis-course/blob/main/concept/Symbol_Alphabet.md)

[порождающая грамматика](https://github.com/Dememedp/yapis-course/blob/main/concept/Generative_Grammar.md)

[регулярные выражения](https://github.com/Dememedp/yapis-course/blob/main/concept/Regular_Expression.md)

[конечный автомат](https://github.com/Dememedp/yapis-course/blob/main/concept/Finite_State_Machine.md)

[форма Бэкуса-Наура(БНФ)](https://github.com/Dememedp/yapis-course/blob/main/concept/Backus_Naur_Form.md)

## Ссылка на библиографию

[Гладкий А. В. Формальные грамматики и языки.](https://github.com/Dememedp/yapis-course/blob/main/bibliography/Gladkiy-Formal-book.md)
