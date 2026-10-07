# Funzioni inverse

**Funzione inversa**: funzione che “annulla” l'effetto di un'altra funzione, invertendo il legame tra input e output.
  **Etimologia:** “inverso” deriva dal latino *inversus*, “capovolto, rovesciato”.
  **Origine storica:** il concetto di funzione inversa nasce con lo studio delle relazioni biiettive e con la necessità di risolvere equazioni in modo invertito.

## Argomenti

1. **Definizione**
	- Se $f:A\to B$ è biiettiva, esiste una funzione inversa
	  $f^{-1}:B\to A$
	  tale che
	  $f^{-1}(f(x))=x$ e $f(f^{-1}(y))=y$.
	- La funzione inversa scambia i ruoli di dominio e codominio.

2. **Condizione di esistenza**
	- Una funzione ha inversa se e solo se è biiettiva.
	- Se la funzione non è iniettiva o non suriettiva, l'inversa non è definita sull'intero codominio.

3. **Rappresentazione grafica**
	- Il grafico di $f^{-1}$ è simmetrico rispetto alla bisettrice del primo e del terzo quadrante, cioè alla retta $y=x$.
	- Questo perché se $(a,b)$ appartiene a $f$, allora $(b,a)$ appartiene a $f^{-1}$.

4. **Esempi**
	- La funzione $f(x)=2x+3$ ha inversa $f^{-1}(y)=\frac{y-3}{2}$.
	- La funzione $f(x)=x^2$ non è invertibile su $\mathbb{R}$, ma lo è su $[0,+\infty)$, con inversa $f^{-1}(y)=\sqrt{y}$.

5. **Risoluzione di equazioni**
	- Il calcolo dell'inversa consente di isolare la variabile incognita.
	- È un metodo fondamentale in algebra e in analisi.

6. **Applicazioni**
	- Le funzioni inverse sono usate in logaritmi, esponenziali, radici e trasformazioni geometriche.
	- Sono essenziali anche nello studio di funzioni monotone e di algoritmi di inversione.

La funzione inversa è il modo rigoroso di dire: “mi serve la relazione che ti riporta indietro al valore iniziale”.
