# Voorbeeld van twee metrieken die topologisch equivalent zijn, maar verschillende Cauchyrijen hebben.
> Maar metrieken kunnen topologisch equivalent zijn maar toch verschillende Cauchyrijen hebben.

Een voorbeeld wordt [in deze math StackExchange post aangehaald](https://math.stackexchange.com/questions/3901984/examples-of-metrics-that-are-topologically-equivalent-but-have-different-cauchy).
Hieronder werk ik de details verder uit.

Neem $d(x,y) = |x-y|$ als eerste metriek en $d_{atan} = |\arctan(x) - \arctan(y)|$ als tweede metriek binnen de ruimte $\mathbb{R}$.

## $d$ is een metriek in $\mathbb{R}$
$d$ is de standaard euclidische metriek dus daarvoor weten we al dat M1,M2,M3 geldt.

## $d_{atan}$ is een metriek in $\mathbb{R}$
Voor $d_{atan} = |\arctan(x) - \arctan(y)|$ moeten we eerst nog nagaan of dit inderdaad een metriek is.

### M1 - zerodistant
Gezien $\arctan(x)$ injectief is op heel $\mathbb{R}$ zal zeker
$$\forall x,y \in \mathbb{R} : d_{atan}(x,y) = 0 = |\arctan(x) - \arctan(y)| \Rightarrow x = y$$

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
*TODO* 

## Verschilllende Cauchyrijen

### De rij $(n)_n$ is gèèn Cauchyrij voor $d(x,y)$

Neem een $\epsilon >0$ willekeurig.
We kunnen nu heel eenvoudig twee elementen uit de rij nemen die verder dan $\epsilon$ van elkaar liggen.
Bvb. $x = n$ en $\lceil x+2*\epsilon \rceil$ deze liggen volgense meteriek $d$ op een afstand van $|x - x+\lceil 2\epsilon \rceil| = 2\epsilon > \epsilon$

### De rij $(n)_n$ is wèl een Cauchyrij voor $d_{atan})$
*TODO* argument finaliseren
Om aan te tonen dat $(n)_n$ een Cauchyrij is voor $d_{atan})$ moet er voor elke willekeurige $epsilon >0 $ een $n_0$ bestaan zo dat als $m, n > n_0$ dat $d_atan(x_n,x_m) < \epsilon$ 
