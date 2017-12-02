<h1> Funkcja: printf()</h1>

<p>
W celu użycia funkcji printf() należy użyć biblioteki: #include <stdio.h> Funkcja printf() wysyła sformatowane dane do standardowego strumienia wyjściowego (stdout) printf ( tekst_sterujcy , argument_1 , argument_2 , . . . ) ; tekst sterujący → jest to stała łańcuchowa (w cudzysłowach) zawierająca:</p>
<ul>
zwykłe znaki (które są po prostu kopiowane na ekran) 
kody formatujące kolejnych argumentów:
<ul>
<li>%c pojedynczy znak </li>
<li>%s łańcuch znaków </li>
<li>%d liczba dziesiętna ze znakiem </li>
<li>%f liczba zmiennoprzecinkowa (notacja dziesiętna) </li>
<li>%e liczba zmiennoprzecinkowa (notacja wykładnicza) </li>
<li>%e liczba zmiennoprzecinkowa (krótszy z formatów %f %e) </li>
<li>%u liczba dziesiętna bez znaku</li>
<li>%x liczba w kodzie szesnastkowym (bez znaku) </li>
<li>%o liczba w kodzie ósemkowym (bez znaku) </li>
<li>l przedrostek (long) stosowany przed:  d  u  x  o</li>
</ul>
