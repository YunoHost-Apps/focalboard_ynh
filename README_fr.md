# Focalboard pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/focalboard.svg)](https://dash.yunohost.org/appci/app/focalboard) ![](https://ci-apps.yunohost.org/ci/badges/focalboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/focalboard.maintain.svg)  
[![Installer Focalboard avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=focalboard)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Focalboard rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Focalboard est un outil de gestion de projet qui aide à définir, organiser, suivre et gérer le travail entre les équipes, à l'aide d'une vue de tableau kanban familière.


**Version incluse :** 0.9.2~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot.jpg)

## Documentations et ressources

* Site officiel de l'app : https://www.focalboard.com/
* Documentation officielle utilisateur : https://www.focalboard.com/guide/user/
* Documentation officielle de l'admin : https://www.focalboard.com/guide/admin/
* Dépôt de code officiel de l'app : https://github.com/mattermost/focalboard
* Documentation YunoHost pour cette app : https://yunohost.org/app_focalboard
* Signaler un bug : https://github.com/YunoHost-Apps/focalboard_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing --debug
ou
sudo yunohost app upgrade focalboard -u https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps