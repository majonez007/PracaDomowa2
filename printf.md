Funkcja: printf()
=================

>
W celu użycia funkcji printf() należy użyć biblioteki: #include <stdio.h> Funkcja printf() wysyła sformatowane dane do standardowego strumienia wyjściowego (stdout) printf ( tekst_sterujcy , argument_1 , argument_2 , . . . ) ; tekst sterujący → jest to stała łańcuchowa (w cudzysłowach) zawierająca:


>zwykłe znaki (które są po prostu kopiowane na ekran) 
kody formatujące kolejnych argumentów:
+ %c pojedynczy znak
+ %s łańcuch znaków
+ %d liczba dziesiętna ze znakiem
+ %f liczba zmiennoprzecinkowa (notacja dziesiętna)
+ %e liczba zmiennoprzecinkowa (notacja wykładnicza)
+ %e liczba zmiennoprzecinkowa (krótszy z formatów %f %e)
+ %u liczba dziesiętna bez znaku
+ %x liczba w kodzie szesnastkowym (bez znaku)
+ %o liczba w kodzie ósemkowym (bez znaku) 
+ l przedrostek (long) stosowany przed:  d  u  x  o

Zródło: [Wikipedia][1]
[1]: https://pl.wikipedia.org "Wikipedia"
