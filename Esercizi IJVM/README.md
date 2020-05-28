## Laboratorio di Architettura degli Elaboratori Esercizi IJVM

### Esercizio 1
Utilizzando il linguaggio assemblativo nel formato JAS visto in laboratorio, scrivere un metodo F con 3 parametri formali (chiamateli X,Y,Z) che restituisca al chiamante il numero 1 se l’AND logico tra X ed Y è uguale all’OR logico tra Y e Z ed il numero 0 altrimenti. Scrivere anche il main contenente il codice che realizzi la chiamata di tale metodo con parametri attuali X=1, Y=1, Z=1 e che scriva il risultato restituito dal metodo F in una sua variabile locale chiamata RESULT.

### Esercizio 2
Utilizzando il linguaggio assemblativo nel formato JAS visto in laboratorio, scrivere un metodo both_lt che riceva come parametri due numeri X e Y, e restituisca al chiamante il valore 1 se X ed Y sono entrambi minori di 0 e che restituisca 0 altrimenti. Scrivere anche il main contenente il codice che realizzi la chiamata di tale metodo con parametri attuali rispettivamente -1 e 1 (in notazione decimale) e che scriva il risultato restituito dal metodo in una variabile chiamata flag.

### Esercizio 3
Utilizzando il linguaggio assemblativo nel formato JAS visto in laboratorio, scrivere un metodo “restoint” che riceve come parametri due numeri positivi X e Y, e restituisce al chiamante il resto della divisione intera tra X e Y. Scrivere anche il main contenente il codice che realizzi la chiamata di tale metodo con parametri attuali rispettivamente 13 e 5 (in notazione decimale) e che scriva il risultato restituito dal metodo in una variabile chiamata result (il risultato attuale atteso è 3). Si eviti l’uso di variabili locali nel metodo.

### Esercizio 4
Utilizzando il linguaggio assemblativo nel formato JAS visto in laboratorio, scrivere un metodo ISTRIANGLE che riceve come parametri tre numeri interi positivi x,y,z e che restituisce al chiamante 1 se x,y,z possono essere i lati di un triangolo, mentre restituisce 0 in caso contrario. Si ricordi che in un triangolo ciascun lato è minore della somma degli altri due. Scrivere anche il main contenente il codice che realizzi la chiamata di tale metodo con parametri attuali 5,9,4 e che scriva il risultato restituito dal metodo in una variabile chiamata result (il risultato attuale atteso è 0). Si eviti l’uso di variabili locali nel metodo.

### Esercizio 5
Utilizzando il linguaggio assemblativo nel formato JAS visto in laboratorio, scrivere un metodo “estraibit” che riceve come parametri due numeri X e Y, e restituisce al chiamante il valore del Y-esimo bit del numero X (assumere che Y sia compreso tra 0 e 31). Scrivere anche il main contenente il codice che realizzi la chiamata di tale metodo con parametri attuali rispettivamente 7 e 2 e che scriva il risultato restituito dal metodo in una variabile chiamata result (il risultato attuale atteso è 1). Si limiti al minimo l'uso di variabili locali nel metodo. (consiglio: in IJVM non sono disponibili istruzioni di scorrimento, pertanto si costruisca con un ciclo una opportuna maschera da mettere in AND con X).
