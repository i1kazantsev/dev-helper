# Основные консольные команды для работы с файловой системой

## Перемещение

* `cd path/to/directory` - перейти в каталог `directory`

* `ls` - показать содержимое каталога
  * `-a` - включая скрытые файлы
  * `-1` - вывести в столбик

------------------------------------------

## Создание

* `mkdir directory` - создать каталог `directory`
* `touch style.scss` - создать файл `style.scss`

------------------------------------------

## Копирование

* `copy style.scss path/to/directory` - копировать `style.scss` в `directory`
  * `-r` - копирование каталога

------------------------------------------

## Переименование/перемещение

* `mv style.scss style.css` - переименовать файл `style.scss` в `style.css`
* `mv style.scss path/to/directory` - переместить файл `style.scss` в `directory`

------------------------------------------

## Удаление

* `rm style.scss` - удалить файл `style.css`
* `rm path/to/directory -rf` - удалить каталог `directory`
