# Como estruturar um arquivo txt para conter perguntas e respostas.
Os arquivos txt de perguntas e respostas são estruturados para conter uma a várias seções de perguntas e respostas a propostas.
Como estruturar uma seção de perguntas e respostas?
Vamos aprender pelo exemplo; veja a seção de perguntas e respostas abaixo:

```
Entre os seguintes animais,
qual destes animais vive na água?
-Gato
-Cão
*Peixe
-cavalo
>Os peixes são animais aquáticos que povoam
mares, oceanos, rios, lagoas e pontos de água.
```

Por este exemplo, podemos destacar que:
   * Uma seção sempre começa com o texto da pergunta, pode ser escrita em mais de uma linha.
     No entanto, nenhuma quebra de linha é aceita (linha branca correspondente a duas linhas Return)
   * As respostas propostas seguem o texto da pergunta e são organizadas de modo que:

            As proposições verdadeiras são precedidas por um asterisco (*)

            As falsas proposições são precedidas por um traço (-)

            NB: proposições também podem ser escritas em várias linhas (sem quebras de linha)
   * Na última posição, temos o comentário: deve ser precedido pelo símbolo (>) e também pode ser escrito em várias linhas sem quebra de linha (NB: escrever um comentário não é obrigatório)



É assim que uma seção de perguntas e respostas é composta.
No entanto, um questionário é composto de uma a várias seções de perguntas respondidas. Para fazer isso, basta separar cada seção de perguntas e respostas com uma quebra de linha;
então, você tem que voltar duas vezes para a linha (aqueles que resultam em uma linha vazia).
Abaixo está um exemplo com um conjunto de duas (2) perguntas e respostas. (Observe a linha vazia entre as duas seções)

```
Entre os seguintes animais,
qual destes animais vive na água?
-Gato
-O cachorro
*Peixe
-cavalo
>Os peixes são animais aquáticos que povoam
mares, oceanos, rios, lagoas e pontos de água.

Quais desses animais estão voando?
*Pombo
-O cachorro
*O Corvo
*A águia
>O pombo, o corvo e a águia são todos pássaros voadores
```
**Observação:**  
Mesmo que o recurso de importação suporte quase toda a codificação de arquivo de texto, se você encontrar qualquer problema de codificação, prefira usar a codificação **UTF-8** para garantir o melhor desempenho.  

Questões? Idéias? Precisa esclarecer? Entre em contato pelo e-mail: [qcmmakerapp@gmail.com] (mailto: qcmmakerapp@gmail.com)
