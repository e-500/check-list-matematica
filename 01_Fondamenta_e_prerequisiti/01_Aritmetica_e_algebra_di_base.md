# Aritmetica e algebra di base

**Aritmetica**: branca della matematica che studia **numeri e operazioni fondamentali**, come somma, sottrazione, moltiplicazione e divisione.
  **Etimologia:** dal greco antico **arithmētikḗ** (ἀριθμητική), «arte del calcolo», da **arithmós** (ἀριθμός), «numero».
  **Origine storica:** è una delle forme più antiche di matematica, nata con il bisogno di contare e misurare; fu sviluppata già da **Babilonesi ed Egizi**, poi sistematizzata dai Greci e notevolmente ampliata dalla tradizione indiana e islamica.

**Algebra**: branca della matematica che studia **quantità, relazioni e operazioni attraverso simboli e strutture**.
  **Etimologia:** dall’arabo **al-jabr** («ricomposizione», «ristabilimento»), nel titolo dell’opera di **al-Khwarizmi** del IX secolo, *Kitāb al-jabr wa-l-muqābala*. Il termine indicava originariamente tecniche per risolvere equazioni.
  **Origine storica:** nasce dalla matematica islamica medievale, sviluppando però idee già presenti in matematica babilonese, greca e indiana.

## Argomenti

1. **Insiemi numerici**
	- Numeri naturali (N):  
	$\left[(0),1,2,3,\dots\right]$
	- Numeri interi (Z)  
	$\left[\dots,-2,-1,0,1,2,\dots]\right]$
	- Numeri razionali ($\mathbb{Q}$): numeri esprimibili come frazioni 
	$\left[ -\frac{1}{2}, \dots, -\frac{1}{3}, \dots, 0, \dots, \frac{1}{3}, \dots, \frac{1}{2}, \dots, 1, \dots \right]$
	- Numeri reali (R): tutti i numeri
	- Numeri irrazionali: tutti i numeri non esprimibili come frazioni
	$[\pi,\sqrt2,\dots)]$
	- Rappresentazione sulla retta reale

2. **Operazioni fondamentali**

	- Addizione $(a + b)$
	- Sottrazione $(a - b)$
	- Moltiplicazione $(a \cdot b)$
	- Divisione $(a / b)$
	- Priorità delle operazioni:  
		1. Parentesi 
		2. Potenze
		3. Moltiplicazione e divisione
		4. Somma e sottrazione
	- Proprietà delle operazioni:
		* **Commutativa:** Cambiando l'ordine degli addendi o dei fattori, il risultato non cambia. $a + b = b + a$ oppure $a \cdot b = b \cdot a$
		* **Associativa:** Sostituendo a due o più numeri la loro somma o il loro prodotto, il risultato non cambia. $(a + b) + c = a + (b + c)$
		* **Dissociativa:** Sostituendo a un numero due o più numeri la cui somma (o prodotto) sia uguale al numero stesso, il risultato non cambia. $15 + 4 \rightarrow (10 + 5) + 4$
		* **Invariantiva:** Aggiungendo o sottraendo (nella sottrazione), o moltiplicando o dividendo (nella divisione) uno stesso numero a entrambi i termini, il risultato non cambia. $(a \cdot c) \div (b \cdot c) = a \div b$
		* **Distributiva:** Moltiplicare (o dividere) una somma o una differenza per un numero equivale a moltiplicare (o dividere) ogni termine di quella somma o differenza per quel numero. $a \cdot (b + c) = a \cdot b + a \cdot c$	
			| Proprietà | Somma | Sottrazione | Moltiplicazione | Divisione |
			| :--- | :---: | :---: | :---: | :---: |
			| **Commutativa** | X | | X | |
			| **Associativa** | X | | X | |
			| **Dissociativa** | X | | X | |
			| **Invariantiva** | | X | | X |
			| **Distributiva** | | | X (rispetto a + e -) | X (a destra rispetto a + e -) |

3. **Frazioni**

	- **Frazioni proprie, improprie e apparenti:** una frazione è $a/b$, con $a,b \in \mathbb{Z}$ e $b \ne 0$.
		* **Proprie:** $|a| < |b|$; il valore assoluto della frazione è minore di 1.
		* **Improprie:** $|a| > |b|$; il valore assoluto della frazione è maggiore di 1.
		* **Apparenti:** $a$ è multiplo di $b$; la frazione equivale a un numero intero, per esempio $6/3 = 2$.
	- **Frazioni equivalenti:** rappresentano lo stesso numero; si ottengono moltiplicando o dividendo numeratore e denominatore per uno stesso numero diverso da zero, per esempio $1/2 = 2/4$.
	- **Semplificazione:** si dividono numeratore e denominatore per un loro divisore comune; è ridotta ai minimi termini quando il MCD dei valori assoluti è 1.
	- **Somma e sottrazione:** con lo stesso denominatore si sommano o sottraggono i numeratori; con denominatori diversi, si portano prima le frazioni a un denominatore comune.
	- **Moltiplicazione e divisione:** si moltiplicano numeratore per numeratore e denominatore per denominatore; per dividere, si moltiplica la prima frazione per il reciproco della seconda.
	- **Espressioni con frazioni:** si rispettano le priorità delle operazioni e si semplifica il risultato, quando possibile.

