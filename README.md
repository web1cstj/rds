## Intégration Web I — Exercice formatif
# Exercice : Découpage du site RDS

## Consignes

- But: Placer les balises de base de la structure d'une page web.
- Utilisez _Firefox_ (pas _Chrome_).
- Testez votre page après __chaque__ modification.
- Toutes les balises sont des balises avec contenu.
- __Ne__ passez à l'étape suivante __que__ si la page vous l'a indiqué.
- Si une bordure jaune clignotante apparaît, c'est que des éléments sont mal placés.

## Préparation

1. [Téléchargez le dossier compressé](https://github.com/web1cstj/rds/archive/refs/heads/depart.zip) dans votre espace de travail sur le `disque D`.
1. Décompressez le fichier pour obtenir le dossier `rds-depart`.
1. Ouvrez le dossier `rds-depart` (et le fichier `index.html`) dans _VSCode_.

## Étape 1
![Aperçu du final](etape1.png)

1. Dans la balise body ajoutez un attribut `class` dont la valeur est `etape1`. Visionnez le résultat.
1. Dans le contenu de l'élément `body`, ajoutez un élément `div` ayant un attribut `class` dont la valeur est `interface`. Visionnez les changements. Une version gris pâle de la page devrait être apparue.
1. Dans le contenu de cet élément interface, ajoutez 3 éléments : un `div` de classe `content`, un `footer` et un `header`. Faites attention de les placer dans le bon ordre logique!
1. Si la page est complète, passez à l'étape suivante.

## Étape 2

![Aperçu du final](final.png)
1. Changez la classe du `body` pour `etape2`.
1. Dans le `header`, ajoutez dans cet ordre :
   - une `section`
   - un `nav`
   - une `section` avec la classe `logo`
   - une `section` avec le `id` resultats
1. Dans le `div` de classe `content` :
   1. Ajoutez 3 balises `section` ayant la classe `colonne`.
   1. Aux balises `section`, ajoutez respectivement dans cet ordre les classes `gauche`, `centre` et `droite`. Chaque balise devrait donc avoit une classe double.
1. Dans le `footer`
   1. Ajoutez un `nav`.
   1. Ajoutez un `div` ayant l'attribut `id` avec la valeur `copyright`
1. La page devrait vous indiquer que vous avez terminé.

## Solution

Vous pouvez [téléchager la solution](https://github.com/web1cstj/rds/archive/refs/heads/master.zip) pour comparer vos résultats.
