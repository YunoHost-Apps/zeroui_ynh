<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# ZeroUI para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/zeroui.svg)](https://dash.yunohost.org/appci/app/zeroui) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/zeroui.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/zeroui.maintain.svg)

[![Instalar ZeroUI con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zeroui)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarZeroUI rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

ZeroTier Controller Web UI is a web user interface for a self-hosted ZeroTier network controller.

This project is highly inspired by [ztncui](https://github.com/key-networks/ztncui) and was developed to address the current limitations of applying the self-hosted [network controllers](https://github.com/zerotier/ZeroTierOne/tree/master/controller). Some [ztncui](https://github.com/key-networks/ztncui) problems cannot be fixed because of the core architecture of the project. ZeroUI tries to solve them and implements the following features:

- Full React-powered lightweight [SPA](https://en.wikipedia.org/wiki/Single-page_application) that brings a better user experience, and ZeroUI is mobile-friendly.
- ZeroUI has ZeroTier Central compatible API. That means you could use CLI tools and custom applications made only for ZeroTier Central to manage your networks.
- ZeroUI implements controller-specific workarounds that address some existing [issues](https://github.com/zerotier/ZeroTierOne/issues/859). ZTNCUI [does not](https://github.com/key-networks/ztncui/issues/63).
- ZeroUI is more feature complete. ZeroUI has almost all network-controller-supported features, for example, rule editor. The development process hasn't stopped, so you will enjoy new features and bug fixes shortly.


**Versión actual:** 1.5.8~ynh1

## Capturas

![Captura de ZeroUI](./doc/screenshots/homepage.png)

## :red_circle: Características no deseables

- **Non-free dependencies**: Relies on software dependencies that are not free in order to run.

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/dec0dOS/zero-ui>
- Catálogo YunoHost: <https://apps.yunohost.org/app/zeroui>
- Reportar un error: <https://github.com/YunoHost-Apps/zeroui_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
o
sudo yunohost app upgrade zeroui -u https://github.com/YunoHost-Apps/zeroui_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
