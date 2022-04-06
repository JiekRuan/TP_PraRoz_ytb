# TP sur la correction du site de PraRoz 

Lors de ce TP nous devons relever les erreurs présente dans le code source HTML, CSS et JS.</br>
Puis une fois toute les erreurs noté sur un Readme, nous allons procèder à la correction de celle-ci. En plus, de réaliser la responsive ainsi que le js non fonctionnelle.
 

![alt text](./asset/Capture.PNG)
## HTML

- il n'y a pas de sous dossier (asset / css / js)
- le code est non SEMANTIQUE
- absence de balises "meta" pour le viewport et l'encodage.
- le gros titre "praroz" en H2 dans une div / dans un header avec h1 
inversion entre h1 et h2 
- eviter les divs / utiliser plutot (nav, section...)
- une div avec une classe main non sémentique / plutot mettre une balise "main"
- une balise button dans une balise a.
- un formulaire mal réalisé / absence de label et de la balise form et fieldset 
- la balise``<a href="#">``Sign up ``</a>`` here``</a> </p>``  a été fermé a plusieurs reprises 
- div icons une liste de ``<a>`` non contenu dans une liste avec ``<ul>`` ``<li>``
- 2 fermeture de div qui ne ferme aucune balise(absence d'ouverture)
- accessibilité DEPLORABLE 

---

## CSS

- PAS DE RESET !
- NON RESPONSIVE!!
- utilisation de px / conseillé d'utiliser rem pour une meilleure, Cette unité peut être alors utilisée pour créer des éléments et propriétés CSS responsives  

---

## JS

- Le DOM pour charger la page js avant.
- possibiliter de déclarer les variables avec ``let`` au lieu de ``var```
- déclarer les variables au début du code pour les utiliser de maniere globale