4. **Potenze**

	- **Definizione:** $a^n$ è il prodotto di $n$ fattori uguali ad $a$, per $n$ naturale positivo.
	- **Esponenti naturali, interi e razionali:** $a^0=1$ e $a^{-n}=1/a^n$ ($a\ne0$); gli esponenti frazionari definiscono le radici, per esempio $a^{1/n}=\sqrt[n]{a}$ nel dominio reale.
	- **Proprietà delle potenze:** a parità di base, $a^m a^n=a^{m+n}$ e $a^m/a^n=a^{m-n}$; inoltre $(a^m)^n=a^{mn}$ e $(ab)^n=a^n b^n$.
	- **Potenze di 10:** $10^n$ sposta la virgola di $n$ posti a destra se $n>0$ e di $|n|$ posti a sinistra se $n<0$.
	- **Notazione scientifica:** un numero si scrive $c\cdot10^n$, con $1\le |c|<10$ e $n\in\mathbb{Z}$.

5. **Radicali**

	- **Radice quadrata e $n$-esima:** $\sqrt[n]{a}$ è il numero che elevato a $n$ dà $a$; se $n$ è pari, nei reali occorre $a\ge0$.
	- **Proprietà dei radicali:** per radicandi non negativi, $\sqrt[n]{ab}=\sqrt[n]{a}\sqrt[n]{b}$; nel quoziente $\sqrt[n]{a/b}=\sqrt[n]{a}/\sqrt[n]{b}$, con $b\ne0$ e, se $n$ è pari, $b>0$.
	- **Semplificazione:** si estraggono dal radicale i fattori che sono potenze dell'indice, per esempio $\sqrt{12}=2\sqrt3$.
	- **Operazioni con radicali:** si sommano o sottraggono solo radicali simili; prodotti e quozienti si calcolano usando le proprietà dei radicali.
	- **Razionalizzazione:** si elimina il radicale dal denominatore moltiplicando per un fattore opportuno, senza cambiare il valore della frazione.

6. **Divisibilità**

	- **Multipli e divisori:** $a$ è divisibile per $b$ se $a=bk$ per qualche intero $k$; in tal caso $b$ è un divisore di $a$.
	- **Numeri primi:** interi maggiori di 1 divisibili soltanto per 1 e per se stessi.
	- **Scomposizione in fattori primi:** ogni intero maggiore di 1 si esprime come prodotto di potenze di numeri primi.
	- **Criteri di divisibilità:** regole rapide per riconoscere divisori, per esempio un intero è divisibile per 2 se termina con una cifra pari.
	- **Massimo comune divisore (MCD):** il maggiore intero positivo che divide tutti i numeri considerati.
	- **Minimo comune multiplo (mcm):** il minore intero positivo multiplo di tutti i numeri considerati.

7. **Rapporti e proporzioni**

	- **Rapporti:** il rapporto tra $a$ e $b$ è il quoziente $a/b$, con $b\ne0$.
	- **Proporzioni:** uguaglianze tra rapporti, per esempio $a:b=c:d$; se i termini sono non nulli, il prodotto dei medi è uguale a quello degli estremi.
	- **Percentuali:** una percentuale è una frazione con denominatore 100; $p\%$ di $N$ è $(p/100)N$.
	- **Proporzionalità diretta e inversa:** in quella diretta $y=kx$; in quella inversa $y=k/x$, con $k$ costante.
	- **Problemi con percentuali e proporzioni:** si individuano le grandezze note e incognite e si traduce il loro rapporto o la variazione percentuale in un'uguaglianza.

8. **Algebra simbolica**

	- **Variabili e costanti:** una variabile rappresenta un valore che può cambiare; una costante mantiene un valore fissato.
	- **Monomi:** prodotti di numeri e potenze di variabili con esponenti interi non negativi, per esempio $-3x^2y$.
	- **Polinomi:** somme algebriche finite di monomi, per esempio $x^2-3x+2$.
	- **Grado:** per un monomio è la somma degli esponenti delle variabili; per un polinomio è il massimo grado dei suoi monomi non nulli.
	- **Operazioni tra monomi e polinomi:** si riducono i termini simili; prodotti e potenze si sviluppano applicando le proprietà distributiva e delle potenze.

