11. Composants Spécifiques Réseaux & Vidéo

[[prompts_ameliore React + Vite]]

### VideoCall (Advanced)
**Composant VideoCall**  
Crée un composant React nommé `VideoCall` pour une application Vite. Le composant doit :  
- Simuler une interface d'appel vidéo en affichant des flux vidéo fictifs ou des placeholders pour la caméra et le micro.  
- Offrir des contrôles pour activer/désactiver la caméra et le micro, et inclure un bouton pour terminer l'appel.  
- Gérer l'état des flux et des contrôles via `useState` et utiliser `useEffect` pour l'initialisation et le nettoyage.  
- Ajouter des commentaires pour décrire la logique de gestion des flux vidéo.

---

### CalendarEvent (Intermediate)
**Composant CalendarEvent**  
Crée un composant React nommé `CalendarEvent` pour une application Vite. Le composant doit :  
- Afficher un événement de calendrier avec la date, l'heure, le titre et une description.  
- Proposer des boutons ou liens permettant d’éditer ou de supprimer l’événement via des callbacks.  
- Utiliser `useState` pour gérer l’état d’édition ou d’affichage et prévoir une interface claire pour la modification.  
- Ajouter des commentaires pour expliquer la logique de mise à jour.

---

### ServerStatusIndicator (Intermediate)
**Composant ServerStatusIndicator**  
Crée un composant React nommé `ServerStatusIndicator` pour une application Vite. Le composant doit :  
- Afficher en temps réel l'état du serveur (en ligne/hors ligne) en interrogeant une API ou une URL spécifique à intervalle régulier.  
- Mettre à jour l'affichage via `useState` et `useEffect` selon l'état retourné, avec une icône ou une couleur indicatrice.  
- Gérer les erreurs de connexion et afficher un message d'alerte le cas échéant.  
- Ajouter des commentaires pour expliquer la logique de sondage.

---