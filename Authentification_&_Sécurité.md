 [[prompts_ameliore React + Vite]]
## 1. Authentification & Sécurité
### RegistrationPage (Intermediate)
**Composant RegistrationPage**  
Crée un composant React nommé `RegistrationPage` pour une application générée avec Vite. Le composant doit inclure :  
- Un formulaire d'inscription avec les champs : nom, email, mot de passe et confirmation de mot de passe.  
- L'utilisation du hook `useState` pour gérer l'état du formulaire.  
- Une validation simple pour s'assurer que tous les champs sont remplis, que le format de l'email est valide et que le mot de passe correspond à sa confirmation.  
- Une gestion des erreurs avec affichage de messages clairs en cas de problème de validation.  
- Des commentaires explicatifs dans le code pour chaque section importante.  
- *(Optionnel)* Un test unitaire (par exemple, avec Jest) pour vérifier le comportement du formulaire.

---

### LoginPage (Intermediate)
**Composant LoginPage**  
Crée un composant React nommé `LoginPage` pour une application Vite. Le composant doit :  
- Afficher un formulaire de connexion avec les champs : email et mot de passe.  
- Utiliser `useState` pour gérer l'état des champs du formulaire.  
- Simuler un appel à une API d'authentification (éventuellement via `useEffect`) et gérer la réponse.  
- Afficher des messages d'erreur clairs en cas d'échec de la connexion.  
- Inclure des commentaires pour expliquer la gestion de l'état et la logique d'authentification.

---

### Logout (Basic)
**Composant Logout**  
Crée un composant React nommé `Logout` qui permet de déconnecter l'utilisateur. Le composant doit :  
- Appeler une fonction de déconnexion qui efface le token JWT stocké dans le `localStorage` et réinitialise l'état d'authentification.  
- Utiliser React Router pour rediriger l'utilisateur vers la page de connexion après la déconnexion.  
- Ajouter des commentaires pour expliquer le processus de déconnexion et la redirection.

---

### Dashboard (Intermediate)
**Composant Dashboard**  
Crée un composant React nommé `Dashboard` qui servira de page d'accueil pour les utilisateurs authentifiés. Le composant doit :  
- Afficher un message de bienvenue personnalisé et proposer une navigation vers d'autres modules (ex. : profil ou notifications).  
- Vérifier l'authentification (par exemple, en vérifiant la présence d'un token JWT) et rediriger vers la page de connexion si l'utilisateur n'est pas authentifié.  
- Utiliser `useState` et `useEffect` pour gérer l'état et les effets liés au montage du composant.  
- Inclure des commentaires explicatifs pour faciliter la compréhension du code.

---

### Module de Gestion du Token JWT (Basic–Intermediate)
**Module Gestion du Token JWT**  
Crée un module utilitaire en JavaScript ou TypeScript pour gérer le token JWT dans une application React créée avec Vite. Ce module doit inclure :  
- Une fonction pour stocker le token dans le `localStorage`.  
- Une fonction pour récupérer le token.  
- Une fonction pour vérifier l'expiration du token (en comparant la date d'expiration avec la date actuelle).  
- Une fonction pour supprimer le token du `localStorage`.  
- Des commentaires détaillés pour expliquer la logique et l'utilisation de chaque fonction.

---

### PasswordReset (Intermediate)
**Composant PasswordReset**  
Crée un composant React nommé `PasswordReset` permettant à un utilisateur de réinitialiser son mot de passe. Le composant doit :  
- Afficher un formulaire demandant l'email de l'utilisateur pour initier la réinitialisation.  
- Utiliser `useState` pour gérer l'état du formulaire et `useEffect` pour gérer les effets secondaires liés à l'appel API.  
- Envoyer une requête à une API fictive pour déclencher le processus de réinitialisation.  
- Gérer et afficher les erreurs ainsi que les confirmations selon la réponse de l'API.  
- Ajouter des commentaires explicatifs pour décrire le processus complet.

---

### EmailVerification (Intermediate)
**Composant EmailVerification**  
Crée un composant React nommé `EmailVerification` qui gère la vérification de l'email de l'utilisateur. Le composant doit :  
- Extraire un token de vérification depuis l'URL (via React Router).  
- Utiliser `useEffect` pour appeler une API fictive qui vérifiera la validité du token dès le montage du composant.  
- Afficher un message de confirmation ou d'erreur en fonction du résultat de la vérification.  
- Ajouter des commentaires pour expliquer la logique d'extraction du token et de vérification.

---

### ProtectedRoute (Intermediate)
**Composant ProtectedRoute**  
Crée un Higher-Order Component (HOC) ou un wrapper nommé `ProtectedRoute` pour protéger certaines routes de ton application React. Le composant doit :  
- Vérifier si l'utilisateur est authentifié (par exemple, en vérifiant la présence d'un token JWT dans le `localStorage`).  
- Rendre le composant enfant (`children`) si l'utilisateur est authentifié, sinon rediriger vers la page de connexion avec React Router.  
- *(Optionnel)* Permettre la personnalisation du message affiché en cas d'accès non autorisé.  
- Ajouter des commentaires pour expliquer la logique de protection et la redirection.

---

### RoleBasedAccessControl (Advanced)
**Composant RoleBasedAccessControl**  
Crée un composant React nommé `RoleBasedAccessControl` qui gère l'affichage conditionnel de ses enfants en fonction du rôle de l'utilisateur. Le composant doit :  
- Accepter en props un tableau `allowedRoles` et une valeur `userRole` pour déterminer si l'utilisateur peut accéder au contenu.  
- N'afficher le contenu que si le rôle de l'utilisateur figure dans `allowedRoles`, sinon afficher un message ou rediriger.  
- Ajouter des commentaires pour expliquer la logique de contrôle d'accès.

---