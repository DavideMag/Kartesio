# Kartesio
Kartesio è la stazione robotica a geometria cartesiana di Zetapunto. Permette attività di pick and place di un prodotto in una o molteplici posizioni di deposito.

Ci sono due strutture di programma principale: a singola posizione di deposito e a multipla posizione di deposito. Il primo caso a livello di CN è struttrato come il caso multiprodotto, ma viene abilitato solo la prima posizione di deposito, quindi i due programmi risultano molto simili sotto questo punto di vista.

A livello di interfaccia invece si trovano le distinzioni più ampie: quando deve essere prodotto un nuovo programma nel caso di programma con singola posizione di deposito si avrà una procedura guidata di programmazione, mentre nel caso di programma multiprodotto si avrà una pagina per la posizione di presa ed una per ciascun prodotto, rendendo la programmazione molto meno guidata.

Il caso ISEM invece è anomalo per due motivi fondamentali: la programmazione è molto più simile al caso multiprodotto (essendo una versione molto vecchia del programma) e l'interfaccia è in "colori Zechini".
