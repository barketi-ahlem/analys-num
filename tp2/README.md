# TP2
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Introduction](#introduction)
 - [interpolationdelagrange](#interpolationdelagrange)
 - [FormedeNewton](#FormedeNewton)
 - [conclusion](#conclusion)
  # Introduction
> En analyse numérique, les polynômes de Lagrange, du nom de Joseph-Louis Lagrange, permettent d'interpoler une série de points par un polynôme qui passe exactement par ces points appelés aussi nœuds.
> Le problème de l’approximation d’une fonction f intervient dans plusieurs situations,comme par exemple :
> 1) la fonction f(x) est connue, mais difficile a manipuler. L’approximation a pour but de remplacer f par une fonction plus simple, Π(f), qui est plus accessible pour           >    l’integration.
> 2) la fonction f(x) n’est pas connue, on ne connaˆıt que les valeurs dans certains points xi.Le but de l’approximation est alors de trouver une représentation synthétique       >   (analytique)des données experimantales.
# interpolationdelagrange
> le but de l’interpolation est de trouver une fonction Π(x), qui appartient a une certaine classe et qui prend dans les noeuds d’interpolation xi les valeurs yi.
> Soit a = x0 ≤ · · · ≤ xi ≤ · · · ≤ xn = b une division de l’intervalle [a, b], des valeurs correspondantes. Le probléme est de trouver un polynôme de degré inférieur ou égale à > m, Πm ∈ Pm, appelé polynôme d’interpolation, vérifiant Πm(xi) = yi, ∀i. Posé sous cette forme, ce probléme peut avoir un nombre infini de solutions, une seule solution ou       >   aucune. Toutefois, il y a une et une seule solution, si on cherche cette solution dans l’espace Pn (m = n).
# FormedeNewton
> La forme de Lagrange du polynôme d’interpolation n’est pas la plus commode d’un point de vue pratique. 
> D’aprés le théoréme d’existence et unicité du polynôme d’interpolation, le polynôme d’interpolation de Newton n’est rien d’autre qu’une autre forme du polynôme de
> Lagrange. L’avantage de la formule de Newton est que les différences divisées sont invariantes par rapport à la permutation des noeuds. Par consequent, pour rajouter un
> nouveau noeud xn+1, on n’a qu’à rajouter au polynˆome Πnf le terme an+1ωn+1, ce qui signifie une considerable réduction du coût numérique, par rapport à l’implémentation de la   >   formule de Lagrange.
