# Composizione di funzioni

**Composizione di funzioni**: operazione che applica una funzione dopo l'altra, ottenendo una nuova funzione.
  **Etimologia:** “composizione” deriva dal latino *compositio*, “unione, assemblaggio”.
  **Origine storica:** il concetto di funzione composta è naturale nella matematica moderna, dove si studiano trasformazioni successive di insiemi e grandezze.

## Argomenti

1. **Definizione**
	- Date $f:A\to B$ e $g:B\to C$, la composizione è
	  $(g\circ f)(x)=g(f(x))$.
	- Si legge “$g$ composta con $f$”.
	- Prima si applica $f$, poi $g$.

2. **Dominio della funzione composta**
	- Il dominio di $g\circ f$ è l'insieme dei punti $x$ per cui $f(x)$ è definita e $g(f(x))$ è definita.
	- In simboli:
	  $\mathrm{Dom}(g\circ f)=\{x\in\mathrm{Dom}(f)\mid f(x)\in\mathrm{Dom}(g)\}$.

3. **Esempio**
	- Se $f(x)=x+1$ e $g(x)=x^2$, allora
	  $(g\circ f)(x)=(x+1)^2$.
	- Invece,
	  $(f\circ g)(x)=x^2+1$.
	- La composizione non è, in generale, commutativa.

4. **Proprietà**
	- La composizione di funzioni è associativa:
	  $(h\circ g)\circ f = h\circ(g\circ f)$.
	- In generale non è commutativa: $f\circ g \ne g\circ f$.
	- La composizione conserva alcune proprietà, come la continuità e la monotonia, nelle opportune condizioni.

5. **Interpretazione**
	- La composizione descrive una successione di trasformazioni.
	- È uno strumento essenziale in analisi, geometria e modello matematico di fenomeni complessi.

6. **Applicazioni**
	- È usata per studiare funzioni composte, trasformazioni del piano, e problemi di modellizzazione.
	- In molti casi, la funzione matematica reale rappresenta un processo in più passaggi.

La composizione è il modo di concatenare relazioni: un processo avviato da una funzione e continuato da un'altra.
