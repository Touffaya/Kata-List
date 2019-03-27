# Kata-List

| Nom | Langage | Durée | From scratch ? | Tests existants ? | Solution ? | Apprentissages | Cas d'utilisation (ex : recrutement n1, formation TDD02, etc) | Mises à jour nécessaires ? |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Elo Chart](EloChart/README.md) |  | < 3 hours | oui | non | non | Trouver une bonne liste de tests pour implémenter la formule |  |  |
| [Tennis Game](TennisGame/README.md) |  | < 3 hours | oui | non | non |  |  | voir repo EmilyBache pour setup ? |
| [Game Of Life](GameOfLife/README.md) |  | < 3 hours | oui | non | non |  |  |  |
| [Online Shopping](OnlineShopping/README.md) |  | < 1 day | oui | non | non |  |  |  |
| [Archi Clean](https://github.com/octo-technology/Kata-List/tree/master/ArchiClean) | Java | 3 hours | non | oui | non | Refactoring API de GameOfLife |  | Java 8 |
| [Archi Clean](https://github.com/octo-technology/Kata-List/tree/master/ArchiClean) | Php | 3 hours | non | oui | non | Refactoring API de GameOfLife |  | ? |
| [Archi Clean](https://github.com/octo-technology/Kata-List/tree/master/ArchiClean) | Python | 3 hours | non | oui | non | Refactoring API de GameOfLife |  | - |
| [Puissance 4](https://www.codewars.com/kata/connect-4) |  | > 1 jour | oui | non | à retrouver |  | TDD01 |  |
| [Kata Bank](https://github.com/sandromancuso/Bank-kata) |  | 1 day |  |  | Live code en outside-in de Sandro Mancuso |  | TDD01 |  |
| [Gilded rose](https://github.com/octo-technology/GildedRose-Refactoring-Kata) |  | 3 hours | non | oui | Live code FLA | Pose de tests de caractérisation (boîte noire) | TDD02 |  |
| [Trip service](https://github.com/octo-technology/trip-service-kata) |  | 3 hours |  |  | Live code Sandro Mancuso | Dépendances | TDD02 |  |
| [Trivia](https://github.com/octo-technology/trivia) |  | > 1 jour |  |  |  |  | TDD02 |  |
| [Mars Rover](https://github.com/octo-technology/mars-rover-starter) |  | 1 jour | oui | non | oui | Problématique d’extensibilité du code | TDD03 |  |
| [Risk Game Of Thrones](https://gitlab.com/blndr/risk) |  | > 1 jour | oui | non | non | POO, Data structures |  |  |
| [Salle de sport](https://github.com/octo-technology/salle-de-sport-java) |  | 3 hours |  |  |  |  |  |  |
| [Kuzco](https://github.com/jcraftsman/hotel-cuzco) |  | 1 jour | oui | non | oui |  |  |  |
| [kata-theater](https://github.com/emilybache/Theater-Kata) |  |  | oui | oui | non |  |  |  |
| [Transitive Dependencies](http://codekata.com/kata/kata18-transitive-dependencies/) |  |  | oui | non | non | Data structures |  |  |
| [Bowling]() |  | 3 hours |  |  | cf CTH |  |  |  |
| [CQRS and Event Sourcing Koans](https://github.com/DevLyon/mixter) |  |  |  |  |  |  |  |  |
| [Roman Numerals]() |  |  |  |  |  |  |  |  |
| [URL Bar Runner](https://v6p9d9t4.ssl.hwcdn.net/html/1005038/index.html) |  |  |  |  |  |  |  |  |

# Starters-list

| Langage | Lien |
| --- | --- |
| Java | TODO |
| Javascript | TODO |
| Python | TODO |

# Idées de contraintes

* Limite à 1 sur les niveaux d'indentations
* Pas de else
* Single return statement
* Pas de if
* Pas de switch
* Une seule méthode par classe
* Immutabilité
* Respecter la loi de Déméter
* Pas de type primitifs
* Pas de getters/setters
* Maximum deux attributs par classe
* Maximum 50 lignes de code par fichier
* Que des fonctions, pas de classe
* TCR
* Baby steps : revert toutes les 2 minutes si les tests ne sont pas verts
* Pas d'exceptions comme valeur de retour
* Pas de variables globales
* Pas de valeurs de retour
* Pas de debugger ni "printf"
* Mute ping-pong si en pair
* Pas de boucles. Récursif, map, stream
* Que des exceptions

**Sources**

* https://williamdurand.fr/2013/06/03/object-calisthenics/
* http://kata-log.rocks/constraint.html

# Contributing

Pour enrichir la liste, les règles  sont les suivantes :
* un repo = un kata dans un seul langage
* un README pour :
  * présenter le kata
  * objectif(s) pédagogique(s) du kata (pour faciliter la préparation d'une formation, d'un recrutement, etc)
  * expliquer le setup
* optionnel : une branche solution avec des pistes de résolution, un step-by-step, ou plusieurs commits pour montrer les étapes de résolution du kata, etc

# TODO

* Lister les apprentissages
* Extraire les 3 langages principaux pour les katas qui les ont déjà
* Mettre à jour les versions des katas existants si besoin (exemple : PR sur les repos existants)
* Remplir la section des starters en Java, JS, Python
* Proposer des solutions aux katas de la liste qui n'en ont pas encore
* Autre exemples d'exercices/katas : [exercism.io](exercism.io)
