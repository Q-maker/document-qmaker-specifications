# Structuration de fichier txt de question-réponses.
Les fichiers txt de questions-réponses sont structurés de tel sorte à contenir une à plusieurs sections de questions et de propositions de réponses.
Comment structurer une section de question et de réponses?
Apprenons par l'exemple; observons la section de question-réponses ci dessous:

```
Parmis les animaux suivant,
lequel de ces animaux vit dans l'eau?
-Le chat
-Le chien
*Le poisson
-le cheval
>Les poissons sont des animaux aquatiques qui peuplent
les mers, les océans, les rivières, les étangs et les points d'eau.
```

Par cet exemple, nous pouvons faire ressortir que:
   * Une section commence toujours par le libellé de la question, celui-ci peut s'écrire sous plusieus lignes.
    Cependant, aucun saut de ligne n'est accepté (ligne blanche correspondant à deux retours à la ligne)
   * Les propositions de réponses s'écrivent juste en dessous du libellé de la question et sont disposées de sorte que:

            - Les propositions vraies; sont précédées par un astérix (*)

            - Les propositions fausses; sont précédées par un tiret (-)

            NB: Les propositons aussi peuvent être écrites sous plusieurs lignes (sans saut de ligne)
   * En dernière position nous avons le commentaire: il doit être précédé du symbole (>) et peut aussi s'écrire sur plusieurs lignes sans saut de ligne



C'est ainsi que se compose une section de question-réponses.
Cependant, un questionnaire est composé de une à plusieurs sections de question-réponses. Pour ce faire, il suffit de séparer chaque section de question-réponses par un saut de ligne;
c'est à dire retourner deux fois à la ligne (ceux qui à pour résultat une ligne vide).
Çi dessous un exemple comportant un ensemble de deux (2) sections de question-réponses. (Bien remarquer la ligne vide entre les deux sections)

```
Parmis les animaux suivants,
lequel de ces animaux vit dans l'eau?
-Le chat
-Le chien
*Le poisson
-le cheval
>Les poissons sont des animaux aquatiques qui peuplent
les mers, les océans, les rivières, les étangs et les points d'eau.

Les quels de ces animaux volent?
*Le pigeon
-Le chien
*Le corbeau
*L'aigle
>Le pigeon, le corbeau et l'aigle sont tous des oiseaux volant
```

Des questions? Des propositions? Besoin de détails? Contactez nous sur notre email: [devupdateness@gmail.com](mailto:devupdateness@gmail.com)