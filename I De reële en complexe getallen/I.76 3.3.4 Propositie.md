# I.76 3.3.4 Propositie

## (1) => (2)

We krijgen voor prop 3.3.4 gegeven dat
Als A een niet-leeg deel van $\mathbb{R}$ is en $x \in \mathbb{R}$ dat de volgende twee uitspraken equivalent zijn

(1) x is een ophopingspunt van A

(2) Voor alle $\delta > 0$ bevat  \] $x - \delta, x + \delta$ \[  $\cap A$ oneindig veel punten

Om (1) => (2) aan te tonen ga ik te werk met behulp van contrapositie.

Uit het gegeven weten we dat A een niet-leeg deel van $\mathbb{R}$ is, $x \in \mathbb{R}$ en we willen nu aantonen dat $\neg (1)$ of dus x geen ophopingspunt is van A.

Verder nemen we $\neg (2)$ aan dus: 
Er is bestaat een $\delta > 0$ zo dat  \] $x - \delta, x + \delta$ \[  $\cap A$ eindig veel punten bevat. 
Laten we zo'n $\delta_1$ nemen waarvoor dat interval slechts eindig veel punten bevat van A.
We kunnen nu omdat A niet leeg is alle punten makkelijk nummeren, neem $A_1, \cdots, A_N$ exact die punten met $N \in \mathbb{N}_0$. 

Laten we nu een nieuwe $\delta_m$ die strikte kleiner is dan het minimum van alle afstanden van $x$ tot $A_i$. 
Dus $\delta_m < min \lbrace |x - A_1|, \cdots | x - A_N| \rbrace$, dat minimum bestaat zeker gezien er maar eindig veel punten zijn en we kunnen ook een kleinere $\delta_m$ vinden wegens de archimedische eigenschap. 
Voor deze kleine $0 < \delta_m < \delta_1 $.
Deze $\delta_m$ is er nu een waardoor x geen ophopingspunt van A kan zijn want uit definitie 3.3.3 blijkt dat x enkel een ophopingspunt van A is als voor elke $\delta > 0$ geldt dat \] $x - \delta, x + \delta$ \[  $\cap ( A \ \lbrace x \rbrace ) \neq \emptyset $.
Gezien we een concrete $\delta_m$ vonden waarvoor dit niet geldt (immers die verzameling is per constructie leeg) is x geen ophopingspunt van A.
Dit laatste is precies wat $\neg (1)$ zegt en we dus moesten aantonen. $\square$

## (2) => (1)

## (1) => (3)

## (3) => (1)

## (2) => (3)

## (3) => (2)
