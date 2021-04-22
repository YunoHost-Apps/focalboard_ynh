# Focalboard pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/focalboard.svg)](https://dash.yunohost.org/appci/app/focalboard) ![](https://ci-apps.yunohost.org/ci/badges/focalboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/focalboard.maintain.svg)  
[![Installer Focalboard avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=focalboard)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Focalboard rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Focalboard est une alternative open source auto-hébergée à Trello, Notion et Asana. Il aide à définir, organiser, suivre et gérer le travail entre les individus et les équipes.

**Version incluse :** 0.6.5

## Captures d'écran

![](https://www.focalboard.com/img/hero.jpg)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : https://www.focalboard.com/guide/user/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/focalboard.svg)](https://ci-apps.yunohost.org/ci/apps/focalboard/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/focalboard.svg)](https://ci-apps-arm.yunohost.org/ci/apps/focalboard/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/focalboard_ynh/issues
 * Site de l'application : https://www.focalboard.com/
 * Dépôt de l'application principale : https://github.com/mattermost/focalboard
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing --debug
ou
sudo yunohost app upgrade focalboard -u https://github.com/YunoHost-Apps/focalboard_ynh/tree/testing --debug
```
