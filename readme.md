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




