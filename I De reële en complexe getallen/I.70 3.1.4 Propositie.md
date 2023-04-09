# I.69 3.1.4 Propositie.md

# Propositie
Deze propositie is het spiegelbeeld van [I.69 3.1.3 Propositie.md](I.69%203.1.3%20Propositie.md) voor open verzamelingen.

## a)

Een doorsnede van gesloten verzamelingen is gesloten.

Mnemotechnisch middel: Beeld je een (oneindige) verzameling in van gesloten (met de opening naar onder opgestelde) $\cap$-vormige regenemmers. Zelfs oneindig veel emmers van die emmers zullen de Belgische nooit vangen.

🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧️🌧

$\cap {\tiny \cap} \cap {\small\cap} \cap {\Huge\cap} \cap {\small\cap} \cap {\Huge\cap} \cap \large{\cap} \cap {\tiny\cap} \cap {\small\cap} \cap  {\Large\cap} \cap {\LARGE\cap} \cap \ldots$ 

## b)

Een _eindige_ unie van gesloten verzamelingen is gesloten.

Mnemotechnisch middel: met het mnemotechnisch uit a) en onthouden dat als de operatie veranderd de al dan niet (on)eindigheids voorwaarde mee veranderd.


# Bewijs a)

Stel dat $\mathcal{G}$ een niet-lege verzameling is van gesloten verzamelingen. 
We onderscheiden nu twee gevallen:
## Geval 1) Stel dat $\emptyset \in \mathcal{G}$.
We weten dat elke doorsnede met de lege verzameling $\emptyset$ ook leeg is en we weten ook dat $\emptyset$ een gesloten verzameling is.
Hieruit volgt dat ${\large \cap} \lbrace A | A \in \mathcal{G} \rbrace = \emptyset$ en dus ook gesloten.

## Geval 2) Stel dat $\emptyset \notin \mathcal{G}$.
Nu is elke $A \in \mathcal{G}$ niet-leeg en bij aanname gesloten.
We weten dat als $A$ gesloten is dat $A^c$ per definitie open is.
We kunnen nu één v/d [wetten v/d Morgan](https://nl.wikipedia.org/wiki/Wetten_van_De_Morgan#Verband_met_andere_logica) gebruiken om iets te zeggen over
$({\large \cap} \lbrace A | A \in \mathcal{G} \rbrace)^c =  {\large \cup} \lbrace A^c | A \in \mathcal{G} \rbrace $.
Deze laatste verzameling is nu een (on)eindige unie van open verzamelingen en uit [I.69 3.1.3 Propositie.md](I.69%203.1.3%20Propositie.md) weten we dat die zeker ook open is.
Gezien $({\large \cap} \lbrace A | A \in \mathcal{G} \rbrace)^c$ open is, is ${\large \cap} \lbrace A | A \in \mathcal{G} \rbrace$ zelf gesloten en dat is wat we moesten bewijzen. 

Geval 1) en 2) samen geven dat elke doorsnede van gesloten verzamelingen gesloten is. $\square$
