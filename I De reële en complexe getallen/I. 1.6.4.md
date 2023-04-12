Zij $(\mathbb{F}, +, \cdot)$ een veld. Toon de volgende eigenschappen aan:
1. Voor elke $x \in \mathbb{F}$ is $0 \cdot x = 0$. Hierin staat $0$ voor het neutraal element van de optelling.
*Bewijs:*
We weten dat $0=0$, $0$ is het neutraal element van de optelling, dus $0+0=0$. Omdat $x \in \mathbb{F}$, met $\mathbb{F}$ een veld, geldt dat $x \cdot (0+0)= x \cdot 0$. Door de distributiviteit volgt: $(x \cdot O)+(x \cdot 0) = x \cdot 0$. We trekken nu van beide leden de volgende term af: $[(x \cdot 0)+(x \cdot 0)]-(x \cdot 0) = (x \cdot 0)-(x \cdot 0)$. $-(x \cdot 0)$ is het tegengestelde van $(x \cdot 0)$, er volgt: $(x \cdot 0)+(x \cdot 0)-(x \cdot 0)=0$.
We passen deze eigenschap nog eens toe en bekomen $(x \cdot 0)=0$.
$\square$

2. Voor elke $x \in \mathbb{F}$ is $(-1)\cdot x = -x$. Hierbij staat $-1$ voor het tegengestelde van het neutraal element van de vermenigvuldiging, en $-x$ voor het tegengestelde element van $x$.
*Bewijs:*
Omdat $1 \cdot x = x$ (1 is het neutraal element van de vermenigvuldiging), tellen we nu $(-1)\cdot x=x$ toe bij beide leden: $1 \cdot x + (-1)\cdot x = x + (-1)\cdot x$.
Omdat $\mathbb{F}$ een veld is, geldt de distributiviteit: $1 \cdot x + (-1) \cdot x = x \cdot (1+ (-1))$. Dit is op zijn beurt gelijk aan: $1 \cdot x + (-1)\cdot x = 0 \cdot x$ (nu wegens voorgaand lemma) = 0.
Omdat $1 \cdot x (-1) \cdot x = 0$, is $(-1)\cdot x$. Het tegengestelde van $1 \cdot x$, en hierdoor gelijk aan $-x$.
$\square$

3. Voor alle $x, y \in \mathbb{F}$ met $x \neq 0 \neq y$ geldt dat $xy \neq 0$.
*Bewijs:*
Stel dat $x \neq 0, y \neq 0$ en $x \cdot y = 0$, we delen nu beide leden door $y$ en bekomen:
$x \cdot \frac{y}{y}=\frac{0}{y}=x=0$ (want $\frac{y}{y}=1$ en $x \cdot 1 = x$) ($\frac{0}{y}= 0$, omdat $\frac{0}{y}= 0 \cdot \frac{1}{y}$ en een nul het neutraal element van de vermenigvuldiging is). We hadden aangenomen dat $x \neq 0$ en bekomen dus een tegenspraak. 
$\square$

