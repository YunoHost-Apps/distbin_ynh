<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Distbin для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/distbin)](https://ci-apps.yunohost.org/ci/apps/distbin/)
![Состояние работы](https://apps.yunohost.org/badge/state/distbin)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/distbin)

[![Установите Distbin с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Distbin быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Поставляемая версия:** 1.3.0~ynh14

**Демо-версия:** <https://distbin.com/>

## Снимки экрана

![Снимок экрана Distbin](./doc/screenshots/screenshot.PNG)

## :red_circle: Анти-функции

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://distbin.com/about>
- Репозиторий кода главной ветки приложения: <https://github.com/gobengo/distbin>
- Магазин YunoHost: <https://apps.yunohost.org/app/distbin>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
или
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
