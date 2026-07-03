# RTPPlugin

Кастомный RTP-плагин для Paper/Spigot.

## Команды

- `/rtp` - открыть меню телепортов
- `/rtp low` - телепорт на 400-500 блоков
- `/rtp high` - телепорт на 1000-5000 блоков
- `/rtp near` - телепорт рядом со случайным игроком в радиусе 10000 блоков
- `/rtp help` - показать помощь
- `/rtp reload` - перезагрузить config.yml и gui/gui.yml

## Права

- `rtp.use` - доступ к `/rtp`
- `rtp.low` - доступ к `/rtp low`
- `rtp.high` - доступ к `/rtp high`
- `rtp.near` - доступ к `/rtp near`
- `rtp.help` - доступ к `/rtp help`
- `rtp.reload` - доступ к `/rtp reload`

## Файлы настройки

После первого запуска плагин создаст папку:

`plugins/RTPPlugin/`

Главный конфиг:

`plugins/RTPPlugin/config.yml`

Настройка меню:

`plugins/RTPPlugin/gui/gui.yml`

В `config.yml` редактируются радиусы, кулдаун, мир, количество попыток поиска безопасной точки и сообщения.

В `gui/gui.yml` редактируются размер меню, название меню, слоты, материалы, названия, описание и эффект зачарования предметов.

## Сборка

```bash
mvn clean package
```

Готовый файл будет:

`target/RTPPlugin.jar`
