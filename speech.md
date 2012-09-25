# Title

# Global scope
 * For security reasons, an empty global scope is awesome
 * Global variables can be altered anytime by anyone and then break your app

# Variables are agoraphobic
 *
 * Scope handling is one of the most difficult things to learn in JS
 * Most notably due to its asynchronous APIs
#



Module -> C'est génial (me, myself, my job)

On ne peut pas coder toute une app sur un seul fichier
-> Gérer les dépendances de plusieurs fichiers/modules, c'est galère

Pour des questions de sécurité, on ne peut pas exposer de variables

Besoin d'une solution qui gère tout ça: les modules et les loaders.
Definition d'un module/loader
TESTING/Separation des contraintes/

Javascript -> variables ont un scope étendu jusqu'à la fonction dans laquelle ils ont été définis
Donc, plein de manière de faire des modules
-> Différents types de modules en Plain Old JS (function, IIFE, {})
Ne permettent pas de gérer les problèmes d'exposition et de gestion des dépendances
Il faut un loader
Exemples: AMD/CommonJS/ES6
===> Focus sur ES6 modules


Exemple de base
 * XHR + template

Exemple complexe -> c'est la merde sans
 * Gestion des dépendances

Complications
 * dependances cycliques
 * Transition vers modules
 * Build process

 * Passage à l'échelle
