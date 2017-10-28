# mkfs.ntfs

> Создает файловую систему NTFS на разделе.

- Создать файловую систему NTFS на разделе `1` устройства `b` (`sdb1`):

`mkfs.ntfs {{/dev/sdb1}}`

- Создать файловую систему NTFS и задать метку тома:

`mkfs.ntfs -L {{volume_label}} {{/dev/sdb1}}`

- Создать файловую систему NTFS и задать определенный UUID:

`mkfs.ntfs -U {{UUID}} {{/dev/sdb1}}`