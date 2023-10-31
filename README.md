<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Distbin for YunoHost

[![Integration level](https://dash.yunohost.org/integration/distbin.svg)](https://dash.yunohost.org/appci/app/distbin) ![Working status](https://ci-apps.yunohost.org/ci/badges/distbin.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/distbin.maintain.svg)

[![Install Distbin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Distbin quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Shipped version:** 1.3.0~ynh13

**Demo:** https://distbin.com/

## Screenshots

![Screenshot of Distbin](./doc/screenshots/screenshot.PNG)

## Documentation and resources

* Official app website: <https://distbin.com/about>
* Upstream app code repository: <https://github.com/gobengo/distbin>
* YunoHost Store: <https://apps.yunohost.org/app/distbin>
* Report a bug: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
or
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
