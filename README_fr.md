# HedgeDoc pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)  
[![Installer HedgeDoc avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer HedgeDoc rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l'installer.*

## Vue d'ensemble
HedgeDoc ([anciennement connu sous le nom de CodiMD](https://hedgedoc.org/history/)) est un éditeur Markdown collaboratif open-source. Avec HedgeDoc, vous pouvez facilement collaborer sur des notes, des graphiques et même des présentations en temps réel. Tout ce que vous avez à faire est de partager votre lien de note avec vos collègues. 

**Version incluse :** 1.8.1

## Captures d'écran

![](https://demo.hedgedoc.org/screenshot.png)

## Démo

* [Démo officielle](https://demo.hedgedoc.org/)

## Configuration

Vous pouvez configurer HedgeDoc en modifiant le fichier `/var/www/hedgedoc/config.json` et en vous aidant de la [documentation](https://github.com/hedgedoc/hedgedoc/blob/master/docs/configuration.md)  
Lorsque vous avez terminé de modifier la configuration, pour que vos modifications prennent effet, vous devrez exécuter : `sudo systemctl restart hedgedoc`.

## Documentation

 * Documentation officielle : https://github.com/hedgedoc/hedgedoc/tree/master/docs
 * Documentation YunoHost : https://yunohost.org/fr/app_hedgedoc

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/hedgedoc.svg)](https://ci-apps.yunohost.org/ci/apps/hedgedoc/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/hedgedoc.svg)](https://ci-apps-arm.yunohost.org/ci/apps/hedgedoc/)

## Limitations

* HedgeDoc a besoin de plus de 3 Go de RAM pour être installé.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/hedgedoc_ynh/issues
 * Site de l'application : https://hedgedoc.org
 * Dépôt de l'application principale : https://github.com/hedgedoc/hedgedoc
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```
