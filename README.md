# Vite & Gourmand

Application web pour un traiteur de Bordeaux permettant de présenter ses menus, à terme et de gérer les commandes en ligne.

> **État d'avancement** : la partie **front-end (HTML / CSS)** est en cours de réalisation. La partie **back-end (PHP / base de données)** n'est pas terminé.

---

## Stack technique

### Actuellement utilisé (front-end)
- **HTML5** — structure sémantique des pages
- **CSS3** — mise en forme et responsive (media queries)
- **Bootstrap 5.3** — framework CSS (grille, composants, responsive)
- **Bootstrap Icons** — bibliothèque d'icônes
- **Police** : Poppins (Google Fonts)

### Prévu (back-end)
- **PHP 8** — logique serveur (architecture MVC maison)
- **PDO** — accès sécurisé à la base de données
- **MySQL / MariaDB** — base de données relationnelle
- **MongoDB** — base de données NoSQL (statistiques)

---

## Pages réalisées

| Page | Fichier | Description |
|------|---------|-------------|
| Accueil | `index.html` | Présentation, engagements, avis clients |
| Catalogue | `catalogue.html` | Liste des menus avec filtres |
| Connexion / Inscription | `auth.html` | Authentification à 2 onglets |

---

## Structure des fichiers (front actuel)

```
├── index.html          # Page d'accueil
├── catalogue.html      # Catalogue des menus
├── auth.html           # Connexion / Inscription
├── index.css           # Styles page d'accueil
├── catalogue.css       # Styles catalogue
├── auth.css            # Styles authentification
└── images/             # Images des menus et visuels
```

---

## Lancer le projet en local

1. Cloner le dépôt
   ```bash
   
   ```

2. Ouvrir le fichier `index.html` directement dans un navigateur
   - Double-clic sur `index.html`

---

## Déploiement (GitHub Pages)

Le site étant statique, il peut être déployé gratuitement via **GitHub Pages** :

1. Pousser le code sur un dépôt GitHub **public**
2. Aller dans **Settings** → **Pages**
3. Dans **Source**, choisir la branche `main`
4. Cliquer sur **Save**
5. Le site sera accessible à l'adresse : ``

---

## Charte graphique

| Élément | Valeur |
|---------|--------|
| Couleur principale | Bordeaux `#7B1E2E` |
| Couleur accent | Doré `#C9A961` |
| Fond | Crème `#FAF6EF` |
| Texte | Café `#3A2A15` |
| Police | Poppins |

La charte graphique complète est disponible dans le fichier `Charte_graphique.pdf`.

---

## Accessibilité (RGAA)

Le projet vise une conformité RGAA :
- Structure sémantique (`header`, `nav`, `main`, `section`, `article`, `footer`)
- Attributs `alt` sur les images de contenu
- `aria-label` sur les navigations et liens iconographiques
- Contrastes de couleurs respectant les ratios recommandés

---
