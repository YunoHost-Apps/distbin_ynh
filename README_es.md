<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Distbin para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/distbin.svg)](https://dash.yunohost.org/appci/app/distbin) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/distbin.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/distbin.maintain.svg)

[![Instalar Distbin con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarDistbin rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**Versión actual:** 1.3.0~ynh13

**Demo:** <https://distbin.com/>

## Capturas

![Captura de Distbin](./doc/screenshots/screenshot.PNG)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://distbin.com/about>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/gobengo/distbin>
- Catálogo YunoHost: <https://apps.yunohost.org/app/distbin>
- Reportar un error: <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
o
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
