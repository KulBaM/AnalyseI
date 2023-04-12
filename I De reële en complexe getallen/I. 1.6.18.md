Toon aan: als $I$ een interval is in $\mathbb{R}$ dat niet naar boven en niet naar onder begrensd is, dan is $I = \mathbb{R}$.

*Bewijs:*
Neem een interval $I \neq \emptyset$ en $I \subseteq \mathbb{R}$, met $I$ onbegrensd langs boven en lans onder. We nemen nu een willekeurige $x \in \mathbb{R}$. Uit het ongerijmde nu, neem dat $x \notin I$. Neem $y \in I$ (dit kan omdat $I$ niet leeg is, welke geldt omdat $I$ geen onder of bovengrens heeft), omdat $x \notin A$, zal $x \neq y$. Neem nu een willekeurige $z \in A$, als $y<x$, dan zal $z<x$ (omdat $x \notin A$, geldt dat als $x$ groter is dan 1 element van $A$, er geen ander element van $A$ kan bestaan dat groter is dan $x$ (een interval kan geen "gaten" bevatten), omdat er geen grotere elementen dan $x$ in $A$ zitten, resten er enkel nog de elementen kleiner dan $x$, deze is een strikte ongelijkheid, omdat, opnieuw, $x \notin A$ en dus $\forall a \in A: x \neq a$), dus de verzameling $A$ is naar boven begrensd. 
Dit is een tegenspraak. Als $y>x$, dan volgt via een analogue redenering dat $z>x$, en dan zou $A$ naar onder begrensd zijn. Contradictie.
Omdat onze assumptie dat $x \notin A$ fout is, en $x$ willekeurig gekozen is, is $x \in A, \forall x \in \mathbb{R}$. Dus volgt $A = \mathbb{R}$.
$\square$
-> Ik ben ergens van $I$ naar $A$ over gegaan, dit is gewoon uit stomheid, deze twee zijn natuurlijk dezelfde verzameling.

Misschien zou dit ook bewezen kunnen worden door 2 intervallen $I_{1}=]-\infty, a]$ en $I_{2} =]a,+\infty[$ te definiëren en te bewijzen dat hun unie: 1. Niet naar boven en niet naar onder begrensd is, en 2. dat hun unie gelijk is aan $\mathbb{R}$. Waarom gaat dit wel/niet?