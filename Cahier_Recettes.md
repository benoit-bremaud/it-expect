### Cahier de Recettes pour l'Application HappiHub

#### 1. Présentation de l'Application

**HappiHub** est une plateforme communautaire dédiée à l'organisation et à la promotion d'événements culturels. Conçue pour faciliter la connexion entre les organisateurs d'événements et les participants, HappiHub permet aux utilisateurs de créer, gérer, et participer à des événements tout en interagissant avec d'autres membres de la communauté par le biais de commentaires et de discussions.

##### Objectifs de l'Application :
- **Faciliter l'organisation d'événements :** Les utilisateurs peuvent créer des événements en ligne, définir des détails tels que le titre, la description, la date, et le lieu, et les publier pour que la communauté puisse y accéder.
- **Promouvoir l'interaction communautaire :** En plus de la création et de la gestion d'événements, HappiHub encourage l'interaction sociale par le biais de fonctionnalités de commentaires, permettant aux utilisateurs de partager leurs idées, poser des questions, et interagir avec d'autres participants.
- **Offrir une expérience utilisateur fluide :** L'application est conçue pour être intuitive et facile à utiliser, tant pour les organisateurs que pour les participants. Les utilisateurs peuvent rapidement s'inscrire, se connecter, et naviguer à travers les différentes fonctionnalités pour participer pleinement à la vie communautaire.

##### Fonctionnalités Clés de l'Application :
1. **Gestion des Utilisateurs :**
   - Permet l'inscription et la gestion des comptes utilisateurs.
   - Authentification sécurisée des utilisateurs pour accéder à leur espace personnel.
   - Gestion des profils, permettant aux utilisateurs de personnaliser leurs informations.

2. **Gestion des Événements :**
   - Création d'événements avec des détails complets (titre, description, date, lieu).
   - Modification et suppression d'événements par les organisateurs.
   - Consultation des événements disponibles pour les utilisateurs inscrits.

3. **Gestion des Commentaires :**
   - Permet aux utilisateurs de commenter sur les événements.
   - Modification et suppression de leurs propres commentaires par les utilisateurs.
   - Affichage des commentaires associés à chaque événement pour encourager la discussion et l'interaction.

##### Public Cible :
- **Organisateurs d'Événements :** Personnes ou organisations souhaitant promouvoir des événements culturels, éducatifs, ou communautaires.
- **Participants aux Événements :** Utilisateurs intéressés par la participation à des événements, souhaitant s'informer, s'inscrire, et interagir avec d'autres participants.
- **Communauté Générale :** Toute personne souhaitant se connecter à une communauté partageant des intérêts similaires en matière d'événements culturels.

##### Valeur Ajoutée :
- **Centralisation des Événements :** HappiHub centralise toutes les informations relatives aux événements, permettant aux utilisateurs de découvrir facilement des événements d'intérêt.
- **Engagement de la Communauté :** En offrant une plateforme de discussion intégrée, HappiHub favorise l'engagement et la communication entre les utilisateurs, créant une communauté active et interconnectée.
- **Accessibilité :** Une interface utilisateur simple et intuitive, accessible sur différentes plateformes (web, mobile), permet aux utilisateurs d'interagir avec l'application où qu'ils soient.

---
### 2. Fonctionnalités Clés de l'Application HappiHub

Dans cette section, nous allons détailler les fonctionnalités clés implémentées dans l'application HappiHub. Chaque fonctionnalité sera présentée avec une description complète, expliquant son rôle au sein de l'application, ainsi que les interactions utilisateurs prévues. Ces détails fourniront le contexte nécessaire pour les scénarios de test qui seront définis dans les sections suivantes du cahier de recettes.

#### 2.1 Gestion des Utilisateurs

**Description :**
La gestion des utilisateurs est une fonctionnalité essentielle de HappiHub, permettant aux utilisateurs de s'inscrire, de se connecter et de gérer leur profil. Cette fonctionnalité comprend plusieurs sous-fonctionnalités qui assurent la sécurité et la personnalisation de l'expérience utilisateur.

**Sous-Fonctionnalités :**
- **Inscription d'un Utilisateur :** Permet à un nouvel utilisateur de créer un compte en fournissant un email, un nom d'utilisateur, et un mot de passe. Une fois inscrit, l'utilisateur reçoit un email de confirmation pour vérifier son compte.
- **Connexion d'un Utilisateur :** Permet à un utilisateur existant de se connecter à son compte en utilisant ses identifiants. La connexion ouvre l'accès à l'espace personnel de l'utilisateur, où il peut gérer ses informations et ses activités.
- **Gestion du Profil :** Après la connexion, l'utilisateur peut accéder à son profil pour mettre à jour ses informations personnelles telles que le nom d'utilisateur, l'adresse email, et le mot de passe.

