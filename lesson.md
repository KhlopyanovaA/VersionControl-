# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Cоздание копии (удаленного) репозитория

Для начала работы с центральным репозиторием, следует создать копию оригинального проекта со всей его историей локально, ввести команду  git clone https:// .....git (используя ссылку протокола)

## Для стягивания изменений с удаленного репозитория

Команда git pull сразу забирает изменения и проводит слияние с активной веткой. Забирает из репозитория, для которого были созданы удаленные ветки по умолчанию.

## Вносити изменения в удаленный репозиторий

Команда git push отправляет свои изменения в удаленную ветку, созданную при клонировании по умолчанию




# Задание 1
~~задание 2~~
задание 0

#  Домашнее задание


## Заголовок

Для выделения заголовка используется решетка, количество решеток соответствует уровню заголовка. Например, вот так:
# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвёртого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня

## Форматирование текста
Выделить текст курсивом - обрамить звездочками или нижним подчеркиванием, например, вот так: *курсив* или _курсив_.

Жирный текст- обрамить двойными звездочками, например, вот так: **жирный**

Зачеркнутый тест- обрамить двойными волнами, например, вот так: ~~зачеркнутый~~

## Цитата

Для обозначения цитат используется знак «больше» («>»), например, вот так:
>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф.
Вложение цитаты в цитату выглядит следующим образом:

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования

## Списки
Чтобы выделить ненумерованный список, используйте (*)

Чтобы добавить ненумерованные списки необходимо выделить пункты звездочкой.
Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3

Чтобы добавить нумерованные списки, необходимо просто пронумеровать.
Наприме, вот так:
1. Первый пункт
2. Второй пункт
3. Третий пункт

## Работа с изображениями

Чтобы вставить изображение в текс, достаточно написать следующее:
![Леопард](leopard.jpeg)

## Таблицы

Таблицы можно записать вот таким образом:
| один | два | три  | четыре |
|:------|-----|------|-----:|
| один | два | три  | четыре |
| один | два | три  |четыре  |

## Ссылки
Ссылка  имеет следующий синтаксис: [Текст ссылки](url)