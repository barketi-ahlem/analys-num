
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/barketi-ahlem/analys-num/main)
# analys-num
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Requirements](#requirements)
- [TP1][TP1] si vous cliquez sur TP1 le fichier sera ouvert sur le jupyter lab .
- [TP2][TP2]
- [Introduction](#introduction)
- [dichotomie](#dichotomie)
- [point fixe](#point_fixe)
- [newton](#newton)
- [Conclusion](#conclusion)
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Requirements

* [ANACONDA For windows][ANACONDA] 
* [ANACONDA For Linux][ANACONDA]
* [Jupyter][Jup]

## Introduction
> Analytiquement on ne peut pas donner la valeur exacte de alpha.C'est pour quoi on a recours à des méthode itérative pour espérer a donner une valeur approché de alpha.
> On a 3 méthodes de recherche itératives la premiére méthode de dichotomie la deuxiéme méthode de poit fixe et la derniére la méthode de newton.
## dichotomie
> La méthode de dichotomie ou méthode de la bissection est, en mathématiques, un algorithme de recherche d'un zéro d'une fonction qui consiste à répéter des partages d'un intervalle en deux parties puis à sélectionner le sous-intervalle dans lequel existe un zéro de la fonction.
## point_fixe
> La méthode du point fixe appliquée à la résolutions d’équations non linéaires consiste à élaborer un schéma itératif, en l’occurence une suite convergente vers un point fixe x > d’une certaine application g, ce point fixe est en l’occurence la solution de l’équation f(x)=0.
## newton
> pour eviter la recherche des locales I on a un théoreme de convergence globale de la méthode de newton:
> - f continu sur a,b]
> - f(a)f(b)<0
> - f'(x) différent de zero
> - f"(x) différent de zero
> - f(x0)f"(x0)>0
> =>xn converge globalement 
> - g'(alpha)=0 => l'ordre de convergence est au moins 2(quatratique)
## Conclusion
> - la méthode de newton est plus rapide que la méthode de la dichotomie
> - la méthode de dichotomie toujours converge 
 


[ANACONDA]: https://www.anaconda.com/products/individual
[Jup]: https://jupyter.org/

[tp1]:https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2Fbarketi-ahlem%2Fanalys-num/f4d9dc2f956850e17708ecaccd83a3c6fd87bdbf?urlpath=lab%2Ftree%2FBarketi%20Ahlem.ipynb
