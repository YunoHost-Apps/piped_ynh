<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Piped для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/piped)](https://ci-apps.yunohost.org/ci/apps/piped/)
![Состояние работы](https://apps.yunohost.org/badge/state/piped)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/piped)

[![Установите Piped с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=piped)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Piped быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

# The Problem

YouTube has an extremely invasive privacy policy which relies on using user data in unethical ways. You give them a lot of data - ranging from ideas, music taste, content, political opinions, and much more than you think.

By using Piped, you can freely watch and listen to content without the fear of prying eyes watching everything you are doing.

## Features:

**User Features**

-   [x] No Ads
-   [x] No Tracking
-   [x] Lightweight on server and client
-   [x] Infinite Scrolling
-   [x] Light/Dark themes
-   [x] Login
-   [x] Feeds
-   [x] Playlists
-   [x] Integration with [SponsorBlock](https://github.com/ajayyy/SponsorBlock)
-   [x] Integration with [LBRY](https://lbry.com/) for streaming
-   [x] Integration with [Return YouTube Dislike](https://returnyoutubedislike.com/) via [RYD-Proxy](https://github.com/TeamPiped/RYD-Proxy)
-   [x] 4K support
-   [x] No connections to Google's servers
-   [x] Playing just audio
-   [x] PWA support
-   [x] Locally saved Preferences
-   [x] [Available in many languages](src/locales), thanks to [our translators](https://hosted.weblate.org/projects/piped/frontend/)
-   [x] Embedded video support
-   [x] No age restriction
-   [x] Bypasses Geo restrictions if possible through a federated network

**Technical Features**

-   [x] Multi-region load-balancing
-   [x] Performant by design, designed to handle 1000s of users concurrently
-   [x] Does not use official YouTube APIs
-   [x] Uses [NewPipeExtractor](https://github.com/TeamNewPipe/NewPipeExtractor) to extract information
-   [x] Public [JSON API](https://docs.piped.video/docs/api-documentation/)
-   [x] Federated protocol on Matrix to let instances collaborate with each other

**Поставляемая версия:** 2025.03.11~ynh1

**Демо-версия:** <https://piped.video/>

## Снимки экрана

![Снимок экрана Piped](./doc/screenshots/channel.png)
![Снимок экрана Piped](./doc/screenshots/player.png)

## :red_circle: Анти-функции

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://docs.piped.video/>
- Официальная документация администратора: <https://docs.piped.video/docs/>
- Репозиторий кода главной ветки приложения: <https://github.com/TeamPiped/Piped>
- Магазин YunoHost: <https://apps.yunohost.org/app/piped>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/piped_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/piped_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
или
sudo yunohost app upgrade piped -u https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
