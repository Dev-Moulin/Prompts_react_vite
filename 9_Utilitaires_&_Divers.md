9. Utilitaires & Divers
[[prompts_ameliore React + Vite]]

### CookieConsentBanner (Basic)
**Composant CookieConsentBanner**  
Crée un composant React nommé `CookieConsentBanner` pour une application Vite. Le composant doit :  
- Afficher une bannière de consentement aux cookies en bas de l'écran.  
- Permettre à l'utilisateur d'accepter ou refuser les cookies et stocker le choix dans le `localStorage`.  
- Se fermer automatiquement après la décision et ne plus s'afficher lors des visites ultérieures.  
- Ajouter des commentaires pour expliquer la gestion du consentement.

---

### SkeletonLoader (Basic)
**Composant SkeletonLoader**  
Crée un composant React nommé `SkeletonLoader` pour une application Vite. Le composant doit :  
- Afficher un placeholder de chargement (skeleton) pendant que les données se chargent.  
- Être générique et personnalisable via des props (largeur, hauteur, formes).  
- Utiliser des styles CSS modulaires ou une librairie d'animation pour simuler le chargement.  
- Ajouter des commentaires pour expliquer la logique et la personnalisation.

---

### useLocalStorage (Basic)
**Hook useLocalStorage**  
Crée un hook personnalisé nommé `useLocalStorage` pour une application Vite. Le hook doit :  
- Accepter une clé et une valeur initiale, et renvoyer un tableau contenant la valeur actuelle et une fonction de mise à jour.  
- Synchroniser automatiquement les mises à jour avec le `localStorage` et gérer les erreurs éventuelles.  
- Ajouter des commentaires pour expliquer la logique de synchronisation.

---

### LazyImage (Intermediate)
**Composant LazyImage**  
Crée un composant React nommé `LazyImage` pour une application Vite. Le composant doit :  
- Charger les images de manière paresseuse (lazy loading) afin d'améliorer les performances.  
- Afficher un placeholder (ex. spinner ou image de substitution) jusqu'au chargement complet de l'image.  
- Remplacer le placeholder par l'image finale dès qu'elle est chargée, en utilisant `useState` et `useEffect`.  
- Ajouter des commentaires pour décrire la logique de lazy loading.

---

### QuickActionMenu (Intermediate)
**Composant QuickActionMenu**  
Crée un composant React nommé `QuickActionMenu` pour une application Vite. Le composant doit :  
- Afficher un menu d'actions rapides accessible via un bouton flottant.  
- Se déployer au clic pour révéler des options (création d'un nouvel élément, accès aux paramètres, etc.) et déclencher des callbacks spécifiques pour chaque action.  
- Gérer l'état d'ouverture et de fermeture via `useState` et assurer l'accessibilité.  
- Ajouter des commentaires pour expliquer la logique de déploiement.

---

### ScrollToTopButton (Basic)
**Composant ScrollToTopButton**  
Crée un composant React nommé `ScrollToTopButton` pour une application Vite. Le composant doit :  
- S'afficher lorsque l'utilisateur défile vers le bas de la page.  
- Inclure une animation de défilement fluide vers le haut lors du clic, en utilisant des méthodes JavaScript pour la transition.  
- Être stylisé de manière discrète et responsive, en gérant son affichage via `useState` et des écouteurs d'événements sur le scroll.  
- Ajouter des commentaires pour décrire la logique de détection du scroll et de l'animation.

---

### SessionTimeout (Intermediate)
**Composant SessionTimeout**  
Crée un composant React nommé `SessionTimeout` pour une application Vite. Le composant doit :  
- Surveiller l'inactivité de l'utilisateur et afficher une alerte ou une modal avant la fin de la session.  
- Permettre à l'utilisateur de prolonger sa session ou de se déconnecter via des callbacks.  
- Utiliser `useEffect` pour lancer la surveillance et `useState` pour gérer l'état de l'alerte.  
- Ajouter des commentaires pour expliquer la logique de détection d'inactivité.

---

### UserPresenceIndicator (Basic)
**Composant UserPresenceIndicator**  
Crée un composant React nommé `UserPresenceIndicator` pour une application Vite. Le composant doit :  
- Recevoir en prop un booléen `isOnline` indiquant si l'utilisateur est en ligne.  
- Afficher une icône ou une couleur différente selon l'état (en ligne/hors ligne) et s'assurer que le rendu soit accessible et responsive.  
- Ajouter des commentaires pour expliquer la logique de rendu conditionnel.

---

### NotificationSettings (Intermediate)
**Composant NotificationSettings**  
Crée un composant React nommé `NotificationSettings` pour une application Vite. Le composant doit :  
- Afficher des options de configuration pour les notifications (e-mail, push, SMS) sous forme de cases à cocher ou de boutons.  
- Stocker et mettre à jour les préférences dans l'état local ou via un contexte, avec une simulation d'enregistrement via une API fictive.  
- Ajouter des commentaires pour décrire la logique de gestion des préférences.

---

### UserConsentManager (Intermediate)
**Composant UserConsentManager**  
Crée un composant React nommé `UserConsentManager` pour une application Vite. Le composant doit :  
- Afficher des options permettant à l'utilisateur d'accepter ou refuser différentes catégories de consentement (cookies, collecte de données, etc.).  
- Stocker ces préférences dans le `localStorage` et gérer leur mise à jour via `useState` ou un contexte global.  
- Proposer une interface conviviale et responsive, avec la possibilité de modifier ultérieurement les préférences.  
- Ajouter des commentaires pour décrire la logique de gestion des consentements.

---

### MultiLanguageSwitcher (Intermediate)
**Composant MultiLanguageSwitcher**  
Crée un composant React nommé `MultiLanguageSwitcher` pour une application Vite. Le composant doit :  
- Permettre à l'utilisateur de changer la langue de l'application via une liste déroulante ou des boutons.  
- Déclencher une mise à jour globale de la langue (ex. via un contexte ou une librairie i18n) en fonction du choix de l'utilisateur.  
- Gérer l'état de la langue sélectionnée avec `useState` et assurer un rendu responsive.  
- Ajouter des commentaires pour expliquer la logique de changement de langue.

---

### SEO (Intermediate)
**Composant SEO**  
Crée un composant React nommé `SEO` pour une application Vite. Le composant doit :  
- Gérer dynamiquement les meta tags (titre, description, keywords, etc.) d'une page en acceptant ces informations via des props.  
- Mettre à jour le `<head>` du document à l'aide d'une librairie comme `react-helmet`.  
- Ajouter des commentaires pour expliquer la logique de mise à jour des meta tags.

---

### PrivacyPolicy (Basic)
**Composant PrivacyPolicy**  
Crée un composant React nommé `PrivacyPolicy` pour une application Vite. Le composant doit :  
- Afficher la politique de confidentialité de l'application en récupérant le contenu depuis un fichier markdown ou via une API fictive.  
- Permettre une navigation fluide dans le contenu (table des matières ou ancres).  
- Être stylisé pour assurer une lecture confortable sur tous les écrans.  
- Ajouter des commentaires pour expliquer la logique de chargement et de navigation.

---

### TermsOfService (Basic)
**Composant TermsOfService**  
Crée un composant React nommé `TermsOfService` pour une application Vite. Le composant doit :  
- Afficher les conditions d'utilisation de l'application avec une mise en forme claire et lisible.  
- *(Optionnel)* Intégrer une fonctionnalité de recherche ou filtrage dans le texte.  
- Gérer l'affichage avec `useState` si nécessaire et être responsive.  
- Ajouter des commentaires pour décrire la logique d'affichage.

---