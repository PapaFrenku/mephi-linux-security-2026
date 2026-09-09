ДЗ №1 Изучение средств защиты ОС GNU/Linux

## Выполненные задания

| № | Тема                  | Результат                                         |
| - | --------------------- | ------------------------------------------------- |
| 1 | Пользователь и группа | `user1`, UID `1234`, группа `students`            |
| 2 | Set-UID и процессы    | Найдены Set-UID файлы и процесс `passwd` с EUID 0 |
| 3 | Set-UID               | Создан `mycat` с Set-UID root                     |
| 4 | Capabilities          | `mychown` получил `cap_chown=ep`                  |
| 5 | Sudo                  | `user1` получил доступ к `timedatectl`            |

## Артефакты

* `history.out` — история выполненных команд
* `stat.out` — информация о файлах и их атрибутах
* `getcap.out` — назначенные файловые capabilities
* `setuid-files.out` — найденные Set-UID файлы
* `privileged-processes.out` — процессы с RUID ≠ 0 и EUID = 0
* `processes.out` — дополнительный вывод списка процессов
