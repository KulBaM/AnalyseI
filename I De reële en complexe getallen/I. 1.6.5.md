Zij $(\mathbb{F}, +, \cdot )$ een veld. Veronderstel dat er een deel $\mathbb{P} \subseteq \mathbb{F}$ bestaat met de volgende eigenschappen:
1) $0 \in \mathbb{P}$
2) Voor alle $x, y \in \mathbb{P}$, is $x+y \in \mathbb{P}$ en $x \cdot y \in \mathbb{P}$
3) Voor alle $x \in \mathbb{F}$, met $x \neq 0$, treedt één en slechts één van de volgende eigenschappen op:
	1) $x \in \mathbb{P}$
	2) $-x \in \mathbb{P}$
Bewijs dat er een unieke orderelatie $\leq$ bestaat op $\mathbb{F}$, zo dat $(\mathbb{F}, +, \cdot, \leq)$ een totaal geordend veld is, en zodat $\mathbb{F}^{+}= \mathbb{P}$.
![[I. 1.1.4 Totaal geordend veld]]

*Bewijs:*
Uit 3 weten we dat $x$ ofwel positief of negatief is. Ook is $\mathbb{P}$ gesloten onder de optelling. Dus $y-x \in \mathbb{P}$, we definiëren $0 \leq y-x \Leftrightarrow x \leq y \Leftrightarrow x-y \leq 0$. Deze relatie voldoet aan de eigenschappen voor een totale orde relatie $\leq$.
Bijgevolg is $(\mathbb{F}, +, \cdot, \leq)$ een totaal geordend veld.
$\square$