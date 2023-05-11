# Voorbeeld van twee metrieken die topologisch equivalent zijn, maar verschillende Cauchyrijen hebben.
> Maar metrieken kunnen topologisch equivalent zijn maar toch verschillende Cauchyrijen hebben.

Een voorbeeld wordt [in deze math StackExchange post aangehaald](https://math.stackexchange.com/questions/3901984/examples-of-metrics-that-are-topologically-equivalent-but-have-different-cauchy).
Hieronder werk ik de details verder uit.

Neem $d(x,y) = |x-y|$ als eerste metriek en $d_{atan} = |\arctan(x) - \arctan(y)|$ als tweede metriek binnen de ruimte $\mathbb{R}$.

## $d$ is een metriek in $\mathbb{R}$
$d$ is de standaard euclidische metriek dus daarvoor weten we al dat M1,M2,M3 geldt.

## $d_{atan}$ is een metriek in $\mathbb{R}$
$d_{atan}$ moeten we eerst nagaan of dit inderdaad een metriek is.

### M1 - zerodistant
$$ \forall x,y \in \mathbb{R} : d_{atan}(x,y) = 0 = |\arctan(x) - \arctan(y)| \Rightarrow x = y$$
Gezien $\arctan(x)$ continue is op heel 

### M2 - symmetric

Geldt omdat $d$ symeterisch is:
$$d_{atan}(x,y) = |\arctan(x) - \arctan(y)| = | -\arctan(y) + \arctan(x)| = | \arctan(y) - \arctan(x)| = \d_{atan}(y,x)$$

##  M3 - $\triangle-inequality$

## $\mathcal T_d = \mathcal T_{d_{arctan}}$ (Topologische equivalentie)

### $B_{d} \subseteq B_{atan}$

Laten we $x \in \mathbb{R}$ en $r>0$ beiden willekeurig nemen. We willen nu aantonen dat er nu een $r' >0$ bestaat zo dat $B_{d}(x,r') \subseteq B_{atan}(x,r)$.

Volgens de $d_{atan}$-metriek is de open bol
```math
B_{atan}(x,r) =  \{y \in X | d(x,y) = |\arctan(x)-\arctan(y)| < r \}
```
We weten ook dat $arctan(x)$ continu is en dus dat voor elke $\epsilon > 0$ er een $\delta >0$ bestaat zo dat voor elke $x \in \mathbb{R}$ geldt dat als
$d(x,y) < \delta \Rightarrow d(\arctan(x),\arctan(y)) < \epsilon$
Wegens de definitie van continuiteit van $\arctan$ hierboven weten we dat specifieker voor onze willekeurige $r = \epsilon$ er zo een $\delta = r'$ bestaat.
Omdat we zowel $r$ als $x$ willekeurig kozen en we inderdaad een $r' = \delta$ vonden vinden we voor elke open bol $B_{atan}(x,r)$ een kleinere $B_{d}(x,\delta)$ die hier volledig in past.

### $B_{atan} \subseteq B_{d}$

## Verschilllende Cauchyrijen
