# heroku-lavalink-server

Текущая версия lavalink: **v3.3.1**
\nПоддержать автора [донатом](https://qiwi.me/xdope)
##### Примичание:
Автоматическая установка перезапустит ваш сервер, поэтому устанавливайте эго на свой страх и риск, автор не несет ответственности за любой ущерб, который может возникнуть в результате автоматической установки!

### Установка в один клик:
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/XDopi/heroku-lavalink-server/tree/auto)

Buildpacks должны быть добавлены автоматически, вы можете изменить переменную `PASS` во время установки, чтобы изменить пароль от сервера.

## Примичания:
1. После изменения `PASS` вы должны повторно развернуть или щелкнуть меню `More` и нажать **Restart all dynos**.
2. Если Heroku не может автоматически настроить buildpacks, зайдите в настройки ваших проектов на сайте Heroku и добавьте java и nodejs.

Пожалуйста, поймите, что на вашем сервере lavalink **не хватает памяти**. Если вы делаете обновление, вы должны изменить -Xmx в `JAVA_TOOL_OPTIONS` на новое количество оперативной памяти.
