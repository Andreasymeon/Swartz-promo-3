# Simple Exercice sur AJAX

## Bon, on va encre faire plus simple pour commencer.

Après avoir parcouru hier les différents usages d’Ajax ( Pas seulement nettoyer ), nous allons faire un exemple simple, du point de vous tant fonctionnel que du code.

1. Reprenez votre site cinema.
2. Ajouter à votre formulaire de connexion un bouton annuler à côté du bouton envoyer.

3. Créer un login et un mot de passe, et le mettre dans un tableau. Ceux-ci vont vous permettre de simuler une connexion.

**_Donc, avant que le client de votre site puisse louer ou acheter un film, il  doit se connecter.
Donc une fois connexion faite, il ne doit pas quitter la page au risque de perdre ses achats.
Et donc c’est là qu’Ajax intervient: que le client puisse se connecter sans rafraichir la page._**

## L’utilisateur remplit le formulaire puis valide. 
* L’application interroge alors le serveur sans demander une nouvelle page.
* Si le serveur est lent, (simuler un serveur lent en utilisant la fonction php **SLEEP()**), il faut alors l’avertir visuellement que la requête est en cours de traitement, de même qu’il faudra l’avertir quand elle sera terminée.
* Un moyen simple pour faire cela, c’est de changer l’apparence du bouton de login en remplaçant le texte par une image animée suggérant le chargement. 
* Il faut donner à l’utilisateur la possibilité d’annuler la requête, c’est pour cela que je vous ai demandé de créer un bouton annuler.

# Attention:
Le bouton est inactif tant qu’on n’a pas encore cliqué sur le bouton login. Il devient actif lorsque la requête est envoyée pour permettre à l’utilisateur d’annuler la requête.

Si l’utilisateur annule la requête, le bouton LOGIN affiche à nouveau le texte initial, et le bouton Annuler est désactivé.

Pour terminer, si l’utilisateur a saisi les bons login et mot de passe, l’application l’en avertit qu’il peut continuer à faire ses achats, dans le cas contraire, elle affiche un message d’erreur. 

**ATTENTION**, bien que simple, il va falloir mettre en place plusieurs briques AJAX pour que cela fonctionne. L'écriture côté serveur est en PHP.

Courage.

