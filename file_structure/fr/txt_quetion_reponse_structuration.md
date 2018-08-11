# Structuration de Fichier txt de question-réponses.
Les fichiers txt de questions-réponse sont structurés de tel sorte à contenir une à plusieurs sections de questions et de propositions de réponse.
Comment structuré une section de question et de réponses?
Apprenons par l'exemple; observons la section de question-réponse ci dessous:

```
Parmis les animaux suvant,
lequel de ces animaux vient dans l'eau?
-Le chat
-Le chien
*Le poisson
-le cheval
>Les poissons sont des animaux aquatiques qui peuplent
les mère, les océans, les rivières, les étangs et les points d'eau.
```

Par cet exemple, nous pouvons faire ressortir que:
   * Une section commence toujours par le libellé de la question, celui-ci peut s'écrire sous plusieus lignes.
    Cependant, aucun saut de ligne n'est accepté (ligne blanche correspondant à deux retours à la ligne)
   * Les propositions de réponse suivent le libellé de la question et sont disposées de sorte que:
            - Les propositions vraies sont précédées par un astérix (*)

            - Les propositions fausses sont précédées par un tiret (-)

            NB: Les propositons aussi peuvent être écrites sous plusieurs lignes (sans saut de ligne)
   * En dernière position nous avons le commentaire: il doit être précédé du symbole (>) et peut aussi s'écrire sur plusieurs lignes sans saut de ligne



C'est donc ainsi que se compose une section de question-réponses.
Cependant, un questionnaire est composé de une à plusieurs sections de question réponse. pour ce faire, il suffit de séparer chaque section de question-réponse par un saut de ligne;
c'est à dire retourné deux fois à la ligne (ceux qui à pour résultat une ligne vide).
çi dessous un exemple comportant un ensemble de deux (2) sections de question réponse. (Bien remarquer la ligne vide entre les deux sections)

```
Parmis les animaux suvants,
lequel de ces animaux vient dans l'eau?
-Le chat
-Le chien
*Le poisson
-le cheval
>Les poissons sont des animaux aquatiques qui peuplent
les mère, les océans, les rivières, les étangs et les points d'eau.

Les quels de ces animaux volent?
*Le pigeon
-Le chien
*Le corbeau
*L'aigle
>Le pigeon, le corbeau et l'aigle sont tous des oiseaux volant
```

Des questions? Des propositions? Besoin d'éclairçir? Contactez nous sur notre email: [devupdateness@gmail.com](mailto:devupdateness@gmail.com)