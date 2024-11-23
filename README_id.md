<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Distbin untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/distbin.svg)](https://ci-apps.yunohost.org/ci/apps/distbin/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/distbin.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/distbin.maintain.svg)

[![Pasang Distbin dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Distbin secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Versi terkirim:** 1.3.0~ynh14

**Demo:** <https://distbin.com/>

## Tangkapan Layar

![Tangkapan Layar pada Distbin](./doc/screenshots/screenshot.PNG)

## :red_circle: Antifitur

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://distbin.com/about>
- Depot kode aplikasi hulu: <https://github.com/gobengo/distbin>
- Gudang YunoHost: <https://apps.yunohost.org/app/distbin>
- Laporkan bug: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
atau
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
