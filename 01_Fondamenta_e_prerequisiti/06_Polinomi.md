### Polinomi

#### 1. Concetti fondamentali

* **Definizione di polinomio:** somma finita di monomi con coefficienti in un insieme numerico, per esempio $P(x)=2x^2-3x+1$.
* **Monomi e coefficienti:** ogni termine è un monomio; il coefficiente è il fattore numerico che moltiplica le variabili.
* **Variabili e termini:** le variabili sono simboli che possono assumere valori; i termini sono i monomi che compongono il polinomio.
* **Grado di un monomio:** è la somma degli esponenti delle variabili, per esempio il grado di $3x^2y$ è 3.
* **Grado di un polinomio:** è il massimo grado dei suoi monomi con coefficiente non nullo.
* **Termine noto:** è il termine senza variabili; in una variabile coincide con $P(0)$.
* **Coefficiente dominante:** è il coefficiente del termine di grado massimo, dopo aver ordinato il polinomio.
* **Polinomi ordinati e completi:** un polinomio è ordinato se i termini sono disposti per grado; è completo se contiene tutti i gradi dal massimo fino al termine noto.
* **Polinomio nullo:** ha tutti i coefficienti uguali a zero; il suo grado non è definito.
* **Polinomi omogenei:** tutti i monomi non nulli hanno lo stesso grado.

#### 2. Classificazione

* **Monomio:** polinomio formato da un solo termine, come $4x^2$.
* **Binomio:** polinomio formato da due termini non simili, come $x+1$.
* **Trinomio:** polinomio formato da tre termini, come $x^2+2x+1$.
* **Polinomio con più termini:** somma algebrica di quattro o più monomi.
* **Polinomi di primo, secondo, terzo grado, ecc.:** il nome indica il grado massimo, per esempio $x^2+1$ è di secondo grado.

#### 3. Operazioni

* **Somma di polinomi:** si sommano i coefficienti dei termini simili.
* **Sottrazione di polinomi:** si somma l'opposto del secondo polinomio, cambiando il segno di ogni suo termine.
* **Moltiplicazione di polinomi:** si applica la proprietà distributiva e poi si riducono i termini simili.
* **Prodotto di un monomio per un polinomio:** si moltiplica il monomio per ogni termine del polinomio.
* **Prodotto tra polinomi:** ciascun termine del primo fattore si moltiplica per ciascun termine del secondo.
* **Potenze di polinomi:** si moltiplica il polinomio per se stesso tante volte quanto indica l'esponente; si possono usare i prodotti notevoli quando la forma lo permette.
* **Divisione tra polinomi:** si cercano quoziente e resto tali che $P=DQ+R$, con $D\ne0$ e, se $R\ne0$, $\deg R<\deg D$.

#### 4. Divisione tra polinomi

* **Algoritmo della divisione:** determina quoziente $Q$ e resto $R$ in modo che $P=DQ+R$ e il grado del resto sia minore di quello del divisore.
* **Dividendo, divisore, quoziente e resto:** nella relazione $P=DQ+R$, $P$ è il dividendo, $D$ il divisore, $Q$ il quoziente e $R$ il resto.
* **Divisione per un monomio:** si dividono coefficienti e potenze termine per termine; il quoziente è un polinomio se ogni termine è divisibile.
* **Divisione per un binomio:** si applica l'algoritmo generale; se il binomio è $x-a$, il resto è $P(a)$.
* **Divisione sintetica o regola di Ruffini:** procedura abbreviata per dividere un polinomio per un binomio della forma $x-a$.

#### 5. Prodotti notevoli

* **Quadrato di un binomio:** $(a\pm b)^2=a^2\pm2ab+b^2$.
* **Cubo di un binomio:** $(a+b)^3=a^3+3a^2b+3ab^2+b^3$; $(a-b)^3=a^3-3a^2b+3ab^2-b^3$.
* **Somma per differenza:** $(a+b)(a-b)=a^2-b^2$.
* **Quadrato di un trinomio:** $(a+b+c)^2=a^2+b^2+c^2+2ab+2ac+2bc$.
* **Somma e differenza di cubi:** $a^3\pm b^3=(a\pm b)(a^2\mp ab+b^2)$.

#### 6. Scomposizione

* **Fattore comune:** si mette in evidenza un fattore presente in tutti i termini, per esempio $ax+ay=a(x+y)$.
* **Raccoglimento totale:** si raccoglie il massimo fattore comune a tutti i termini.
* **Raccoglimento parziale:** si raggruppano i termini per ottenere un fattore comune tra i gruppi.
* **Differenza di quadrati:** $a^2-b^2=(a-b)(a+b)$.
* **Trinomio quadrato perfetto:** $a^2\pm2ab+b^2=(a\pm b)^2$.
* **Trinomio particolare:** $x^2+px+q=(x+r)(x+s)$ se $r+s=p$ e $rs=q$.
* **Somma e differenza di cubi:** $a^3+b^3=(a+b)(a^2-ab+b^2)$ e $a^3-b^3=(a-b)(a^2+ab+b^2)$.
* **Scomposizione mediante Ruffini:** se $P(a)=0$, allora $x-a$ è un fattore di $P(x)$; la divisione di Ruffini aiuta a trovare il quoziente.
* **Scomposizione completa:** si continua a fattorizzare finché i fattori ottenuti sono irriducibili nell'insieme numerico scelto.

