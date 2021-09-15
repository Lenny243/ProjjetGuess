   

Voici mon Compte rendu

Pour commencer j'ai tout d'abord verifier les prérequis, pour que php cli et composer soit opérationel.Ensuite de la 
racine du projet j'ai tapé les commandes composer install, composer update et php.\bin\phpunit--version.
Apres cela j'ai commencé le lancement des test unitares, à la racine du projet j'ai lancé la commande
 :./bin/phpunit ce qui me disait 8test(100% sans bug), dont en échec(FAILURE) 

Pour le Chalenge 2 :

j'ai téléchargé phpstorm pour me placer dans guesswhat.Puis depuis le terminal jai tapé
./bin/phpunit ce qui m'affiche "Ther were 4 failures".Jai donc créé une constante dans CardGame32.php, afin de définir 
l'ordre entre les colors et les cards de façon croissante, j'ai ensuite rajouté une ligne de code pour définir que si 
le colors trefle est superieur à, coeur cela ferai +1 et de meme pour les cards mais inverssement. 

testCompareSameNameNoSameColor() { // TODO $card1 = new Card('As', 'Coeur'); $card2 = new Card('As', 'pique'); 
$this->assertEquals(+1, CardGame32::compare($card1,$card2)); }

En effet c'est le meme nom (name) mais pas la meme (couleure) colors. Et donc  "coeur" est superieur à "pique" donc +1. 
C'est cela qui regle les 4 faillures

Puis pour le challenge 3:

J'ai ajouté une nouvelle classe de test Cardgame32 pur créer un test.

Mes problemes rencontré:
J'ai commencé en retard car je n'avais pas de PC  et pas de disque dure externe.J'ai commncé vendredi soir et ai essayé 
de faire mon possible.De plus le fait de prendre du temps pour comprendre , m'a fait perdre enormenet de temps.