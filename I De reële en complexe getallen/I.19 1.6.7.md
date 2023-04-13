1. Toon aan dat $\mathbb{Q}[\sqrt{2}]\overset{def}{=}\{a+\sqrt{2}b |a, b \in \mathbb{Q}\} \subseteq \mathbb{R}$ een totaal geordend veld is ten opzichten van de gewonen optelling, vermenigvuldiging en orde in $\mathbb{R}$.
2. Bewijs dat $\mathbb{Q}[\sqrt{2}]$ *strikt* ligt tussen $\mathbb{Q}$ en $\mathbb{R}$ ma.a.w. dat $\mathbb{Q} \subsetneq \mathbb{Q}[\sqrt{2}]\subsetneq \mathbb{R}$.
3. Voldoet $(\mathbb{Q}[\sqrt{2}], +, \cdot )$ aan de supremum eigenschap?

*Bewijs:*
We beginnen met **2**.
We zullen eerst tonen dat $\mathbb{Q}$ een strikte deelverzameling is van $\mathbb{Q}[\sqrt{2}]$. Dit wilt zeggen dat $\mathbb{Q} \subseteq \mathbb{Q}[\sqrt{2}]$ en $\mathbb{Q} \neq \mathbb{Q}[\sqrt{2}]$.
Om te tonen dat $\mathbb{Q} \subseteq \mathbb{Q}[\sqrt{2}]$, kunnen we $\mathbb{Q}[\sqrt{2}]$ verkleinen, en dan tonen dat deze deelverzameling van $\mathbb{Q}[\sqrt{2}]$ gelijk is aan $\mathbb{Q}$. We weten dat $0 \in \mathbb{Q}$, en dus dat $\{a+\sqrt{2}b |a\in \mathbb{Q}, b =0\} \subseteq \mathbb{Q}[\sqrt{2}]$. Deze verzameling staat gelijk met het volgende:
$\{a|a \in \mathbb{Q}\}$, welke uiteraard hetzelfde is als $\mathbb{Q}$. Er is dus aangetoond dat $\mathbb{Q} \subseteq \mathbb{Q}[\sqrt{2}]$, er moet nog worden aangetoond dat $\mathbb{Q} \neq \mathbb{Q}[\sqrt{2}]$. Hiervoor nemen we het element van $\mathbb{Q}[\sqrt{2}]$, met $a=0, b=1$, m.a.w. $\sqrt{2}$. Er is bewezen, in [[I. 1.6.7]], dat $\sqrt{3} \notin \mathbb{Q}$, hetzelfde bewijs kan op analoge wijze worden gebruikt om aan te tonen dat $\sqrt{2} \notin \mathbb{Q}$. Er bestaat minstens één element in $\mathbb{Q}[\sqrt{2}]$ dan niet in $\mathbb{Q}$ zit, dus volgt inderdaad dat $\mathbb{Q} \neq \mathbb{Q}[\sqrt{2}]$.
Nu moeten we tonen dat $\mathbb{Q}[\sqrt{2}] \subseteq \mathbb{R}$, en $\mathbb{Q}[\sqrt{2}] \neq \mathbb{R}$.
We weten dat $\mathbb{Q}$ dicht ligt op $\mathbb{R}$, we tonen nu nog aan dat de toevoegingen van $\mathbb{Q}[\sqrt{2}]$ op $\mathbb{Q}$, ook in $\mathbb{R}$ liggen. Al deze toevoegingen zijn de som van een rationaal getal en een irrationaal getal, dus ook element van $\mathbb{R}$. Nemen we nu een getal $a = \pi$, dan zien we dat $\pi \in \mathbb{R}$, maar niet $\pi \in \mathbb{Q}[\sqrt{2}]$.
$\square$

Nu beginnen we aan **3**.
Hoewel ons vorige argument met $x^{2}\leq \sqrt{2}$ niet meer geldig is, kunnen we simpel weg gewoon een getal kiezen. De verzameling $\{x \in \mathbb{Q}|x^{2}\leq 5\}$ is een deelverzameling van $\mathbb{Q}[\sqrt{2}]$ en is niet-leeg, en is dus naar boven begrensd, maar heeft geen supremum.
$\square$
(Bewijs is analoog aan dat er geen $p \in \mathbb{Q}$ bestaat met $p^{2}\leq 3$)

Nu zijn we aan **1**.
De verzameling $\mathbb{Q}[\sqrt{2}]$ is een deelverzameling van $\mathbb{R}$ zoals hierboven bewezen, dus gelden de eigenschappen sowieso.
$\square$