**Rôle dans l'Application :**
Cette fonctionnalité est cruciale car elle assure la sécurité des données utilisateurs et contrôle l'accès aux autres parties de l'application. Sans une gestion efficace des utilisateurs, il serait impossible de garantir que seuls les utilisateurs autorisés peuvent créer et gérer des événements ou participer aux discussions.

#### 2.2 Gestion des Événements

**Description :**
La gestion des événements est au cœur de l'application HappiHub. Elle permet aux utilisateurs, en particulier les organisateurs, de créer, modifier et supprimer des événements. Les événements créés sont ensuite consultables par l'ensemble des utilisateurs de la plateforme.

**Sous-Fonctionnalités :**
- **Création d'un Événement :** Un utilisateur peut créer un nouvel événement en remplissant un formulaire détaillé qui comprend le titre de l'événement, une description, la date et l'heure, ainsi que le lieu. Une fois créé, l'événement est visible par tous les utilisateurs.
- **Modification d'un Événement :** L'organisateur d'un événement peut modifier les détails de l'événement. Cette option est réservée à l'utilisateur qui a créé l'événement, assurant ainsi que les informations ne peuvent être altérées que par l'organisateur.
- **Suppression d'un Événement :** L'organisateur peut également supprimer un événement. Une fois supprimé, l'événement disparaît de la liste des événements disponibles sur la plateforme.

**Rôle dans l'Application :**
Cette fonctionnalité est essentielle pour permettre aux utilisateurs d'organiser et de promouvoir des événements culturels. Elle fournit les outils nécessaires pour gérer tous les aspects d'un événement, depuis sa création jusqu'à sa suppression, tout en garantissant que seuls les utilisateurs autorisés peuvent effectuer des modifications.

#### 2.3 Gestion des Commentaires

**Description :**
La gestion des commentaires permet aux utilisateurs d'interagir les uns avec les autres en commentant les événements. Cette fonctionnalité encourage l'engagement communautaire en offrant un espace pour les discussions et les échanges d'opinions sur chaque événement.

**Sous-Fonctionnalités :**
- **Ajout de Commentaires :** Tout utilisateur inscrit et connecté peut ajouter un commentaire à un événement. Le commentaire est ensuite visible par tous les utilisateurs qui consultent l'événement.
- **Modification de Commentaires :** Les utilisateurs peuvent modifier leurs propres commentaires. Cela leur permet de corriger des erreurs ou de mettre à jour leurs pensées en fonction de nouvelles informations.
- **Suppression de Commentaires :** Les utilisateurs peuvent également supprimer leurs propres commentaires s'ils le souhaitent. Une fois supprimé, le commentaire n'est plus visible sous l'événement.

**Rôle dans l'Application :**
La gestion des commentaires est essentielle pour créer une interaction active et dynamique au sein de la communauté HappiHub. En permettant aux utilisateurs de discuter des événements, cette fonctionnalité renforce le lien entre les participants et les organisateurs, contribuant ainsi à une meilleure expérience communautaire.

---
### 3.1 Gestion des Utilisateurs

##### 3.1.1 Inscription d'un Utilisateur

**Objectif :** Valider le processus d'inscription pour garantir que les utilisateurs peuvent créer des comptes avec des informations valides et que le système gère correctement les erreurs courantes.

**Scénarios de Test Courants :**

1. **Inscription avec des Données Valides**
   - **Étapes :**
     1. Accéder à la page d'inscription.
     2. Remplir le formulaire avec :
        - **Email :** `valid.email@example.com`
        - **Nom d'utilisateur :** `JohnDoe`
        - **Mot de passe :** `Password123!`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `201 Created`
     - **Réponse JSON :**
       ```json
       {
         "userID": "12345",
         "email": "valid.email@example.com",
         "username": "JohnDoe"
       }
       ```
     - **Email de confirmation :** L'utilisateur reçoit un email avec un lien de confirmation.
     - **Message UI :** "Inscription réussie ! Veuillez vérifier votre email pour confirmer votre compte."

2. **Inscription avec un Email Déjà Utilisé**
   - **Étapes :**
     1. Accéder à la page d'inscription.
     2. Remplir le formulaire avec un email déjà enregistré dans le système :
        - **Email :** `duplicate.email@example.com`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `409 Conflict`
     - **Réponse JSON :**
       ```json
       {
         "error": "EmailAlreadyInUse",
         "message": "Cet email est déjà utilisé. Veuillez en choisir un autre."
       }
       ```
     - **Message UI :** "Cet email est déjà utilisé. Veuillez en choisir un autre."

3. **Inscription avec un Mot de Passe Non Conforme**
   - **Étapes :**
     1. Accéder à la page d'inscription.
     2. Remplir le formulaire avec un mot de passe qui ne respecte pas les critères (par exemple, moins de 8 caractères) :
        - **Mot de passe :** `short`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "WeakPassword",
         "message": "Le mot de passe doit comporter au moins 8 caractères."
       }
       ```
     - **Message UI :** "Le mot de passe doit comporter au moins 8 caractères."

4. **Inscription avec un Email au Format Incorrect**
   - **Étapes :**
     1. Accéder à la page d'inscription.
     2. Remplir le formulaire avec un email incorrectement formaté :
        - **Email :** `invalid-email`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "InvalidEmailFormat",
         "message": "L'adresse email est invalide."
       }
       ```
     - **Message UI :** "L'adresse email est invalide."

---

##### 3.1.2 Connexion d'un Utilisateur

**Objectif :** Valider le processus de connexion pour s'assurer que les utilisateurs peuvent accéder à leurs comptes avec des identifiants valides et que le système gère correctement les erreurs courantes liées à l'authentification.

**Scénarios de Test Courants :**

1. **Connexion avec des Identifiants Valides**
   - **Étapes :**
     1. Accéder à la page de connexion.
     2. Entrer les informations suivantes :
        - **Email :** `valid.email@example.com`
        - **Mot de passe :** `Password123!`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Réponse JSON :**
       ```json
       {
         "userID": "12345",
         "email": "valid.email@example.com",
         "username": "JohnDoe",
         "token": "JWT_TOKEN"
       }
       ```
     - **Redirection :** L'utilisateur est redirigé vers son tableau de bord.
     - **Message UI :** "Connexion réussie !"

2. **Connexion avec un Mot de Passe Incorrect**
   - **Étapes :**
     1. Accéder à la page de connexion.
     2. Entrer les informations suivantes :
        - **Email :** `valid.email@example.com`
        - **Mot de passe :** `WrongPassword!`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `401 Unauthorized`
     - **Réponse JSON :**
       ```json
       {
         "error": "InvalidCredentials",
         "message": "Le mot de passe est incorrect."
       }
       ```
     - **Message UI :** "Le mot de passe est incorrect."

3. **Connexion avec un Email Inexistant**
   - **Étapes :**
     1. Accéder à la page de connexion.
     2. Entrer les informations suivantes :
        - **Email :** `nonexistent.email@example.com`
        - **Mot de passe :** `Password123!`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `404 Not Found`
     - **Réponse JSON :**
       ```json
       {
         "error": "UserNotFound",
         "message": "Cet email n'existe pas."
       }
       ```
     - **Message UI :** "Cet email n'existe pas."

4. **Connexion avec un Email Non Confirmé**
   - **Étapes :**
     1. Accéder à la page de connexion.
     2. Entrer les informations suivantes :
        - **Email :** `unconfirmed.email@example.com`
        - **Mot de passe :** `Password123!`
     3. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `403 Forbidden`
     - **Réponse JSON :**
       ```json
       {
         "error": "EmailNotConfirmed",
         "message": "Veuillez confirmer votre adresse email avant de vous connecter."
       }
       ```
     - **Message UI :** "Veuillez confirmer votre adresse email avant de vous connecter."

---

##### 3.1.3 Gestion du Profil

**Objectif :** Valider que les utilisateurs peuvent accéder à leur profil, mettre à jour leurs informations personnelles, et que le système gère correctement les erreurs courantes lors de la modification du profil.

**Scénarios de Test Courants :**

1. **Mise à Jour des Informations du Profil avec des Données Valides**
   - **Étapes :**
     1. Se connecter avec un compte valide.
     2. Accéder à la section "Mon Profil".
     3. Modifier les informations suivantes :
        - **Nom d'utilisateur :** `UpdatedJohnDoe`
        - **Email :** `updated.email@example.com`
     4. Soumettre les modifications.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Réponse JSON :**
       ```json
       {
         "userID": "12345",
         "email": "updated.email@example.com",
         "username": "UpdatedJohnDoe"
       }
       ```
     - **Message UI :** "Profil mis à jour avec succès."

