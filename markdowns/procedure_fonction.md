# Procédures et fonctions

## Définitions

Une prodédure est une suite d'action qui ne renvoie rien.
Une fonction est une procédure qui renvoie quelque chose.

Je vais imaginer comme ceci :

* Si je demande à quelqu'un de faire une addition, c'est une procédure, mais si je demande le résultat en plus, c'est une fonction.

Par exemple, une procédure classique c'est d'afficher quelque chose (`print`). Elle ne renvoie pas de résultat dans ton code, mais elle fait quelque chose. Tiens, une procédure c'est quand vous demander à votre turtle de faire quelque chose.

Par exemple, une fonction classique est justement l'exemple de l'addition. On demande à calculer a+b & on veut le résultat.


La raison pour laquelle on écrit des procédures et des fonctions c'est de pouvoir couper le code en petit morceaux. On peut du coup écrire une fonction qui fait un traitement pour ne pas avoir à répéter le code. Si je veux pouvoir faire calcul suivant : `f(x) = x*x + 55`, et que je veux calculer le résultat pour 10 valeurs différentes, c'est plus simple d'avoir une fonction :).

En python, il n'y a pas de procédures (pas tapé). En fait, comme je l'ai dis plus haut, une procédure est une fonction qui ne renvoie **rien**. En python, le rien a une notation, c'est le type `None`.

Comment on peut renvoyer quelque chose ? Le mot clef return est là pour ça. Si on ne le mets pas, python va automatiquement renvoyer `None`.

Prenons l'exemple d'une addition: 

```python
def add(a, b):
  c = a + b
  return c
```

Ici on a défini une fonction, qui prends 2 arguments (a et b). Ensuite, tout ce qui est une tabulation ou plus après la ligne du mot-clef `def` est dans la fonction.

Par exemple :

```python
def add(a, b):
  c = a + b
  return c
a = 5
```

La ligne `a = 5` n'est pas dans la fonction add. Cette dernière (la fonction), calcule la somme de a et b, et la stocke dans une variable c. Ensuite, il renvoie la valeur de c grâce au return.

## Appel de fonction

Maintenat qu'on a écrit des fonctions, il faut pouvoir les utiliser. On peut appeler les fonctions en utilisant son identifiant, et des parenthèses. 

```python
input()
```

En cours, vous avez utilisé la fonction `input` pour attendre une entrée utilisateur, et du coup mettre en pause votre programme.

Dans les parenthèses, on mets les arguments. Il y a plusieurs façons:

* Soit dans l'ordre `add(5, 2)`
* Soit en précisant les variables `add(a=5, b=2)` ou `add(b=2, a=5)`

On peut tout à fait écrire des variables à la place des nombres : 

```python
a = 5
b = 8
add(a, b)  # ou add(b, a)
```
La valeur renvoyée est stockée directement après l'appel de fonction, ainsi on peut les imbriquer :

```python
add(5, add(2, 3))  # 5 + (2 + 3)
```

On peut même reccupérer le résultat à travers l'affectation classique :

```
a = 5
resultat = add(a, 5)
```

La variable résultat contient donc `10`.
