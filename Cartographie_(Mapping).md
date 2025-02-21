8. Cartographie (Mapping)
[[prompts_ameliore React + Vite]]

### InteractiveMap (Advanced)
**Composant InteractiveMap**  
Crée un composant React nommé `InteractiveMap` pour une application Vite. Le composant doit :  
- Intégrer une carte interactive en utilisant une librairie telle que Leaflet ou Google Maps.  
- Permettre le zoom, le déplacement et l'affichage de marqueurs basés sur des données reçues en props ou via une API.  
- Gérer l'état de la carte (position, zoom, marqueurs) avec `useState` et charger les données via `useEffect`.  
- Gérer les erreurs lors du chargement de la carte ou des données, avec un message d'erreur si nécessaire.  
- Ajouter des commentaires pour expliquer l'intégration et les interactions.

---

### MapMarker (Intermediate)
**Composant MapMarker**  
Crée un composant React nommé `MapMarker` pour une application Vite. Le composant doit :  
- Représenter un marqueur sur une carte interactive en acceptant des props pour la latitude, la longitude et une info-bulle (nom ou description).  
- Être facilement intégrable dans un composant de carte utilisant une librairie telle que Leaflet ou Google Maps.  
- Gérer l'affichage de l'info-bulle lors du survol ou du clic et être responsive.  
- Ajouter des commentaires pour expliquer la logique d'intégration.

---

### MapClusterer (Advanced)
**Composant MapClusterer**  
Crée un composant React nommé `MapClusterer` pour une application Vite. Le composant doit :  
- Intégrer une librairie de cartographie (ex. Leaflet ou Google Maps) et afficher des marqueurs sur une carte interactive.  
- Regrouper automatiquement les marqueurs proches pour améliorer la lisibilité, en mettant à jour dynamiquement l'affichage.  
- Gérer les états avec `useState` et `useEffect`.  
- Ajouter des commentaires pour expliquer la logique de regroupement.

---
