<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Distbin dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/distbin)](https://ci-apps.yunohost.org/ci/apps/distbin/)
![Status działania](https://apps.yunohost.org/badge/state/distbin)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/distbin)

[![Zainstaluj Distbin z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Distbin na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Dostarczona wersja:** 1.3.0~ynh14

**Demo:** <https://distbin.com/>

## Zrzuty ekranu

![Zrzut ekranu z Distbin](./doc/screenshots/screenshot.PNG)

## :red_circle: Niepożądane funkcje

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://distbin.com/about>
- Repozytorium z kodem źródłowym: <https://github.com/gobengo/distbin>
- Sklep YunoHost: <https://apps.yunohost.org/app/distbin>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
lub
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
