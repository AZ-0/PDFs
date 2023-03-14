# PDFs
Quelques PDFs de maths ou de cryptographie.

### CRT
Mon tout premier pdf!
Donne deux preuves du théorème des restes chinois, une algébrique et une élémentaire.
Décrit deux applications de ce théorème (une formule pour l'indicatrice d'Euler, et les attaques par morphisme).

### Goldwasser Micali
Très mauvais pdf, eg. ne contient pas de preuves.
Présentation du cryptosystème de Goldwasser-Micali, exemple d'attaque quand les nonces sont biaisés.

### Quotients et Sommandes

Ce document répond partiellement à la question de quand est-ce qu'un quotient $M/N$ d'un module s'injecte en tant que sommande de $M$, ie quand est-ce qu'il existe $A$ pour lequel $M\cong A\oplus M/N$.
Il possède trois sections; la première donne des rappels sur les sommes directe et montre les propriétés universelles de la somme et du produit.
La seconde introduit le langage des suites exactes puis donne une preuve du lemme de séparation.

Finalement, la dernière définit un module libre, montre qu'il sépare toute suite exacte courte dont il est le quotient, et utilise cette propriété pour motiver la définition de module projectif.
Deux caractérisations de la projectivité sont données, puis le document termine par la liberté des sous-modules d'un module libre sur un PID.

Très clairement le meilleur pdf jusqu'à présent.

### Pell-Fermat

Exposé pour l'uni; détermine la structure de groupe des solutions entières à l'équation de Pell-Fermat (PF) $x^2 - dy^2 = 1$.
Un point de vue géométrique est tout d'abord abordé, montrant que toute conique non-vide irréductible sur un corps algébriquement clos est rationnelle; on obtient les triplets pythagoriciens ainsi qu'une paramétrisation rationnelle des solutions sur $\mathbb Q$ de PF.
On motive "géométriquement" l'introduction de $\mathbb Z[\sqrt d]$ pour étudier PF.

La norme d'un élément est introduite, et on étudie un peu $\mathbb Z[\sqrt d]$ de manière théorique.
L'existence d'une solution entière non-triviale est démontrée, puis l'existence d'une solution $\gamma$ minimale en un certain sens.
Ce $\gamma$ est employé pour obtenir la structure du groupe des solutions entières de PF, $\mathbb Z\oplus \mathbb Z/2\mathbb Z$.

En annexe, il est montré que si $d$ est un entier possédant un facteur carré, alors $\mathbb Z[\sqrt d]$ n'est pas factoriel.

### Groupes profinis et Topologie

Donne quelques rappels sur les groupes topologiques et introduit les groupes profinis.
La dernière section démontre que si $G$ est un groupe, $(H_i)_{k\in\mathbb N}$ est une chaîne descendante de sous-groupes normaux vérifiant $\bigcap_{\mathbb N} H_i = 1$, alors la limite $L=\varprojlim G/H_i$ coïncide avec la complétion $\tilde G$ de $G$ par les suites de Cauchy, où $G$ est muni de la topologie induite par les cosets des $H_i$.

### Modules injectifs, Dualité

Rappelle quelques résultats à propos des modules injectifs et divisibles, puis définit le dual $M^*=\mathrm{Hom}(M, Q/R)$ d'un module $M$ finiment généré de torsion sur un PID.
Cette dualité est employée pour montrer la correspondance image/sous-module.
Est donnée une définition générale de foncteur dual $D:\mathfrak C\to\mathfrak C$; il est prouvé que conditionné à son existence, tout diagramme $F:J\to\mathfrak C$ admet une limite si et seulement si $DF$ admet une colimite.

### Neukirch notes

Notes de lecture du livre *Algebraic Number Theory* de Jürgen Neukirch.
Mises à jour au fur et à mesure de mon avancée dans le livre.
