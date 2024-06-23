<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Simply Translate YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/simplytranslate.svg)](https://dash.yunohost.org/appci/app/simplytranslate) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/simplytranslate.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/simplytranslate.maintain.svg)

[![Instalatu Simply Translate YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simplytranslate)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Simply Translate YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

The frontend for SimplyTranslate engine, which you can use for translation for many translation engine, there are DeepL, Reverso, ICIBA, Google Translate, and LibreTranslate (which instance LibreTranslate fetch from can be configured) engine.

**Paketatutako bertsioa:** 2023.4.9~ynh4

## Pantaila-argazkiak

![Simply Translate(r)en pantaila-argazkia](./doc/screenshots/st_id-en.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.
- **Libreak ez diren sareko zerbitzuak**: Librea ez den sare-zerbitzu bat sustatzen du edo horren mende dago erabat.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://simplytranslate.org/>
- Jatorrizko aplikazioaren kode-gordailua: <https://codeberg.org/SimpleWeb/SimplyTranslate-Web>
- YunoHost Denda: <https://apps.yunohost.org/app/simplytranslate>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/simplytranslate_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing --debug
edo
sudo yunohost app upgrade simplytranslate -u https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
