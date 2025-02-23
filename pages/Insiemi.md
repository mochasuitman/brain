type:: [[course topic]]
title:: Insiemi
main-course:: #[[Analisi 1]] #[[Algebra Lineare e Geometria]] 
mental-map:: ![Insiemi_map.pdf](../assets/Insiemi_map_1696168616980_0.pdf) 
difficulty:: #[[🟢 simple]]

-
- ## Introduzione
	- Un insieme è una collezione di oggetti che condividono una medesima proprietà (o gruppo di proprietà)
-
- ## Insiemi numerici
	- Gli insiemi numerici identificano gli insiemi dei numeri:
	- $$\mathbb{N} = \text{Numeri Naturali} = \left\{0, 1, 2, ...\right\} \newline\mathbb{Z} = \text{Numeri Interi}= \left\{..., -2, -1, 0, 1, 2, ...\right\} \newline\mathbb{Q} = \text{Numeri Razionali}= \left\{...,-\frac{1}{2}, \frac{2}{3}, \frac{4}{2}, ...\right\} \newline\mathbb{I} = \text{Numeri Irrazionali}= \left\{\pi, e, \sqrt{2}, ...\right\} \newline\mathbb{R} = \mathbb{Q} \cup \mathbb{I} = \text{Numeri Reali} = \left\{-\frac{3}{2}, \pi, \sqrt{9}, 0, 2, ...\right\} \newline\mathbb{C} = \text{Numeri Complessi}= \left\{1 + 3i, -4 - i, 4\left[\cos\left(\frac{\pi}{2}\right) + i\sin\left(\frac{\pi}{2}\right)\right], ...\right\}$$
	-
- ## Operazioni
	- Le principali operazioni eseguibili sugli insiemi sono:
		- ### [[unione]]
		- ### [[intersezione]]
		- ### [[differenza tra insiemi]]
		- ### [[prodotto cartesiano]]
		-
- ## Insiemi numerici e [[campo]]
	- Gli insemi numerici $$\mathbb{Q}; \mathbb{R}; \mathbb{C}$$ possono definirsi campi
	-
- ## Proiezioni
	- Sia $$S \subseteq X \times Y$$
	- Si definisce proiezione di $$S$$ su $$X$$ $$:=\left\{x : x \in X \land (x, k) \in S\right\}$$
	- Si definisce proiezione di $$S$$ su $$Y$$ $$:=\left\{y : y \in Y \land (k, y) \in S\right\}$$
	  :LOGBOOK:
	  CLOCK: [2023-10-10 Tue 10:49:07]--[2023-10-10 Tue 10:49:10] =>  00:00:03
	  CLOCK: [2023-10-10 Tue 10:49:19]
	  :END:
	- In seguito un esempio di proiezione su $$X$$ (asse x):
	- ![insiemi_proiezioni.png](../assets/insiemi_proiezioni_1696191140923_0.png)
	-
- ## Relazioni
	- Si dice [[relazione]] $$R$$ in un insieme $$A$$ la relazione (anche detta regola) che associa a un elemento di $$A$$ un altro elemento di $$A$$
	- $$R \subseteq A \times A$$
	- Le relazioni possono godere delle seguenti proprietà:
		- ### [[proprietà riflessiva]]
			- $$\forall a \in A \Rightarrow (a, a) \in R$$
		- ### [[proprietà antiriflessiva]]
			- $$\forall a \in A \Rightarrow (a, a) \notin R$$
		- ### [[proprietà simmetrica]]
			- $$\forall a \in A, \forall b \in A \Rightarrow (a, b) \in R \land (b, a) \in R$$
		- ### [[proprietà antiriflessiva]]
			- $$\forall a \in A, \forall b \in A : (a, b) \in R \land (b, a) \in R \Rightarrow a = b$$
		- ### [[proprietà transitiva]]
			- $$\forall a \in A, \forall b \in A, \forall c \in A : (a, b) \in R \land (b, c) \in R \Rightarrow (a, c) \in R$$
		-
- ## Relazione di Equivalenza
	- Una relazione di equivalenza è una [[relazione]] che possiede la [[proprietà riflessiva]], [[proprietà simmetrica]] e [[proprietà transitiva]]
	- $$R \subseteq A \times A \newline R = \left\{x: x \text{ rispetta una data condizione}\right\}$$
	-
- ## Classe di Equivalenza
	- Avendo definito una [[relazione]] di equivalenza, una classe di equivalenza è un [[insieme]] di numeri posti in relazione con il [[rappresentante]]
	- $$R = \left\{x : x \text{ rispetta una data condizione}\right\} \newline [a]_{R} = \left\{x \in A : a R x\right\}$$
	-
	- Esempio:
		- $$R \subseteq \mathbb{N} \times \mathbb{N} = \left\{a - b = \text{ pari}\right\} \newline [0]_R = \left\{x \in \mathbb{N} : xR0\right\} = \left\{2, 4, 6, 8, ...\right\} \newline [1]_{R} = \left\{x \in \mathbb{N} : xR1\right\} = \left\{3, 5, 7, 8, ...\right\}$$
	- Si dice [[insieme quoziente]] l'insieme di tutte le classi di equivalenza
	-
- ## Gerarchia insiemi infiniti
	-