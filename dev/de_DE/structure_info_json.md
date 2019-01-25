**Dokumentation, info.json Datei**

Seit Version 3.0 von Jeedom, ist die Datei **info.json** für das reibungslose Funktionieren der Plugins und ihrer erfolgreichen Bereitstellung auf dem  Jeedom Markt erforderlich.

Die Datei info.json wird im Ordner /plugin_info/ Ihres Plugins gespeichert.

Liste der Variablen, der info.json Datei.

Mit * gekennzeichnete Felder sind Pflichtfelder.

Felder                   | Werte                                                                                                                   |
------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
id *                     | Eindeutige Kennung des Plugins auf dem Jeedom Markt. Muss mit einem Buchstaben beginnen. Ohne Akzente.                             |
name *                   | Name des Plugins.                                                                                                            |
description *            | Beschreibung des Plugins, wie es auf dem Jeedom Markt angezeigt wird, mindestens 80 Zeichen. (`<br/>` für einen Zeilenumbruch.)                                  |                                                                                     |
usage                    | Weitere Informationen in der Dokumentation über die Verwendung des Plugins.                                                    |
licence *                | Art der Lizenz.                                                                                                          |
author *                 | Name des Plugin-Autors, wie er nach der Installation des Plugins angezeigt wird, in der Informationen von ihm.         |
require *                | Minimale Version von Jeedom.                                                                                                |
category *               | Kategorie-Ranking des Plugins, auf dem Jeedom Markt. **Es ist unbedingt erforderlich, die Kategorie in der Tabelle unten zu beachten** |
mobile                   | Wenn das Plugin ein eigenes Panel in der Jeedom WebApp verwendet, ist dies der Name der Hauptdatei dieses Panels.   |
changelog *              | Html Link zum Änderungsprotokoll.                                                                                              |
documentation *          | Html Link zur Plugin Dokumentation.                                                                                |
link -> video               | Html  Link zu einer Video-Präsentation.                                                                                 |
link -> forum               | Html Link zum Forum, zum offiziellen Thema des Plugins.                                                                  |
languages                | Liste der verfügbaren Sprachen, für das Plugin : Französisch, Englisch, Deutsch, Italienisch, Spanisch, Russisch, Indonesisch            |
compatibility            | Die Plugin-Kompatibilität : miniplus, smart, docker, rpi, diy, mobileapp.                                                   |
hasDependency            | «true» wenn das Plugin Abhängigkeiten installieren muss, sonst «false» oder nichts.                                              |
hasOwnDeamon             | «true» wenn das Plugin Deamons ausführen soll, sonst «false» oder nichts.                                                   |
maxDependancyInstallTime | Maximale Zeit für die Installation von Abhängigkeiten, ausgedrückt in Minuten.                                            |
issue                    | URL vers le bugtracker si externe (si non remplis alors vous receverez un mail)

**Exemple** :

[Fichier plugin-template/plugin_info/info.json](https://github.com/jeedom/plugin-template/blob/master/plugin_info/info.json)




**NOMENCLATURE CATEGORIES**

Market Jeedom         | info.json               |
--------------------- | ----------------------- |
Communication         | communication           |
Confort               | wellness                |
Energie               | energy                  |
Météo                 | weather                 |
Monitoring            | monitoring              |
Multimédia            | multimedia              |
Nature                | nature                  |
Objets Connectés      | devicecommunication     |
Organisation          | organization            |
Passerelle domotique  | home automation protocol|
Programmation         | programming             |
Protocole domotique   | automation protocol     |
Santé                 | health                  |
Sécurité              | security                |
Automatisme           | automatisation          |











  









