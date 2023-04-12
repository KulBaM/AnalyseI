Voor $n \in \mathbb{N}$, met $n\geq 2$ noteren we met $\mathbb{Z}_n$ de verzameling van de gehele getallen modulo $n$, dus
$$\mathbb{Z}_{n} = \{\overline{0}, \overline{1}, \dots , \overline{n-1}\},$$
waarbij
$$\overline{i} = \{i + kn|k \in \mathbb{Z}\},\quad \text{met} \quad i \in \mathbb{Z}.$$
We definiëren de optelling en de vermenigvuldiging op $\mathbb{Z}_n$ door
$$\overline{i}+\overline{j} = \overline{(i+j)\mod(n)} \quad \text{en} \quad \overline{i}\cdot \overline{j} = \overline{(i \cdot j) \mod{n}},$$
waarbij $+$ en $\cdot$ in het rechterlid van bovenstaande vergelijkingen staan voor de gewone optelling en vermenigvuldiging in $\mathbb{Z}$.
Ga na of $(\mathbb{Z}_{n}, +, \cdot )$ een veld is voor $n = 3, 4, 5, 6, 7$.
Wie waagt zich aan een veralgemening?

*Bewijs:*
[[I. 1.1.3 Veld]]
Er geldt dat dit enkel een veld is als $n$ een priem getal is.
Neem aan dat $\mathbb{Z}_{n}$ een veld is, voor elke $a: 0 \leq a \leq n$, bestaat er een $b$, met $\overline{ab}=1$. Dus er bestaat er een $k$, zodat $ab + kn = 1$. Hierdoor is $\text{ggd}(a, n)=1$.
Dus $n$ moet een priemgetal zijn.
$\square$

