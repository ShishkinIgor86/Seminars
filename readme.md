**git init** -инициализируем наш репозитарий

**git status** - общий статус гита

**git add <file name>** - добавить файлу версионность

**git add .** - добавить всем файлам версионность

**git commit -m 'message'** - фиксирование изменений в терминале напрямую

**git commit** - фиксирование изменений

**git commit -am 'message'** - фиксирование изменений напрямую в терминале без использования git add

**git log** - вывод истории коммитов

**git checkout hash** - переход к коммиту по хешу

**git checkout main/master** - вернутся в обычное состояние

**git diff** - разница изменений между файлом и последним коммитом

# MarkDown (shot guide)

**Для выделения заголовка первого уровня, достаточно поставить #**
# Пример - заголовок 1 уровня
*Для выделения заголовка второго и следующих уровней, достаточно поставить необходимое число #*
## Пример - заголовок 2-го уровня
### Пример - заголовок 3-го уровня
и т.д.

*Для выделения зоголовков можно также использовать знак '=' для выделения заголовка 1-го уровня, для заголовка 2-го уровня применятся '-' при этом можно ставить любое количество знаков, и на тип заголовка это не повлияет между заголовком и знаками не должно быть пустых строк*

**Заголовок 1-го уровня:**

Пример
=

**Заголовок 2-го уровня:**

Пример
-

Выделение текста (emphasis)
=

Для выделения текста курсивом нужно использовать одну звёздочку * или нижнее подчёркивание _

*Пример* - использовали *

_Пример_ - использовали _

Для выделения текста жирным нужно использовать две звёздочки ** или два нижних подчёркивания __.

**Пример** - использовали **

__Пример__ - использовали __

Для выделения текста сразу обоими стилями нужно использовать три звёздочки *** или три нижних подчёркивания ___

***Пример*** - использовали ***

___Пример___ - использовали ___

Обратите внимание, что если вы хотите выделить фрагмент внутри слова, то это корректно сработает только при использовании звёздочек.

П*рим*ер - использовали * между буквами рим

Чтобы зачеркнуть текст, нужно использовать две тильды ~~. Такая опция есть только в диалекте GitHub Flavored Markdown.

~~Пример ~~ 

В синтаксисе Markdown нет встроенного способа подчеркнуть текст. Но если ваш редактор поддерживает HTML, то можно использовать теги '<'u'>' '<'/u'>':

<u> Пример </u> - использовали тэги '<'u'>' '<'/u'>'

Разделители (horizontal rules)

Чтобы оформить горизонтальный разделитель, нужно поставить три или больше специальных символа: звёздочки *, дефиса - или нижних подчёркивания _. Они должны находиться на отдельной строке, и между ними можно ставить любое количество пробелов и табуляций.

Если ваш редактор поддерживает HTML-теги, то для разметки можно также использовать тег <hr>.

Пример:
***
___
*   ***

 Цитаты (blockquotes)
 
 Чтобы параграф отобразился как цитата, нужно поставить перед ним закрывающую угловую скобку >

 >Пример

 Внутрь одного блока цитаты можно поместить сразу несколько параграфов и использовать любые элементы оформления. Например, заголовки и другие цитаты. Чтобы сделать это, нужно поместить закрывающую угловую скобку перед началом каждой строки.   

 >Пример
 >>Пример            

Списки (lists)

В синтаксисе Markdown есть несколько видов списков. Для их оформления перед каждым пунктом нужно поставить подходящий тег и отделить его от текста пробелом.

Нумерованные (ordered)

Для создания нумерованного списка перед пунктами нужно поставить число с точкой. При этом нумерация в разметке ленивая. Неважно, какие именно числа вы напишете: Markdown пронумерует список автоматически.

1. Пример
2. Пример

Для создания нумерованного списка перед пунктами нужно поставить число с точкой. При этом нумерация в разметке ленивая. Неважно, какие именно числа вы напишете: Markdown пронумерует список автоматически.

30. Пример
31. Пример

Обратите внимание, что между двумя нумерованными списками, идущими подряд, нужно отбить две пустые строки. Если отбить только одну, то Markdown воспримет два списка как один. Некоторые редакторы в таком случае увеличивают интервал между пунктами.

1. Пример 1
2. Пример 2


10. Пример 3
11. Пример 4

Ненумерованные (unordered)

Для создания ненумерованного списка нужно поставить перед каждым пунктом звёздочку *, дефис - или плюс +.

* Пример *
- Пример -
+ Пример +

Обратите внимание, что Markdown относит к разным спискам пункты, перед которыми стоят разные маркеры. Даже несмотря на то, что мы не оставляем пустых строк между списками.

Если же два списка идут подряд, а перед их пунктами стоят одинаковые маркеры, тогда между ними нужно отбить две пустые строки (как в случае с нумерованными списками).

Чекбоксы (checkboxes)

Чтобы сделать чекбоксы, нужно использовать маркированный список, но между маркером и текстом поставить [x] для отмеченного пункта и [] — для неотмеченного.

