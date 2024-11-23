<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Distbin YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/distbin)](https://ci-apps.yunohost.org/ci/apps/distbin/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/distbin)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/distbin)

[![Instalatu Distbin YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Distbin YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Paketatutako bertsioa:** 1.3.0~ynh14

**Demoa:** <https://distbin.com/>

## Pantaila-argazkiak

![Distbin(r)en pantaila-argazkia](./doc/screenshots/screenshot.PNG)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://distbin.com/about>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/gobengo/distbin>
- YunoHost Denda: <https://apps.yunohost.org/app/distbin>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
edo
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
