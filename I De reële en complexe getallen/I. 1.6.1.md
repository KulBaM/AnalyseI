Veronderstel dat $a, b, c, d \in \mathbb{R}$. Welke van de volgende eigenschappen zijn juist? Bewijs (door enkel gebruik te maken van de eigenschappen van een totaal geordend veld) of geef een tegenvoorbeeld.

![[I. 1.1.4 Totaal geordend veld]]

1. Als $a \leq b$ en $c \leq d$, dan is $a-c \leq b-d$.
*Bewijs:*
Als $a \leq b$ en $c \leq d$, dan is $a-c \leq b-d$, $b-a \geq 0$ en $c-d \geq 0$.
Dus $b-a+c-d \geq 0$. Er volgt $a-c \leq b-d$.
$\square$

2. Als $a \neq 0$, $b \neq 0$ en $a \leq b$, dan is $\frac{1}{b}\leq \frac{1}{a}$.
*Bewijs:*
We hebben $a \leq b$, vermenigvuldig beide leden met $\frac{1}{ab}$. 
Er volgt: $\frac{1}{ab}\cdot a \leq \frac{1}{ab}\cdot b \Leftrightarrow \frac{1}{b} \leq \frac{1}{b}$.
$\square$

3. Als $0 \leq a \leq b$, dan is $a^{2}\leq b^{2}$.
*Bewijs:*
Neem $b \geq a \implies b-a \geq 0 \implies (b-a) \cdot (b+a)\geq 0 \implies b^{2}-a^{2}\geq 0 \implies b^{2}\geq a^{2}$.
$\square$

4. Als $a \leq b$, dan is $ac \leq bc$.
*Bewijs:*
Dit geldt niet altijd, klopt enkel voor $c\geq 0$.
Tegenvoorbeeld: Neem $a=1, b=2, c=-1$.
$1 \leq 2 \cancel{\implies} -1 \leq -2$
$\square$
