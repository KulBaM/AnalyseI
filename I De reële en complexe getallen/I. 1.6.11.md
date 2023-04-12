Zij $A$ en $B$ twee niet-lege delen van $\mathbb{R}$. We veronderstellen dat $A$ en $B$ respectievelijk naar boven en naar onder begrensd zijn. Zijn de volgende uitspraken dan waar?
1. $\sup(A)\geq \inf(B) \implies \exists a \in A, \exists b \in B: a \geq b$.
2. $\sup(A)>\inf(B)\implies \exists a \in A, \exists b \in B:a>b$.

*Bewijs:*
We bewijzen dit met contradictie.
Stel dat er geen $a \in A, b \in B$, met $a < b$ zijn, er volgt dan dat $a \geq b$, voor alle $a \in A, b \in B$. In dit geval is $a$ een bovengrens voor $B$, zo dat $a \geq \sup(B)$. Omdat $a \leq \sup(A)$ (aangezien $\sup(A)$ een bovengrens is voor $A$ en $a \in A$), bekomen we nu $\sup(B)\leq \inf(A)$, dit is een tegenspraak.
$\square$

*Alternatief bewijs:*
Neem $\epsilon = \sup(A)-\inf(B)$. Per definitie van het supremum, bestaat er een $a \in [\inf(B),\inf(B)+ \frac{\epsilon}{2}[$ en bestaat er ook een $a \in ]\sup(A)- \frac{\epsilon}{2}, \sup(A)]$. Per constructie is dus $b<a$, en hiermee is de stelling bewezen.
$\square$
