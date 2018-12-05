# Cahier des charges du blog

## Contexte

Un responsable de formation d'une école de développement web souhaite mettre un blog à disposition de ses élèves.

### Objectif

Un blog à but pédagogique qui va nous permettre de voir de nouvelles notions autour du développement web.

### Budget

- 2300 €

### Délai

- 6 jours

## Specs fonctionnelles

### Apparence

Blog classique avec thème autour du cosmos. Le site doit être responsive (répondant, adaptatif).

### Contenus

Types de contenus :

- articles
- catégories
- auteurs

Une interface d'administration n'est pas nécessaire pour l'instant. À voir par la suite.
Les contenus seront fournis par le client.

### Interactions services

- Moteur de recherche

### Langue

Site en français.

### Arborescence

- Accueil
- Page d'article
- Page de catégorie
- Page d'auteur
- Mentions légales
- À propos
- Page de contact

Il faut prévoir une page d'erreur pour toutes les pages inexistantes.

### Navigation

- Menu principal
- Pagination
- Fil d'Ariane (breadcrumb)
- Menu d'auteurs
- Menu de catégories
- Liens vers les réseaux sociaux
- Menu secondaire (Mentions légales, À propos, ...)

#### Layout global

- Header
  - Image
  - Titre
  - Slogan (baseline)
  - Fil d'Ariane
- Sidebar
  - Recherche
  - Menu d'auteurs
  - Menu de catégories
- Main
  - Liste d'articles
  - Biographie d'auteur
  - Contenu d'un article
  - ...
- Footer
  - Navigation secondaire
  - Réseaux sociaux

#### Liste des articles

- Article
  - Lien (Titre, Lire la suite)
  - Titre
  - Un résumé
  - Image de mise en avant
  - Auteur :
    - Nom d'affichage
    - Image
  - Catégorie
  - Date
- Pagination

### Contraintes techniques

- Site responsive
- Compatibilités avec les dernières versions des navigateurs

## Specs techniques

### Description précises des données manipulées

- articles
  - titre
  - description
  - contenu
  - image
  - date
  - catégorie
  - auteur
- auteurs
  - nom
  - prénom
  - pseudo
  - avatar
  - position
- catégories
  - nom

### Architecture logicielle choisie

- PHP
- JS
- HTML
- CSS - Bootstrap
- MySQL
