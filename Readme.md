# Инструкция по работе с git

## Что такое git
Git - это наиболее популярная реализация распределенной системы контроля версий. Самая популярная реализация **Git** - это [g]ithub] (https://github.com/)

## Подготовка репозитория
Для создания репозитория используется команда *git init* Для этого необходимо в терминале перейти в пустую папку где в будущем будет репозиторий.
## Создание сохранений

## Создание коммита 
Для создания коммита используется команда *git commit*. Для этого в терминале с папкой репозиторием необходимо написать *git commit -m <сообщение к коммиту>*.Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Добавление файла к коммиту
Для добавления файла к будущему коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*. 
 
## Перемещение между сохранениями
Для перемещения на предыдущие коммиты используется команда *git checkout*. для этого необходимо в журнале изменений , как показано в предыдущей части необходиммый коммит и его номер  
## Журнал изменений
Для просмотра журнала изменений используется команда *git log* для этого в терминале с папкой репозиторием необходимо написать *git log*.

## Ветки git
Для создания ветки, нужно ввести команду  **git branch <название ветки> (желательно на англ)** После чего ввести команду *git checkout <название ветки>* чтобы перейти в нее. 
## Слияние веток и разрешение конфликтов

## Удаление веток
Чтобы удалить ветку, надо находясь в **ветке мастер** нажать команду **git branch -d <название ветки>.