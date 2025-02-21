4. Composants UI & Interaction
[[prompts_ameliore React + Vite]]
### Modal (Intermediate)
**Composant Modal**  
Crée un composant React générique nommé `Modal` qui affiche du contenu en overlay. Le composant doit :  
- Gérer son état d'affichage (visible/invisible) via des props ou `useState`.  
- Permettre la fermeture via un bouton ou un clic en dehors de la zone modale.  
- Inclure des animations de transition pour l'apparition/disparition.  
- Ajouter des commentaires pour expliquer le fonctionnement et la personnalisation.

---

### Tabs (Intermediate)
**Composant Tabs**  
Crée un composant React nommé `Tabs` qui permet de naviguer entre différentes sections via des onglets. Le composant doit :  
- Recevoir en props un tableau d'objets (titre et contenu pour chaque onglet).  
- Gérer l'état de l'onglet actif avec `useState` et afficher le contenu correspondant.  
- Ajouter des commentaires pour décrire la logique de changement d'onglet.

---

### Accordion (Basic–Intermediate)
**Composant Accordion**  
Crée un composant React nommé `Accordion` qui affiche des sections repliables. Le composant doit :  
- Afficher plusieurs sections avec un titre cliquable permettant d'afficher ou masquer le contenu.  
- Gérer l'état ouvert/fermé de chaque section avec `useState`.  
- *(Optionnel)* Autoriser l'ouverture simultanée ou unique des sections.  
- Ajouter des commentaires pour expliquer la gestion des états.

---

### Tooltip (Basic)
**Composant Tooltip**  
Crée un composant React nommé `Tooltip` qui affiche une infobulle contextuelle lorsque l'utilisateur survole un élément. Le composant doit :  
- Afficher une infobulle contenant un message passé en props lors du survol.  
- Gérer l'affichage conditionnel via `useState` et les événements onMouseEnter/onMouseLeave.  
- Assurer un positionnement correct par rapport à l'élément parent.  
- Ajouter des commentaires pour expliquer la logique d'affichage.

---

### LoaderButton (Intermediate)
**Composant LoaderButton**  
Crée un composant React nommé `LoaderButton` qui combine un bouton et un indicateur de chargement. Le composant doit :  
- Accepter en props un texte, un booléen indiquant l'état de chargement, et une callback pour l'action du bouton.  
- Désactiver les interactions et afficher un loader (animation ou icône) pendant l'action.  
- Ajouter des commentaires pour décrire la logique de désactivation et d'affichage conditionnel.

---

### ExpandableCard (Intermediate)
**Composant ExpandableCard**  
Crée un composant React nommé `ExpandableCard` qui affiche une carte d'information avec du contenu partiellement masqué. Le composant doit :  
- Inclure un bouton ou lien "Voir plus" pour étendre la carte et révéler le contenu complet.  
- Gérer l'état d'extension via `useState` et prévoir une animation fluide lors des transitions.  
- Ajouter des commentaires pour expliquer la logique d'expansion.

---

### ToastNotifications (Intermediate)
**Composant ToastNotifications**  
Crée un composant React nommé `ToastNotifications` qui affiche des notifications temporaires (toasts). Le composant doit :  
- Permettre l'ajout de notifications via une fonction callback et leur suppression automatique après un délai, avec possibilité de suppression manuelle.  
- Gérer l'état des notifications avec `useState` et utiliser un timer pour le délai d'affichage.  
- Ajouter des commentaires pour décrire la logique d'ajout et de suppression.

---

### Loader (Basic)
**Composant Loader**  
Crée un composant React nommé `Loader` qui affiche une animation de chargement pendant le traitement des données. Le composant doit :  
- Afficher un spinner ou une animation pendant le chargement.  
- Être générique et réutilisable dans toute l'application, avec personnalisation via des props.  
- Utiliser des styles CSS modulaires ou une bibliothèque pour l'animation.  
- Ajouter des commentaires pour expliquer l'intégration et la personnalisation.

---

### ModalConfirm (Intermediate)
**Composant ModalConfirm**  
Crée un composant React nommé `ModalConfirm` qui affiche une fenêtre modale de confirmation avant d'exécuter une action sensible. Le composant doit :  
- Accepter en props un message de confirmation, des libellés personnalisables pour "Confirmer" et "Annuler", et des callbacks associés.  
- Gérer l'affichage via `useState` et prévoir une animation d'apparition/disparition.  
- Ajouter des commentaires pour expliquer la logique de confirmation.

---