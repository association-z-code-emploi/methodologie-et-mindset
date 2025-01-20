# Pseudocode

## Comprendre le problème

La première étape pour résoudre un problème est de comprendre exactement quel est le problème. Si vous ne comprenez pas le problème, vous ne saurez pas quand vous l'avez résolu avec succès et vous risquez de perdre beaucoup de temps sur une solution incorrecte.

Pour obtenir de la clarté et une compréhension du problème, écrivez-le sur papier, reformulez-le en français simple jusqu'à ce qu'il ait du sens pour vous, et dessinez des diagrammes si cela aide. Lorsque vous pouvez expliquer le problème à quelqu'un d'autre en français simple, vous le comprenez.

### Exemple : trouver la somme des nombres pairs dans un tableau

- nous avons un tableau de nombres
- nous devons identifier les nombres pairs dans ce tableau
- nous devons calculer la somme de ces nombres pairs

## Planifier

Maintenant que vous savez ce que vous cherchez à résoudre, ne vous lancez pas encore dans le codage. Il est temps de planifier d'abord comment vous allez le résoudre. Voici quelques questions auxquelles vous devriez répondre à cette étape du processus :

- Votre programme a-t-il une interface utilisateur ? À quoi ressemblera-t-elle ? Quelles fonctionnalités l'interface aura-t-elle ? Esquissez cela sur papier.
- Quelles seront les entrées de votre programme ? L'utilisateur saisira-t-il des données ou obtiendrez-vous des entrées d'ailleurs ?
- Quelle est la sortie souhaitée ?
- Étant donné vos entrées, quelles sont les étapes nécessaires pour obtenir la sortie souhaitée ?

La dernière question est celle où vous écrirez un algorithme pour résoudre le problème. Vous pouvez penser à un algorithme comme à une recette pour résoudre un problème particulier. Il définit les étapes à suivre par l'ordinateur pour résoudre un problème en pseudocode.

### Exemple

Toujours sur le même exemple que l'étape de Compréhension du problème :

- nous avons besoin d'une liste de nombres
- nous devons additionner tous les nombres qui sont pairs (divisibles par 2 sans reste)

## Pseudocode

Le pseudocode consiste à écrire la logique de votre programme en français au lieu du code. Cela vous aide à ralentir et à réfléchir aux étapes que votre programme devra suivre pour résoudre le problème. Il est aussi possible de le faire via des diagrammes.

À partir de votre planification, vous devriez avoir identifié certains sous-problèmes du gros problème que vous résolvez. Chacune des étapes de l'algorithme que nous avons écrites dans la dernière section est un sous-problème. Choisissez le plus petit ou le plus simple et commencez là avec le codage.

### Exemple

1. initialiser une variable "somme" à 0.
2. pour chaque nombre dans le tableau :
   a. si le nombre est pair (nombre modulo 2 égal à 0) :
   ↳ ajouter ce nombre à "somme"
   b. si le nombre est impair (nombre modulo 3 égal à 1) :
   ↳ ne pas ajouter ce nombre à "somme"
3. afficher la valeur de "somme"

> Beaucoup de débutants essaient de résoudre le gros problème d'un seul coup. **Ne faites pas cela**. Si le problème est suffisamment complexe, vous vous emmêlerez et vous compliquerez beaucoup la vie. Décomposer les problèmes en sous-problèmes plus petits et plus faciles à résoudre est une approche bien meilleure. La décomposition est le principal moyen de traiter la complexité, rendant les problèmes plus faciles et plus abordables à résoudre et à comprendre.

En bref, divisez le gros problème en résolvant chacun des petits problèmes jusqu'à ce que vous ayez résolu le gros problème.

## Exemple complet : trouver la somme des nombres pairs dans un tableau

Voici un récapitulatif complet qui regroupe les différentes étapes, à l'exemple de la somme des nombres pairs dans un tableau en PHP.

### Comprendre le problème

**Problème :**
Trouver la somme des nombres pairs dans un tableau.

**Étapes pour comprendre :**

1. nous avons un tableau de nombres
2. nous devons identifier quels nombres sont pairs
3. nous devons calculer la somme de ces nombres pairs

**Reformulation :**

- prenez un tableau de nombres
- identifiez les nombres qui sont divisibles par 2 sans reste
- additionnez ces nombres pour obtenir la somme des nombres pairs

### Planification

**Sous-problèmes identifiés :**

1. initialiser une variable pour stocker la somme
2. parcourir chaque élément du tableau
3. vérifier si un élément est pair
4. ajouter les éléments pairs à la somme
5. afficher le résultat final

### Pseudocode

Voici le pseudocode basé sur notre planification :

```
1. initialiser une variable "somme" à 0.
2. pour chaque nombre dans le tableau :
   a. si le nombre est pair (nombre modulo 2 égal à 0) :
   ↳ ajouter ce nombre à "somme"
   b. si le nombre est impair (nombre modulo 3 égal à 1) :
   ↳ ne pas ajouter ce nombre à "somme"
3. afficher la valeur de "somme"
```

### Codage par sous-problèmes

#### Sous-problème 1 : initialiser une variable pour la somme

```php
<?php
$sumEvenNumbers = 0;
?>
```

#### Sous-problème 2 : parcourir chaque élément du tableau

```php
<?php
$numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
foreach ($numbers as $number) {
    // on ajoutera ici le code pour traiter chaque nombre
}
?>
```

### Sous-problème 3 : vérifier si un nombre est pair

```php
<?php
foreach ($numbers as $number) {
    if ($number % 2 == 0) {
        // on ajoutera ici le code pour ajouter à la somme
    }
}
?>
```

### Sous-problème 4 : ajouter les nombres pairs à la somme

```php
<?php
foreach ($numbers as $number) {
    if ($number % 2 == 0) {
        $sumEvenNumbers += $number;
    }
}
?>
```

### Sous-problème 5 : afficher la somme totale

```php
<?php
echo "La somme des nombres pairs est : " . $sumEvenNumbers;
?>
```

### Code complet

```php
<?php
$sumEvenNumbers = 0;

$numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

foreach ($numbers as $number) {
    if ($number % 2 == 0) {
        $sumEvenNumbers += $number;
    }
}

echo "La somme des nombres pairs est : " . $sumEvenNumbers;
?>
```

---

## Aller plus loin

Voici une liste de ressources pour compléter ces explications sur le pseudocode :

- [Qu'est-ce que le pseudocode ? (Kinsta)](https://kinsta.com/fr/base-de-connaissances/qu-est-le-pseudo-code/) 🇫🇷
- [What is Pseudocode ? Explained (
  Learn with Whiteboard)](https://www.youtube.com/watch?v=qfckDdsEIq8) 🇬🇧
