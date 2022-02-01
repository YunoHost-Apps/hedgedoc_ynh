# HedgeDoc pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)  
[![Installer HedgeDoc avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer HedgeDoc rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Éditeur collaboratif pour travailler sur des notes en Markdown

**Version incluse :** 1.9.2~ynh1

**Démo :** https://demo.hedgedoc.org/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

Vous pouvez configurer HedgeDoc en modifiant le fichier `/var/www/hedgedoc/config.json` et en vous aidant de la [documentation](https://github.com/hedgedoc/hedgedoc/blob/master/docs/configuration.md)  
Lorsque vous avez terminé de modifier la configuration, pour que vos modifications prennent effet, vous devrez exécuter : `sudo systemctl restart hedgedoc`.

## Documentations et ressources

* Site officiel de l'app : https://hedgedoc.org
* Documentation officielle de l'admin : https://docs.hedgedoc.org/
* Dépôt de code officiel de l'app : https://github.com/hedgedoc/hedgedoc
* Documentation YunoHost pour cette app : https://yunohost.org/app_hedgedoc
* Signaler un bug : https://github.com/YunoHost-Apps/hedgedoc_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps