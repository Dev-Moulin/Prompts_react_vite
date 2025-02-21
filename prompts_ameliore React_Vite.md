-[[React]] 
-[[DEV++]] 
-[[IA]]
# Prompts Améliorés pour Composants React avec Vite  
*Triés par Catégories Fonctionnelles avec Indication de Complexité*

Ce document regroupe 100 prompts pour générer des composants modulaires en React avec Vite.  
Chaque composant est classé par catégorie fonctionnelle et accompagné d'une note de complexité :  
- **Basic** : Composants simples, souvent statiques ou à gestion d'état minimale.  
- **Intermediate** : Composants avec une logique d'interaction ou de validation modérée.  
- **Advanced** : Composants impliquant des interactions complexes, des intégrations d'API ou une gestion d'états avancée.

---

## 1. Authentification & Sécurité [[1. Authentification & Sécurité]]

- **RegistrationPage** (Intermediate)  
  Permet aux utilisateurs de s'inscrire via un formulaire complet avec validation et gestion des erreurs.

- **LoginPage** (Intermediate)  
  Fournit un formulaire de connexion avec gestion de l'état et des erreurs de connexion.

- **Logout** (Basic)  
  Déconnecte l'utilisateur en effaçant le token et redirige vers la page de connexion.

- **Dashboard** (Intermediate)  
  Page d'accueil personnalisée pour les utilisateurs authentifiés, intégrant une navigation sécurisée.

- **Module de Gestion du Token JWT** (Basic–Intermediate)  
  Module utilitaire pour stocker, récupérer, vérifier et supprimer un token JWT dans le localStorage.

- **PasswordReset** (Intermediate)  
  Permet aux utilisateurs de réinitialiser leur mot de passe via un formulaire et une simulation d'API.

- **EmailVerification** (Intermediate)  
  Vérifie l'email de l'utilisateur en extrayant un token de l'URL et en simulant une validation API.

- **ProtectedRoute** (Intermediate)  
  Protège les routes en vérifiant l'authentification de l'utilisateur et en redirigeant si nécessaire.

- **RoleBasedAccessControl** (Advanced)  
  Affiche conditionnellement du contenu en fonction du rôle de l'utilisateur, gérant des autorisations complexes.

---

## 2. Navigation & Layout [[2. Navigation & Layout]]

- **Header** (Basic–Intermediate)  
  Affiche la navigation principale, le logo et les liens de profil/déconnexion avec gestion de l'état.

- **Footer** (Basic)  
  Affiche des liens informatifs (À propos, Contact, etc.) et s'intègre en bas de page.

- **Sidebar** (Intermediate)  
  Menu latéral de navigation, adapté aux écrans mobiles et desktop, avec état d'ouverture/fermeture.

- **Breadcrumbs** (Basic)  
  Affiche un fil d'Ariane permettant une navigation hiérarchique intuitive.

- **BreadcrumbItem** (Basic)  
  Représente un élément individuel du fil d'Ariane, facilitant la navigation.

- **Pagination** (Basic)  
  Permet de naviguer entre les pages d'une liste grâce à des boutons interactifs.

- **ResponsiveGrid** (Intermediate)  
  Organise dynamiquement le contenu dans une grille responsive configurable via des props.

---

## 3. Formulaires & Entrées [[3. Formulaires & Entrées]]

- **UserProfile** (Intermediate)  
  Affiche et permet la modification des informations du profil utilisateur via un formulaire interactif.

- **ContactForm** (Intermediate)  
  Formulaire de contact complet avec validation des champs et simulation d'envoi de données.

- **NewsletterSignup** (Basic–Intermediate)  
  Permet aux utilisateurs de s'inscrire à une newsletter avec vérification du format d'email.

- **FeedbackForm** (Intermediate)  
  Collecte les retours des utilisateurs via un formulaire validé et affiche des messages de confirmation.

- **FormField** (Basic)  
  Composant générique pour divers champs de formulaire, incluant validation et affichage d'erreurs.

- **MultiStepForm** (Advanced)  
  Formulaire divisé en plusieurs étapes avec navigation, validation par étape et gestion d'état global.

- **CommentSection** (Intermediate)  
  Affiche une liste de commentaires et permet d'ajouter de nouveaux commentaires via un formulaire contrôlé.

---

## 4. Composants UI & Interaction [[4. Composants UI & Interaction]]

- **Modal** (Intermediate)  
  Fenêtre modale générique pour afficher du contenu en overlay avec animations de transition.

- **Tabs** (Intermediate)  
  Permet de naviguer entre différentes sections de contenu via des onglets interactifs.

- **Accordion** (Basic–Intermediate)  
  Sections repliables permettant d'afficher ou masquer du contenu selon l'interaction de l'utilisateur.

- **Tooltip** (Basic)  
  Affiche une infobulle contextuelle lors du survol d'un élément pour fournir des informations complémentaires.

- **LoaderButton** (Intermediate)  
  Bouton combiné à un indicateur de chargement pour signaler une action en cours.

- **ExpandableCard** (Intermediate)  
  Carte d'information qui s'étend pour révéler du contenu supplémentaire via une animation fluide.

- **ToastNotifications** (Intermediate)  
  Affiche des notifications temporaires (toasts) avec gestion du temps d'affichage et suppression automatique.

- **Loader** (Basic)  
  Indicateur de chargement générique, sous forme de spinner ou animation, pour signaler le traitement des données.

- **ModalConfirm** (Intermediate)  
  Fenêtre modale de confirmation pour les actions sensibles, avec options personnalisables.

---

## 5. Médias & Fichiers [[5. Médias & Fichiers]]

- **VideoPlayer** (Intermediate)  
  Lecteur vidéo intégrant des contrôles de lecture et une barre de progression pour l'utilisateur.

- **AudioPlayer** (Intermediate)  
  Lecteur audio avec contrôles standards et barre de progression indiquant l'état de la lecture.

- **ImageGallery** (Intermediate)  
  Galerie d'images en grille, permettant d'agrandir une image dans une modale pour une meilleure visualisation.

- **FileUploader** (Intermediate)  
  Permet le téléversement de fichiers via un champ de type file, avec barre de progression et gestion d'erreurs.

- **FilePreview** (Intermediate)  
  Affiche un aperçu d'un fichier (image, document, etc.) avant téléchargement, avec gestion de fallback.

- **DragAndDropUploader** (Advanced)  
  Interface de glisser-déposer pour téléverser des fichiers, avec simulation de téléchargement et barre de progression.

- **FileDownload** (Intermediate)  
  Affiche les informations d'un fichier et simule le téléchargement avec un indicateur de progression.

- **ImageCropper** (Advanced)  
  Permet de rogner et redimensionner une image via une interface interactive et précise.

---

## 6. Données & Visualisation [[6. Données & Visualisation]]

- **DataTable** (Advanced)  
  Tableau interactif pour afficher et trier des données, avec options de filtrage et recherche.

- **Chart** (Advanced)  
  Graphique interactif personnalisable à partir de données fournies, avec options de style et légende.

- **CustomizableChart** (Advanced)  
  Graphique offrant des options de personnalisation en temps réel, adapté aux besoins avancés.

- **DataVisualizer** (Advanced)  
  Visualise des jeux de données via des graphiques interactifs et personnalisables pour une meilleure analyse.

- **DataExport** (Advanced)  
  Permet d'exporter des données affichées sous forme de fichier CSV ou Excel, avec options de format.

- **DataImport** (Advanced)  
  Facilite l'importation de données depuis un fichier CSV ou Excel, avec validation et parsing des données.

- **QRCodeGenerator** (Intermediate)  
  Génère dynamiquement un QR code à partir d'un texte ou URL fourni, avec possibilité de téléchargement.

---

## 7. Social & Communication [[7. Social & Communication]]

- **SocialShare** (Basic)  
  Affiche des boutons de partage pour diffuser du contenu sur divers réseaux sociaux.

- **SocialFeed** (Intermediate)  
  Affiche un flux de posts sociaux avec options pour aimer et partager les publications.

- **ChatRoom** (Intermediate–Advanced)  
  Interface de messagerie en temps réel pour envoyer et recevoir des messages.

- **ChatMessage** (Basic)  
  Représente un message individuel dans une conversation, avec distinction visuelle entre messages envoyés et reçus.

- **LoginWithSocial** (Intermediate)  
  Permet aux utilisateurs de se connecter via des réseaux sociaux grâce à des boutons dédiés.

- **SocialMediaEmbed** (Intermediate)  
  Intègre du contenu provenant de réseaux sociaux (comme Twitter ou Instagram) dans la page.

---

## 8. Cartographie (Mapping) [[8. Cartographie (Mapping)]]

- **InteractiveMap** (Advanced)  
  Carte interactive avec fonctionnalités de zoom, déplacement et affichage de marqueurs basés sur des données.

- **MapMarker** (Intermediate)  
  Représente un marqueur sur une carte avec une info-bulle affichant des informations sur le lieu.

- **MapClusterer** (Advanced)  
  Regroupe automatiquement des marqueurs proches pour améliorer la lisibilité de la carte.

---

## 9. Utilitaires & Divers [[9. Utilitaires & Divers]]

- **CookieConsentBanner** (Basic)  
  Affiche une bannière de consentement aux cookies avec stockage du choix dans le localStorage.

- **SkeletonLoader** (Basic)  
  Composant d'affichage de placeholder (skeleton) pendant le chargement des données.

- **useLocalStorage** (Basic)  
  Hook personnalisé pour synchroniser l'état d'un composant avec le localStorage.

- **LazyImage** (Intermediate)  
  Charge les images de manière paresseuse pour améliorer les performances, avec un placeholder.

- **QuickActionMenu** (Intermediate)  
  Menu d'actions rapides accessible via un bouton flottant pour déclencher des actions spécifiques.

- **ScrollToTopButton** (Basic)  
  Bouton qui apparaît lors du défilement pour permettre un retour fluide en haut de la page.

- **SessionTimeout** (Intermediate)  
  Surveille l'inactivité de l'utilisateur et affiche une alerte pour prolonger ou terminer la session.

- **UserPresenceIndicator** (Basic)  
  Affiche visuellement l'état en ligne ou hors ligne de l'utilisateur via une icône ou couleur.

- **NotificationSettings** (Intermediate)  
  Permet à l'utilisateur de configurer ses préférences de notifications (e-mail, push, SMS).

- **UserConsentManager** (Intermediate)  
  Gère les consentements de l'utilisateur pour les cookies et la collecte de données.

- **MultiLanguageSwitcher** (Intermediate)  
  Offre la possibilité de changer la langue de l'application via une interface intuitive.

- **SEO** (Intermediate)  
  Gère dynamiquement les meta tags d'une page pour améliorer le référencement.

- **PrivacyPolicy** (Basic)  
  Affiche la politique de confidentialité de l'application de manière lisible.

- **TermsOfService** (Basic)  
  Affiche les conditions d'utilisation de l'application avec une mise en forme claire.

---

## 10. Interactions Avancées & Médias Complémentaires [[10. Interactions Avancées & Médias Complémentaires]]

- **SearchBar** (Basic)  
  Champ de recherche simple permettant la saisie et la soumission de requêtes.

- **Autocomplete** (Advanced)  
  Saisie semi-automatique qui propose des suggestions en temps réel en fonction de la saisie.

- **DragAndDropList** (Intermediate)  
  Permet de réordonner une liste d'éléments par glisser-déposer, avec gestion d'état.

- **InfiniteScrollList** (Advanced)  
  Liste à défilement infini qui charge dynamiquement de nouveaux éléments à mesure que l'utilisateur défile.

- **CountdownTimer** (Intermediate)  
  Affiche un compte à rebours dynamique mis à jour en temps réel vers un événement donné.

- **Calendar** (Intermediate)  
  Calendrier interactif permettant la sélection d'une date et la navigation entre les mois.

- **RichTextEditor** (Advanced)  
  Éditeur de texte riche offrant des options de mise en forme (gras, italique, souligné, etc.).

- **DatePicker** (Intermediate)  
  Sélecteur de date interactif avec un calendrier et validation des sélections.

- **ThemeSwitcher** (Basic)  
  Permet de basculer entre un mode clair et sombre, avec stockage du choix dans le localStorage.

- **SearchResults** (Basic)  
  Affiche une liste de résultats de recherche, avec gestion d'un message en cas d'absence de résultats.

- **UserList** (Intermediate)  
  Affiche une liste d'utilisateurs récupérée via une API fictive, avec pagination ou défilement infini.

---

## 11. Composants Spécifiques Réseaux & Vidéo [[11. Composants Spécifiques Réseaux & Vidéo]]

- **VideoCall** (Advanced)  
  Simule une interface d'appel vidéo avec flux vidéo fictifs et contrôles pour la caméra et le micro.

- **CalendarEvent** (Intermediate)  
  Représente un événement de calendrier avec informations de date, heure, titre et description, et options d'édition.

- **ServerStatusIndicator** (Intermediate)  
  Affiche en temps réel l'état du serveur (en ligne/hors ligne) en sondant une API régulièrement.

---

## 12. Export, Import & Personnalisation [[12. Export, Import & Personnalisation]]

- **ExportToPDF** (Intermediate)  
  Permet d'exporter le contenu affiché en PDF en générant dynamiquement le document via une librairie.

---

## 13. Composants Complémentaires (Suite 70-100) [[13. Composants Complémentaires]]

- **NotificationBadge** (Basic)  
  Affiche un badge indiquant le nombre de notifications non lues, avec gestion des valeurs élevées (ex. "99+").

- **RatingStars** (Basic)  
  Permet à l'utilisateur d'évaluer un élément en cliquant sur des étoiles, avec mise à jour de la note.

- **ProductCard** (Basic–Intermediate)  
  Affiche les informations d'un produit (image, titre, description, prix) avec un bouton "Ajouter au panier".

- **APIErrorDisplay** (Basic)  
  Affiche un message d'erreur stylisé en cas d'échec d'une requête API, avec option de relance.

*Note : Certains composants de cette suite sont déjà inclus dans les catégories précédentes.*
  
---

## Remarques

- **Niveaux de complexité** :  
  Les niveaux (Basic, Intermediate, Advanced) indiquent la simplicité ou la complexité d'implémentation du composant.  
- **Regroupements** :  
  Les composants sont organisés par domaine fonctionnel pour faciliter leur identification et leur réutilisation.  
- **Utilisation** :  
  Ce tri permet de retrouver rapidement les composants nécessaires selon le besoin et la complexité souhaitée.

---

*Fin du document.*
