<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ZeroUI YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/zeroui.svg)](https://ci-apps.yunohost.org/ci/apps/zeroui/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/zeroui.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/zeroui.maintain.svg)

[![Instalatu ZeroUI YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zeroui)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ZeroUI YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

ZeroTier Controller Web UI is a web user interface for a self-hosted ZeroTier network controller.

This project is highly inspired by [ztncui](https://github.com/key-networks/ztncui) and was developed to address the current limitations of applying the self-hosted [network controllers](https://github.com/zerotier/ZeroTierOne/tree/master/controller). Some [ztncui](https://github.com/key-networks/ztncui) problems cannot be fixed because of the core architecture of the project. ZeroUI tries to solve them and implements the following features:

- Full React-powered lightweight [SPA](https://en.wikipedia.org/wiki/Single-page_application) that brings a better user experience, and ZeroUI is mobile-friendly.
- ZeroUI has ZeroTier Central compatible API. That means you could use CLI tools and custom applications made only for ZeroTier Central to manage your networks.
- ZeroUI implements controller-specific workarounds that address some existing [issues](https://github.com/zerotier/ZeroTierOne/issues/859). ZTNCUI [does not](https://github.com/key-networks/ztncui/issues/63).
- ZeroUI is more feature complete. ZeroUI has almost all network-controller-supported features, for example, rule editor. The development process hasn't stopped, so you will enjoy new features and bug fixes shortly.


**Paketatutako bertsioa:** 1.5.8~ynh1

## Pantaila-argazkiak

![ZeroUI(r)en pantaila-argazkia](./doc/screenshots/homepage.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Libreak ez diren dependentziak**: Libreak ez diren dependentzien mende dago exekutatu ahal izateko.

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/dec0dOS/zero-ui>
- YunoHost Denda: <https://apps.yunohost.org/app/zeroui>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zeroui_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zeroui -u https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
