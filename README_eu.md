<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Piped YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/piped.svg)](https://ci-apps.yunohost.org/ci/apps/piped/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/piped.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/piped.maintain.svg)

[![Instalatu Piped YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=piped)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Piped YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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

**Paketatutako bertsioa:** 2024.10.13~ynh2

**Demoa:** <https://piped.video/>

## Pantaila-argazkiak

![Piped(r)en pantaila-argazkia](./doc/screenshots/channel.png)
![Piped(r)en pantaila-argazkia](./doc/screenshots/player.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Libreak ez diren sareko zerbitzuak**: Librea ez den sare-zerbitzu bat sustatzen du edo horren mende dago erabat.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://docs.piped.video/>
- Administratzaileen dokumentazio ofiziala: <https://docs.piped.video/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/TeamPiped/Piped>
- YunoHost Denda: <https://apps.yunohost.org/app/piped>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/piped_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/piped_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
edo
sudo yunohost app upgrade piped -u https://github.com/YunoHost-Apps/piped_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
