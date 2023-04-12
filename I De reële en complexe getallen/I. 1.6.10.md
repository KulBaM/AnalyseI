Veronderstel dat $A$ en $B$ niet-lege naar boven begrensde deelverzamelingen van $\mathbb{R}$ zijn. Toon aan dat $\max\{\sup(A), \sup(B)\}=\sup(A \cup B)$.

*Bewijs:*
We weten dat elke niet-lege, naar boven begrensde verzameling een supremum heeft. We tonen twee ongelijkheden aan.
Neem een willekeurige $x \in A \cup B \implies x \in A \wedge x \in B$. Dit impliceert dat $x \leq \sup(A)$ en $x \leq \sup(B)$, dus volgt er $x \leq \max\{\sup(A), \sup(B)\}$ en dus geldt per definitie: $\sup(A \cup B) \leq \max\{\sup(A), \sup(B)\}$.
Voor elke $a \in A$, geldt $a \in A \cup B$, voor analoge reden als hiervoor, is $\sup(A)\leq \sup(A \cup B)$. En volgens de symmetrie, $\sup(B) \leq \sup(A \cup B)$.
Er geldt dus: $\max\{\sup(A),\sup(B)\} \leq \sup(A \cup B)$. Twee ongelijkheden dus de gelijkheid is aangetoond.
$\square$
