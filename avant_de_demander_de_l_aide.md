> Réécriture de l'article de [The Odin Project](https://www.theodinproject.com/guides/community/before_asking) (repris sous [Creative Commons license](https://github.com/TheOdinProject/curriculum/blob/main/license.md))

---

# Aidez-vous avant de demander aux autres

Lorsque vous faites partie d'une communauté active de développeurs expérimentés, comme notre serveur Discord, il peut être tentant de demander de l'aide avant de faire suffisamment d'efforts de votre côté. Si cela devient une habitude, cela entravera votre propre progression car vous passerez à côté des occasions de renforcer vos propres compétences en dépannage. Ces compétences sont essentielles pour devenir un développeur accompli. Examinons donc quelques conseils pratiques pour vous aider avant de demander de l'aide !

## Ajustez vos attentes

La plupart des exercices et projets sont conçus pour vous pousser à vos limites et vous obliger à faire des recherches par vous-même. Cette expérience est similaire à celle d'être chargé de développer une nouvelle fonctionnalité dans votre futur emploi. Lorsque vous commencez, il est fort probable que vous ne sachiez pas comment accomplir toutes les tâches. Au lieu de maintenir des attentes irréalistes, ajustez votre perspective et habituez-vous à ne pas avoir toutes les réponses dès le départ.

## Décomposez le problème

Décomposez le problème en petites parties et écrivez-le en pseudo-code. Si vous souhaitez une explication détaillée de cette étape, lisez notre leçon sur [la résolution de problèmes](#TBA) en gardant ce problème spécifique à l'esprit.

## Effectuez une recherche sur un "sous-problème"

Après avoir décomposé votre problème en sous-problèmes plus petits, vous devriez effectuer une recherche sur un sous-problème en utilisant votre moteur de recherche préféré. Par exemple, vous devriez rechercher "retourner un élément aléatoire d'un tableau en JavaScript", pas "comment créer pierre-feuille-ciseaux en JavaScript".

Si vous n'obtenez pas de résultats de recherche utiles, lisez l'article "[Comment utiliser Google pour résoudre vos questions de programmation (eng.)](https://old.codinginflow.com/google-programming-questions)" pour des conseils sur la manière d'ajuster vos critères de recherche.

## Examiner les messages d'erreur

Les messages d'erreur sont conçus pour vous aider à identifier la source du problème. Lorsque vous rencontrez une erreur, il est important de lire le message d'erreur en entier pour comprendre la nature de l'erreur et son emplacement. Si vous ne comprenez pas le message d'erreur, copiez et collez la ligne la plus pertinente dans votre moteur de recherche préféré. Vous pouvez également utiliser la fonction de recherche sur notre serveur Discord pour voir comment d'autres personnes ont pu résoudre des problèmes similaires. Pour obtenir encore plus de conseils, lisez l'article sur [la compréhension des erreurs](#TBA).

## Triple vérification des commandes du terminal

Si vous suivez des instructions et obtenez un message d'erreur ou un résultat inattendu, suivez les conseils de débugage suivants :

1. Recommencez depuis le début et relisez toutes les instructions.
2. Comparez les instructions à votre historique de terminal pour vous assurer de ne rien avoir oublié.
3. Copiez et collez la commande exacte du terminal depuis le guide/le tutoriel/l'exercice/etc. pour éviter les fautes de frappe.
4. Utilisez la commande `pwd` pour vérifier que vous êtes dans le bon répertoire.
5. Si vous ne suivez pas d'instructions, faites des recherches pour confirmer que vous utilisez la commande correctement. Vous pouvez également rechercher le message d'erreur ou le résultat inattendu, car quelqu'un d'autre a probablement rencontré une situation similaire.

## Revoir les leçons précédentes

Il peut être utile de revoir les leçons/notions précédentes car vous avez peut-être oublié quelque chose que vous pouvez appliquer à votre tâche actuelle.

## Vérifiez les fautes de frappe

Il est important de vérifier votre code pour les fautes de frappe, car elles peuvent entraîner une grande variété de comportements étranges et de messages d'erreur. Pour vous aider à éviter les fautes de frappe, utilisez [IntelliSense de VS Code (eng.)](https://code.visualstudio.com/docs/editor/intellisense) pour automatiquement compléter les méthodes, les paramètres, les variables, etc.

## Débuguez votre code

Lorsque votre code présente un comportement inattendu, l'outil le plus important à votre disposition est un débugueur. Cela peut sembler excessif, mais examinez toutes vos variables à chaque point de votre code. Soyez sûr que votre code fait exactement ce que vous lui avez demandé de faire. Le problème réside souvent dans une mauvaise compréhension de ce que vous avez demandé à votre code de faire. Votre tâche est d'enquêter sur l'endroit où cette incompréhension se produit. Pour obtenir encore plus d'informations, consultez les [DevTools de JavaScript (fr.)](https://developer.chrome.com/docs/devtools/javascript?hl=fr).

## Lisez attentivement la documentation

Lorsque vous avez identifié que votre problème est lié à une fonction ou une méthode spécifique qui produit des résultats inattendus, prenez le temps de lire attentivement sa documentation. Il est très courant de découvrir que vous avez mal compris ce que fait la fonction/méthode, sa valeur de retour ou ses effets secondaires possibles.

## Sachez quand faire une pause

Il est temps de faire une pause lorsque vous commencez à vous sentir fatigué, frustré, dépassé, etc. À un certain point, s'obstiner peut être plus nocif que bénéfique.

De plus, il existe un phénomène très courant en programmation où de nouvelles idées et solutions vous viennent après une pause. Cela peut sembler fou (jusqu'à ce que vous l'ayez vécu), donc vous devez nous faire confiance sur ce point. Parfois, cela vous vient lorsque vous effectuez une tâche banale, comme promener votre chien, cuisiner un repas, plier du linge, etc. Parfois, cela se produit lorsque vous revenez à votre bureau et commencez à revoir le problème et votre code.

## Expliquez votre code ligne par ligne

Un dernier conseil important est d'expliquer votre code ligne par ligne, une technique éprouvée appelée "[débugage du canard en caoutchouc (fr.)](https://fr.wikipedia.org/wiki/M%C3%A9thode_du_canard_en_plastique)". Cela peut sembler ridicule, donc vous devez aussi nous faire confiance sur ce point. Lorsque vous prenez le temps d'examiner chaque ligne de code, surtout après avoir fait une pause, vous serez étonné de voir des choses que vous n'aviez pas vues auparavant !

## Conclusion

Appliquer chacun de ces conseils peut prendre un certain temps, mais avec de l'expérience, beaucoup d'entre eux deviendront des habitudes intégrées à votre processus de développement, ce qui vous fera gagner du temps à long terme. Si vous n'avez pas trouvé la source du problème après avoir travaillé sur chacun de ces conseils, il est temps de demander de l'aide à d'autres. Cependant, demander de l'aide à d'autres n'est pas aussi simple que cela puisse paraître, donc veuillez lire "[Comment poser une question technique](poser_des_questions_techniques.md)".
