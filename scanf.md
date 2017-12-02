<h1> Funkcja: scanf()</h1>

<p>
W celu użycia funkcji scanf() należy użyć biblioteki: #include <stdio.h> odczytuje dane ze standardowego strumienia wejściowego (stdin) w/g zadanego formatu i zapamiętuje je pod zadanymi adresami pamięci int scanf ( tekst_sterujący , adres_1 , adres_2 , . . . ) ; tekst sterujący → jest to stała łańcuchowa (w podwójnych cudzysłowach) zawierająca polecenia jak traktować kolejne dane wczytywane ze strumienia (jakie typy zmiennych są pod adresami adres_1, adres_2, ... ) Kody formatujące (podobne jak dla printf() ):</p>
<ul>
<li>%c pojedynczy znak </li>
<li>%s łańcuch znaków </li>
<li>%d liczba dziesiętna ze znakiem   </li>
<li>%f lub %e liczba zmiennoprzecinkowa </li>
<li>%u liczba dziesiętna bez znaku </li>
<li>%x liczba w kodzie szesnastkowym (bez znaku)  </li>
<li>%o liczba w kodzie ósemkowym (bez znaku) </li>
<li>l przedrostek stosowany przed:  d u x o  (long int) </li> 
<li>l przedrostek stosowany przed:  f e  (double) </li>
<li>L przedrostek stosowany przed:  f e  (long double)  </li>
<li>& operator adresowania (zwraca adres zmiennej podanej po operatorze) </li>
</ul>

