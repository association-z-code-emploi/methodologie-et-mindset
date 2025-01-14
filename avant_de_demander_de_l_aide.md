> Réécriture de l'article de [The Odin Project](https://www.theodinproject.com/guides/community/before_asking) (repris sous [Creative Commons license](https://github.com/TheOdinProject/curriculum/blob/main/license.md))

---

# Aidez-vous avant de demander aux autres

Ne redoutez pas de poser la question et de déranger les autres : [posez simplement la question sans plus attendre](https://dontasktoask.com/) !

## Ajustez vos attentes

- Les projets sont conçus pour vous pousser à apprendre
- Acceptez de ne pas avoir toutes les réponses immédiatement : elles seront encore plus savoureuses quand vous les découvrirez !

## Décomposez le problème

- Divisez le problème en sous-problèmes
- Écrivez-les en pseudo-code

### Exemple

On veut vérifier si un nombre est pair ou impair :

- on va devoir prendre un nombre en paramètre, donné par exemple par l'utilisateur
- on va ensuite vérifier si le nombre est divisible par 2
- on va enfin affiche un message indiquant si le nombre est pair ou impair

↳ on va donc concrètement avoir besoin :

- d'une fonction avec le nombre en paramètre, car on veut pouvoir répéter l'opération autant de fois que l'utilisateur le voudra
- de diviser le nombre en 2, et voir si le reste de la division renvoie 0 (donc il sera pair) ou autre chose (donc il sera impair)
- d'afficher le résultat quand la fonction est terminée

## Recherche ciblée

- Recherchez des solutions pour des sous-problèmes spécifiques
- Adaptez vos critères de recherche si nécessaire

### Exemple

On ne sait pas comment récupérer le reste d'une division : on peut commencer par faire une recherche sur le web avec "_[comment récupérer un reste de division en PHP](https://www.google.com/search?q=comment+r%C3%A9cup%C3%A9rer+un+reste+de+division+en+PHP)_" !

On sait aussi, dans notre exemple, qu'il s'agit sûrement d'une opération mathématique : on peut aller regarder dans la documentation la section des _[fonctions mathématiques](https://www.php.net/manual/fr/ref.math.php)_.

> Attention : une erreur courante est parfois d'être trop précis et trop spécifique alors que [votre problème est peut-être plus généralisé/simple que vous ne le pensez](https://xyproblem.info/)

## Messages d'erreur

- Lisez et analysez les messages d'erreur
- Recherchez les erreurs spécifiques en ligne ou dans votre communauté

### Exemple

Dans notre code PHP, on se retrouve avec cette erreur :

`PHP Parse error syntax error unexpected end of file, expecting variable or "${" or "{$" in file.php on line 4`

- on prend le temps de lire l'erreur : ici, on explique qu'il manque quelque chose pour que le code soit complet, mais `"${"` ou `"{$"` n'a pas l'air nécessaire
- on peut copier/coller l'erreur dans un moteur de recherche ou de la documentation : on tombera généralement sur de la documentation ou [des messages d'autres développeurs ayant une erreur similaire](<https://phoenixnap.com/kb/php-error-types#:~:text=PHP%20Parse%20(Syntax)%20Error>)

## Revoir les leçons/projets précédents

- Révisez les notions déjà apprises pouvant être appliquées
- Consulter la documentation ou d'autres sites d'apprentissage sur le langage que vous utilisez (eg. dans notre exemple, on peut soit aller voir [la doc officielle de PHP](https://www.php.net/docs.php) ou un site comme [W3Schools](https://www.w3schools.com/php/default.asp))

## Vérifiez les fautes de frappe

- Relisez-vous ! La majorité des erreurs de code se trouvent entre le clavier et le dossier de votre siège ... Peut-être avez-vous codez trop rapidement, et oublié un caractère, un espace, etc...
- Des outils comme IntelliSense (sur VSCode) permettent de vous suggérer la syntaxe et de minimiser les erreurs en les soulignant

## Débuggage

- Utilisez un débugueur pour vérifier les variables et le comportement du code
- Consultez les DevTools pour des informations supplémentaires dans votre navigateur

## Faites une pause

- Prenez du recul en cas de frustration ou fatigue
- Les solutions peuvent surgir après une pause : inconsciemment, votre cerveau continue de réfléchir au problème, mais plus posément, moins rapidement

## Expliquez votre code

- Réfléchir va vite, parler ou écrire va plus lentement et permet à votre cerveau de réfléchir plus calmement (comme indiqué au point précédent ; "Faites une pause")
- Faîtes le "[canard](https://fr.wikipedia.org/wiki/M%C3%A9thode_du_canard_en_plastique)" pour mieux comprendre votre code : demandez de l'aide à un camarade en vous écoutant simplement expliqué votre problème. Peut-être vous rendrez-vous compte de votre erreur ou votre camarade vous pointera ce qui lui semble être le problème !

## Conclusion

Appliquer chacun de ces conseils peut prendre un certain temps, mais avec de l'expérience, beaucoup d'entre eux deviendront des habitudes durant votre formation, ce qui vous fera gagner du temps à long terme. Si vous n'avez pas trouvé la source du problème après avoir travaillé sur chacun de ces conseils, il est temps de demander de l'aide à d'autres !

Cependant, demander de l'aide à d'autres n'est pas aussi simple que cela puisse paraître, donc veuillez lire "[Comment poser une question technique](poser_des_questions_techniques.md)".
