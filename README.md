# distbin app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/distbin.svg)](https://dash.yunohost.org/appci/app/distbin)  
[![Install distbin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=distbin)

> *This package allow you to install distbin quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here). .

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.

**Shipped version:** 1.0

## License

**LICENSE:** Apache-2.0

## Demo

* [Official demo](https://distbin.com/)

## Configuration

No configuration parameter available for now.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

LDAP and HTTP are not supported
The app be used by multiple users, anonymously.

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/distbin%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/distbin/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/distbin%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/distbin/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/distbin%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/distbin/)

## Limitations

* No known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/distbin_ynh/issues
 * App website: https://distbin.com/about
 * GitHub website: https://github.com/gobengo/distbin
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
or
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```
