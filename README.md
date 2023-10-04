<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Simply Translate for YunoHost

[![Integration level](https://dash.yunohost.org/integration/simplytranslate.svg)](https://dash.yunohost.org/appci/app/simplytranslate) ![Working status](https://ci-apps.yunohost.org/ci/badges/simplytranslate.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/simplytranslate.maintain.svg)

[![Install Simply Translate with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simplytranslate)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Simply Translate quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

The frontend for SimplyTranslate engine, which you can use for translation for many translation engine, there are DeepL, Reverso, ICIBA, Google Translate, and LibreTranslate (which instance LibreTranslate fetch from can be configured) engine.

**Shipped version:** 2023.4.9~ynh1

## Screenshots

![Screenshot of Simply Translate](./doc/screenshots/st_id-en.png)

## :red_circle: Antifeatures

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentation and resources

* Official app website: <https://simple-web.org/projects/simplytranslate.html>
* Upstream app code repository: <https://codeberg.org/SimpleWeb/SimplyTranslate-Web>
* Report a bug: <https://github.com/YunoHost-Apps/simplytranslate_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing --debug
or
sudo yunohost app upgrade simplytranslate -u https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
