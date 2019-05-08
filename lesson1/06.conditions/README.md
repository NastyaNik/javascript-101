# Traitments conditionnés

+ [MDN > opérateurs de comparaison](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators)
+ [MDN > If...Else](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
+ [JavaScript.info > opérateurs de comparaison](https://javascript.info/comparison)
+ [JavaScript.info > If...Else](https://javascript.info/comparison)

![ifs](https://pics.me.me/a-programmers-wife-sends-him-to-the-grocery-store-with-31715874.png)

## Opérateurs de comparaison
​
+ Ecrivez en ligne de code un moyen de vérifier si 2 est supérieur à 1.
+ Ecrivez en ligne de code un moyen de vérifier si 2 est inférieur à 1. 
+ Ecrivez en ligne de code un moyen de vérifier si 20 est supérieur ou égal à 10.
+ Ecrivez en ligne de code un moyen de vérifier si 10 est supérieur ou égal à 10. 
+ Ecrivez en ligne de code un moyen de vérifier si 4 n'est pas égal à 6. 
+ Ecrivez en ligne de code un moyen de vérifier si '2' est égal à 2 avec l'opérateur d'égalité stricte.
+ Ecrivez en ligne de code un moyen de vérifier si 0 n'est pas égal à '0'. 
+ Ecrivez en ligne de code un moyen de vérifier si 'hello' est égal à 'hello'.
+ Ecrivez en ligne de code un moyen de vérifier si 'hello' est égal à 'Hello'.


+ Ecrivez en ligne de code un moyen de vérifier si `5` est supérieur à `0` OU inférieur à `10`.
+ Ecrivez en ligne de code un moyen de vérifier si `10` est supérieur à `5` ET inférieur ou égal à `10`.

<!-- + Ecrivez en ligne de code un moyen de vérifier si 2 est inférieur à 5. -->
<!-- + Ecrivez en ligne de code un moyen de vérifier si 5 est inférieur ou égal à 10. -->
<!-- + Ecrivez en ligne de code un moyen de vérifier si '5' converti en nombre n'est pas égal à 5. --> 
<!-- + Ecrivez en ligne de code un moyen de vérifier si '2' est égal à 2 avec l'opérateur d'égalité simple. -->
<!-- + Ecrivez en ligne de code un moyen de vérifier si 0 n'est pas strictement égal à '0'. -->
<!-- + Ecrivez en ligne de code un moyen de vérifier si `'true'` est égal à `true`. -->

## If ... Else

Ecrivez en ligne de code un moyen de vérifier si `20` divisé par `2` est supérieur ou égal à 10 OU inférieur à 15 dans la même expression. Si vrai, loggez `'Yes'`, sinon loggez `'No'`.

<!-- ---

!!!!!!!!!!! TODO:
Check data type
Log 'C'est un boolean/une cahine de caracters, nombre'. Utiliser un operateur `typeof`. -->

---

Déclarez une variable qui contient un nombre.
Ecrivez une instruction `if ... else` pour determiner si ce nombre est pair ou impair avec l'aide de l'opérateur `%`.

---

Déclarez deux variables qui contiennent des nombres.
Ecrivez une instruction `if ... else` pour choisir le plus grand nombre entre eux. Ensuite loggez dans la console: "The greater number of NUMBER1 and NUMBER2 is BIGGEST_NUMBER".
> N'oubliez pas de changer les valeurs des variables pour tester votre solution.

<!-- !!! Write a JavaScript program that accept two integers and display the larger
Write a function named greaterNum that:
takes 2 arguments, both numbers.
returns whichever number is the greater (higher) number.
Call that function 2 times with different number pairs, and log the output to make sure it works (e.g. "The greater number of 5 and 10 is 10."). -->

---

Déclarez une variable represantant une note d'élève qui contient un nombre entre 0 et 100.
Ecrivez une instruction `if ... else if ... else` pour transformer une note numerique en lettre: A - entre 90 et 100, B entre 90 et 80, C - entre 80 et 70, D - entre 70 et 60, F - inférieur à 60. 

<!-- !!! Write a JavaScript program which compute, the average marks of the following students Then, this average is used to determine the corresponding grade.
Range	Grade
<60	F
<70	D
<80	C
<90	B
<100	A -->

---

Déclarez une variable qui contient une chaîne de caractères: 'es', 'de' ou 'en'.
Ecrivez une instruction `if ... else if ... else` pour choisir un salutation selon la langue utilisée: '¡Hola mundo!', 'Hallo, wereld!', 'Hello World'. La salutation par defaut doit être en français ('Salut le Monde!').

<!-- !!! 
Write a function named helloWorld that:
takes 1 argument, a language code (e.g. "es", "de", "en")
returns "Hello, World" for the given language, for atleast 3 languages. It should default to returning English.
Call that function for each of the supported languages and log the result to make sure it works. -->

---

Déclarez deux variables, première contient une chaîne de caractères (un nom, par exemple, 'pomme', 'orange', 'personne'), deuxième un nombre entre 1 et 100.
Ecrivez une instruction `if ... else` pour transformer le nom en pluriel si le nombre est supérieur à 1. 
Loggez le resultat dans la console.

<!-- !!!
Write a function named pluralize that:
takes 2 arguments, a noun and a number.
returns the number and pluralized form, like "5 cats" or "1 dog".
Call that function for a few different scores and log the result to make sure it works.
Bonus: Make it handle a few collective nouns like "sheep" and "geese". -->

---

Demandez à l’utilisateur de se présenter avec la méthode [prompt](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt). Si le prénom est saisi, [alert](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert) 'Nice to meet you $username ($username est le prénon saisi)!', sinon alert 'Don't be shy!'

---

Un groupe peut être publique ou privé. Un utilisateur peut accéder au contenu d’un groupe si ce groupe est publique ou si le groupe est privé mais qu’il est membre ce groupe.
​
Utilisez deux variables `isPrivate` et `isMember` pour écrire une seule condition qui vérifie si utilisateur peut accéder au contenu d’un groupe​

Testez votre solution avec les valeurs suivantes:
```js
// can see the group
let isPrivate = false;
let isMember = false;

// can't see the group
let isPrivate = true;
let isMember = false;

// can see the group
let isPrivate = true;
let isMember = true;

```

<!-- ## Vrai ou faux? -->

<!-- ![null comparisons](https://i.ibb.co/99xX5c7/comparisons.png) -->

<!-- Assignez à une variable chaque valeur suivante précédé par l'opérateur `!`. Observez comment il transforme les valeurs.
Expliquez dans un commentaire pourquoi on utilise cet opérateur.
```js
'', '0', 1, 0, undefined, null, NaN, 'Hello World', {hello: 'World'}, {}, [1, 2, 3], []
```

---

```js
let isButtonVisible = true; // can be true or false
```
Comparer `isButtonVisible` avec `false` pour vérifier si le bouton n'est pas visible. Si non visible, loggez `'Hidden'`, sinon loggez `'Visible'`.
Refactorisez votre code pour utiliser l'opérateur `!`.

---

Assignez à une variable chaque valeur suivante précédé par l'opérateur `!!`. Observez comment il transforme les valeurs.
Expliquez dans un commentaire pourquoi on utilise cet opérateur.
```js
'', '0', 1, 0, undefined, null, NaN, 'Hello World', {hello: 'World'}, {}, [1, 2, 3], []
```

--- -->

<!-- Demandez à l’utilisateur de se présenter avec la méthode [prompt](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt). Si le prénom est saisi, [alert](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert) 'Nice to meet you $username ($username est le prénon saisi)!', sinon alert 'Don't be shy!' -->
<!-- Utilisez l'opérateur `!!`. -->

<!-- ---

Testez les valeurs suivantes dans la construction `if`. Lesquelles sont TRUTHY et lesquelles sont FALSY? 
```js
'', '0', 1, 0, undefined, null, NaN, 'Hello World', {hello: 'World'}, {}, [1, 2, 3], []
// List truthy values here:
// List falsy values here:
```

Copiez collez le code de la tâche ("Demandez à l’utilisateur de se présenter...") puis refactorisez-le pour vérifier que la valeur saisie est simplement truthy/falsy. -->

## Nested if

Un utilisateur de votre site web est soit connecté, soit pas connecté. Celui qui est connecté peut avoir des statuts différents:
0 - standard user
1 - admin
2 - website owner

S'il n'est pas connecté, loggez 'Please, connect'.
Si un utilisateur est connecté, vérifiez son statut.
Si un utilisateur est un 'standard user', loggez 'Hello %username'.
Si un utilisateur est un 'admin', loggez 'Hello powerful'. 
Si un utilisateur est un 'website owner' loggez 'Hello almighty'.

## Switch

Copier coller le code de la tâche précédante puis refactorisez-le pour utiliser l'instruction [switch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)

---

Obtenez le jour de la semaine avec l'objet [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) et sa méthode `getDay`.
Utilisez l'instruction `switch` pour traduire les jours de la semaine en français. 
En JavaScript, le premier jour de la semaine est dimanche 😉.
```js
const today = new Date();
const todayDay = today.getDay();
```

---

Obtenez le mois en cours toujours avec l'objet Date.
Utilisez l'instruction `switch` avec le regroupement des cas pour dire dans quelle saison on se trouve: hiver, été ou mi-saison.

## Opérateur ternaire

Utilisez l'opérateur ternaire pour effectuer l'opération suivante:
Si l'id du client est valide, sauvegarder ces achats dans la base de données (ou juste loggez 'Saved'). Sinon loggez 'Cancel'.

--- 

Un utilisateur arrive sur votre site web. Si c'est sa première fois ici, vous devez montrer une bannière que vous utilisez cookies selon le RGPD (Règlement Général à la Protection des Données). Sinon, cachez la bannière.

```js
const isFirstTimeHere = true; // ou false
const isCookiesVisible = // use ternary operator here to assign value to isCookiesVisible variable
```

## Pour aller plus loin

Créez un calculateur de [Body Mass Index](https://fr.wikipedia.org/wiki/Indice_de_masse_corporelle).
Utilisez la méthode prompt pour récevoir les données nécessaires.
Pour calculer le BMI utilisez la formule suivante: poids / ((hauteur / 100) * (hauteur / 100)).
Ecrivez une construction `if` pour trouver le résultat:
Si l'indice est inférieur à 18.5, le résultat est 'considered underweight';
Si l'indice est égal ou supérieur à 18.5 ET égal ou inférieur à 25, le résultat est 'a healthy weight';
Si l'indice est supérieur à 25, le résultat est 'considered underweight';

Loggez le résultat: 'Your BMI is $insert_bmi_value_here. It is $insert_the_result_here. This test is not the most reliable, but if you are concerned about the result, check it with your doctor.'

## Reading List

+ [Eloquent JavaScript > Conditions](https://eloquentjavascript.net/02_program_structure.html#h_wpz5oi2dy7)
+ [You Don't Know JS > Conditions](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md#conditionals)
+ [You Don't Know JS > Operators precedence](https://github.com/getify/You-Dont-Know-JS/blob/master/types%20%26%20grammar/ch5.md#operator-precedence)

