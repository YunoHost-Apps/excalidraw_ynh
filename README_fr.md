# Excalidraw pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/excalidraw.svg)](https://dash.yunohost.org/appci/app/excalidraw) ![](https://ci-apps.yunohost.org/ci/badges/excalidraw.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/excalidraw.maintain.svg)  
[![Installer Excalidraw avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=excalidraw)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Excalidraw rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
CodiMD est un service web de traitement de texte collaboratif en temps réel. Il utilise le langage Markdown.

**Version incluse :** 1.0.0

## Captures d'écran

![]()

## Démo

* [Démo officielle](https://excalidraw.com/)

## Configuration

## Documentation

 * Documentation officielle : https://github.com/codimd/server/tree/master/docs/
 * Documentation YunoHost : https://yunohost.org/#/app_codimd_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/excalidraw%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/excalidraw/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/excalidraw%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/excalidraw/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/excalidraw_ynh/issues
 * Dépôt de l'application principale : https://github.com/excalidraw/excalidraw
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/excalidraw_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/excalidraw_ynh/tree/testing --debug
ou
sudo yunohost app upgrade excalidraw -u https://github.com/YunoHost-Apps/excalidraw_ynh/tree/testing --debug
```
