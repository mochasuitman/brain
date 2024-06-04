type:: [[theorem]]
title:: Calcolo somma numeri fino a n
topic:: #[[Analisi 1]] #Successioni
language:: #[[🇮🇹 ITA]]

-
- ## Statement
	- $$\sum_{i=1}^{n}i = \sum_{i=1}^{n/2}(i + (n - i + 1)) = n(n + 1)/2$$
	-
- ## Proof
	- Il teorema viene dimostrato (grazie a [[Carl Friedrich Gauss]] ) riscrivendo la somma in modo riflesso e sommando i termini di uguale posto:
	- $$\begin{cases}1 + 2 + 3 + 4 + ... + 100 = x \\ 100 + 99 + 98 + 97 ... + 1 = x \end{cases}$$
	- Sommo membro a membro e ottengo:
	- $$101 + 101 + 101 + 101 + ... + 101 = 2x \Rightarrow 100 \cdot 101 = 2x \\ x = \frac{101 \cdot 100}{2}$$
	- Generalizzando il concetto:
	- $$\forall n \in \mathbb{N} \Rightarrow \sum_{i=1}^{n} = \frac{n(n + 1)}{2}$$
	-
- ## Corollary
	-
	-