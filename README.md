﻿## Команды консоли


git log <hash> --max-count=<number> - для вывода лога начиная с коммита <hash> на <number> коммитов назад. 


pwd - Команда для вывода рабочей директории


dir - Вывод содержимого папки


cd - Переход в указанную папку, ''cd ~'' - перейти в домашнюю папку


```ls``` - Вывод содержимого папки, которую указали в команде


```ls -a``` - То же, с отображением скрытых файлов


'''Bash touch  <>''' - Создать файл


rm -rf - Удаление указанной папки, включая все вложенные папки, не запрашивать разрешение на удаление


cat - Вывод содержимого папки


cp - Скопировать файл, поменять название файла


mkdir - Создать папку


vim, nano


## Разметка Markdown



### Списки  
-Пункт ненумерованного списка 1  
-Пункт ненумерованного списка 2  

''Markdown
- Пункт ненумерованного списка 1  
- Пункт ненумерованного списка 2  
''

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

### Разделение


\***


\---


\___


### Установка акцентов
курсив  
полужирый  
комбинировать   
зачеркнутый использует две ~ тильды  
##Таблицы  


|-----------------|-------------------|-----------------| 
|\*\*Asterisks\*\*| Bold **Asterisks**|  
|-----------------|-------------------|  
|\_Underline\_	  | Курсив _Курсив_   |  
|-----------------|-------------------|  

## Сведения о Git из уроков.  
# Ветск в Git  

Чтобы посмотреть все активные ветки в проекте, нужно вызвать команду `git branch` без аргументов. 

Для сравнения веток есть команда `git diff`.

С помощью комнды `git merge` можно слить две ветки в одну.  


git log - Покажет последние сделанные изменения


git log -oneline - Покажет последние изменения в компактном виде(Одна строка на коммит)


_HEAD_ - Указатель на коммит, файл HEAD находится в папке .git и содержит хеш коммита
Как и _branch_ - ссылка на коммит.


```Markdown _Хеш файла_ - это отпечаток файла сигнатура файла```
_Хеш файла_ - это отпечаток файла сигнатура файла  


Закодированная строка SHA-1, содержит 40 символов.


## Состояния файлов в файловой структуре Git

Git repos contains 3 conditions of filesystems of projects is  
staged AND NOT staged AND commited.  
project_file->status is NOT staged->CHANGIN->status  
is NOT staged->git add project_file->status is staged.  
git commit->projects_file commited.
staged /  not staged  tracked/untracked  changed  commited
1)STAGED AREA
2)COMMITED AREA
3)area  MODIFIED files


git status - Показать текущее состояние файловой системы репо.  


##Редактирование


ESC  !:qa - Выйти из редактора без сохранения


ESC - escape to view


W,B - over word BACK and FORWARD


o,a - INSERT


a - insert After


i - start Inserting


o - insert line


u - step back