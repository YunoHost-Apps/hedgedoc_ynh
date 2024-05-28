<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# HedgeDoc pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)

[![Installer HedgeDoc avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer HedgeDoc rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

HedgeDoc (anciennement connu sous le nom de CodiMD) est un éditeur open source, basé sur le Web, auto-hébergé et collaboratif.
Vous pouvez l'utiliser pour collaborer facilement sur des notes, des graphiques et même des présentations en temps réel. Tout ce que vous avez à faire est de partager votre lien de note avec vos collègues et ils sont prêts à partir.

### Caractéristiques

- Collaboration en temps réel
- Graphiques et diagrammes
- Révisions
- Mode présentation
- Système d'autorisation facile à utiliser
- Faible configuration système requise


**Version incluse :** 1.9.9~ynh3

**Démo :** <https://demo.hedgedoc.org/>

## Captures d’écran

![Capture d’écran de HedgeDoc](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://hedgedoc.org>
- Documentation officielle de l’admin : <https://docs.hedgedoc.org/>
- Dépôt de code officiel de l’app : <https://github.com/hedgedoc/hedgedoc>
- YunoHost Store : <https://apps.yunohost.org/app/hedgedoc>
- Signaler un bug : <https://github.com/YunoHost-Apps/hedgedoc_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
