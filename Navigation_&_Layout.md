
2. Navigation & Layout 
[[prompts_ameliore React + Vite]]
### Header (Basic–Intermediate)
**Composant Header**  
Crée un composant React nommé `Header` pour une application Vite. Le composant doit :  
- Afficher la navigation principale incluant le logo de l'application et un menu de navigation.  
- Intégrer des liens vers le profil utilisateur et une option de déconnexion, en utilisant React Router pour les redirections.  
- Gérer l'état (par exemple, l'ouverture/fermeture du menu sur mobile) avec `useState`.  
- Ajouter des commentaires pour expliquer la structure et la gestion des interactions.

---

### Footer (Basic)
**Composant Footer**  
Crée un composant React nommé `Footer` pour une application Vite. Le composant doit :  
- Afficher des liens vers des pages informatives (À propos, Contact, Mentions légales, etc.).  
- Être intégré en bas de chaque page et être responsive.  
- Utiliser des styles CSS pour assurer une mise en forme cohérente.  
- Ajouter des commentaires pour expliquer la structure et la logique de navigation.

---

### Sidebar (Intermediate)
**Composant Sidebar**  
Crée un composant React nommé `Sidebar` qui affiche un menu latéral de navigation. Le composant doit :  
- Permettre la navigation entre différentes sections de l'application.  
- Intégrer des icônes pour améliorer l'expérience utilisateur.  
- Être responsive et proposer un comportement adapté sur mobile et desktop (menu rétractable ou déroulant).  
- Utiliser `useState` pour gérer l'ouverture/fermeture et ajouter des commentaires explicatifs.

---

### Breadcrumbs (Basic)
**Composant Breadcrumbs**  
Crée un composant React nommé `Breadcrumbs` pour une application Vite. Le composant doit :  
- Afficher un fil d'Ariane permettant la navigation hiérarchique.  
- Recevoir en props un tableau d'objets contenant un titre et un lien pour chaque étape.  
- Afficher chaque étape avec un séparateur (ex. " > ") et rendre cliquables les étapes précédentes.  
- Ajouter des commentaires pour expliquer la structure et la logique de navigation.

---

### BreadcrumbItem (Basic)
**Composant BreadcrumbItem**  
Crée un composant React nommé `BreadcrumbItem` pour une application Vite. Le composant doit :  
- Représenter un élément individuel d'un fil d'Ariane en recevant un titre et un lien via des props.  
- Être conçu pour s'intégrer dans un composant parent `Breadcrumbs`.  
- Ajouter des commentaires pour expliquer la logique d'intégration et le rendu.

---

### Pagination (Basic)
**Composant Pagination**  
Crée un composant React nommé `Pagination` pour une application Vite. Le composant doit :  
- Afficher des boutons pour naviguer entre plusieurs pages (précédent, suivant, numéros cliquables).  
- Gérer l'état de la page courante avec `useState` et déclencher un callback lors du changement de page.  
- Permettre la personnalisation des styles et de la logique via des props.  
- Ajouter des commentaires pour décrire la gestion de l'état et les interactions.

---

### ResponsiveGrid (Intermediate)
**Composant ResponsiveGrid**  
Crée un composant React nommé `ResponsiveGrid` pour une application Vite. Le composant doit :  
- Organiser dynamiquement le contenu passé en props dans une grille responsive.  
- Accepter des options de configuration (nombre de colonnes, espacements, alignements) via des props.  
- Ajuster automatiquement la mise en page en fonction de la taille de l'écran, via CSS Flex ou Grid.  
- Ajouter des commentaires pour expliquer la logique de mise en page.

---