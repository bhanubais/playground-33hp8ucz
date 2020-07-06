# Les types

Il y a plusieurs façon de classifier les langages, ici on va parler du typage.
Une variable est un identifiant qui va stocker une valeur. On l'a vu précédemment, mais en python peu importe le nom de ta variable, tu peux lui attribuer ce que tu veux.
Python est ce qu'on appel un langage avec un typage dynamique fort. En fait, quand vous créez une variable, vous n'avez pas à préciser le type.

Exemple :

```python
	a = 5
	a = "BLABLA"
```

Il va lui même déterminer le type au moment où vous lui attribuer une valeur.

En python, il y a plusieurs types:

* Les String (chaines de caractères). La variable `a` au dessus est du coup du type str (on appelle ça `String`).
* Les booleéns. C'est en fait un type pour définir le vrai et le faux. Vrai est représenté par `True` et faux par `False`. Retenez bien la majuscule, c'est parfois fourbe.
* Les int (entiers). Les nombre relatifs sont représentés dans ce type. Les nombres `3` et `-5` seront des int :)
* Nous verrons plus tard la suite :)

__attention__ : Si tu mélanges des types à travers des `+` ou `-`, python ne te laissera pas faire, donc faut être sur de ce que contient tes variables :)


# Structure de données

Maintenant que nous avons vu les types, on peut parler de structures plus complexes. C'est bien marrant de jouer avec des variables, mais souvent on utilise pas cela.

On peut retrouver des informations à travers des structures de donnée. En python, il y en a trois : les tuples, les listes et les dictionnaires.

Notez bien qu'il ne s'agit pas de type, mais de structure de donnée. Du coup, vous pouvez les imbriquer autant que vous voulez. Une liste peut contenir un tuple qui lui même contient une liste.

## Les tuples

Un tuple est une structure de donnée particulière. Voyez la comme un ensemble. En fait, on peut coller des éléments les un avec les autres.

```python
t = (0, "a")
```

Ici la variable t est un ensemble, le premier élément est un entier (0) et le deuxième est la lettre `a`.

On peut accéder aux éléments internes à travers la notation `t[indice]`.
L'indice est l'indice de l'élément dans le tuple.

__attention__: En 99.99% des langages, on commence à compter à 0 :)

Du coup, pour accéder au premier élément du tuple t:

```
t[0] => 0
t[1] => "a"
```

## Les listes

Les listes , ou tableaux, dépendant de comment vous aimez l'appeler, sont une structure capital en python.

On peut avoir une liste de liste d'entiers, ou une liste de tout et n'importe quoi. On peut avoir plusieurs types dans la même liste.

On crée une liste des crochets :

```python
liste = [] # liste vide
liste = [1, 2, 3] # liste contenant 1, 2 et 3
```

Je vous conseil énormément de lire la section Types séquentiels sur la documentation officiel [https://docs.python.org/fr/3/library/stdtypes.html#sequence-types-list-tuple-range](https://docs.python.org/fr/3/library/stdtypes.html#sequence-types-list-tuple-range).
