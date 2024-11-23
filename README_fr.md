<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Distbin pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/distbin)](https://ci-apps.yunohost.org/ci/apps/distbin/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/distbin)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/distbin)

[![Installer Distbin avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Distbin rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Version incluse :** 1.3.0~ynh14

**Démo :** <https://distbin.com/>

## Captures d’écran

![Capture d’écran de Distbin](./doc/screenshots/screenshot.PNG)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://distbin.com/about>
- Dépôt de code officiel de l’app : <https://github.com/gobengo/distbin>
- YunoHost Store : <https://apps.yunohost.org/app/distbin>
- Signaler un bug : <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
ou
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
