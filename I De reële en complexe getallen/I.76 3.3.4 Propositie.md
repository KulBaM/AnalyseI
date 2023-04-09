# I.76 3.3.4 Propositie

## (1) => (2)

**TODO: Verbetering afwerken**

We krijgen voor prop 3.3.4 gegeven dat
Als A een niet-leeg deel van $\mathbb{R}$ is en $x \in \mathbb{R}$ dat de volgende twee uitspraken equivalent zijn

(1) x is een ophopingspunt van A

(2) Voor alle $\delta > 0$ bevat  \] $x - \delta, x + \delta$ \[  $\cap A$ oneindig veel punten

Om (1) => (2) aan te tonen ga ik te werk met behulp van contrapositie.

Uit het gegeven weten we dat A een niet-leeg deel van $\mathbb{R}$ is, $x \in \mathbb{R}$ en verder nemen we $\neg (2)$ aan dus: 
Er bestaat een $\delta > 0$ zo dat  \] $x - \delta, x + \delta$ \[  $\cap A$ = I eindig veel punten bevat. 
We willen nu aantonen dat $\neg (1)$ of m.a.w. dat x geen ophopingspunt is van A.
Laten we zo'n $\delta_1$ nemen waarvoor dat interval I slechts eindig veel punten bevat van A.
We kunnen nu omdat A niet leeg is alle punten makkelijk nummeren, neem $a_1, \cdots, a_n$ exact die punten met $n \in \mathbb{N}_0$. 

Laten we nu een nieuwe $\delta_m$ die het minimum is van alle afstanden van $x$ tot $A_i$. 
Dus $\delta_m = min \lbrace |x - A_1|, \cdots | x - A_N| \rbrace$, dat minimum bestaat zeker gezien er maar eindig veel punten zijn.
Nu onderscheiden we twee gevallen.

Geval 1) Stel dat x één van de punten van $a_1, \ldots, a_n$ is, neem $x = a_i$.
Dan zal $\delta_m = 0$ in dit geval 
**TODO** 

Geval 2) Stel dat x geen van de punten $a_1, \ldots, a_n$ is 
Nu kunnen we ook een kleinere $\delta_2$ vinden wegens de archimedische eigenschap en we kunnen $\delta_2$ zo kiezen dat die nog steeds groter is dan 0.
Deze $\delta_2$ is er nu een waardoor x geen ophopingspunt van A kan zijn want uit definitie 3.3.3 blijkt dat x enkel een ophopingspunt van A is als voor elke $\delta > 0$ geldt dat \] $x - \delta, x + \delta$ \[  $\cap ( A \setminus \lbrace x \rbrace ) \neq \emptyset $.
Gezien we een concrete $\delta_m$ vonden waarvoor dit niet geldt (immers die verzameling is per constructie leeg) is x geen ophopingspunt van A.
Dit laatste is precies wat $\neg (1)$ zegt en we dus moesten aantonen. $\square$



## (2) => (1)

## (1) => (3)

## (3) => (1)

## (2) => (3)

## (3) => (2)
