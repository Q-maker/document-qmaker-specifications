# How to structure a txt file to contain questions and answers.
The question-answers txt files are structured to contain one to several sections of questions and answer proposals.
How to structure a question and answer section?
Let's learn by example; see the question-answers section below:

```
Among the following animals,
which of these animals lives in the water?
-Cat
-Dog
*Fish
-horse
> Fish are aquatic animals that populate
seas, oceans, rivers, ponds and water points.
```

By this example, we can highlight that:
   * A section always begins with the wording of the question, it can be written under more than one lines.
    However, no line break is accepted (white line corresponding to two line Return)
   * The proposed answers follow the wording of the question and are arranged so that:

            -The true propositions are preceded by an asterix (*)

            -The false propositions are preceded by a dash (-)

            NB: Propositions can also be written in several lines (without line breaks)
   * In the last position we have the comment: it must be preceded by the symbol (>) and can also be written on several lines without line break



This is how a question and answer section is composed.
However, a questionnaire is composed of one to several sections of question answering. To do this, simply separate each question-answers section with a line break;
so, you have to go back twice to the line(those that result in an empty line).
Below is an example with a set of two (2) questions and answers sections. (Note the empty line between the two sections)

```
Among the following animals,
which of these animals lives in the water?
-Cat
-The dog
*Fish
-horse
> Fish are aquatic animals that populate
seas, oceans, rivers, ponds and water points.

Which of these animals are flying?
*Pigeon
-The dog
*The raven
*The Eagle
> The pigeon, the raven and the eagle are all flying birds
```

Questions? Ideas? Need to clarify? Contact us on our email: [devupdateness@gmail.com](mailto:devupdateness@gmail.com)
