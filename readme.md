# 🌟 Plateforme de Témoignages Codeloccol

## 📝 Description du Projet

Ce projet est une page web responsive conçue pour afficher les témoignages des étudiants de Codeloccol. Le design est basé sur une grille asymétrique sur desktop et s'adapte parfaitement aux tablettes et mobiles.

L'objectif principal était d'implémenter un ensemble strict de spécifications de design (couleurs, typographie, breakpoints) tout en conservant la structure HTML et les noms de classes existants.

## 🚀 Fonctionnalités Clés

* **Design Responsive:** Optimisation pour Desktop (min-width: 1440px), Tablette (max-width: 768px), et Mobile (max-width: 375px).
* **Grille Modulaire:** Utilisation de CSS Grid pour une disposition variée des cartes de témoignages.
* **Style Visuel Cohérent:** Respect des palettes de couleurs spécifiques, y compris un dégradé de fond et des bordures de cartes multicolores.
* **Accessibilité:** Utilisation de la police système "Segoe UI", Tahoma, Geneva, Verdana, sans-serif.

## 🛠️ Technologies Utilisées

* **HTML5:** Structure de la page.
* **CSS3:** Mise en page (Grid/Flexbox) et application des styles spécifiques.
* **Font Awesome:** Pour l'affichage des icônes d'étoiles (`fa-star`) et l'icône de citation (via pseudo-élément CSS).

## ⚙️ Installation et Lancement

Ce projet est purement frontal (frontend) et ne nécessite qu'un navigateur web pour être visualisé.

1.  **Cloner ou télécharger** ce répertoire.
2.  Assurez-vous que les fichiers `index.html` et `style.css` sont dans le même dossier racine.
3.  Ouvrez le fichier `index.html` avec votre navigateur web préféré (ex: Chrome, Firefox).

## 🎨 Spécifications de Design Appliquées (Résumé)

| Élément | Spécification |
| :--- | :--- |
| **Font Family** | "Segoe UI", Tahoma, Geneva, Verdana, sans-serif |
| **Background** | `linear-gradient(135deg, #667eea 0%, #764ba2 100%)` |
| **Bordures Cartes**| Dégradé de couleurs appliqué aux bordures gauches (ex: `#ff6b6b`, `#4ecdc4`, etc.) |
| **H1 Desktop** | `2.5rem` |
| **H1 Mobile** | `2rem` (appliqué à `max-width: 768px`) |
| **Animation Hover**| `transform 0.3s ease, box-shadow 0.3s ease` |

---

## 🛑 Note Importante (Font Awesome)

Le projet utilise un lien CDN pour Font Awesome :
`<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css" ... />`

Si les icônes (étoiles ou icône de citation) ne s'affichent pas, veuillez vous assurer que :
1. Le CDN est accessible.
2. La version de Font Awesome 7 est compatible avec les classes utilisées (`fa-solid`).
##
![La capture du projet](./images/Capture%20d’écran%20.png)
## 📱 Pour le mobile
![La capture du projet](./images/Capture%20d’écran1.png)