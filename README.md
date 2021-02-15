# FC Furious
 
bonjour
## Partie intelligence artificielle
Dans ce cas, on traité un réseau de neurone profond, c'est à dire avec plusieurs couches. On peut le representer sous cette forme :
![Reseau](img/reseau.png)
* En entrée, on rentre un état représentatif de la position des robots sous la forme d'un vecteur de dimension 4x9x9.  
* En sortie, on obtient une prédiction pour chacune des actions qui est proportionnelle à la récompense qu'on peut espérer à long terme. On choisit donc l'action pour laquelle l'espérance est la plus grande.  

Voici l'algorithme général d'apprentissage dans le cas du deep Q learning :
![Deep Q learning](img/algo.png)

Il peut être simplifié sous la forme suivante :
![Deep q simplifie](img/algo_simplifie.png)
