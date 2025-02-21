13. Composants Complémentaires

[[prompts_ameliore React + Vite]]

> *Note : Les composants suivants apparaissent dans la suite (91-100) mais sont déjà intégrés dans les catégories précédentes. Ils sont ici rappelés pour complétude.*

### NotificationBadge (Basic)
**Composant NotificationBadge**  
Crée un composant React nommé `NotificationBadge` pour une application Vite. Le composant doit :  
- Afficher un badge indiquant le nombre de notifications non lues, avec une gestion particulière pour des valeurs élevées (ex. "99+").  
- Accepter en props le nombre de notifications et s'intégrer facilement avec d'autres composants (menu, icône, etc.).  
- Ajouter des commentaires pour décrire la logique d'affichage.

---

### RatingStars (Basic)
**Composant RatingStars**  
Crée un composant React nommé `RatingStars` pour une application Vite. Le composant doit :  
- Afficher un nombre défini d'étoiles permettant à l'utilisateur d'évaluer un élément.  
- Gérer l'état de la note sélectionnée avec `useState` et déclencher un callback lors d'un changement de note.  
- Proposer une option en lecture seule via une prop pour désactiver l'interaction.  
- Ajouter des commentaires pour expliquer la logique de sélection.

---

### ProductCard (Basic–Intermediate)
**Composant ProductCard**  
Crée un composant React nommé `ProductCard` pour une application Vite. Le composant doit :  
- Afficher les informations d'un produit (image, titre, description, prix) reçues en props.  
- Inclure un bouton "Ajouter au panier" qui déclenche un callback pour ajouter le produit au panier.  
- Être responsive et s'intégrer dans une grille de produits.  
- Ajouter des commentaires pour expliquer la structure et la gestion des interactions.

---

### APIErrorDisplay (Basic)
**Composant APIErrorDisplay**  
Crée un composant React nommé `APIErrorDisplay` pour une application Vite. Le composant doit :  
- Afficher un message d'erreur stylisé en cas d'échec d'une requête API, en acceptant une prop `errorMessage`.  
- Proposer un bouton ou lien pour permettre à l'utilisateur de relancer l'action ou masquer l'erreur.  
- Gérer l'état d'affichage de l'erreur via `useState` et ajouter des commentaires pour décrire la logique.

---