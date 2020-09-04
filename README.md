# Distbin for YunoHost

[![Integration level](https://dash.yunohost.org/integration/distbin.svg)](https://dash.yunohost.org/appci/app/distbin) ![](https://ci-apps.yunohost.org/ci/badges/distbin.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/distbin.maintain.svg)  
[![Install distbin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=distbin)

> *This package allows you to install distbin quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here). .

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.

**Shipped version:** 1.3.0

## Screenshots

![distbin-screenshot](https://user-images.githubusercontent.com/30271971/54859831-38405100-4d12-11e9-9273-e44596e04e5c.PNG)

## Demo

* [Official demo](https://distbin.com/)

## Configuration

No configuration parameters available for now.

## YunoHost specific features

#### Multi-user support

LDAP and HTTP are not supported.

The app can be used by multiple users, anonymously.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/distbin%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/distbin/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/distbin%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/distbin/)

## Limitations

* No known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/distbin_ynh/issues
 * App website: https://distbin.com/about
 * Upstream app repository: https://github.com/gobengo/distbin
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
or
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```
