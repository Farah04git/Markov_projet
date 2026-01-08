##### Probabilité
La probabilité mesure *la chance qu’un événement se produise*. 
- Elle est toujours comprise entre 0 (**impossible**) et 1 (**certain**)

|             |                                                                                  |
| ----------- | -------------------------------------------------------------------------------- |
| probabilité | prédit ce qui pourrait arriver dans le futur, avec un certain degré de certitude |
| statistique | décrit ce qui s’est passé dans un ensemble limité                                |
- les probas peuvent se baser sur des statistiques
##### Expérience aléatoire
Une expérience aléatoire est un événement dont *le résultat dépend du hasard*.

> Exemple : lancement d'un dé
- résultat entre 1 et 6
- Si le dé est correct (pas pipé), chaque face a la même chance : 1/6
- La somme de toutes les probabilités = 1
##### Probabilité conditionnelle
La chance qu’un événement se produise *dépend d’un autre événement déjà arrivé*.

![[probas conditionnelles.png]]
##### Séquences et dépendances
Dans la langue ou la musique, les éléments ne tombent pas au hasard.
- Exemple : la probabilité qu’un mot apparaisse dépend souvent du mot précédent.
Pour modéliser ces séquences, on utilise les **chaînes de Markov**.
##### Chaînes de Markov
Une **chaîne de Markov** est un modèle qui permet de *prévoir la prochaine étape d’une séquence* en se basant uniquement sur l’état actuel, ou sur quelques états précédents si la chaîne est d’ordre supérieur.

- On évolue pas à pas dans le temps, c’est ce qu’on appelle un **temps discret** : on regarde chaque étape l’une après l’autre.
- L’état suivant dépend seulement de l’état présent, ou des **n derniers états**, selon l’**ordre de la chaîne** :
    - **Ordre 1** : le futur dépend uniquement du dernier mot ou caractère.
    - **Ordre 2** : le futur dépend des deux derniers mots ou caractères.

