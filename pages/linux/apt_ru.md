# apt

> Менеджер пакетов для дистрибутивов основанных на Debian.

- Обновляет список доступных пакетов и версий. Рекомендуется выполнять перед запуском дополнительных команд apt:

`sudo apt update`

- Поиск пакетов по имени:

`apt search {{package}}`

- Показывает информацию о пакете:

`apt show {{package}}`

- Устанавливает новый пакет:

`sudo apt install {{package}}`

- Удаляет пакет (используйте совместно с командой "purge" для удаления пакета вместе с его конфигурационными файлами):

`sudo apt remove {{package}}`

- Обновляет установленные пакеты до последней доступной в репозиториях версии:

`sudo apt upgrade`
