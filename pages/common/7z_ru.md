# 7z

> Файловый архиватор с высокой степенью сжатия.

- Заархивировать файл или директорию:

`7z a {{archived.7z}} {{path/to/file}}`

- Разархивировать существующий 7z архив с исходной структурой директорий:

`7z x {{archived}}`

- Заархивировать, используя специфичный тип архива:

`7z a -t {{zip|gzip|bzip2|tar|...}} {{archived}} {{path/to/file}}`

- Список доступных типов архивации:

`7z i`

- Вывести список cодержимого архива:

`7z l {{archived}}`
