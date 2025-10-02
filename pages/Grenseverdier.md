- En grenseverdi skrives på formen $\lim\limits_{x\to a}$ der $a$ kan være hva som helst
- Når vi har grenseverdier, lurer vi ofte på hva en verdi for en [funksjon]([[Funksjoner]]) kan være der den ikke er definert.
	- La oss for eksempel ta funksjonen $f(x)=\frac{x}{x}$
	- Hvis vi hadde prøvd å regne ut $f(0)$ hadde vi fått et udefinert svar
		- Dette er fordi $\frac{x}{0}$ er [udefinert for alle verdier av x]([[Dele med null]])
	- Vi kan se derimot, at for verdier veldig nær 0, så får vi alltid svaret 1
		- $f(1)=\frac{1}{1}=1$
		  $f(0.1)=\frac{0.1}{0.1}=1$
		  $f(0)=\frac{0}{0}=\text{udefinert}$
		  $f(-0.1)=\frac{-0.1}{-0.1}=1$
	- Vi kan derfor overbevise oss selv i å si at $f(0)$ **burde** være 1.
	- Dette er der grenseverdier kommer inn, vi kan nemlig ikke si at $f(0)=1$ siden, som nevn, dette er udefinert. Vi kan derimot si at når $x$ nærmer seg $0$, så blir $f(x)$ lik $1$
	- Dette skriver vi slik $\lim\limits_{x\to 0}f(x)=\lim\limits_{x\to 0}\frac{x}{x}=1$
	-
- Merk at det går an å definere en funksjon som har en annen grenseverdi enn nøyaktig verdi
	- $f(x) = \begin{cases} 1 &\text{if } x\ne0 \\ 0 &\text{if } x=0 \end{cases}$
	- $\lim\limits_{x\to 0}f(x)=1$
	- $f(0)=0$