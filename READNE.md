# Практическая работа №1 
## Средства работы с командной строкой 
1. pwd (print working directory, «показать рабочую папку») — покажи, в какой я папке;
2. ls (list directory contents, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;
3. ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа .;
4. cd first-project (change directory, «сменить директорию») — перейди в папку first-project;
5. cd first-project/html — перейди в папку html, которая находится в папке first-project;
6. cd .. — перейди на уровень выше, в родительскую папку;
7. cd ~ — перейди в домашнюю директорию (/Users/Username);
8. cd / — перейди в корневую директорию.
---------
## Создание файлов
1. touch index.html (англ. touch, «коснуться») — создай файл index.html в текущей папке;
2. touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;
3. mkdir second-project (от англ. make directory, «создать директорию») — создай папку с именем second-project в текущей папке
--------
## Копирование/перемещене/чтение/удаление
1. cp file.txt ~/my-dir (от англ. copy, «копировать») — скопируй файл в другое место;
2. mv file.txt ~/my-dir (от англ. move, «переместить») — перемести файл или папку в другое место.
3. cat file.txt (от англ. concatenate and print, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.
4. rm about.html (от англ. remove, «удалить») — удали файл about.html;
5. rmdir images (от англ. remove directory, «удалить директорию») — удали папку images;
6. rm -r second-project (от англ. remove, «удалить» + recursive, «рекурсивный») — удали папку second-project и всё, что она содержит.
---------
---------
# Связь локального репозитория с github 
git init
touch EXAMPLE.TXT
git add EXAMPLE.TXT // . 
git commit -m "Initial commit"
git remote add origin git@github.com:KaterinaVat/git_helper.git
git remote -v
$ git push -u origin master
