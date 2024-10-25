# 1. Les Ensembles (Sets)

Les **ensembles** sont l'une des bases fondamentales des mathématiques et constituent une notion clé pour décrire des collections d'objets. Un ensemble est simplement un groupe d'éléments distincts, qui peuvent être des nombres, des points, ou même des concepts abstraits. En mécanique et en robotique, les ensembles permettent de regrouper des informations utiles, comme un ensemble de points dans l’espace ou des ensembles de paramètres spécifiques.

!!! quote inline end "In english please !"
    **Set**: a collection of distinct objects or elements.

## 1.1 Notation et Symboles des Ensembles

Les ensembles sont généralement notés avec des lettres majuscules, comme \( A \), \( B \), ou \( S \). Les éléments d’un ensemble sont placés entre accolades `{ }`, et on les sépare par des virgules. Par exemple, si l’on veut décrire l’ensemble des trois premiers nombres naturels, on peut écrire :
\[
A = \{1, 2, 3\}
\]

Dans ce cas, **1**, **2**, et **3** sont des éléments de l’ensemble **A**.

!!! quote inline end "In english please !"
    **Element**: an individual object within a set, often represented with the symbol **∈** to indicate "belongs to."

Si un élément appartient à un ensemble, on utilise le symbole **∈**. Par exemple, pour exprimer que **1** est dans **A**, on écrit :
\[
1 \in A
\]

## 1.2 Types d’Ensembles

Il existe différents types d’ensembles qui seront utiles à connaître pour vos travaux en mécanique et robotique.

- **Ensemble vide** \( \emptyset \) : Un ensemble qui ne contient aucun élément. Par exemple, l’ensemble des solutions d’une équation sans solution.
- **Ensemble fini** : Un ensemble avec un nombre limité d’éléments, comme \( B = \{a, b, c\} \).
- **Ensemble infini** : Un ensemble avec un nombre illimité d’éléments, comme l’ensemble des nombres naturels \( N = \{1, 2, 3, \dots\} \).

!!! quote inline end "In english please !"
    **Empty set**: a set with no elements, often represented by **∅** or **{}**.

## 1.3 Opérations sur les Ensembles

Les ensembles permettent de réaliser plusieurs opérations qui nous seront utiles dans des situations pratiques, en particulier pour organiser et manipuler les données.

1. **Union** \( A \cup B \) : L’union de deux ensembles \( A \) et \( B \) est l’ensemble de tous les éléments présents dans **A** ou dans **B** (ou dans les deux). Par exemple, si \( A = \{1, 2\} \) et \( B = \{2, 3\} \), alors :
   \[
   A \cup B = \{1, 2, 3\}
   \]

2. **Intersection** \( A \cap B \) : L’intersection de deux ensembles \( A \) et \( B \) est l’ensemble de tous les éléments présents à la fois dans **A** et dans **B**. Par exemple, avec \( A = \{1, 2\} \) et \( B = \{2, 3\} \), on obtient :
   \[
   A \cap B = \{2\}
   \]

3. **Différence** \( A \setminus B \) : La différence entre deux ensembles **A** et **B** est l’ensemble des éléments qui sont dans **A** mais pas dans **B**. Par exemple, avec \( A = \{1, 2\} \) et \( B = \{2, 3\} \), on a :
   \[
   A \setminus B = \{1\}
   \]

!!! quote inline end "In english please !"
    **Union**: the set of all elements in either or both sets, represented as **A ∪ B**.

## 1.4 Exercice Pratique

Essayez de répondre aux questions suivantes pour pratiquer l’utilisation des ensembles :

1. Soit \( C = \{4, 5, 6\} \) et \( D = \{5, 6, 7\} \). Quelle est l’union de \( C \) et \( D \) ?
2. Quelle est l’intersection de \( C \) et \( D \) ?
3. Quelle est la différence entre \( C \) et \( D \) (c’est-à-dire, \( C \setminus D \)) ?

Ces exercices permettent de consolider la compréhension des opérations de base sur les ensembles, qui sont des outils essentiels pour organiser et analyser des données dans des projets de mécanique et robotique.
