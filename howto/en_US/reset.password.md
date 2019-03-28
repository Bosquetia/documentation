Nous allons voir ici comment changer le mot de passe Jeedom directement
en modifiant celui-ci dans la base de données, dans le cas où vous l’auriez oublié 

The first thing to do is to connect in SSH to Jeedom (with a
software type kitty or putty).

Une fois connecté, il faut récupérer les identifiants de la base de
données :

`` `{.bash}
cat /var/www/html/core/config/common.config.php
`` `

Ici, vous trouverez le mot de passe pour accéder à la base de données
Jeedom, il faut ensuite faire :

`` `{.bash}
mysql -ujeedom -p
`` `

There he asks you for the password recovered above (the password
is not displayed: it is normal). Then type (or better,
copy paste. You have to make "right-click" under Putty to "paste"):

``` {.bash}
use jeedom;
REPLACE INTO user SET `login`='adminTmp',password='c7ad44cbad762a5da0a452f9e854fdc1e0e7a52a38015f23f3eab1d80b931dd472634dfac71cd34ebc35d16ab7fb8a90c81f975113d6c7538dc69dd8de9077ec',profils='admin', enable='1';
```

Voilà. Vous pouvez vous déconnecter/reconnecter à votre Jeedom avec les
identifiants adminTmp/admin ce qui vous permettra de modifier le mot de
passe des autres comptes également.

>**IMPORTANT**
>
>N'oubliez pas une fois vos accès récupéré de bien supprimer l'utilisateur adminTmp, le laisser pourrait être une potentielle
faille de sécurité dont vous seriez seul responsable.

>**IMPORTANT**
>
> Si vous avez activé l'authentification AD/LDAP cette méthode de remise à zéro ne marchera pas à moins de désactiver le mode AD/LDAP. Vous pouvez le faire en faisant : 
>``` {.bash}
>use jeedom;
>REPLACE INTO `config` SET `value`='0',`key`='ldap:enable',`plugin`='core';
>```