2. **Tentative de Mise à Jour avec un Email Déjà Utilisé**
   - **Étapes :**
     1. Se connecter avec un compte valide.
     2. Accéder à la section "Mon Profil".
     3. Tenter de modifier l'email avec un email déjà enregistré dans le système :
        - **Email :** `duplicate.email@example.com`
     4. Soumettre les modifications.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `409 Conflict`
     - **Réponse JSON :**
       ```json
       {
         "error": "EmailAlreadyInUse",
         "message": "Cet email est déjà utilisé."
       }
       ```
     - **Message UI :** "Cet email est déjà utilisé."

3. **Tentative de Mise à Jour avec un Email au Format Incorrect**
   - **Étapes :**
     1. Se connecter avec un compte valide.
     2. Accéder à la section "Mon Profil".
     3. Tenter de modifier l'email avec un email au format incorrect :
        - **Email :** `invalid-email`
     4. Soumettre les modifications.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "InvalidEmailFormat",
         "message": "L'adresse email est invalide."
       }
       ```
     - **Message UI :** "L'adresse email est invalide."

4. **Tentative de Modification avec un Mot de Passe Non Conforme**
   - **Étapes :**
     1. Se connecter avec un compte valide.
     2. Accéder à la section "Mon Profil".
     3. Tenter de modifier le mot de passe avec une valeur qui ne respecte pas les critères (par exemple, `short` pour un mot de passe de moins de 8 caractères).
     4. Soumettre les modifications.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "WeakPassword",
         "message": "Le mot de passe doit comporter au moins 8 caractères."
       }
       ```
     - **Message UI :** "Le mot de passe doit comporter au moins 8 caractères."

---

### 3.2 Gestion des Événements

La gestion des événements est une fonctionnalité clé de l'application HappiHub. Elle permet aux utilisateurs, notamment les organisateurs, de créer, modifier, supprimer et consulter des événements culturels. Cette section détaille les scénarios de test pour vérifier que ces fonctionnalités fonctionnent correctement.

#### 3.2.1 Création d'un Événement

**Objectif :** Valider que les utilisateurs peuvent créer des événements avec des informations complètes et que le système gère correctement les erreurs courantes.

**Scénarios de Test Courants :**

1. **Création d'un Événement avec des Données Valides**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page de création d'événement.
     3. Remplir le formulaire de création d'événement avec :
        - **Titre :** `Concert de Jazz`
        - **Description :** `Un concert de jazz en plein air avec des artistes locaux.`
        - **Date :** `2024-09-15 19:00`
        - **Lieu :** `Parc Central`
     4. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `201 Created`
     - **Réponse JSON :**
       ```json
       {
         "eventID": "67890",
         "title": "Concert de Jazz",
         "description": "Un concert de jazz en plein air avec des artistes locaux.",
         "date": "2024-09-15T19:00:00Z",
         "location": "Parc Central"
       }
       ```
     - **Message UI :** "Événement créé avec succès."
     - **Affichage :** L'événement apparaît dans la liste des événements disponibles.

2. **Création d'un Événement avec une Date Invalide**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page de création d'événement.
     3. Remplir le formulaire avec une date incorrecte (par exemple, une date passée) :
        - **Date :** `2022-05-01 15:00`
     4. Soumettre le formulaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "InvalidDate",
         "message": "La date de l'événement ne peut pas être dans le passé."
       }
       ```
     - **Message UI :** "La date de l'événement ne peut pas être dans le passé."

3. **Création d'un Événement sans Titre**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page de création d'événement.
     3. Tenter de soumettre le formulaire sans remplir le champ du titre.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "MissingTitle",
         "message": "Le titre de l'événement est requis."
       }
       ```
     - **Message UI :** "Le titre de l'événement est requis."

#### 3.2.2 Modification d'un Événement

**Objectif :** Valider que les organisateurs peuvent modifier les détails d'un événement existant et que le système gère correctement les erreurs courantes.

**Scénarios de Test Courants :**

