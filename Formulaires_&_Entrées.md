3. Formulaires & Entrées
[[prompts_ameliore React + Vite]]
### UserProfile (Intermediate)
**Composant UserProfile**  
Crée un composant React nommé `UserProfile` qui affiche les informations du profil utilisateur et permet leur modification. Le composant doit :  
- Afficher les informations actuelles (ex. nom, email) dans un formulaire modifiable.  
- Utiliser `useState` pour gérer l'état des champs du formulaire et `useEffect` pour charger les données via une API.  
- Implémenter une validation des champs et gérer les erreurs lors de la mise à jour.  
- Envoyer les modifications à une API fictive et afficher un message de succès ou d'erreur.  
- Ajouter des commentaires pour clarifier la gestion des données.

---

### ContactForm (Intermediate)
**Composant ContactForm**  
Crée un composant React nommé `ContactForm` qui présente un formulaire de contact. Le composant doit :  
- Inclure des champs pour le nom, l'email, le sujet et le message.  
- Utiliser `useState` pour gérer l'état des champs et implémenter une validation (ex. format d'email, champs requis).  
- Simuler l'envoi des données à une API fictive, avec affichage d'un message de succès ou d'erreur.  
- Ajouter des commentaires pour détailler la logique de validation et d'envoi.

---

### NewsletterSignup (Basic–Intermediate)
**Composant NewsletterSignup**  
Crée un composant React nommé `NewsletterSignup` qui permet aux utilisateurs de s'inscrire à une newsletter. Le composant doit :  
- Afficher un champ de saisie pour l'email, avec validation du format.  
- Simuler l'envoi des données à une API fictive et afficher un message de succès ou d'erreur.  
- Ajouter des commentaires pour expliquer la validation et la gestion de l'envoi.

---

### FeedbackForm (Intermediate)
**Composant FeedbackForm**  
Crée un composant React nommé `FeedbackForm` qui permet aux utilisateurs de soumettre leurs retours ou commentaires. Le composant doit :  
- Inclure un formulaire avec des champs pour le nom, l'email et le message.  
- Valider les entrées (format d'email, non vide) et simuler l'envoi des données à une API fictive.  
- Afficher un message de succès ou d'erreur en fonction de la réponse.  
- Ajouter des commentaires pour expliquer la logique de validation et d'envoi.

---

### FormField (Basic)
**Composant FormField**  
Crée un composant React nommé `FormField` qui sert de composant générique pour divers champs de formulaires (input, textarea, select). Le composant doit :  
- Gérer l'état local, la validation et l'affichage d'éventuels messages d'erreur.  
- Permettre la personnalisation via des props (placeholder, label, type, etc.).  
- Ajouter des commentaires pour décrire la logique de validation et la gestion des attributs.

---

### MultiStepForm (Advanced)
**Composant MultiStepForm**  
Crée un composant React nommé `MultiStepForm` qui guide l'utilisateur à travers plusieurs étapes de saisie d'un formulaire. Le composant doit :  
- Valider les données à chaque étape et permettre la navigation (suivante/précédente).  
- Gérer l'état global du formulaire et l'étape active via `useState` et éventuellement `useEffect`.  
- Afficher des messages d'erreur clairs et ajouter des commentaires pour expliquer la logique de navigation.

---

### CommentSection (Intermediate)
**Composant CommentSection**  
Crée un composant React nommé `CommentSection` qui permet aux utilisateurs de lire et d'ajouter des commentaires. Le composant doit :  
- Afficher une liste de commentaires existants récupérés via une API fictive avec `useEffect` et `useState`.  
- Proposer un formulaire contrôlé pour l'ajout de nouveaux commentaires, avec validation.  
- Actualiser dynamiquement la liste après soumission.  
- Ajouter des commentaires pour décrire la gestion et la validation des commentaires.
