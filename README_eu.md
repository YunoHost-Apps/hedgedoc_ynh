<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# HedgeDoc YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/hedgedoc)](https://ci-apps.yunohost.org/ci/apps/hedgedoc/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/hedgedoc)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/hedgedoc)

[![Instalatu HedgeDoc YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek HedgeDoc YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

HedgeDoc (formerly known as CodiMD) is an open-source, web-based, self-hosted, collaborative markdown editor.
You can use it to easily collaborate on notes, graphs and even presentations in real-time. All you need to do is to share your note-link to your co-workers and they’re ready to go.

### Features

- Real-time collaboration
- Graphs & diagrams
- Revisions
- Presentation mode
- Easy to use permission system
- Low system requirements


**Paketatutako bertsioa:** 1.10.0~ynh2

**Demoa:** <https://demo.hedgedoc.org/>

## Pantaila-argazkiak

![HedgeDoc(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://hedgedoc.org>
- Administratzaileen dokumentazio ofiziala: <https://docs.hedgedoc.org/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/hedgedoc/hedgedoc>
- YunoHost Denda: <https://apps.yunohost.org/app/hedgedoc>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/hedgedoc_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
edo
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
