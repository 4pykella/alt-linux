<h1 align="center">Hi there, I'm Chep</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Это моя маленькая инструкция для себя самого. Я не умею писать READ.ME файлы и это проба пера.</h3>

# Alt-linux как основная система разработки
&nbsp;&nbsp;&nbsp;&nbsp; Это виденье моей операционной системы на регулярки гнома. Здесь инстркуция для меня, чтобы я быстро мог востановить программы и настройки моей операционной системы. 
# Шаг первый наебнуть драйвера 
&nbsp;&nbsp;&nbsp;&nbsp; Проблема один это дрова под переферию и цаще всего все устанавливается кроме драйверов на видеокарту.
```bash
su -
epm play switch-to-nvidia
```
# Установка основных программ для работы через EMP
&nbsp;&nbsp;&nbsp;&nbsp; Этот файл содержит инструкции для быстрой установки популярных программ на Alt Linux с использованием EMP (Alt Linux Package Manager). Мы рассмотрим следующие приложения:

- Git
- Visual Studio Code
- Docker
- VLC
- Telegram
- Discord
- LibreOffice
- Google Chrome
- OBS Studio


Вот команда для исполнения:

```bash
epm -i git code docker-engine vlc telegram-desktop LibreOffice-still obs-studio -y
epm play discord chrome -y
```
# Установка расширений для работы на Gnome
проверяем уствновку расширения
```bash
epm -i gnome-extensions-app
```
Затем ставим необходимые по ссылкам
- [Blur my Shell](https://extensions.gnome.org/extension/3193/blur-my-shell/) блюрит красиво окошки.
- [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/) постоянно отображает панель программ.
- [GSConnect](https://extensions.gnome.org/extension/1319/gsconnect/) Связь телефона и пк.
- [Legacy (GTK3)](https://extensions.gnome.org/extension/4998/legacy-gtk3-theme-scheme-auto-switcher/) Фикс.
# Заключение
Вы успешно завершили настройку вашей системы на базе ALT Linux. Теперь у вас есть все необходимые инструменты для продуктивной работы. В случае возникновения вопросов или необходимости в дополнительных настройках и расширенных возможностях, вы можете обратиться к [официальной документации ALT Linux](https://alt-gnome.wiki/).
