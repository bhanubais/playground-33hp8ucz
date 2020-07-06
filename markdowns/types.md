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
