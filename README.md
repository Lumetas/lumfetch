Этот репозиторий представляет собой форк neofetch. Запуск:
```
curl -fsSL https://raw.githubusercontent.com/Lumetas/lumfetch/refs/heads/master/lumfetch | bash
```
Без информации он характеристиках:
```
curl -fsSL https://raw.githubusercontent.com/Lumetas/lumfetch/refs/heads/master/lumfetch | NO_HARDWARE_INFO=yes bash
```
Для загрузки файла локально:
```
echo '#!/bin/bash' > lumfetch && curl -fsSL https://raw.githubusercontent.com/Lumetas/lumfetch/refs/heads/master/lumfetch >> lumfetch; chmod +x lumfetch
```

В рамках форка были убраны коментарии и некоторые другие моменты которые могли мешать запуску neofetch без установки, а так же добавлена возможность скрыть информацию об оборудовании.

