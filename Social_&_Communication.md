7. Social & Communication

[[prompts_ameliore React + Vite]]

### SocialShare (Basic)
**Composant SocialShare**  
Crée un composant React nommé `SocialShare` pour une application Vite. Le composant doit :  
- Afficher des boutons de partage pour des réseaux sociaux (Facebook, Twitter, LinkedIn, etc.).  
- Accepter en props l’URL à partager, un titre, et des options de style personnalisables.  
- Utiliser des icônes (ex. FontAwesome) et inclure des attributs d’accessibilité pour chaque bouton.  
- Assurer un design responsive et personnalisable via CSS ou styled-components.  
- Ajouter des commentaires pour expliquer la logique de rendu.

---

### SocialFeed (Intermediate)
**Composant SocialFeed**  
Crée un composant React nommé `SocialFeed` pour une application Vite. Le composant doit :  
- Récupérer des posts fictifs via une API simulée en utilisant `useEffect` et gérer l'état avec `useState`.  
- Afficher chaque post avec son contenu, le nom de l'auteur et la date de publication.  
- Permettre à l'utilisateur d'aimer ou de partager chaque post via des boutons déclenchant des callbacks.  
- Gérer l'affichage d'un indicateur de chargement et des erreurs lors de la récupération.  
- Ajouter des commentaires pour décrire la logique de récupération et d'affichage.

---

### ChatRoom (Intermediate–Advanced)
**Composant ChatRoom**  
Crée un composant React nommé `ChatRoom` pour une application Vite. Le composant doit :  
- Afficher une liste de messages en temps réel.  
- Inclure un formulaire pour envoyer de nouveaux messages.  
- Utiliser `useState` pour gérer la liste des messages et le contenu du formulaire.  
- Employer `useEffect` pour simuler la réception de messages via une API fictive ou un WebSocket (ex. avec un timer).  
- Gérer les erreurs éventuelles et ajouter des commentaires pour expliquer la logique de messagerie.

---

### ChatMessage (Basic)
**Composant ChatMessage**  
Crée un composant React nommé `ChatMessage` pour une application Vite. Le composant doit :  
- Représenter un message individuel dans une conversation en affichant le contenu, le nom de l'expéditeur et l'heure d'envoi.  
- Différencier visuellement les messages envoyés par l'utilisateur connecté de ceux reçus.  
- Utiliser des props pour recevoir les informations nécessaires et ajouter des commentaires explicatifs.

---

### LoginWithSocial (Intermediate)
**Composant LoginWithSocial**  
Crée un composant React nommé `LoginWithSocial` pour une application Vite. Le composant doit :  
- Afficher des boutons de connexion pour divers réseaux sociaux (Facebook, Google, etc.) avec leurs icônes.  
- Déclencher une action simulant l'authentification sociale via un callback lors du clic sur un bouton.  
- Assurer un design responsive et inclure des attributs d’accessibilité.  
- Ajouter des commentaires pour décrire la logique d'authentification.

---

### SocialMediaEmbed (Intermediate)
**Composant SocialMediaEmbed**  
Crée un composant React nommé `SocialMediaEmbed` pour une application Vite. Le composant doit :  
- Permettre d'intégrer du contenu provenant de réseaux sociaux (ex. Twitter, Instagram) en acceptant une URL ou un identifiant de publication en props.  
- Afficher le contenu intégré via une iframe ou un script d'intégration, en s'assurant que le rendu soit responsive.  
- Gérer l'affichage et les éventuels messages d'erreur en cas de problème d'intégration.  
- Ajouter des commentaires pour décrire la logique d'intégration.

---