# Crypto-DM
 
# Binôme : Lysa Derbah , Mohand Arezki Acherir.

Ce Dm a pour but  d’implanter en C, en utilisant la librairie GMP, deux tests de primalité populaires qui sont:
le test de Fermat et le test de Miller-Rabin.

1/ Fermat : dans notre programme "test-de-fermat"\n
* Il est basé sur le Petit Théoréme de Fermat\n
2/ Miller-Rabin.\n

La compilation se fait sur la ligne de commandes avec la commande : make\n
Pour tester, toujours sur la ligne de commandes, on tape : ./tp nombre réps\n
-"tp" : Le nom de l'éxecutable, qui signifie TestPrimalité.\n
-Le premier argument : nombre à tester.\n
-Le deuxième argument : nombre de répétition(facultatif).\n

3/ Square And Multiply: dans notre programme "SnM"\n
* C'est la fonction qui effectue l’exponentiation modulaire qui utilise la décomposition binaire de l’exposant.\n
-Le premier argument : un entier a.\n
-Le deuxième argument :  le module n .\n
-Le troisiéme argument : un exposant h.\n
