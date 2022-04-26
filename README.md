# Crypto-DM
 
# Binôme : Lysa Derbah , Mohand Arezki Acherir.

Ce Dm a pour but  d’implanter en C, en utilisant la librairie GMP, deux tests de primalité populaires qui sont:
le test de Fermat et le test de Miller-Rabin.

1/ Fermat : dans notre programme "test-de-fermat"
 * Il est basé sur le Petit Théoréme de Fermat

2/ Miller-Rabin.

La compilation se fait sur la ligne de commandes avec la commande : make                                                                                    
Pour tester, toujours sur la ligne de commandes, on tape : ./tp nombre réps

-"tp" : Le nom de l'éxecutable, qui signifie TestPrimalité.

-Le premier argument : nombre à tester.

-Le deuxième argument : nombre de répétition(facultatif).


3/ Square And Multiply: dans notre programme "SnM"
* C'est la fonction qui effectue l’exponentiation modulaire qui utilise la décomposition binaire de l’exposant.
-Le premier argument : un entier a.
-Le deuxième argument :  le module n .
-Le troisiéme argument : un exposant h.
