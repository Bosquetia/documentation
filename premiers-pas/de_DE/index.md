Willkommen bei der Dokumentation "Ersten Schritte", sie wird Ihnen helfen Ihr Jeedom zu benutzen.

> **Tipp**
>
> Dieses Handbuch soll die vollständige Dokumentation auf der Jeedom
> Webseite, [hier](https://jeedom.fr/doc) nicht ersetzen.

Registrierung auf dem Markt 
=========================

Als erstes müssen Sie ein Konto auf dem Markt erstellen, um Ihr Jeedom zu registrieren. Klicken Sie [hier](https://market.jeedom.fr), um zu beginnen

![premier market](../images/premier-market.png)

Klicken Sie oben rechts auf die Schaltfläche "Registrieren" :

![premier market2](../images/premier-market2.png)

Füllen Sie die verschiedenen Felder aus und bestätigen Sie diese. Sie werden danach auf diese Seite gelangen :

![premier market3](../images/premier-market3.png)

Ihr Markt Konto wurde erstellt, für mehr Einzelheiten über den Markt klicken Sie
[hier](https://www.jeedom.fr/doc/documentation/core/fr_FR/doc-core-market.html).

Hinzufügen von Service Pack-Code 
================================

Wenn Sie eine Jeedom Box gekauft haben, dann erhalten Sie eine E-Mail die
den Service Pack Code enthält.

> **Wichtig**
>
> Es ist wichtig ihn zu merken, da dieser Code Ihnen Zugang zu einigen
> kostenlosen Plugins, sowie zu exklusiven Diensten bietet.

> **Wichtig**
>
> Wenn Sie ein Service Pack vom Jeedom Markt kaufen, haben Sie nichts zu
> tun, es wird Ihnen automatisch zugesendet.

Sobald der Code mit der E-Mail zurückgeschickt wurde, gehen Sie zum [Jeedom Markt](https://market.jeedom.fr) hin und identifizieren Sie sich. 

Dann gehen Sie zu Ihrer Profilseite :

![premier servicepack](../images/premier-servicepack.png)

Klicken Sie dann auf die Registerkarte "Mein Jeedom".

![premier servicepack2](../images/premier-servicepack2.png)

Geben Sie Ihre Service Pack Nummer ein und bestätigen sie :

![premier servicepack3](../images/premier-servicepack3.png)

Damit ist Ihr Service Pack registriert. Für weitere Details zum Markt,
klicken Sie
[hier](https://github.com/jeedom/core/blob/stable/doc/fr_FR/market.asciidoc).

> **Tipp**
>
> Wenn Sie eine offizielle Jeedom Box gekauft haben, dann wurde die
> Service Pack Nummer Ihnen per E-Mail versendet. Wenn Sie sie nicht
> erhalten haben, kontaktieren sie den Laden, wo Sie die Box gekauft haben.

Ihr Jeedom im Netz finden
==================================

Sobald Jeedom elektrisch angeschlossen und mit Ihrem lokalen Netzwerk
verbunden ist, können Sie wie folgt eine Verbindung herstellen.

Jeedom finden
--------------

### Durch den Markt

Die einfachste Lösung ist es (aber funktioniert nicht in 100% der Fälle je nach
Konfiguration Ihres Internetzugangs), die Box zu starten, warten Sie ca. 10
Minuten (Achtung, wenn Sie eine Abbild vom Typ Netinstallation verwenden,
wird es eher 30min) und dann gehen Sie
[hier](https://www.jeedom.com/market/index.php?v=d&p=find) hin.

> **Tipp**
>
> Achtung, Sie müssen im selben Netzwerk wie die Jeedom-Box sein, damit
> diese Methode funktioniert.

> **Wichtig**
>
> Abhängig von Ihrer ADSL-Box funktioniert diese Metode möglicherweise nicht.
> Ist dies der Fall, ist es nicht so schlimm, verbinden Sie sich einfach mit Ihrer
> ADSL-Box und Sie finden die IP von Jeedom darin. Dieser Schritt dient nur
> dazu, Ihnen die lokale IP von Ihrem Jeedom zu liefern.
> Dies ist nicht der Zeitpunkt, dass Ihr Jeedom zu Ihrem Markt-Konto 
> hinzugefügt wird.

### Durch Ihre Internet-Box

-   Gehen Sie zur Administrationsoberfläche Ihrer Internet-Box und 
    suchen Sie in Ihrem Netzwerkgerät nach Jeedom.

-   Sie bekommen Ihre IP angezeigt.

-   Fügen Sie diese IP in Ihren Internetbrowser ein. Sie sollten auf die 
    Jeedom-Oberfläche gelangen.

Erste Verbindung
------------------

Unabhängig von der gewählten Methode, kommen Sie dann auf die
Anmeldeseite. Das Standard-Login und Passwort sind "admin".

![premier jeedomfinder6](../images/premier-jeedomfinder6.png)

Mein Jeedom mit meinem Markt Konto verbinden
===================================

Wir werden sehen, wie Sie Ihr Jeedom mit Ihrem Market-Konto verknüpfen können.

-   Sobald Sie mit Ihrem Jeedom verbunden sind, müssen Sie auf
    Administration → Konfiguration gehen.

-   Klicken Sie auf die Registerkarte **Updates**.

-   Klicken Sie darunter auf die Registerkarte **Markt**.

-   Kreuzen Sie das Kontrollkästchen **Markt aktivieren** an.

-   Geben Sie die Adresse ein : `https://www.jeedom.com/market`

-   Füllen Sie auch die Felder "Benutzername" und "Passwort" entsprechend
    Ihren Anmeldedaten aus (Anmeldedaten des Marktes und nicht 
    von Jeedom).

-   Sie können die Verbindung testen, um sicherzustellen, 
    dass alles richtig gemacht wurde.

-   Vergessen Sie nicht, zu speichern !

Für weitere Details zu der Konfigurationsseite klicken Sie
[hier](https://github.com/jeedom/core/blob/stable/doc/fr_FR/administration.asciidoc).

Meine URL für den direkten Zugang abrufen
==============================

Wenn Sie ein Jeedom Service Pack haben, stellt es Ihnen eine URL für den
direkten Zugang zu Ihrem Jeedom zur verfügung ohne auf Ihrem System
Ports oder anderes zu öffnen.

Um sie zu konfigurieren, genügt es auf 
Allgemein → Einstellungen  →  Konfiguration zu gehen.

Dann gehen Sie zum Teil  "Netzwerkkonfiguration".

![premier dns2](../images/premier-dns2.png)

Sobald Sie hier sind, einfach "Die Jeedom DNS benutzen" aktivieren und dann auf der Zeile "Verwaltung" auf "Neustart" klicken und Ihre URL wird auf der HTTP-Statusebene angezeigt, Sie können sie auf der Market Profil Seite selbstverständlich individuell gestalten.

> **Wichtig**
>
> Wenn Sie Ihr Jeedom mit Ihrem Market-Account verbunden haben, müssen
> Sie 24 bis 48 Stunden warten, bevor Sie den DNS-Service nutzen können.

Jeedom Standardpasswort ändern
============================================

Einer der wichtigsten Schritte besteht darin, das Standardpasswort Ihres
Jeedom-Kontos zu ändern, indem Sie auf Administration → Benutzer
(oben rechts) klicken :

Erst einmal müssen Sie nur die Zeile mit dem Benutzer **admin** wählen und
auf **Passwort ändern** klicken :

![premier changeuser2](../images/premier-changeuser2.png)

Ein Fenster wird sie nach dem neuen Passwort fragen. Achtung, merken sie
es sich, andernfalls haben Sie keinen Zugang zu Ihrem Jeedom :

![premier changeuser3](../images/premier-changeuser3.png)

Jetzt haben Sie das Passwort des Admin-Kontos geändert, für mehr
Information klicken sie auf diese Seite
[hier](https://github.com/jeedom/core/blob/stable/doc/fr_FR/user.asciidoc).

Mein erstes Objekt erstellen
=======================

Sie werden Ihr erstes Objekt erstellen, aber zuerst müssen Sie wissen, was ein Objekt ist.

In Jeedom kann es alles sein, egal was, aber es wird empfohlen, es entsprechend ihren Räumen zu machen.

> **Tipp**
>
> Sie können Beziehungen zwischen Objekten definieren, zB : das Objekt
> Wohnzimmer gehört zum Objekt Erdgeschoss, das wiederum gehört zum
> Objekt Haus

Ein Objekt zu erstellen ist einfach :

-   Gehen Sie zu Werkzeuge → Objekte.

-   Klicken Sie auf die Schaltfläche Hinzufügen :

![premier objet2](../images/premier-objet2.png)

-   Jeedom wird Sie nach den Namen für das Objekt fragen :

![premier objet3](../images/premier-objet3.png)

-   Bestätigen Sie es. Dies ist Ihr erstes erstelltes Objekt :

![premier objet4](../images/premier-objet4.png)

Für weitere Informationen zu diesem Teil klicken Sie
[hier](https://github.com/jeedom/core/blob/stable/doc/fr_FR/administration.asciidoc) .

Mein erstes Plugin installieren
============================

Ein Plugin erlaubt das hinzufügen von Funktionen zu Jeedom. Es gibt
Hunderte von ihnen. Viele sind kostenlos, andere müssen bezahlt werden.
Um auf die Plugin-Seite zuzugreifen, gehen Sie zu Plugins → Plugin
Verwaltung.

Dann klicken Sie einfach auf Markt :

![premier plugin2](../images/premier-plugin2.png)

Sie erhalten dann eine Liste mit allen Plugins, die installiert werden 
können.

> **Hinweis**
>
>Achtung, einige Plugins sind offiziell und andere nicht, bei Problemen mit
> einem nicht offiziellen Plugin kann das Jeedom Team nicht verantwortlich
> gemacht werden.

![premier plugin3](../images/premier-plugin3.png)

Auf ein Plugin klickend, erhalten Sie eine Karteikarte :

![premier plugin4](../images/premier-plugin4.png)

Vous retrouvez alors : 

- des boutons pour installer le plugin : la version stable est fortement recommandée, 
- un bouton pour supprimer le plugin, 
- une brève description, 
- un lien vers la documentation du plugin, 
- un lien vers le changelog (les dernières modifications apportées), 
- la compatibilité avec les différentes plateformes, 
- les avis des utilisateurs, 
- la façon d’utiliser le plugin, 
- des informations complémentaires comme l’auteur, le lien vers la discussion du forum concernant ce plugin, la date de dernière mise à jour, etc.

Pour plus d’informations sur les plugins cliquez [ici](https://jeedom.github.io/core/fr_FR/plugin).

Support 
=======

Jeedom aborde des champs très vastes et évoluant de jour en jour.
Cependant, de nombreux moyens sont mis à votre disposition pour trouver
de l’aide et poser vos questions.

La documentation de Jeedom 
--------------------------

Vous trouverez une documentation complète [ici](https://jeedom.fr/doc) :

Celle-ci se compose de plusieurs catégories :

-   Core : une partie pour le "coeur" de Jeedom,

-   Premiers-pas : Une partie (où vous êtes actuellement) pour les
    premiers éléments à connaître,

-   Installation : Tout ce qui concerne l’installation de Jeedom,

-   Howto : Des tutoriels pour progresser dans divers domaines,

-   Plugins : Les documentations des différents plugins officiels de
    Jeedom,

-   les autres : diverses pages sur les différents protocoles utilisés
    dans Jeedom, la présentation de Jeedom, des listes de
    compatibilité, etc.

Vous trouverez également en dessous la liste des documentations pour les
plugins tiers.

N’hésitez pas à utiliser la fonction **rechercher** en haut à droite de
la page pour trouver les pages en fonction d’un mot précis.

Le forum 
--------

Vous le trouverez [ici](https://jeedom.com/forum) .

Le forum est très actif et contient énormément d’informations. Si vous
avez une question, n’hésitez pas à la poser. Vous aurez une réponse en
moins d’une heure (en moyenne). Attention cependant, le forum est
maintenu par la communauté Jeedom, composée de bénévoles, et non par la
société Jeedom.

![premier support3](../images/premier-support3.png)

Les demandes de support (ou tickets) 
------------------------------------

> **Important**
>
> Attention, toute demande de support nécessite obligatoirement d’avoir
> un compte sur le Market.

Si vous n’avez pas trouvé de solution à votre problème, en dernier
recours, vous pouvez faire une demande de support à l’équipe Jeedom.
Cette demande passe par un ticket. Il est possible d’en ouvrir un de
plusieurs façons :

-   Directement à partir de Jeedom (méthode conseillée) : où que vous
    soyez dans Jeedom, il y a un point d’exclamation en haut à droite
    qui permet de faire une demande de support :

![premier support4](../images/premier-support4.png)

-   Si pour une raison ou pour une autre vous n’avez pas accès à votre
    Jeedom, vous pouvez toujours ouvrir un ticket à partir du Market :

    -   soit avec le point d’exclamation en haut à droite,

    -   soit en allant sur votre profil (cliquez ensuite sur le bouton
        "Ouvrir une demande de support").

![premier support5](../images/premier-support5.png)

Toute la suite des échanges se fera par mail.

> **Tip**
>
> Si, lors de l’ouverture d’un ticket, vous obtenez une erreur indiquant
> que vous avez atteint votre quota, c’est que vous êtes limités à un
> certain nombre de demandes de support par mois, en fonction de votre
> service pack.

Les différents services packs sont : \* Community (gratuit) : 2
tickets/mois (sur plugins payants uniquement) \* Power : 10 tickets/mois
\* Pro : 100 tickets/mois

Vous pouvez retrouver le détail des services packs
[ici](https://www.jeedom.com/site/fr/soft.html#obtenir)