9. **Prodotti notevoli**

	- **Quadrato di un binomio:** $(a+b)^2=a^2+2ab+b^2$ e $(a-b)^2=a^2-2ab+b^2$.
	- **Cubo di un binomio:** $(a+b)^3=a^3+3a^2b+3ab^2+b^3$ e $(a-b)^3=a^3-3a^2b+3ab^2-b^3$.
	- **Prodotto della somma per la differenza:** $(a+b)(a-b)=a^2-b^2$.
	- **Altri prodotti notevoli fondamentali:** per esempio, $(x+a)(x+b)=x^2+(a+b)x+ab$.

10. **Scomposizione**

	- **Raccoglimento a fattor comune:** si mette in evidenza il fattore presente in tutti i termini, per esempio $ax+ay=a(x+y)$.
	- **Raccoglimento parziale:** si raggruppano i termini per raccogliere fattori comuni e ottenere un fattore binomio comune.
	- **Differenza di quadrati:** $a^2-b^2=(a-b)(a+b)$.
	- **Trinomio quadrato perfetto:** $a^2\pm2ab+b^2=(a\pm b)^2$.
	- **Somma e differenza di cubi:** $a^3+b^3=(a+b)(a^2-ab+b^2)$ e $a^3-b^3=(a-b)(a^2+ab+b^2)$.
	- **Scomposizione di polinomi:** si riscrive un polinomio come prodotto di fattori, scegliendo e combinando i metodi adatti.

11. **Frazioni algebriche**

	- **Condizioni di esistenza:** i valori che annullano un denominatore sono esclusi dal dominio.
	- **Semplificazione:** si scompongono numeratore e denominatore e si cancellano solo i fattori comuni, mantenendo le condizioni di esistenza iniziali.
	- **Operazioni:** si applicano le regole delle frazioni numeriche, considerando i denominatori comuni per somme e differenze.
	- **Espressioni con frazioni algebriche:** si determinano prima le condizioni di esistenza e poi si eseguono le operazioni rispettando le priorità.

12. **Equazioni**

	- **Principi di equivalenza:** si può aggiungere o sottrarre la stessa quantità ai due membri e moltiplicarli o dividerli per lo stesso numero non nullo.
	- **Equazioni di primo grado:** dopo aver raccolto i termini simili, si isolano l'incognita e il suo coefficiente.
	- **Equazioni fratte:** si escludono i valori che annullano i denominatori e si controllano le soluzioni nell'equazione iniziale.
	- **Equazioni con radicali:** si impongono le condizioni di esistenza e si elevano i membri a una potenza, verificando poi le soluzioni nell'equazione iniziale.
	- **Equazioni di secondo grado:** hanno forma $ax^2+bx+c=0$, con $a\ne0$.
	- **Formula risolutiva:** le soluzioni sono $x=(-b\pm\sqrt{b^2-4ac})/(2a)$.
	- **Discriminante:** $\Delta=b^2-4ac$; se è positivo ci sono due soluzioni reali, se è zero una soluzione doppia, se è negativo nessuna soluzione reale.
	- **Equazioni di grado superiore:** si risolvono, quando possibile, scomponendo in fattori o riconducendosi a equazioni più semplici.

13. **Disequazioni**

	- **Disequazioni di primo grado:** si isolano i termini con l'incognita; moltiplicando o dividendo per un numero negativo, il verso cambia.
	- **Disequazioni di secondo grado:** gli zeri del trinomio dividono la retta in intervalli, nei quali se ne studia il segno.
	- **Disequazioni fratte:** si studiano separatamente zeri di numeratore e denominatore con una tabella dei segni; gli zeri del denominatore sono esclusi.
	- **Sistemi di disequazioni:** le soluzioni sono i valori che soddisfano tutte le disequazioni, cioè l'intersezione dei rispettivi insiemi soluzione.
	- **Rappresentazione delle soluzioni:** si usano intervalli sulla retta reale, con estremi inclusi o esclusi secondo il segno di uguaglianza.

14. **Valore assoluto**

	- **Definizione:** $|x|$ è la distanza di $x$ da zero: vale $x$ se $x\ge0$ e $-x$ se $x<0$.
	- **Proprietà:** $|x|\ge0$, $|xy|=|x||y|$ e $|x+y|\le|x|+|y|$.
	- **Equazioni con valore assoluto:** $|x|=a$ non ha soluzioni se $a<0$; se $a\ge0$, equivale a $x=a$ oppure $x=-a$.
	- **Disequazioni con valore assoluto:** per $a>0$, $|x|<a$ equivale a $-a<x<a$, mentre $|x|>a$ equivale a $x<-a$ oppure $x>a$.

