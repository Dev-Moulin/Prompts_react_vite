5. Médias & Fichiers

[[prompts_ameliore React + Vite]]

### VideoPlayer (Intermediate)
**Composant VideoPlayer**  
Crée un composant React nommé `VideoPlayer` pour une application Vite. Le composant doit :  
- Utiliser la balise HTML `<video>` ou une librairie tierce pour lire des vidéos.  
- Offrir des contrôles de lecture (play, pause, volume, plein écran) et une barre de progression.  
- Gérer l'état de lecture avec `useState` et mettre à jour l'affichage avec `useEffect`.  
- Prévoir des messages ou fallback en cas d'erreur de lecture.  
- Ajouter des commentaires pour expliquer la gestion des événements.

---

### AudioPlayer (Intermediate)
**Composant AudioPlayer**  
Crée un composant React nommé `AudioPlayer` pour une application Vite. Le composant doit :  
- Permettre la lecture de fichiers audio avec des contrôles (play, pause, avance rapide, retour).  
- Afficher une barre de progression pour indiquer le temps écoulé et restant.  
- Utiliser `useState` pour gérer l'état de la lecture et `useEffect` pour synchroniser la barre de progression.  
- Gérer et afficher les erreurs éventuelles.  
- Ajouter des commentaires pour décrire la logique de lecture.

---

### ImageGallery (Intermediate)
**Composant ImageGallery**  
Crée un composant React nommé `ImageGallery` pour une application Vite. Le composant doit :  
- Afficher une galerie d'images en grille à partir d'un tableau d'URLs passé en props.  
- Permettre le clic sur une image pour l'agrandir dans une modale ou lightbox.  
- Être responsive et s'adapter aux différentes tailles d'écran grâce à des grilles CSS.  
- Ajouter des commentaires pour expliquer la logique de rendu et la gestion de la modale.

---

### FileUploader (Intermediate)
**Composant FileUploader**  
Crée un composant React nommé `FileUploader` pour une application Vite. Le composant doit :  
- Inclure un champ de saisie de type `file` pour la sélection de fichiers.  
- Afficher une barre de progression indiquant l'avancement du téléchargement.  
- Gérer l'état du téléchargement avec `useState` et simuler l'upload via une API fictive ou un délai artificiel.  
- Gérer et afficher les erreurs éventuelles pendant le processus.  
- Ajouter des commentaires pour décrire le fonctionnement.

---

### FilePreview (Intermediate)
**Composant FilePreview**  
Crée un composant React nommé `FilePreview` pour une application Vite. Le composant doit :  
- Permettre la prévisualisation de fichiers avant téléchargement.  
- Afficher un aperçu pour des images, documents ou autres types, en se basant sur le type MIME ou l'extension.  
- Gérer l'état de chargement et prévoir un mécanisme de fallback (ex. icône ou message) si la prévisualisation n'est pas disponible.  
- Ajouter des commentaires pour expliquer la logique de prévisualisation.

---

### DragAndDropUploader (Advanced)
**Composant DragAndDropUploader**  
Crée un composant React nommé `DragAndDropUploader` pour une application Vite. Le composant doit :  
- Permettre aux utilisateurs de téléverser des fichiers via une interface de glisser-déposer.  
- Gérer les événements de drag and drop (onDragEnter, onDragOver, onDrop) et afficher une zone de dépôt visuelle qui change lors du survol.  
- Afficher une prévisualisation des fichiers sélectionnés et simuler le téléchargement avec une barre de progression pour chaque fichier.  
- Gérer l'état du téléchargement et les erreurs via `useState` et `useEffect`.  
- Ajouter des commentaires pour expliquer la logique des événements et du téléchargement.

---

### FileDownload (Intermediate)
**Composant FileDownload**  
Crée un composant React nommé `FileDownload` pour une application Vite. Le composant doit :  
- Afficher les informations d'un fichier (nom, taille) passées en props.  
- Inclure un bouton déclenchant le téléchargement du fichier, simulant le processus avec un indicateur de chargement et une barre de progression.  
- Gérer les états de téléchargement et d'erreur via `useState` et éventuellement `useEffect`.  
- Ajouter des commentaires pour expliquer la logique du téléchargement.

---

### ImageCropper (Advanced)
**Composant ImageCropper**  
Crée un composant React nommé `ImageCropper` pour une application Vite. Le composant doit :  
- Permettre aux utilisateurs de rogner et redimensionner une image affichée.  
- Offrir une interface interactive pour sélectionner et ajuster la zone de rognage, en utilisant `useState` pour gérer la sélection.  
- Retourner la zone sélectionnée via un callback passé en props, éventuellement en s'appuyant sur une librairie comme `react-image-crop`.  
- Ajouter des commentaires pour expliquer la logique d'interaction et le calcul des coordonnées.

---