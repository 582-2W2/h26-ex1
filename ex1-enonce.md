# Exercice #1 - Mise en page adaptative

**Pondération :** 3% de la note finale  
**Date de remise :** Vérifiez la date spécifique à votre groupe sur Omnivox

---

## Objectif pédagogique

Cet exercice vous permet de mettre en pratique les concepts de **mise en page adaptative** vus en classe :

- Requêtes média simples pour rendre une page Web adaptative (3 points d'arrêt)
- Mise en page adaptative avec le modèle d'affichage Flexbox
- Images adaptatives utilisant l'élément `<picture>`
- Effet de survol : transformation et transition simples

---

## Description

Vous devez compléter le code HTML et CSS fourni pour créer une page Web adaptative en utilisant l'approche **mobile first**.

La disposition des éléments de la page doit s'adapter aux différentes tailles de viewport en utilisant :
- Des requêtes média appropriées
- Les propriétés d'affichage Flexbox
- Des propriétés de style complémentaires

L'image de la page doit également être adaptative en utilisant une image différente pour chaque point d'arrêt.

Consultez les instructions étape par étape ci-dessous ainsi que les commentaires inclus dans les fichiers HTML et CSS fournis.

---

## Instructions étape par étape

### Étape 1 : Formatage pour les petits appareils (2 points)

Le formatage pour petits appareils mobiles est presque complété dans le code fourni. Complétez les éléments manquants en vous référant aux commentaires `[À compléter : étape 1]` dans le fichier CSS.

### Étape 2 : Formatage pour les écrans moyens et grands (4 points)

Créez des requêtes média pour adapter la page aux différents types d'appareils :

- **Point d'arrêt 1 :** À partir de 600px (écrans de taille moyenne)
- **Point d'arrêt 2 :** À partir de 1200px (écrans de grande taille)

Le formatage par défaut s'applique aux petits appareils (jusqu'à 600px de largeur).

Complétez les requêtes média pour obtenir le résultat attendu. Référez-vous aux commentaires `[À compléter : étape 2]` dans le fichier CSS.

### Étape 3 : Image adaptative avec *direction artistique* (2 points)

Dans le fichier HTML, transformez l'élément `<img>` en une image adaptative utilisant les éléments `<picture>` et `<source>`.

Utilisez les attributs appropriés pour afficher l'image correspondant à chaque point d'arrêt défini dans cet exercice.

Référez-vous au commentaire `[À compléter : étape 3]` dans le fichier HTML.

### Étape 4 : Effet de survol : transformation et transition (2 points)

Ajoutez un effet de survol sur les sections contenant l'information de météo quotidienne. L'effet doit au minimum intégrer une transformation CSS discrète, et possiblement d'autres effets.

Ajoutez une transition adéquate pour animer subtilement cet effet de survol.

Référez-vous au commentaire `[À compléter : étape 4]` dans le fichier CSS.

---

## Barème de correction

| Étape | Description | Points |
|-------|-------------|-------:|
| 1 | Formatage CSS de base | 2 |
| 2 | Requêtes média (2 points d'arrêt) | 4 |
| 3 | Image adaptative avec `<picture>` | 2 |
| 4 | Transformation et transition | 2 |
| **Total** | | **10** |

---

## Remise

Faites la remise de vos fichiers de solution dans **une seule archive au format `.zip`** par LÉA avant la date et l'heure d'échéance indiquées sur Omnivox.

L'archive doit contenir :
- Le fichier HTML modifié
- Le fichier CSS modifié
- Tous les fichiers d'images fournis

---

## Conseils

- Commencez par l'approche **mobile first** : le CSS de base s'applique aux petits écrans
- Utilisez les outils de développement du navigateur (F12) pour tester les différentes tailles d'écran
- Testez chaque point d'arrêt pour vous assurer que la mise en page s'adapte correctement
- Vérifiez que les images appropriées s'affichent pour chaque taille d'écran
- Consultez vos notes de cours et les exemples vus en classe

---

## Démo

![Démo de la solution](demo-solution.gif)

