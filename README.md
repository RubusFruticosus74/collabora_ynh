<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Collabora Online for YunoHost

[![Integration level](https://dash.yunohost.org/integration/collabora.svg)](https://dash.yunohost.org/appci/app/collabora) ![Working status](https://ci-apps.yunohost.org/ci/badges/collabora.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/collabora.maintain.svg)  
[![Install Collabora Online with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=collabora)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Collabora Online quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Collabora Online is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate into Nextcloud.

### Features

- View and edit text documents, spreadsheets, presentations & more
- Collaborative editing features
- Works in any modern browser – no plugin needed
- Preservation of layout and formatting of documents
- text documents (odt, docx, doc…)
- spreadsheets (ods, xlsx, xls…)
- presentations (odp, pptx, ppt…)


**Shipped version:** 22.05.8.2~ynh2

## Screenshots

![Screenshot of Collabora Online](./doc/screenshots/Collabora_Online_-_versions_integration.png)

## Disclaimers / important information

## Configuration

**Settings:**
The settings of Collabora are at `https://office.domain.tld/browser/dist/admin/admin.html`.

- User: admin
- Password: The password set during the installation. (If you forgot it, you can find it again in `/etc/coolwsd/coolwsd.xml`).

## Connexion to Nextcloud

If you want to connect with Nextcloud, you have to install the [Collabora Online](https://apps.nextcloud.com/apps/richdocuments) app in Nextcloud, and configure it with the domain of your Collabora installation.

*:warning: There are several Collabora Online apps. Be sure **not** to install the `Collabora Online - Built-in CODE server` apps, which are a lightwheigt version of this Collabora package. :warning:*

## Limitations

**ARM platform not supported.** If you want to run Collabora on Nextcloud, there is a lightweight version of the Collabora server for ARM, called [Collabora Online - Built-in CODE Server (ARM64)](https://apps.nextcloud.com/apps/richdocumentscode_arm64) which can easily connect with the [Collabora Online](https://apps.nextcloud.com/apps/richdocuments) app.

**CODE has a warning limitation**

![](https://www.libreoffice.org/assets/Uploads/LibreOffice-Online-limit.png)

## Documentation and resources

* Official app website: <https://collaboraoffice.com>
* Official admin documentation: <https://www.collaboraoffice.com/code/>
* YunoHost documentation for this app: <https://yunohost.org/app_collabora>
* Report a bug: <https://github.com/YunoHost-Apps/collabora_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/collabora_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/collabora_ynh/tree/testing --debug
or
sudo yunohost app upgrade collabora -u https://github.com/YunoHost-Apps/collabora_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
