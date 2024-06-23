<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Distbin

[![集成程度](https://dash.yunohost.org/integration/distbin.svg)](https://dash.yunohost.org/appci/app/distbin) ![工作状态](https://ci-apps.yunohost.org/ci/badges/distbin.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/distbin.maintain.svg)

[![使用 YunoHost 安装 Distbin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=distbin)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Distbin。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A distributed pastebin. i.e. it is a service where anyone can post things on the web, and others can react by posting anywhere else on the web (including here).

A networked place to store posted web documents. This is meant to allow for distributed social commentary and reaction around these documents using best practices recommended or noted by the W3C Social Web Working Group.


**分发版本：** 1.3.0~ynh13

**演示：** <https://distbin.com/>

## 截图

![Distbin 的截图](./doc/screenshots/screenshot.PNG)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://distbin.com/about>
- 上游应用代码库： <https://github.com/gobengo/distbin>
- YunoHost 商店： <https://apps.yunohost.org/app/distbin>
- 报告 bug： <https://github.com/YunoHost-Apps/distbin_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/distbin_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
或
sudo yunohost app upgrade distbin -u https://github.com/YunoHost-Apps/distbin_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