1. **Modification des Détails d'un Événement**
   - **Étapes :**
     1. Se connecter en tant qu'organisateur.
     2. Accéder à la page de gestion de l'événement `Concert de Jazz`.
     3. Cliquer sur "Modifier".
     4. Modifier les informations suivantes :
        - **Lieu :** `Salle de Concert`
     5. Soumettre les modifications.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Réponse JSON :**
       ```json
       {
         "eventID": "67890",
         "title": "Concert de Jazz",
         "location": "Salle de Concert"
       }
       ```
     - **Message UI :** "Événement mis à jour avec succès."
     - **Affichage :** Les modifications sont immédiatement visibles dans la liste des événements.

2. **Tentative de Modification par un Utilisateur Non-Organisateur**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur normal (non-organisateur).
     2. Tenter d'accéder à la page de modification de l'événement `Concert de Jazz`.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `403 Forbidden`
     - **Réponse JSON :**
       ```json
       {
         "error": "Unauthorized",
         "message": "Vous n'êtes pas autorisé à modifier cet événement."
       }
       ```
     - **Message UI :** "Vous n'êtes pas autorisé à modifier cet événement."

#### 3.2.3 Suppression d'un Événement

**Objectif :** Valider que les organisateurs peuvent supprimer un événement et que le système empêche les utilisateurs non autorisés de le faire.

**Scénarios de Test Courants :**

1. **Suppression d'un Événement par l'Organisateur**
   - **Étapes :**
     1. Se connecter en tant qu'organisateur.
     2. Accéder à la page de gestion de l'événement `Concert de Jazz`.
     3. Cliquer sur "Supprimer".
     4. Confirmer la suppression.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `204 No Content`
     - **Message UI :** "Événement supprimé avec succès."
     - **Vérification :** L'événement n'apparaît plus dans la liste des événements disponibles.

2. **Tentative de Suppression par un Utilisateur Non-Organisateur**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur normal (non-organisateur).
     2. Tenter d'accéder à la page de gestion de l'événement `Concert de Jazz` pour le supprimer.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `403 Forbidden`
     - **Réponse JSON :**
       ```json
       {
         "error": "Unauthorized",
         "message": "Vous n'êtes pas autorisé à supprimer cet événement."
       }
       ```
     - **Message UI :** "Vous n'êtes pas autorisé à supprimer cet événement."

#### 3.2.4 Consultation des Événements Disponibles

**Objectif :** Valider que les utilisateurs peuvent consulter la liste des événements disponibles.

**Scénarios de Test Courants :**

1. **Consultation de la Liste des Événements**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page des événements disponibles.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Affichage :** Tous les événements disponibles, y compris `Concert de Jazz`, sont visibles avec leurs détails respectifs.

2. **Consultation d'un Événement Particulier**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Cliquer sur un événement spécifique (`Concert de Jazz`) dans la liste.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Affichage :** Les détails complets de l'événement `Concert de Jazz` sont affichés.

---

### 4. Gestion des Commentaires

La gestion des commentaires permet aux utilisateurs de discuter et de partager leurs avis sur les événements créés. Cette fonctionnalité est essentielle pour encourager l'interaction et l'engagement au sein de la communauté HappiHub.

#### 4.1 Ajout de Commentaires

**Objectif :** Valider que les utilisateurs peuvent ajouter des commentaires aux événements et que le système gère correctement les erreurs potentielles.

**Scénarios de Test Courants :**

1. **Ajout d'un Commentaire avec des Données Valides**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page d'un événement (par exemple, `Concert de Jazz`).
     3. Remplir le champ de commentaire avec un texte valide :
        - **Commentaire :** `C'était un concert incroyable !`
     4. Soumettre le commentaire.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `201 Created`
     - **Réponse JSON :**
       ```json
       {
         "commentID": "98765",
         "eventID": "67890",
         "userID": "12345",
         "content": "C'était un concert incroyable !"
       }
       ```
     - **Affichage :** Le commentaire apparaît immédiatement sous l'événement.

2. **Ajout d'un Commentaire Vide**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page d'un événement (par exemple, `Concert de Jazz`).
     3. Tenter de soumettre un commentaire vide.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `400 Bad Request`
     - **Réponse JSON :**
       ```json
       {
         "error": "EmptyComment",
         "message": "Le commentaire ne peut pas être vide."
       }
       ```
     - **Message UI :** "Le commentaire ne peut pas être vide."

#### 4.2 Modification de Commentaires

**Objectif :** Valider que les utilisateurs peuvent modifier leurs commentaires existants et que le système gère correctement les erreurs potentielles.

