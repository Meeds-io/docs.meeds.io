---
description: Créer, inviter vos utilisateurs
---

# Créer et gérer les utilisateurs

### Créez vos utilisateurs (unitaire)

#### :point\_right: **Ajouter un utilisateur**

* Depuis le site d'administration, accédez à la gestion des utilisateurs
* Accédez au formulaire d'ajout d'un utilisateur en cliquant sur 'Ajouter un utilisateur'
* Le formulaire s'ouvre et vous propose d'ajouter des informations. Elles sont toutes obligatoires. Voici nos recommandations :&#x20;

:white\_check\_mark: Nom d'utilisateur : utilisez le format suivant \[prenom].\[nom] sans accent, ni caractères spéciaux

:white\_check\_mark: Nom, prénom : Renseignez les informations à votre disposition (minimum 3 caractères). Chiffres non acceptés

:white\_check\_mark: Email : Indiquez l'email qui sera utilisé pour envoi de l'invitation, des notifications et pour authentification

:white\_check\_mark: Mot de passe : Pré-renseignez un mot de passe temporaire que l'utilisateur pourra changer dans son processus d'invitation

#### :point\_right: **Inviter cet utilisateur à rejoindre la plateforme**

* Une fois l'utilisateur créé, retrouvez-le dans la liste des utilisateurs actifs.
* Si vous le souhaitez, vous pouvez l'inviter simplement en cliquant sur l'enveloppe proposée dans l'interface
* Un email lui sera transmis pour rejoindre la plateforme
* Cet email inclut un lien pour personnaliser son mot de passe
* Ce lien est valable durant 24h

:bulb: **Infos clés**&#x20;

* Si nécessaire, transmettez à nouveau l'email en cliquant à nouveau sur l'enveloppe
* Une fois que l'utilisateur a rejoint la plateforme, il ne sera plus possible de lui transmettre cet email

:warning: _Pour créer un utilisateur externe, invitez-le depuis un espace. Il sera automatiquement considéré externe._

### Créez vos utilisateurs (en masse)

#### :point\_right: **Créer votre fichier .csv**

* Ajoutez des utilisateurs en masse en important un fichier au format .csv
* En important votre fichier, vous créerez ainsi les utilisateurs non encore créés
* Si des utilisateurs sont déjà créés, les informations seront mises à jour. Un contrôle de cohérence est réalisé sur le nom d'utilisateur et l'email

:bulb: _Il sera possible d'y intégrer des infos complémentaires telles que la fonction, l'organisation, le lieu, etc. Pour ce faire, contactez votre référent Meeds_

Voici un fichier type pour préparer l'import des utilisateurs :&#x20;

{% file src="../../.gitbook/assets/import.csv" %}

#### :point\_right: **Importer le fichier**

* Depuis la gestion des utilisateurs, accédez à l'option 'Importer par fichier CSV' proposée en seconde option à l'ajout d'utilisateur
* Sélectionnez le fichier préalablement préparé
* L'import est lancé instantanément

:bulb: Si des erreurs sont constatées à l'import, alors un rapport vous aide à comprendre et à modifier vos informations

#### :point\_right: Agir en masse sur des données utilisateurs&#x20;

Sélectionnez des utilisateurs puis cliquez sur l'option proposée que vous souhaitez :&#x20;

* Inviter en masse : les utilisateurs sélectionnés non encore connectés recevront un email
* Désactiver en masse : les utilisateurs sélectionnés seront désactivés. Ils ne pourront plus accéder à la plateforme
* Activer en masse : les utilisateurs sélectionnés (si désactivés) seront activés. Ils pourront se connecter et retrouveront leurs droits précédemment associés.

### Recherchez un utilisateur ou des utilisateurs

#### :point\_right: **Rechercher un utilisateur**

Depuis la gestion des utilisateurs, recherchez vos utilisateurs depuis :&#x20;

* Le champ texte pour filtrer par nom ou prénom de l'utilisateur
* Les filtres avancés pour filtrer par statut : Connecté, Jamais connecté, Enrôlé, Jamais inscrit, Aucun enrôlement possible, Interne, Externe

### Consultez leurs rôles et attributs

#### :point\_right: **Consulter les informations de l'utilisateur**

Pour chaque utilisateur, vous pouvez :&#x20;

* consulter les infos : identifiant, prénom, nom, email
* suivre leur statut : dernière connexion, enrôlement, activé / désactivé, source de la donnée utilisateur, interne / externe
* accéder aux rôles de l'utilisateur : en cliquant dessus, vous accédez à un panneau récapitulatif de ces droits
* modifier la fiche : nom, prénom, email et mot de passe le cas échéant
