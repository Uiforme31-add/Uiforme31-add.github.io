## Команды консоли


git log <hash> --max-count=<number> - для вывода лога начиная с коммита <hash> на <number> коммитов назад. 


pwd - Команда для вывода рабочей директории


dir - Вывод содержимого папки


cd - Переход в указанную папку, cd ~ - перейти в домашнюю папку


ls - Вывод содержимого папки, которую указали в команде


ls -a - То же, с отображением скрытых файлов


touch - Создать файл


rm -rf - Удаление указанной папки, включая все вложенные папки, не запрашивать разрешение на удаление


cat - Вывод содержимого папки


cp - Скопировать файл, поменять название файла


mkdir - Создать папку


vim, nano - text editors, this programs are available on git for Windows distrib!


## Разметка Markdown



### Списки


\- Пункт ненумерованного списка 1 


\- Пункт ненумерованного списка 2


### Заголовки


*h1-h6*


\#


\##


\###


\####


\#####


\######


\####### -too much


### Перенос строки



### Блок кода


\'''


### Разделение


\***


\---


\___


### Установка акцентов


Emphasis, aka italics, with *asterisks* or _underscores_.


Strong emphasis, aka bold, with **asterisks** or __underscores__.


Combined emphasis with **asterisks and _underscores_**.


Strikethrough uses two tildes. ~~Scratch this.~~ 


'''Markdown
Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~
'''


##Таблицы


|--------|--------|---------|---------|
|--------|----------------------------|
|---------------------------|---------|
|\*\*Asterisks\*\*| Bold **Asterisks**|


***

## Сведения о Git из уроков.



git log - Покажет последние сделанные изменения


git log -oneline - Покажет последние изменения в компактном виде(Одна строка на коммит)


HEAD - Указатель на коммит, файл HEAD находится в папке .git и содержит хеш коммита
Как и branch - ссылка на коммит.


Хеш - это отпечаток файла, т.е. строка однозначно идентифицирующая файл, сигнатура файла 


Закодированная строка SHA-1, содержит 40 символов.


## Состояния файлов в файловой структуре Git


staged/not staged  tracked/untracked  changed  commited


git status - Команда показывает текущее состояние файловой системы репо.


##Редактирование


!:qa - Exit Vim editor!


ESC - escape to view


W,B - over word BACK and FORWARD


o,a - INSERT


a - insert After


i - start Inserting


o - insert line


u - step back
