# diskutil

> Утилита управления локальными дисками и томами.

- Вывести список всех доступных в настоящее время дисков, разделов и подключенных томов:

`diskutil list`

- Восстановить структуру данных тома:

`diskutil repairVolume {{/dev/diskX}}`

- Размонтировать том диска:

`diskutil unmountDisk {{/dev/diskX}}`

- Изъять CD/DVD диск (сперва размонтировать):

`diskutil eject {{/dev/disk1}}`