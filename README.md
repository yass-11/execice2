# -->Execice2

## Question 1:

Pour bien comprendre notre programme, c'est d'expliquer la logique qu'on a utiliser :
l'utilisateur entre son texte le programme doit stocker les caractéres et leur fréquence, c'est pour cela on a creer un objet ("Element.h") avec un constructeur (caractere  ,  frequence), pour qu'on stoque dans notre queue des variables de types Element. On est besoin d'une priority queue, c'est pour cela on a le header "Queue.h": dans ce header on est besoin: 
1- enqueue: on va ajouter et trier les elements de queue a la fois avec une priorité pour   l element avec le plus grand nombre d'occurrences en utilisant un getter.
2- dequeue: pour supprimer l element  avec le plus grand nombre d'occurrences du queue.
3- getHighestPriority: qui va jouer le role du peek() pour nous donner l element  avec le plus grand nombre d'occurrences. car avec priorty queue il va etre le premier element.
4- isEmpty.
Mais pour faire ça on a besoin de calculer le nombres d'occurence pour chaque element,en effet on a cree le header "Add.h":
en utilisant la boucle for et un conteur on va circuler notre texte et apres chaque boucle on va remplacer le caractere avec un zero pour ne s'ajoute pas au conteur chaque fois on repete la boucle.

## Question 2:

D'apres ce qu'on a compris, on doit pas coder les caracteres meme mais on doit coder l'index ou la position où se trouve le caractére avec une boucle for qui traverse la queue du Front jusqu'à Rear de la queue et aprés on ajoute ce code a l'element courant en ajoutant un autre constructeur au header "Element.h" et un setter.

## Question 3:

Pour traduire le message, on sera pas besoin de garder le texte d'utilisateur ou le classment du caractere, car on aura le meme resultat juste en utilisant le nombres d'occurence.On a fait une methode qui traduire en binaire en utulisant un getter et pour le reste on a une autre methode qui calcule la somme des uns et nous donne le resultat final.





