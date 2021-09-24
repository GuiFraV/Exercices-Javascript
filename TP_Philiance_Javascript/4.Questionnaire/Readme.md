## Consigne : Ecrire votre réponse en dessous de la question.


1. A quoi sert le Javascript ?

Javascript est un language de programmation qui est utilisé en Front et Back-end d'un site web. Cela permet de rendre un site web dynamique.

2. Quels sont les trois principaux types de données ?

Il y a les chaînes de caractères (String), les nombres et les booléens.


3. Quel est le rôle d’une variable ?

Permet de stocker une information dans une "boîte".

4. Afficher dans la console "Bonjour John" à partir de ces deux variables:

var hello = "Bonjour"
var prenom = "John"

console.log(hello+" "+prenom)


5. Incrémenter la variable score de 5.

var score = 0
console.log(score +5)

6. A quoi sert un tableau JavaScript ?

Contrairement à une variable qui stock une seule information, le tableau JS permet de stocker plusieurs informations dans une "boîte".

7. Réécrire ce code sous forme de tableau.

var prenom1 = "John"
var prenom2 = "Alex"
var prenom3 = "Tom"

var prenoms = ["John","Alex","Tom"]


8. Quelle instruction permet d’afficher "Tom" dans la console ?  

var prenoms = ["John", "Alex", "Tom"]

console.log(prenoms[2])

9. Quelle instruction est manquante pour que le code fonctionne ?

 var prenoms = ["John", "Alex", "Tom"];
...
console.log(prenoms) // affiche ["John", "Alex"]

console.log(prenoms[0]+" "+prenoms[1])

10. Quelles instructions sont manquantes pour que le code fonctionne ?

var prenoms = ["John", "Alex", "Tom"];
...
console.log(prenoms) // affiche ["John", "Laura", "Tom", "Harry"]

prenoms.push("Harry");
prenoms[1] = "Laura"
console.log(prenoms)

11. Réécrire ce code en utilisant un objet javascript.

var prenom = "John"
var nom = "Doe"
var age = 32

var User = {
    prenom : "John",
    nom : "Doe",
    age : 32
};



12. Quelle instruction permet d’afficher "Doe" dans la console ?

var contact = {
 prenom: "John",
 nom: "Doe",
 age: 32
}

console.log(contact.nom)

13. Quelle instruction permet d’ajouter une propriété nom à l’objet suivant ?

var contact = {
 prenom:"James",
}
contact.nom = "Ajout de nom"


14. Réécrire les variables suivantes sous forme d’objet ou de tableau en utilisant le plus adapté.

var fiat = "Fiat"
var bmw = "BMW"
var honda = "Honda"

var voitures = [fiat = "Fiat",bmw = "BMW",honda = "Honda"]

15. Réécrire les variables suivantes sous forme d’objet ou de tableau en utilisant le plus adapté.

var pays = "France"
var capitale = "Paris"
var continent = "Europe"

var géographie = {
    pays : "France",
    capitale : "Paris",
    continent : "Europe",
}















