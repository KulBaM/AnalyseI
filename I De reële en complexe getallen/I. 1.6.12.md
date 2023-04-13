Zij $A$ en $B$ niet-lege naar boven begrensde deelverzamelingen van $\mathbb{R}$. Stel $C = \{a+b|a \in A, b \in B\}$. Toon aan dat $C$ naar boven begrensd is en dat $\sup(C)= \sup(A)+\sup(B)$.

*Bewijs:*
We tonen eerst aan dat $C$ naar boven begrensd is.
Omdat $A$ en $B$ naar boven begrensd zijn, bestaat er een $\hat{a} = \sup(A)$ en een $\hat{b} = \sup(B)$. Er geldt dat voor willekeurige $a \in A$ en $b \in B$ dat $\hat{a}\geq a$ en $\hat{b} \geq b$. Er geldt ook: $a+b< \hat{a}+\hat{b} = \sup(A)+\sup(B)$. Er geldt nu, volgende uit de constructie van $C$, dat voor elke willekeurige $c \in C, c \leq \sup(A) + \sup(B)$, en dus is $C$ naar boven begrensd.
We moeten nog aantonen dat $\sup(C) = \sup(A)+\sup(B)$.
Neem $\epsilon > 0$ willekeurig, per definitie van het supremum, bestaat er een $a \in A$ en een $b \in B$, zodat $\sup(A)- \frac{\epsilon}{2} < a$ en $\sup(B)- \frac{\epsilon}{2} < b$, dan bestaat er dus een $c = a+b \in C$, zodat $\sup(A)+\sup(B)- \epsilon \leq a+b$. Deze $C$ is dus gelijk aan $\sup(C)$.
$\square$
