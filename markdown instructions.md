# Инструкция для работы с MarkDown

## Выделение текста

Что бы выделить текст курсивом необходимо выделить текст звездочкой или знаком нижнего подчеркивания. Например *Вот так* или _вот так_.

Что бы выделить текст полужирным, необходимо обрамить его двойными звездочками или двойным знаком нижнего подчеркивания. Например **Вот так** или __вот так__.

Альтернативные способы выделения текста полужирным или курсивом нужны для того, что бы мы могли совмещать оба этих метода. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.



## Списки

Что бы добавить ненумерованные списки необходимо пункты выделить звездочкой(*) или знаком +.
Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Что бы добавить нумерованные списки, необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Что бы вставить изображение в текст достаточно написать следующее:
![привет это линкс](links.jpg)

## Ссылки

## Работа с таблицами 

## Цитаты

## Заключение  

## Разметка по MarkDown

## Заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. 

Например:

# Заголовок первого уровня #

## Заголовок h2

### Заголовок h3

#### Заголовок h4 

##### Заголовок h5

###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с
обратной стороны.


## Ссылки

Это встроенная ссылка с title элементом (http://example.com/link). Это
— без title (http://example.com/link).

А вот пример (http://example.com/) нескольких
(http://example.com/some) ссылок (http://example.com/links) с
разметкой как у сносок. Прокатит и короткая запись
(http://example.com/short) без указания id.

Вынос длинных урлов из предложения способствует сохранению
читабельности исходника. Сноски можно располагать в любом месте
документа.

Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка").

 Это — [без title]
(http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.

[1]: http://example.com/ "Optional Title Here"

[2]: http://example.com/some

[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short

Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.

## Картинки

Картинка без `alt` текста

![](https://th.bing.com/th/id/OIP.V_oDtpLeduIYYgUnwzev3gHaEK?pid=ImgDet&rs=1)

Картинка с альтом и тайтлом:

![котики](https://minutapozitiva.ru/wp-content/uploads/2018/02/smeshnoj-kot.jpg "и тут котики")

Запомнить просто: синтаксис как у ссылок, только перед
открывающей квадратной скобкой ставится восклицательный
знак.

Картинки «сноски»:

![просто енот][image1]

[image1]: https://th.bing.com/th/id/R.23e05bfb3a1276841b51d95fa473b76d?rik=LxUscc844ZBpbw&riu=http%3a%2f%2fbipbap.ru%2fwp-content%2fuploads%2f2017%2f11%2fKrutye-kartinki-na-avu-dlya-patsanov-klassnye-foto-i-kartinki-na-avu-16.jpg&ehk=gRcJlD6FJoF6sd%2fXUVEmUUMA28zfmc3Nr5d1o8Zw4X8%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1

Картинки-ссылки:

[![Пример ALT text](https://ahrefs.com/blog/wp-content/uploads/2020/03/fb-alt-text.png)]


## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.


Для красоты можно и по бокам линии нарисовать:

## Выводы:

после добавления информации в главу заголовки удалось успешно слить с веткой мастер без конфликта. 

для новой фиксации просто строка
