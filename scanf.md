Funkcja: scanf()
===================

>
W celu użycia funkcji scanf() należy użyć biblioteki: #include <stdio.h> odczytuje dane ze standardowego strumienia wejściowego (stdin) w/g zadanego formatu i zapamiętuje je pod zadanymi adresami pamięci int scanf ( tekst_sterujący , adres_1 , adres_2 , . . . ) ; tekst sterujący → jest to stała łańcuchowa (w podwójnych cudzysłowach) zawierająca polecenia jak traktować kolejne dane wczytywane ze strumienia (jakie typy zmiennych są pod adresami adres_1, adres_2, ... ) 

### Kody formatujące ( tekst_sterujcy , argument_1 , argument_2 , . . . ) ; tekst sterujący → jest to stała łańcuchowa (w cudzysłowach) zawierająca:

+ %c pojedynczy znak
+ %s łańcuch znaków
+ %d liczba dziesiętna ze znakiem
+ %f lub %e liczba zmiennoprzecinkowa
+ %u liczba dziesiętna bez znaku
+ %x liczba w kodzie szesnastkowym (bez znaku)
+ %o liczba w kodzie ósemkowym (bez znaku)
+ l przedrostek stosowany przed:  d u x o  (long int)
+ l przedrostek stosowany przed:  f e  (double)
+ L przedrostek stosowany przed:  f e  (long double)
+ & operator adresowania (zwraca adres zmiennej podanej po operatorze)


Zródło: [Wikipedia][1]

[1]: https://pl.wikipedia.org "Wikipedia"
