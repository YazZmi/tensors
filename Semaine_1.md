# Pitch

_La première partie du cours visera à poser les bases du fonctionnement de réseuax de neurones simples et des mécanismes d'apprentissage. On y développera aussi les notions fondamentales, comme les caractéristiques, les étiquettes, les époques, les fonctions de coût, etc._

# Jour 1

## Introduction

### Qu'appelle-t-on “intelligence Artificielle” ?

#### IA symbolique
- Systèmes à base de règles
- Programmation logique (& par contraintes)
- Modèles linguistiques
- Résolution de problèmes par démonstration logique

#### IA connexionniste
- Solutions de systèmes d‘équations
- Outils statistiques
- Modèles de signaux et de perception
- Résolution de problèmes par apprentissage, essais et erreurs

## Qu'est-ce qu‘un “réseau de neurones” ?

### Un modèle de neurone
#### Qu'est-ce qu'un neurone ?
- Métaphore biologique (& limites)

#### Le neurone comme sommateur
- Les entrées du neurone
- La valeur de sortie
- Les poids associés au différentes entrées

>Exercice : Coder un neurone à partir de l'algorithme de Wikipedia

| Ressource |
|-------------------------|
| [Neurone artificiel sur Wikipedia](https://www.wikiwand.com/en/Artificial_neuron) |


#### Notion de “fonction de seuil”
- Activation du neurone
- Notion de “fonction sigmoïde”

#### Le neurone comme solution d'une équation algébrique
- Equations linéaires

### Quels types de problèmes ?

#### Enoncé du problème
- Comment mettre en relation un résultat (attendu) avec un ensemble de signaux d'entrée ?

##### Classification
- Telle image représente-t-elle un chien, un chat, un perroquet ?

##### Prédiction
- Quelle sera la température demain, en fonction des données disponibles aujourd'hui ?

##### ?
_cf. cours de Stéphane Mallat_

#### Notion de “régression linéaire”
- Exercice : Implémentation d'un algorithme de régression linéaire
- Exercice : Prédire un événement linéairement corrélé à un autre événement _(cf. exemple des grillons sur Google)_

#### Notion d'erreur, de perte

##### Minimisation de l'erreur
- Erreur quadratique moyenne

##### La descente de gradient, une méthode itérative
- La descente de gradient consiste à partir de valeurs arbitraires et de réduire itérativement l'erreur (MSE) pour **converger** vers la solution

### Un réseau de neurones simple

#### Le modèle de réseau à une couche

##### Le perceptron

# Jour 2

# Jour 3

# Jour 4

# Jour 5

### Architectures de réseaux

#### Les limites du perceptron classique
- Le premier hiver du connexionnisme
>Le perceptron ne sait opérer des classifications que selon des hyperplans (résultat démontré par Marvin Minsky dans les années '60) > Il ne permet donc de résoudre qu'une classe très limitée de problèmes : par exemple, si deux classes de points dans un plan ne sont pas séparés par une droite, le perceptron ne saura pas les distinguer.

#### Machine learning > Deep learning
- Une révolution : la rétro-propagation du gradient
>Comment tenir compte de l'erreur d'apprentissage pour affiner le modèle sans avoir besoin de nouveaux exemples.
