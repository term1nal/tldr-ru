# useradd

> Создание нового пользователя.

- Создать нового пользователя:

`useradd {{name}}`

- Создать нового пользователя с домашним каталогом по умолчанию:

`useradd --create-home {{name}}`

- Создать нового пользователя с опредленной коммандной оболочкой:

`useradd --shell {{/path/to/shell}} {{name}}`

- Создать нового пользователя относящегося к опредленным группам (не учитывая пробелы):

`useradd --groups {{group1,group2}} {{name}}`

- Создать нового пользователя без домашней директории:

`useradd --no-create-home --system {{name}}`