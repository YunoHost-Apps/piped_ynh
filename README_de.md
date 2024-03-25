<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# Piped für YunoHost

[![Integrations-Level](https://dash.yunohost.org/integration/piped.svg)](https://dash.yunohost.org/appci/app/piped) ![Funktionsstatus](https://ci-apps.yunohost.org/ci/badges/piped.status.svg) ![Wartungsstatus](https://ci-apps.yunohost.org/ci/badges/piped.maintain.svg)

[![Piped mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=piped)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie Piped schnell und einfach auf einem YunoHost-Server installieren.
Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/#/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

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
**Ausgelieferte Version:** 2024.03.25~ynh1

**Demo:** <https://piped.video/>

## Bildschirmfotos

![Bildschirmfotos von Piped](./doc/screenshots/channel.png)
![Bildschirmfotos von Piped](./doc/screenshots/player.png)

## :red_circle: Anti-Eigenschaften

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Dokumentation und Ressourcen

- Offizielle Website der App: <https://docs.piped.video/>
- Offizielle Verwaltungsdokumentation: <https://docs.piped.video/docs/>
- Upstream App Repository: <https://github.com/TeamPiped/Piped>
- YunoHost-Shop: <https://apps.yunohost.org/app/piped>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/piped_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [testing branch](https://github.com/YunoHost-Apps/piped_ynh/tree/testing),


Um den Testing-Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
oder
sudo yunohost app upgrade piped -u https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
