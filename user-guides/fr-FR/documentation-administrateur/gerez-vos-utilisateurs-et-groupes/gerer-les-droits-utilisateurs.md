---
description: Comprenez comment vos utilisateurs peuvent agir sur la plateforme
---

# Gérer les droits utilisateurs

### Comprendre les différents droits utilisateurs&#x20;

#### :point\_right: **Administration de la plateforme**&#x20;

Plusieurs administrateurs peuvent coexister au sein de la plateforme. Ceci peut être utile pour déléguer des droits sans donner les pleins pouvoirs :



<table><thead><tr><th width="191">Type</th><th width="329">Droits</th><th>Groupe</th></tr></thead><tbody><tr><td>Administrateur plateforme</td><td>Gestion de la plateforme (paramètres généraux, notifications, applications)</td><td>platform/administrators</td></tr><tr><td></td><td>Gestion des utilisateurs, des groupes et des espaces</td><td></td></tr><tr><td></td><td>Accès aux analytiques</td><td></td></tr><tr><td>Gestion des analytiques</td><td>Accès aux analytiques</td><td>platform/analytics</td></tr><tr><td></td><td>Gestion des rapports</td><td></td></tr><tr><td>Administrateur de reconnaissance</td><td>Gestion des paramètres reconnaissance</td><td>platform/rewarding</td></tr><tr><td></td><td>Gestion des programes de contribution</td><td></td></tr><tr><td></td><td>Gestion des récompenses</td><td></td></tr><tr><td></td><td>Gestion des portefeuilles</td><td></td></tr><tr><td>Gestionnaire de contenu</td><td>Gestion de contenu (i.e site public)</td><td>platform/web-contributors</td></tr></tbody></table>

#### :point\_right: **Gestion des communautés**

Par défaut :&#x20;

* toute personne peut créer un espace
* seul l'administrateur plateforme peut gérer les communautés et donc accéder aux espaces pour soutenir les animateurs d'espace

Il est possible de modifier ces paramètres si besoin pour déléguer l'animation des communautés à d'autres personnes.

<table><thead><tr><th width="192">Type</th><th width="297">Droits</th><th>Commentaire</th></tr></thead><tbody><tr><td>Administrateur plateforme</td><td>Création des espaces</td><td>Limitez cette option à certains groupes utilisateurs si besoin</td></tr><tr><td></td><td></td><td>Dans ce cas, seuls quelques personnes seulement pourront créer des espaces.</td></tr><tr><td></td><td>Gestion des espaces : accès aux espaces et aux paramètres, capacité à <a href="../gerer-vos-utilisateurs-et-groupes/lier-un-espace-a-un-groupe.md">lier des espaces aux groupes</a></td><td></td></tr><tr><td>Animateurs de communautés</td><td>Si identifié comme gestionnaire de communautés, alors :</td><td></td></tr><tr><td></td><td>Gestion des espaces : accès aux espaces et aux paramètres, capacité à <a href="../gerer-vos-utilisateurs-et-groupes/lier-un-espace-a-un-groupe.md">lier des espaces aux groupes</a></td><td></td></tr></tbody></table>

#### :point\_right: **Rôles dans les espaces**

Par défaut, toute personne membre d'un espace peut publier des messages, ajouter des notes pour participer aux interactions.&#x20;

L'animateur de l'espace peut décider de restreindre ces droits de rédaction en identifiant des rédacteurs. Cela peut être intéressant dans le cadre d'espaces d'information.

<table><thead><tr><th width="192">Type</th><th width="297">Si aucun rédacteur est nommé</th><th>Si rédacteur nommé</th></tr></thead><tbody><tr><td>Animateur d'espace</td><td>Gestion de l'espace (personnalisation de l'espace et applications)</td><td>idem</td></tr><tr><td></td><td>Gestion des membres (invitation, retrait, identification de rôles)</td><td>idem</td></tr><tr><td>Rédacteur d'espace</td><td>--</td><td>Partage d'informations (message, notes)</td></tr><tr><td>Membre d'espace</td><td>Consultation des contenus</td><td>Consultation des contenus</td></tr><tr><td></td><td>Partage d'informations (message, notes)</td><td>Réactions aux infos</td></tr><tr><td></td><td>Réactions aux informations</td><td></td></tr></tbody></table>

#### :point\_right: **Animation d'un programme**

Par défaut, tout administrateur de reconnaissance peut animer un programme. Il peut déléguer ceci à d'autres membres, manuellement ou tacitement.

En effet, si l'audience du programme est un espace, alors les animateurs d'espace sont les animateurs du programme

A contrario, des animateurs peuvent être promus nommément par d'autres animateurs de programme.

<table><thead><tr><th width="192">Type</th><th width="297">Audience : Aucun espace</th><th>Audience : Espace</th></tr></thead><tbody><tr><td>Administrateur de reconnaissance</td><td>Création des programmes</td><td>Création des programmes</td></tr><tr><td></td><td>Animation des programmes (modification présentation du programme, ajout d'actions, gestion des contributions)</td><td>Animation des programmes (modification présentation du programme, ajout d'actions, gestion des contributions)</td></tr><tr><td></td><td>Identification de nouveaux animateurs de programme</td><td>Identification de nouveaux animateurs de programme</td></tr><tr><td>Animateur de l'audience (AKA de l'espace)</td><td>NA</td><td>Animation des programmes (modification présentation du programme, ajout d'actions, gestion des contributions)</td></tr><tr><td></td><td></td><td>Identification de nouveaux animateurs de programme</td></tr><tr><td>Animateur ajouté manuellement par autre animateur</td><td>--</td><td>Animation des programmes (modification présentation du programme, ajout d'actions, gestion des contributions)</td></tr><tr><td></td><td></td><td>Identification de nouveaux animateurs de programme</td></tr></tbody></table>

### Ajouter des droits utilisateurs

#### :point\_right: Droits administrateurs

* Depuis le site d'administration, accédez à la gestion des groupes utilisateurs
* Accédez au groupe Platform
* Puis accédez au sous-groupe souhaité (administration, analytics, rewarding, content management)
* La liste des utilisateurs précédemment identifiés administrateurs s'affiche
* Ajouter ou modifier les droits

:bulb: **Ajoutez le rôle \* pour tout utilisateur que vous ajoutez dans un groupe administrateur**

#### :point\_right: Droits de gestion d'espace

* Depuis le site d'administration, accédez à la gestion des espaces
* Depuis l'onglet permissions, modifiez les droits de gestion d'un espace
* Ajoutez un groupe utilisateur ou un espace. Ainsi les membres de ces groupes seront considérés 'Animateurs de communautés' / 'Gestionnaires de tous les espaces'

#### :point\_right: Droits d'animation de programme

* Depuis le programme que vous souhaitez modifier, accédez à l'édition du programme
* Dans la seconde étape, ajoutez des animateurs de programme en recherchant leur nom

:bulb: **Pour rappel, tout animateur d'espace est considéré animateur de programme dont l'audience est le même espace**
