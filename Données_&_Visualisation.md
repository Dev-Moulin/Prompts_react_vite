6. Données & Visualisation
[[prompts_ameliore React + Vite]]
### DataTable (Advanced)
**Composant DataTable**  
Crée un composant React nommé `DataTable` pour une application Vite. Le composant doit :  
- Afficher un tableau de données interactif en recevant les données en props.  
- Permettre le tri des colonnes en cliquant sur les en-têtes et gérer l'état du tri avec `useState`.  
- Intégrer un champ de recherche pour filtrer dynamiquement les données.  
- Ajouter des commentaires pour décrire la logique de tri et de filtrage.

---

### Chart (Advanced)
**Composant Chart**  
Crée un composant React nommé `Chart` pour une application Vite. Le composant doit :  
- Afficher un graphique interactif à partir d'un jeu de données passé en props, en utilisant Chart.js ou Recharts.  
- Être personnalisable (type de graphique, couleurs, légendes) via des props et responsive.  
- Gérer les mises à jour des données avec `useState` et `useEffect` et prévoir la gestion d'éventuelles erreurs.  
- Ajouter des commentaires pour décrire l'intégration et la logique de rendu.

---

### CustomizableChart (Advanced)
**Composant CustomizableChart**  
Crée un composant React nommé `CustomizableChart` pour une application Vite. Le composant doit :  
- Afficher un graphique interactif à partir de données fournies en props, en utilisant Chart.js ou Recharts.  
- Permettre la personnalisation de son apparence (couleurs, légendes, type de graphique) via des contrôles interactifs ou des props.  
- Mettre à jour le graphique en temps réel lorsque les options changent, via `useState` et `useEffect`.  
- Ajouter des commentaires pour expliquer la logique de configuration et de mise à jour.

---

### DataVisualizer (Advanced)
**Composant DataVisualizer**  
Crée un composant React nommé `DataVisualizer` pour une application Vite. Le composant doit :  
- Afficher des graphiques interactifs à partir d'un jeu de données passé en props, en utilisant une librairie comme D3.js ou Recharts.  
- Offrir des options de personnalisation (type de graphique, couleurs, légendes) via des props et contrôles interactifs.  
- Gérer l'état des données et les mises à jour via `useState` et `useEffect`.  
- Ajouter des commentaires pour décrire la logique de visualisation.

---

### DataExport (Advanced)
**Composant DataExport**  
Crée un composant React nommé `DataExport` pour une application Vite. Le composant doit :  
- Permettre à l'utilisateur d'exporter des données affichées sous forme de fichier CSV ou Excel.  
- Proposer des options de format d'export via des props et déclencher le téléchargement du fichier généré.  
- Gérer la génération du fichier et afficher une progression ou des erreurs via `useState` et `useEffect`.  
- Ajouter des commentaires pour décrire la logique d'exportation.

---

### DataImport (Advanced)
**Composant DataImport**  
Crée un composant React nommé `DataImport` pour une application Vite. Le composant doit :  
- Permettre à l'utilisateur d'importer des données depuis un fichier CSV ou Excel via un champ de type `file`.  
- Valider le format du fichier et parser les données pour les envoyer à une API fictive ou les intégrer dans l'état.  
- Gérer les erreurs de validation et afficher un indicateur de chargement pendant le traitement.  
- Ajouter des commentaires pour expliquer la logique d'importation.

---

### QRCodeGenerator (Intermediate)
**Composant QRCodeGenerator**  
Crée un composant React nommé `QRCodeGenerator` pour une application Vite. Le composant doit :  
- Générer dynamiquement un QR code à partir d'un texte ou d'une URL fourni(e) en props, en utilisant une librairie comme `qrcode.react`.  
- Afficher un aperçu du QR code généré et offrir la possibilité de le télécharger ou de le partager.  
- Gérer l'état et les mises à jour en temps réel via `useState` et `useEffect` si nécessaire.  
- Ajouter des commentaires pour décrire la logique de génération.

---