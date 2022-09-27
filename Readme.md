# Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*.

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммита
Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***.

## Узнать статус 
Воспользовавшись командой *git status* можно узнать, на какой ветке (branch) репозитория вы сейчас находитесь, какие изменения присутствуют в вашей рабочей копии и другую информацию.

## Историю изменений
История изменений можно посмотреть командой *git log*. Если вся история изменений не умещается на экране, то можно воспользоваться клавишами (*стрелочки*, PgUp, PgDown) выход из режима просмотра изменений осуществляется нажатием клавиши "q"

## Клонирование удаленного репозитория
 Если возникла необходимость клонировать удаленный репозитарий,то можно получить полностью работоспособную копию при помощи команды *git clone*

 ## Запрос изменений с удаленного репозитария
Для того, чтобы получить информацию об изменениях, нужно выполнить команду *git pull*. Она скачивает новые изменения.

## Отправка изменений в удаленный репозитарий
Отправка коммита осуществляется с помощью команды *push*, которая имеет два параметра - имя удаленного репозитория (в нашем случае origin) и ветку, в которую необходимо внести изменения (master — это ветка по умолчанию для всех репозиториев).