15. **Sistemi**

	- **Sistemi di equazioni:** si cercano le soluzioni che soddisfano contemporaneamente tutte le equazioni.
	- **Metodo di sostituzione:** si ricava un'incognita da un'equazione e la si sostituisce nelle altre.
	- **Metodo di confronto:** si esprime la stessa incognita in due equazioni e si uguagliano le espressioni ottenute.
	- **Metodo di riduzione:** si sommano o sottraggono equazioni, eventualmente moltiplicate, per eliminare un'incognita.
	- **Metodo di Cramer:** per un sistema lineare quadrato con determinante non nullo, le soluzioni si calcolano con rapporti di determinanti.
	- **Sistemi di disequazioni:** la soluzione è l'intersezione degli insiemi soluzione delle singole disequazioni.

16. **Ordine e intervalli**

	- **Disuguaglianze:** confrontano due quantità con $<, >, \le$ o $\ge$; aggiungendo lo stesso numero il verso resta, moltiplicando per un negativo si inverte.
	- **Intervalli aperti e chiusi:** $(a,b)$ esclude gli estremi; $[a,b]$ li include; parentesi diverse indicano un estremo incluso e uno escluso.
	- **Intorni:** un intorno di $a$ di raggio $r>0$ è l'intervallo $(a-r,a+r)$.
	- **Maggiore/minore, massimo/minimo:** il massimo e il minimo appartengono all'insieme; l'estremo superiore e quello inferiore sono, rispettivamente, il minimo dei maggioranti e il massimo dei minoranti.
	- **Insiemi di soluzioni:** raccolgono tutti i valori che rendono vera un'equazione o una disequazione.

17. **Proporzionalità e problemi algebrici**

	- **Problemi numerici:** si definiscono le incognite e si traducono i rapporti tra i dati in operazioni o equazioni.
	- **Problemi con percentuali:** si distingue il valore iniziale, la percentuale e il valore della variazione o del risultato.
	- **Problemi con equazioni:** si rappresenta l'incognita con una variabile e si impone l'uguaglianza descritta dal testo.
	- **Problemi con sistemi:** si usano più incognite e più relazioni quando il testo contiene condizioni simultanee.
	- **Traduzione di un problema in linguaggio matematico:** si scelgono variabili, si individuano le relazioni e si scrivono le condizioni prima di calcolare.

18. **Logica algebrica di base**

	- **Implicazione:** $P\Rightarrow Q$ significa che se $P$ è vera, allora è vera anche $Q$.
	- **Equivalenza:** $P\Leftrightarrow Q$ significa che le due proposizioni hanno lo stesso valore di verità, cioè valgono entrambe le implicazioni.
	- **Condizioni necessarie e sufficienti:** $P$ è sufficiente per $Q$ se $P\Rightarrow Q$; è necessaria se $Q\Rightarrow P$.
	- **Negazione:** la negazione di una proposizione è vera esattamente quando la proposizione è falsa.
	- **Quantificatori:** $\forall$ significa “per ogni” ed $\exists$ “esiste”; negando un quantificatore si passa da $\forall$ a $\exists$ (e viceversa) e si nega la proposizione.

19. **Elementi di teoria dei numeri**

	- **Numeri primi:** ogni intero maggiore di 1 si scompone in fattori primi in modo unico, a meno dell'ordine dei fattori.
	- **Divisibilità:** studia quando un intero è multiplo di un altro e le proprietà dei divisori.
	- **Congruenze:** $a\equiv b\pmod m$ significa che $a$ e $b$ hanno lo stesso resto nella divisione per $m$, cioè $m$ divide $a-b$.
	- **Aritmetica modulare:** calcola con i resti modulo un intero positivo, trattando numeri congruenti come equivalenti.
	- **Massimo comune divisore:** il MCD è il più grande divisore positivo comune a due o più interi, non tutti nulli.
	- **Algoritmo di Euclide:** calcola il MCD ripetendo divisioni con resto; l'ultimo resto non nullo è il MCD.

20. **Notazione e linguaggio matematico**

	- **Simboli matematici:** indicano operazioni, relazioni e insiemi; il loro significato va interpretato nel contesto e secondo convenzioni condivise.
	- **Uso delle parentesi:** rende esplicito l'ordine delle operazioni e raggruppa i termini da trattare insieme.
	- **Somme e prodotti:** $\sum_{i=1}^n a_i$ indica una somma e $\prod_{i=1}^n a_i$ un prodotto sui valori dell'indice.
	- **Notazione con indici:** $a_i$ identifica un elemento di una famiglia; l'indice specifica quale elemento si considera.
	- **Manipolazione corretta delle espressioni:** si applicano le proprietà algebriche mantenendo uguaglianze e condizioni di esistenza valide.

Questa è la **cassetta degli attrezzi**: prima di affrontare seriamente funzioni, limiti e analisi, conviene saper usare quasi automaticamente i punti **1–15**. Gli ultimi punti possono essere consolidati poco dopo.

