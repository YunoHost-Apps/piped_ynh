<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Piped para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/piped.svg)](https://ci-apps.yunohost.org/ci/apps/piped/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/piped.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/piped.maintain.svg)

[![Instalar Piped con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=piped)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Piped de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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

**Versión proporcionada:** 2024.06.29~ynh1

**Demo:** <https://piped.video/>

## Capturas de pantalla

![Captura de pantalla de Piped](./doc/screenshots/channel.png)
![Captura de pantalla de Piped](./doc/screenshots/player.png)

## :red_circle: Debes considerar

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentación e recursos

- Web oficial da app: <https://docs.piped.video/>
- Documentación oficial para admin: <https://docs.piped.video/docs/>
- Repositorio de orixe do código: <https://github.com/TeamPiped/Piped>
- Tenda YunoHost: <https://apps.yunohost.org/app/piped>
- Informar dun problema: <https://github.com/YunoHost-Apps/piped_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/piped_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
ou
sudo yunohost app upgrade piped -u https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
