<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Piped voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/piped.svg)](https://ci-apps.yunohost.org/ci/apps/piped/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/piped.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/piped.maintain.svg)

[![Piped met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=piped)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Piped snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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

**Geleverde versie:** 2024.09.15~ynh1

**Demo:** <https://piped.video/>

## Schermafdrukken

![Schermafdrukken van Piped](./doc/screenshots/channel.png)
![Schermafdrukken van Piped](./doc/screenshots/player.png)

## :red_circle: Anti-eigenschappen

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentatie en bronnen

- Officiele website van de app: <https://docs.piped.video/>
- Officiele beheerdersdocumentatie: <https://docs.piped.video/docs/>
- Upstream app codedepot: <https://github.com/TeamPiped/Piped>
- YunoHost-store: <https://apps.yunohost.org/app/piped>
- Meld een bug: <https://github.com/YunoHost-Apps/piped_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/piped_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
of
sudo yunohost app upgrade piped -u https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
