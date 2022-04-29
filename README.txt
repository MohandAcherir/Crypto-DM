Ce Dm a pour but d’implanter en C, en utilisant la librairie GMP, deux tests de primalité populaires qui sont: le test de Fermat et le test de Miller-Rabin.

1/ Fermat : dans notre programme "test-de-fermat"

Il est basé sur le Petit Théoréme de Fermat
2/ Miller-Rabin:

Le test de Miller-Rabin est lui aussi basé sur le Petit Théoréme de Fermat.
Si pour un nombre entier n, a^t ≡ 1 mod n, alors l’algorithme conclue que n est
probablement premier et termine. Si aucune de ces équations n’est vérifiée, alors l’algorithme renvoie que
n est composé.


3/ Square And Multiply: dans notre programme "SnM"

C'est la fonction qui effectue l’exponentiation modulaire qui utilise la décomposition binaire de l’exposant. -Le premier argument : un entier a. -Le deuxième argument : le module n . -Le troisiéme argument : un exposant h.
4/ main :

La compilation se fait sur la ligne de commandes avec la commande : make
Pour tester, toujours sur la ligne de commandes, on tape : ./tp n k

-"tp" : Le nom de l'éxecutable, qui signifie TestPrimalité.

-Le premier argument n : nombre à tester.

-Le deuxième argument k : nombre de répétition(facultatif, n-1 par défaut). Mais il voudrait mieux le mettre quand le nombre à tester est trop grand.
