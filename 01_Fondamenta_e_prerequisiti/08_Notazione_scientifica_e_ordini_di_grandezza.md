### Notazione scientifica e ordini di grandezza

#### 1. Notazione scientifica

* **Definizione:** rappresentazione compatta di un numero come prodotto di un coefficiente e una potenza di 10.
* **Forma $a\times10^n$:** si sceglie $1\le |a|<10$ e $n\in\mathbb{Z}$; per esempio, $53000=5{,}3\times10^4$.
* **Coefficiente e ordine di grandezza:** $a$ è il coefficiente; la potenza $10^n$ dà la scala del numero.
* **Esponente positivo, negativo e nullo:** un esponente positivo indica una potenza maggiore di 1, uno negativo una frazione, mentre $10^0=1$.
* **Conversione da forma decimale a notazione scientifica:** si sposta la virgola finché resta una sola cifra non nulla prima di essa; gli spostamenti determinano $n$.
* **Conversione da notazione scientifica a forma decimale:** si sposta la virgola di $n$ posti a destra se $n>0$ e a sinistra se $n<0$.
* **Numeri molto grandi:** hanno in genere esponente positivo, per esempio $4{,}2\times10^8$.
* **Numeri molto piccoli:** hanno in genere esponente negativo, per esempio $4{,}2\times10^{-8}$.

#### 2. Operazioni in notazione scientifica

* **Somma e sottrazione:** si portano prima i numeri alla stessa potenza di 10 e poi si sommano o sottraggono i coefficienti.
* **Moltiplicazione:** si moltiplicano i coefficienti e si sommano gli esponenti: $(a\times10^m)(b\times10^n)=ab\times10^{m+n}$.
* **Divisione:** si dividono i coefficienti e si sottraggono gli esponenti, con divisore non nullo: $(a\times10^m)/(b\times10^n)=(a/b)\times10^{m-n}$.
* **Potenze:** si eleva il coefficiente e si moltiplica l'esponente di 10: $(a\times10^m)^k=a^k\times10^{mk}$.
* **Radici:** si estrae la radice del coefficiente e si divide l'esponente per l'indice quando è possibile; altrimenti si riscrive la potenza di 10.
* **Normalizzazione del risultato:** si modifica il coefficiente e si compensa l'esponente per riportare il coefficiente nell'intervallo $1\le |a|<10$.

#### 3. Potenze di 10

* **$10^n$ con $n>0$:** vale 1 seguito da $n$ zeri, per esempio $10^3=1000$.
* **$10^0$:** vale 1.
* **$10^{-n}$:** vale $1/10^n$, per esempio $10^{-3}=0{,}001$.
* **Spostamento della virgola decimale:** moltiplicare per $10^n$ sposta la virgola di $n$ posti a destra; dividere per $10^n$ la sposta a sinistra.
* **Relazione tra esponente e numero di zeri:** per esponenti interi positivi, $10^n$ è 1 seguito da $n$ zeri; per esponenti negativi indica una frazione decimale.

#### 4. Ordine di grandezza

* **Definizione:** è la potenza di 10 più vicina al valore assoluto del numero.
* **Determinazione dell'ordine di grandezza:** scritto $x=a\times10^n$ con $1\le |a|<10$, si confronta $|a|$ con $\sqrt{10}$.
* **Arrotondamento alla potenza di 10 più vicina:** si sceglie $10^n$ se $|a|<\sqrt{10}$ e $10^{n+1}$ se $|a|\ge\sqrt{10}$.
* **Differenza tra notazione scientifica e ordine di grandezza:** la notazione scientifica conserva il coefficiente; l'ordine di grandezza dà solo una potenza di 10 approssimata.
* **Confronto tra ordini di grandezza:** a esponenti distanti di $k$, le quantità sono approssimativamente in rapporto $10^k$.
* **Stima dell'ordine di grandezza di un calcolo:** si approssimano i fattori con potenze di 10 e si combinano gli esponenti.

#### 5. Cifre significative

* **Cifre significative:** sono le cifre che indicano le cifre certe di una misura e la prima cifra incerta.
* **Zeri significativi e non significativi:** gli zeri tra cifre non nulle sono significativi; quelli iniziali no; gli zeri finali dopo la virgola sono significativi.
* **Arrotondamento:** si conserva la cifra richiesta e si aumenta di 1 se la prima cifra eliminata è almeno 5.
* **Precisione e accuratezza:** la precisione riguarda la finezza della misura; l'accuratezza indica quanto il valore misurato è vicino a quello reale.
* **Numero di cifre significative:** si conta a partire dalla prima cifra non nulla, includendo gli zeri interni e quelli finali dichiarati significativi.
* **Operazioni e cifre significative:** in prodotti e quozienti si usa, di norma, il minor numero di cifre significative dei dati; in somme e differenze si considera la posizione decimale meno precisa.

#### 6. Applicazioni

* **Conversione di unità:** si usano i fattori di conversione, spesso potenze di 10 nel sistema metrico.
* **Misure fisiche:** la notazione scientifica rende leggibili valori molto grandi o piccoli e aiuta a dichiarare la precisione.
* **Stime numeriche:** si arrotondano i dati a valori semplici per valutare rapidamente il risultato.
* **Confronto tra quantità:** gli esponenti permettono di confrontare subito numeri su scale molto diverse.
* **Calcoli con numeri estremamente grandi o piccoli:** si operano separatamente coefficienti ed esponenti, normalizzando il risultato.
* **Errori e approssimazioni:** l'errore assoluto è $|x_{mis}-x_{reale}|$; l'errore relativo è il rapporto tra errore assoluto e valore reale non nullo.
