1. Voor elke $a \in \mathbb{R}^{+}\_{0}$ en $b \in \mathbb{R}$ bestaat er een $n \in \mathbb{N}$ zo dat $na > b$.
*Bewijs:*
We kunnen $na > b$ herschrijven naar $n > \frac{b}{a}$. Aangezien $a \in \mathbb{R}^{+}\_{0}$, blijft de strikte ongelijkheid behouden (zie eigenschappen van $\mathbb{R}$). We moeten nu aantonen dat $b/a$ een element van de reële getallen is. Dit kan bekomen worden doordat $\mathbb{R}$ gesloten is onder de vermenigvuldiging. De deling is vermenigvuldiging met het inverse element, welke $\mathbb{R}$ bezit, dus $\frac{b}{a}$ is een reëel getal. Noem $c = \frac{b}{a}$. We hebben nu [[I. 1.3.2 Lemma van Archimedes]].
Veronderstel dat voor deze $c$ geldt dat $c \geq n, forall n \in \mathbb{N}$. Dan zou $\mathbb{N}$ naar boven begrensd zijn, en dus volgens de supremum eigenschap een supremum bezitten.
Stel $s = \sup(\mathbb{N})$. Omdat $s$ de kleinste bovengrens is van $\mathbb{N}$, is $s-1$ geen bovengrens van $\mathbb{N}$ meer. Neem nu $k \in \mathbb{N}$, met $s-1 < k$. Dan is $s < k+1$, en $(k+1) \in \mathbb{N}$, dus is $s$  <u>geen</u> bovengrens van $\mathbb{N}$, noch de kleinste bovengrens. 
Dit is een tegenspraak.
$\square$

2. Voor elke $\epsilon \in \mathbb{R}_{0}^{+}$, bestaat er een $n \in \mathbb{N}\_{0}$ zo dat $\frac{1}{n}< \epsilon$.
*Bewijs:*
Er is hierboven bewezen dat de natuurlijke getallen niet naar boven begrensd zijn. $\frac{1}{n}<\epsilon$ kan ter verduidelijking herschreven worden naar $1< n \cdot \epsilon$. Met $\epsilon$ willekeurig klein (of groot), kan er dus steeds een $n \in \mathbb{N}$ gekozen worden groter dan het inverse element van $\epsilon$. Dit volgt uit de onbegrensdheid van $\mathbb{N}$.

3. Voor alle $x \in \mathbb{R}$ bestaat er een $m \in \mathbb{Z}$ zo dat $m-1 \leq x < m$.
*Bewijs:*
(*Uitwerking details einde bewijs uit boek*)
Stel $x < 0$. Neem hier $X = \{n \in \mathbb{N}|-x < n\}$. 
Uit het [[I. 1.3.2 Lemma van Archimedes|Lemma van Archimedes]], volgt dat $X \neq \emptyset$. Kies een getal $m$, en neem hiervoor het kleinste element van $X$. Omdat $m$ het kleinste element van $X$ is, behoort $m-1$ niet tot $X$. Dus is $m-1 \leq x$.
$\square$
