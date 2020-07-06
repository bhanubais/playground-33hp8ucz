# Les blocs

Un bloc est une suite d'actions. En python il est défini par le niveau de tabulation.

## Les blocs conditionnels

Souvent, il faut exécuter une action ou une autre selon la valeur d'une variable.

En python, la structure des blocs conditionnels sont :

```
if [CONDITION]:
	Instructions si condition vraie
	...

ou 

if [CONDITION]:
	Instructions si condition vraie
	...
else:
	Instructions si condition fausse
```

__important__ : Notez bien l'utilisation du `:`, en python il est capital de le mettre à la fin de la première ligne du bloc :)

__note__: on va utilise la fonction print pour afficher dans le terminal :)

Petit exemple :
```python
ta_note_en_maths = 9
if ta_note_en_maths < 10:
	print("Tu as raté")
else:
	print("Félicitations")
```

# Les boucles

Souvent, on se rend compte qu'on doit effectuer plusieurs fois une même action. Il serait dommage de ré-écrire plusieurs fois le même code, c'est pour cela qu'existent les boucles.

Il y a deux types de boucles, cela dépend de si on sait quand ça s'arrête ou non.

## Boucle FOR

La boucle for est important de comprendre et de maîtriser. Elle te permet de répéter une action n fois, ou de parcourir une liste en python.

Vous l'avez utilisé dans vos cours pour répéter n fois une action, mais elle permet aussi de parcourir une liste d'élément :

```python
liste = [1, 4, 5 , 6, 0]
for element in liste:
	print(element)
```

Ci-dessus, la variable `element` va prendre à chaque tour de boucle la valeur dans la liste.


## Boucle while

La boucle while, traduite en boucle tant-que en français :), est une boucle à utiliser lorsqu'on ne sait pas combien de fois on va faire notre traitement.

Par exemple, si on attends que l'utilisateur tape le mot : "StarLight".

```python
entree_utilisateur = "NotStartLight"  # J'initialise la variable
while entree_utilisateur != "StarLight": # tant que l'entrée utilisateur n'est pas StarLight 
	entree_utilisateur = input()  # on demande à l'utilisateur de taper quelque chose
	print(entree_utilisateur)  # On affiche l'entrée utilisateur
```

Ce programme ci-dessus tourne tant que l'utilisateur n'a pas rentrer le mot demandé :).
