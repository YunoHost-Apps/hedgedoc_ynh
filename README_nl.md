<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# HedgeDoc voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/hedgedoc.svg)](https://ci-apps.yunohost.org/ci/apps/hedgedoc/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)

[![HedgeDoc met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je HedgeDoc snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

HedgeDoc (formerly known as CodiMD) is an open-source, web-based, self-hosted, collaborative markdown editor.
You can use it to easily collaborate on notes, graphs and even presentations in real-time. All you need to do is to share your note-link to your co-workers and they’re ready to go.

### Features

- Real-time collaboration
- Graphs & diagrams
- Revisions
- Presentation mode
- Easy to use permission system
- Low system requirements


**Geleverde versie:** 1.9.9~ynh1

**Demo:** <https://demo.hedgedoc.org/>

## Schermafdrukken

![Schermafdrukken van HedgeDoc](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://hedgedoc.org>
- Officiele beheerdersdocumentatie: <https://docs.hedgedoc.org/>
- Upstream app codedepot: <https://github.com/hedgedoc/hedgedoc>
- YunoHost-store: <https://apps.yunohost.org/app/hedgedoc>
- Meld een bug: <https://github.com/YunoHost-Apps/hedgedoc_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
of
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
