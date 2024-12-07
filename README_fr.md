<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Soju pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/soju)](https://ci-apps.yunohost.org/ci/apps/soju/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/soju)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/soju)

[![Installer Soju avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=soju)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Soju rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

soju est un bouncer IRC convivial. soju se connecte aux serveurs IRC en amont au nom de l'utilisateur pour fournir des fonctionnalités supplémentaires. soju prend en charge de nombreuses fonctionnalités telles que les utilisateurs multiples, de nombreuses extensions IRCv3, la lecture de l'historique des discussions et les canaux séparés. Il est bien adapté aux petits et grands déploiements.


**Version incluse :** 1.0~ynh1

**Démo :** <https://demo.example.com>

## Captures d’écran

![Capture d’écran de Soju](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://soju.im>
- Documentation officielle utilisateur : <https://yunohost.org/apps>
- Documentation officielle de l’admin : <https://yunohost.org/packaging_apps>
- Dépôt de code officiel de l’app : <https://some.forge.com/example/example>
- YunoHost Store : <https://apps.yunohost.org/app/soju>
- Signaler un bug : <https://github.com/YunoHost-Apps/soju_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/soju_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/soju_ynh/tree/testing --debug
ou
sudo yunohost app upgrade soju -u https://github.com/YunoHost-Apps/soju_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