Чекбоксы доступны в диалекте GitHub Flavored Markdown (тот самый, который умеет зачёркивать текст) и поддерживаются не всеми редакторами Markdown. Например, нам для демонстрации примера пришлось открывать другой.

[x] Пример

[] Пример

Вложенные (nested)

Чтобы создать вложенный список, нужно поставить перед его пунктами табуляцию или несколько пробелов. В Markdown одна табуляция соответствует четырём пробелам.

Список одного вида можно вкладывать в любой другой.

1. Пример
    1. Пример
        1. Пример
               
* Пример
    * Пример
        * Пример

На самом деле количество пробелов, которые нужно поставить для корректного отступа, рассчитывается чуть сложнее. Берётся количество символов в маркере (один для *, - и +, два для 1., три для 10.), и к нему прибавляется любое число от 1 до 4.

Таким образом, если в маркере 1 символ, нужно поставить от 2 до 5 пробелов, если 2 символа — от 3 до 6, если 3 символа — от 4 до 7.

Другие элементы внутри списков
В пункты списков можно добавлять другие элементы оформления. Например, параграфы или цитаты. Для этого нужно сделать отступ, как если бы вы добавляли вложенный список.

1. Пример
    > Цитата

1. Пример

        Параграф

Ссылки (links)

Самый лёгкий способ поместить ссылку в Markdown — заключить её в угловые скобки. Несмотря на простоту, он не является основным и был добавлен только в спецификации CommonMark.

<https://gb.ru/>

Чтобы оформить ссылкой часть текста, используется такой синтаксис: [текст](ссылка). Можно сделать всплывающую подсказку при наведении курсора. Для этого в круглых скобках после ссылки нужно поставить пробел и написать текст подсказки в кавычках.

[Ссылка на сайт GeekBrains](https://gb.ru/) - без подсказки

[Ссылка на сайт GeekBrains](https://gb.ru/ "Сайт GB") - с всплывающей подсказкой

Ещё один способ оформить ссылку — справочный. Он работает как сноски в книгах: [текст][имя сноски]. При таком способе организации ссылок в конце документа нужно также написать и оформить саму сноску: [имя сноски]: ссылка. При желании после ссылки можно добавить подсказку — точно так же, как в предыдущем методе.

Имя сноски может быть любым сочетанием символов: цифрами, буквами и даже знаками препинания. На одну и ту же сноску в тексте можно ссылаться сколько угодно раз.

Ссылки, оформленные справочным методом, выглядят и работают точно так же, как и в предыдущем способе. Сами сноски в отформатированном документе не отображаются.

[GeekBrains][1]

[Раздел Markdown][MD]

[1]: https://gb.ru/
[MD]: https://en.wikipedia.org/wiki/Markdown

Картинки (images)

Изображения в Markdown оформляются по принципу, схожему с принципом оформления ссылкок, только перед квадратными скобками нужно поставить восклицательный знак: ![текст](путь к изображению). Здесь также можно сделать всплывающую подсказку.

![Логотип Markdown](MD.jpg)

Изображения в Markdown оформляются по принципу, схожему с принципом оформления ссылкок, только перед квадратными скобками нужно поставить восклицательный знак: ![текст](путь к изображению). Здесь также можно сделать всплывающую подсказку.

Такая разметка выведет тот же результат, что и предыдущая.

![Логотип Markdown][2]

[2]: /MD.jpg "Логотип Markdown"

Вставка кода (code)

В Markdown есть несколько способов выделить исходный код:

Если надо отобразить фрагмент кода внутри строки с каким-то текстом, нужно с двух сторон выделить этот код одним или несколькими обратными апострофами (`; их ещё называют бэктиками).
Чтобы выделить фрагмент из нескольких строк, нужно с двух сторон выделить его тремя обратными апострофами.
Также перед фрагментом кода можно поставить табуляцию или четыре пробела, при этом предыдущая строка должна быть пустой.

~~~

n=int(input())

~~~

Если обрамлять код тремя обратными апострофами, то после первой тройки можно указать язык программирования — тогда Markdown правильно подсветит элементы кода.

~~~python

import numpy as np

arr=np.array([[1,2,3,'4'],['6','7','8','9']])
arr[0][1]-=10
arr[0][3]='A'
arr[1][1]=5
print(arr)

~~~

Возможность вставлять блоки кода тремя обратными апострофами появилась в спецификации CommonMark, но там не указан список псевдонимов: как правильно называть языки, чтобы Markdown понял, о чём речь.

Поэтому каждая реализация ведёт свой собственный список языков и их псевдонимов. Так как их очень много, да ещё и новые время от времени добавляются, то удобных таблиц обычно не делают. Предлагают сразу ознакомиться с конфигурационным файлом.

Вот такой список языков <https://github.com/github/linguist/blob/master/lib/linguist/languages.yml>, например, поддерживает диалект GitHub Flavored Markdown.