#### 7. Teoria dei polinomi

* **Identità tra polinomi:** un'uguaglianza tra polinomi che vale per ogni valore delle variabili.
* **Uguaglianza tra polinomi:** due polinomi sono uguali quando hanno gli stessi coefficienti per ogni monomio corrispondente.
* **Zeri o radici di un polinomio:** $a$ è uno zero di $P$ se $P(a)=0$.
* **Molteplicità di una radice:** è il numero di volte che il fattore $x-a$ compare nella scomposizione.
* **Teorema del resto:** dividendo $P(x)$ per $x-a$, il resto è $P(a)$.
* **Teorema di Ruffini:** $P(a)=0$ se e solo se $x-a$ divide $P(x)$.
* **Teorema fondamentale dell'algebra:** ogni polinomio non costante a coefficienti complessi ha almeno una radice complessa e si scompone in fattori lineari su $\mathbb C$.

#### 8. Fattorizzazione

* **Fattori irriducibili:** sono fattori non ulteriormente scomponibili nell'insieme numerico considerato.
* **Fattorizzazione in $\mathbb Z$, $\mathbb Q$ e $\mathbb R$:** le possibilità di scomposizione dipendono dall'insieme dei coefficienti ammessi.
* **Relazione tra radici e fattori:** a ogni radice $a$ corrisponde il fattore $x-a$.
* **Fattorizzazione tramite radici note:** si usa ogni radice trovata per estrarre il relativo fattore e ridurre il grado.
* **MCD tra polinomi:** è il polinomio di grado massimo che divide tutti i polinomi considerati.
* **mcm tra polinomi:** è il polinomio di grado minimo divisibile per tutti i polinomi considerati.

#### 9. Equazioni e disequazioni polinomiali

* **Equazioni polinomiali:** si cercano gli zeri del polinomio, cioè i valori per cui $P(x)=0$.
* **Equazioni di secondo grado:** si risolvono nella forma $ax^2+bx+c=0$, per esempio con la formula risolutiva o la fattorizzazione.
* **Equazioni di grado superiore:** si riducono, quando possibile, a fattori o equazioni di grado minore.
* **Disequazioni polinomiali:** si individua dove il polinomio è positivo, negativo o nullo.
* **Studio del segno di un polinomio:** gli zeri reali dividono la retta in intervalli in cui il segno è costante.
* **Metodo degli zeri:** si ordinano gli zeri e si determina il segno in ciascun intervallo, considerando la molteplicità delle radici.

#### 10. Funzioni polinomiali

* **Definizione di funzione polinomiale:** è una funzione della forma $f(x)=a_nx^n+\cdots+a_1x+a_0$.
* **Grafico di un polinomio:** è continuo e non presenta interruzioni o asintoti verticali.
* **Zeri della funzione:** sono i valori $x$ per cui $f(x)=0$ e corrispondono alle intersezioni con l'asse $x$.
* **Segno della funzione:** si determina studiando il segno del polinomio tra i suoi zeri.
* **Comportamento agli estremi:** per $|x|$ grande domina il termine di grado massimo, che determina l'andamento del grafico.
* **Molteplicità degli zeri:** uno zero di molteplicità pari in genere non cambia il segno del polinomio; uno di molteplicità dispari lo cambia.
* **Relazione tra grado e numero di radici:** un polinomio di grado $n$ ha al massimo $n$ radici distinte; nei complessi ne ha esattamente $n$ contando le molteplicità.

#### 11. Strumenti trasversali

* **Calcolo letterale:** si manipolano espressioni con variabili applicando le proprietà delle operazioni.
* **Proprietà delle potenze:** per basi uguali, nel prodotto si sommano gli esponenti e nel quoziente si sottraggono, se il denominatore è non nullo.
* **Prodotti notevoli:** formule ricorrenti per sviluppare prodotti o riconoscere fattori.
* **Scomposizione in fattori:** si riscrive un polinomio come prodotto per semplificare calcoli e individuare zeri.
* **Frazioni algebriche:** si semplificano cancellando fattori comuni, dopo aver escluso gli zeri dei denominatori.
* **Equazioni e disequazioni:** la fattorizzazione aiuta a trovare soluzioni e intervalli di segno.
* **Notazione matematica e manipolazione simbolica:** parentesi, indici e uguaglianze vanno mantenuti coerenti durante i passaggi.
