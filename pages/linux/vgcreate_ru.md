# vgcreate

> Создание группы томов, объединяющие несколько устройств хранения.

- Создание новой группы томов "vg1", использующей `/dev/sda1` устройство:

`vgcreate {{vg1}} {{/dev/sda1}}`

- Создание новой группы томов "vg1", использующей несколько устройств:

`vgcreate {{vg1}} {{/dev/sda1}} {{/dev/sdb1}} {{/dev/sdc1}}`
