<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Distbin voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/distbin.svg)](https://ci-apps.yunohost.org/ci/apps/distbin/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/distbin.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/distbin.maintain.svg)

[![Distbin met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Distbin snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Geleverde versie:** 1.3.0~ynh13

**Demo:** <https://distbin.com/>

## Schermafdrukken

![Schermafdrukken van Distbin](./doc/screenshots/screenshot.PNG)

## :red_circle: Anti-eigenschappen

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentatie en bronnen

- Officiele website van de app: <https://distbin.com/about>
- Upstream app codedepot: <https://github.com/gobengo/distbin>
- YunoHost-store: <https://apps.yunohost.org/app/distbin>
- Meld een bug: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
of
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
