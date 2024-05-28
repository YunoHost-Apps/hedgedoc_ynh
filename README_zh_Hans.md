<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 HedgeDoc

[![集成程度](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![工作状态](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)

[![使用 YunoHost 安装 HedgeDoc](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 HedgeDoc。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

HedgeDoc (formerly known as CodiMD) is an open-source, web-based, self-hosted, collaborative markdown editor.
You can use it to easily collaborate on notes, graphs and even presentations in real-time. All you need to do is to share your note-link to your co-workers and they’re ready to go.

### Features

- Real-time collaboration
- Graphs & diagrams
- Revisions
- Presentation mode
- Easy to use permission system
- Low system requirements


**分发版本：** 1.9.9~ynh3

**演示：** <https://demo.hedgedoc.org/>

## 截图

![HedgeDoc 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://hedgedoc.org>
- 官方管理文档： <https://docs.hedgedoc.org/>
- 上游应用代码库： <https://github.com/hedgedoc/hedgedoc>
- YunoHost 商店： <https://apps.yunohost.org/app/hedgedoc>
- 报告 bug： <https://github.com/YunoHost-Apps/hedgedoc_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
或
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
