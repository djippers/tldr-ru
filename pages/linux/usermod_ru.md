# usermod

> Модифицирует аккаунт пользователя.

- Изменить имя пользователя:

`usermod -l {{newname}} {{user}}`

- Добавить пользователя в дополнительные группы(учитывая пробелы):

`usermod -a -G {{group1,group2}} {{user}}`

- Создать новую домашную директорию пользователя и переместить туда его файлы:

`usermod -m -d {{/path/to/home}} {{user}}`
