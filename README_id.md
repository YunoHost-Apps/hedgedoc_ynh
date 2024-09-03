<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# HedgeDoc untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/hedgedoc.svg)](https://ci-apps.yunohost.org/ci/apps/hedgedoc/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)

[![Pasang HedgeDoc dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang HedgeDoc secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

HedgeDoc (formerly known as CodiMD) is an open-source, web-based, self-hosted, collaborative markdown editor.
You can use it to easily collaborate on notes, graphs and even presentations in real-time. All you need to do is to share your note-link to your co-workers and they’re ready to go.

### Features

- Real-time collaboration
- Graphs & diagrams
- Revisions
- Presentation mode
- Easy to use permission system
- Low system requirements


**Versi terkirim:** 1.10.0~ynh1

**Demo:** <https://demo.hedgedoc.org/>

## Tangkapan Layar

![Tangkapan Layar pada HedgeDoc](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://hedgedoc.org>
- Dokumentasi admin resmi: <https://docs.hedgedoc.org/>
- Depot kode aplikasi hulu: <https://github.com/hedgedoc/hedgedoc>
- Gudang YunoHost: <https://apps.yunohost.org/app/hedgedoc>
- Laporkan bug: <https://github.com/YunoHost-Apps/hedgedoc_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
atau
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
