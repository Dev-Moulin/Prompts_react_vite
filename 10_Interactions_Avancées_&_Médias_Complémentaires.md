10. Interactions Avancées & Médias Complémentaires
[[prompts_ameliore React + Vite]]

### SearchBar (Basic)
**Composant SearchBar**  
Crée un composant React nommé `SearchBar` pour une application Vite. Le composant doit :  
- Afficher un champ de saisie pour la recherche et un bouton pour déclencher la recherche.  
- Gérer l'état du champ de saisie avec `useState` et déclencher une action via un callback lors de la soumission.  
- *(Optionnel)* Intégrer des suggestions automatiques en temps réel.  
- Ajouter des commentaires pour expliquer la logique de gestion de l'état.

---

### Autocomplete (Advanced)
**Composant Autocomplete**  
Crée un composant React nommé `Autocomplete` pour une application Vite. Le composant doit :  
- Fournir une saisie semi-automatique qui suggère des options en fonction de la saisie de l'utilisateur.  
- Afficher une liste de suggestions filtrées en temps réel avec `useState` pour gérer le champ et les suggestions.  
- Permettre la sélection d'une suggestion qui met à jour le champ et renvoie la valeur via un callback.  
- *(Optionnel)* Charger dynamiquement les suggestions depuis une API fictive via `useEffect`.  
- Ajouter des commentaires pour décrire la logique de filtrage.

---

### DragAndDropList (Intermediate)
**Composant DragAndDropList**  
Crée un composant React nommé `DragAndDropList` pour une application Vite. Le composant doit :  
- Afficher une liste d'éléments réordonnables par glisser-déposer.  
- Gérer l'état des éléments via `useState` et mettre à jour l'ordre lors du déplacement.  
- Utiliser une librairie (ex. `react-dnd`) ou une solution custom pour gérer le drag and drop.  
- Fournir la possibilité de sauvegarder l'ordre via un callback ou une simulation d'appel API.  
- Ajouter des commentaires pour expliquer la logique de manipulation.

---

### InfiniteScrollList (Advanced)
**Composant InfiniteScrollList**  
Crée un composant React nommé `InfiniteScrollList` pour une application Vite. Le composant doit :  
- Afficher une liste d'éléments avec un défilement infini.  
- Détecter automatiquement lorsque l'utilisateur atteint le bas de la liste et charger de nouveaux éléments via un callback ou une API fictive.  
- Gérer l'état du chargement et de la liste avec `useState` et `useEffect`.  
- Afficher un indicateur de chargement et gérer les erreurs potentielles.  
- Ajouter des commentaires pour expliquer la logique de détection et de mise à jour.

---

### CountdownTimer (Intermediate)
**Composant CountdownTimer**  
Crée un composant React nommé `CountdownTimer` pour une application Vite. Le composant doit :  
- Afficher un compte à rebours dynamique vers une date ou un événement donné.  
- Mettre à jour le temps restant en temps réel avec `useState` et `useEffect` (ex. via `setInterval`).  
- Offrir des callbacks ou un affichage personnalisé lorsque le compte à rebours est terminé.  
- Gérer le démarrage et l'arrêt du timer, et prévoir la gestion des erreurs.  
- Ajouter des commentaires pour expliquer la logique de mise à jour.

---

### Calendar (Intermediate)
**Composant Calendar**  
Crée un composant React nommé `Calendar` pour une application Vite. Le composant doit :  
- Afficher un calendrier interactif pour naviguer entre les mois et sélectionner une date.  
- Gérer l'affichage des jours en fonction du mois et de l'année via `useState`.  
- Retourner la date sélectionnée via un callback en props.  
- Assurer une navigation fluide et être responsive.  
- Ajouter des commentaires pour décrire la logique d'affichage.

---

### RichTextEditor (Advanced)
**Composant RichTextEditor**  
Crée un composant React nommé `RichTextEditor` pour une application Vite. Le composant doit :  
- Permettre à l'utilisateur d'éditer du texte avec des options de mise en forme (gras, italique, souligné, etc.).  
- Gérer l'état éditable via `useState` et offrir une interface intuitive avec des boutons pour la mise en forme.  
- Renvoyer le contenu formaté via un callback en props.  
- Gérer les erreurs et l'initialisation du contenu.  
- Ajouter des commentaires pour expliquer la logique de l'éditeur.

---

### DatePicker (Intermediate)
**Composant DatePicker**  
Crée un composant React nommé `DatePicker` pour une application Vite. Le composant doit :  
- Afficher un calendrier interactif pour la sélection d'une date.  
- Retourner la date choisie via un callback passé en props.  
- Gérer l'état de la date sélectionnée avec `useState`.  
- Être accessible (attributs ARIA) et responsive.  
- Ajouter des commentaires pour expliquer la logique et les validations.

---

### ThemeSwitcher (Basic)
**Composant ThemeSwitcher**  
Crée un composant React nommé `ThemeSwitcher` pour une application Vite. Le composant doit :  
- Permettre à l'utilisateur de basculer entre un mode clair et sombre.  
- Stocker le choix du thème dans l'état local via `useState` et synchroniser avec le `localStorage`.  
- Appliquer dynamiquement une classe CSS (ex. `dark-mode` ou `light-mode`) à l'application.  
- Ajouter des commentaires pour expliquer la gestion de la préférence utilisateur.

---

### SearchResults (Basic)
**Composant SearchResults**  
Crée un composant React nommé `SearchResults` pour une application Vite. Le composant doit :  
- Recevoir en props un tableau d'objets représentant les résultats de recherche et les afficher dans une liste.  
- Afficher un message informatif en cas d'absence de résultats.  
- Permettre à l'utilisateur de cliquer sur un résultat pour accéder aux détails via un callback ou redirection.  
- Ajouter des commentaires pour expliquer la logique de rendu.

---

### UserList (Intermediate)
**Composant UserList**  
Crée un composant React nommé `UserList` pour une application Vite. Le composant doit :  
- Récupérer une liste d'utilisateurs via une API fictive en utilisant `useEffect` et gérer l'état avec `useState`.  
- Afficher pour chaque utilisateur une photo miniature, leur nom et leur statut.  
- Intégrer une pagination ou un défilement infini pour gérer un grand nombre d'utilisateurs.  
- Ajouter des commentaires pour détailler la logique de récupération et de pagination.

---