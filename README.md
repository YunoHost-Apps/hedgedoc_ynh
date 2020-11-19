# HedgeDoc for YunoHost

[![Integration level](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)  
[![Install HedgeDoc with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=hedgedoc)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install HedgeDoc quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
hedgedoc is a real-time collaborative word processing web service. It uses Markdown language.

**Shipped version:** 1.6.0

## Screenshots

![](https://demo.hedgedoc.org/screenshot.png)

## Demo

* [Official demo](https://demo.hedgedoc.org/)

## Configuration

You can configure HedgeDoc by editing this file `/var/www/hedgedoc/config.json` using the [documentation](https://github.com/hedgedoc/hedgedoc/blob/master/docs/configuration.md)

## Documentation

 * Official documentation: https://github.com/hedgedoc/hedgedoc/tree/master/docs
 * YunoHost documentation: https://yunohost.org/#/app_hedgedoc

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/hedgedoc%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/hedgedoc/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/hedgedoc%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/hedgedoc/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/hedgedoc_ynh/issues
 * Upstream app repository: https://github.com/hedgedoc/hedgedoc
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
or
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```
