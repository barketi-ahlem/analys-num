# TP1
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
- [Introduction](#introduction)
 - [Dichotomie](#Dichotomie)
 - [pointfixe](#pointfixe)
 - [Newton](#Newton)
 - [coclusion](#conclusion)
  # Introduction
  > Pour résoudrel'équation linéaire f(x)=0 on peut utiliser 3 méthodes itératives qui sont :
  > - la méthode de newton
  > -la méthode de point fixe
  > -la méthode de dichotomie
  > C'est méthodes se basent sur la construction d'une suite(xn) dont le but q"elle converge vers α.
  # Dichotomie
 > Considérons une fonction f continue sur un intervalle [a,b].On suppose que f admet une et une seule racine alpha dans [a,b]
 > et que f(a)f(b)<0. On note
 > c= a+b/2 le milieu de l'intervalle.
 > Si f(c)=0,c'est la racine de f et le problème est résolu.
 > Si f(c)≠0,nous regardons le signe de f(a)f(c)
      > Si f(a)f(c)<0,alors α∈]a,c[
      > Si f(c)f(c)<0,alors α∈]c,b[
# pointfixe
> Le principe de cette méthode consiste à transformer l'équation 
> f(x)=0 en une équation équivalente g(x)=x où g est une fonction auxiliaire "bien" choisie. Le point alpha est alors un point fixe de g. 
> Approcher les zéros de f revient à approcher les points fixes de g. Le choix de la fonction g est motivé par les exigences du théorème de point fixe.
> En effet, elle doit être contractante dans un voisinage I de alpha, ce qui revient à vérifier que ∣g'(x)∣<1 sur ce voisinage. 
> Dans ce cas, on construit une suite (xn)n∈ N définie par:{x0 dans un voisinage Ieα∀n≥0,xn+1=g(xn)
# Newton
> La méthode de Newton est une méthode de point fixe avec pour application g: g(x)=x−f(x)f′(x)".
> On voit clairement que rechercher un point fixe de l’application g revient à chercher une solution de l’équation
#conclusion
> Analytiquement on ne peut pas donner la valeur exacte de telle α.
> c'est pourquoi on a recours à des méthodes itératives pour espérer a donner une valeur approché de α.
