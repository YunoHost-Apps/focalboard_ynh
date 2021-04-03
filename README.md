# Focalboard for YunoHost

[![Integration level](https://dash.yunohost.org/integration/focalboard.svg)](https://dash.yunohost.org/appci/app/focalboard) ![](https://ci-apps.yunohost.org/ci/badges/focalboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/focalboard.maintain.svg)  
[![Install Focalboard with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=focalboard)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Focalboard quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Focalboard is an open source, self-hosted alternative to Trello, Notion, and Asana. It helps define, organize, track and manage work across individuals and teams.

**Shipped version:** 0.6.1

## Screenshots

![](https://www.focalboard.com/img/hero.jpg)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://www.focalboard.com/guide/user/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? **No**
Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/focalboard.svg)](https://ci-apps.yunohost.org/ci/apps/focalboard/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/focalboard.svg)](https://ci-apps-arm.yunohost.org/ci/apps/focalboard/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/focalboard_ynh/issues
 * App website: https://www.focalboard.com/
 * Upstream app repository: https://github.com/mattermost/focalboard
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing --debug
or
sudo yunohost app upgrade focalboard -u https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing --debug
```
