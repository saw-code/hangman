# Консольная игра `Hangman`
###### Язык написания - Ruby

## Описание игры:
> Компьютер загадывает слово (из списка в файле) и показывает, сколько в нем букв.
> Игрок вводит буквы по одной. Если буква есть в слове, компьютер показывает, сколько раз 
> она в нем встречается и на каких местах. Если буквы нет, компьютер засчитывает ошибку.
> Если слово отгадано полностью, игрок победил. 
> После каждой ошибки, дорисовывается виселица. Всего можно сделать 7 ошибок

## Как добавить новые слова в игру:
В папке `data` лежит текстовый файл `words.txt` - внутрь файла можно записывать любые новые слова построчно

## Как запустить игру:
В командной строке, из папки в которой находиться файл `main.rb` 
```
Вводим команду `ruby main.rb`
```

## Пример из игры:

```
Слово: К О __ О __ __
          _______
          |/
          |     ( )
          |      |
          |
          |
          |
          |
          |
        __|________
        |         |

Ошибки (2): Х, У
У вас осталось ошибок: 5

Введите следующую букву:
```