**Scénarios de Test Courants :**

1. **Modification d'un Commentaire**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page d'un événement où un commentaire a été précédemment ajouté.
     3. Cliquer sur "Modifier" à côté du commentaire.
     4. Modifier le texte du commentaire :
        - **Nouveau texte :** `Le concert était vraiment exceptionnel !`
     5. Soumettre les modifications.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Réponse JSON :**
       ```json
       {
         "commentID": "98765",
         "content": "Le concert était vraiment exceptionnel !"
       }
       ```
     - **Affichage :** Le commentaire est mis à jour et le nouveau texte est visible.

2. **Tentative de Modification par un Autre Utilisateur**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur différent de l'auteur du commentaire.
     2. Tenter de modifier un commentaire créé par un autre utilisateur.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `403 Forbidden`
     - **Réponse JSON :**
       ```json
       {
         "error": "Unauthorized",
         "message": "Vous n'êtes pas autorisé à modifier ce commentaire."
       }
       ```
     - **Message UI :** "Vous n'êtes pas autorisé à modifier ce commentaire."

#### 4.3 Suppression de Commentaires

**Objectif :** Valider que les utilisateurs peuvent supprimer leurs commentaires existants et que le système empêche les suppressions non autorisées.

**Scénarios de Test Courants :**

1. **Suppression d'un Commentaire par son Auteur**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page d'un événement où un commentaire a été précédemment ajouté.
     3. Cliquer sur "Supprimer" à côté du commentaire.
     4. Confirmer la suppression.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `204 No Content`
     - **Affichage :** Le commentaire est supprimé de la page de l'événement.

2. **Tentative de Suppression par un Autre Utilisateur**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur différent de l'auteur du commentaire.
     2. Tenter de supprimer un commentaire créé par un autre utilisateur.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `403 Forbidden`
     - **Réponse JSON :**
       ```json
       {
         "error": "Unauthorized",
         "message": "Vous n'êtes pas autorisé à supprimer ce commentaire."
       }
       ```
     - **Message UI :** "Vous n'êtes pas autorisé à supprimer ce commentaire."

---

### Résumé des Scénarios de Test pour la Gestion des Commentaires

Ces scénarios de test couvrent les opérations essentielles pour la gestion des commentaires, y compris l'ajout, la modification, et la suppression de commentaires. En validant ces scénarios, vous garantissez que les fonctionnalités de gestion des commentaires dans HappiHub fonctionnent correctement, en permettant aux utilisateurs d'interagir et de s'engager avec les événements de manière fluide et sécurisée.

---

### 5. Consultation des Événements et des Commentaires

Cette section couvre la fonctionnalité permettant aux utilisateurs de parcourir les événements disponibles et de lire les commentaires associés. C'est une partie cruciale de l'application, car elle permet aux utilisateurs d'accéder aux informations nécessaires pour participer à la vie communautaire.

#### 5.1 Consultation de la Liste des Événements

**Objectif :** Valider que les utilisateurs peuvent consulter la liste des événements disponibles.

**Scénarios de Test Courants :**

1. **Consultation Générale de la Liste des Événements**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page des événements disponibles.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Affichage :** La liste des événements, y compris leurs titres, dates, lieux, et descriptions, est visible.

2. **Filtrage des Événements par Date**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page des événements disponibles.
     3. Utiliser un filtre pour afficher uniquement les événements à venir.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Affichage :** Seuls les événements dont la date est future apparaissent dans la liste.

#### 5.2 Consultation des Commentaires sur un Événement

**Objectif :** Valider que les utilisateurs peuvent lire les commentaires associés à un événement.

**Scénarios de Test Courants :**

1. **Consultation des Commentaires d'un Événement**
   - **Étapes :**
     1. Se connecter en tant qu'utilisateur.
     2. Accéder à la page d'un événement spécifique.
     3. Faire défiler la page pour consulter les commentaires.
   - **Résultat Attendu :**
     - **Code d'état HTTP :** `200 OK`
     - **Affichage :** Tous les commentaires associés à l'événement sont visibles.

---

### Résumé des Scénarios de Test pour la Consultation

Ces scénarios de test valident que les utilisateurs peuvent naviguer efficacement à travers les événements et lire les commentaires associés. En couvrant ces scénarios, vous assurez que la fonctionnalité de consultation dans HappiHub est fluide, réactive, et répond aux besoins des utilisateurs.

---
