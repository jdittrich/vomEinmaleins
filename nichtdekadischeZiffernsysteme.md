# Nichtdekadische Ziffernsysteme

Da wir nun den Bau, die Struktur des Zehnersystems so gut
kennen gelernt haben, wollen wir kühn versuchen, irgendein
anderes System selbständig aufzustellen ^[Der weniger geübte
Leser darf die Einzel-Berechnungen in diesem Kapitel ohne
Schaden für das Endziel überschlagen.]. Wir wählen zuerst
eine Grundzahl, die kleiner ist als zehn, etwa die Zahl
sechs. Und wir werden streng nach dem Muster des
Zehnersystems unseren neuen Algorithmus aufbauen und
zusehen, wie weit wir damit kommen. Zuerst ganz simpel und
nach dem Gefühl: Wir haben im Zehnersystem zehn Zahlzeichen,
zehn Ziffernsymbole, nämlich 0, 1 , 2 , 3, 4, 5, 6, 7, 8, 9
gebraucht. Folglich, so schließen wir, werden wir für unser
Sechsersystem mit sechs Ziffern, also 0, 1, 2, 3, 4, 5
auskommen. Wie aber sollen wir die Sechs schreiben, die
Sieben, die Acht, die Neun? Jetzt denken wir an unsere
Potenzreihe. Die Grundzahl zur ersten Potenz wurde 10¹
geschrieben. Oder einfach 10. Es war also die erste
zweistellige Zahl. Wir werden somit auch im Sechsersystem
die Grundzahl 10 schreiben, nur daß sie hier nicht zehn,
sondern sechs bedeutet.

Ich gebe zu, daß jetzt viele Leser verwirrt sein werden,
weil sie noch an die Gottgegebenheit des Zehnersystems
glauben. Darum wollen wir Schritt vor Schritt weiterwandern
und uns zuerst die ersten zwanzig Zahlen des Zehnersystems
aufschreiben. Darunter die Darunter die gleichwertigen
ersten zwanzig Zahlen des Sechsersystems.

<!-- pandoc simple table -->
--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---<!-- -->
  1   2   3   4   5   6   7   8   9  10  11  12  13  14  15  16  17  18  19  20
  1   2   3   4   5  10  11  12  13  14  15  20  21  22  23  24  25  30  31  32  
--- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---<!-- -->

Wie man sieht, ergibt sich die Schreibweise unmittelbar aus
der Tatsache, daß man im jeweiligen System eben nicht anders
schreiben *kann* . Denn mit fünf Ziffern und der Null kann
ich den Begriff sechs nicht anders schreiben als eben 10.
Ebenso wie ich mit neun Ziffernzeichen und der Null die
Zwölf nie anders ausdrücken kann als eben durch 12.

Nun wollen wir uns die Stufenzahlen ansehen. Diese müssen
(im Zehnersystem geschrieben) die Werte von 6°, 6¹ , 6² , 6³ ,
6⁴ usw. haben. Also, noch immer im Zehnersystem, die Werte
1, 6, 36, 216, 1296 usw. Ich könnte somit in
Reihenschreibung eine beliebige Zahl des Sechsersystems
folgendermaßen ausdrücken: 2⋅6 ° + 4⋅6¹ + 0⋅6² + 3⋅6³ + 5⋅6⁴ ,
was bedeuten würde: 2⋅1 + 4⋅6 + 0⋅36 + 3⋅216 + 5⋅1296 und
dekadisch geschrieben das Ergebnis 7154 lieferte.
Bemerkt sei, daß auch in dekadischer Schreibart die „Koeffizienten"
nie die Fünf überschreiten dürfen, da sonst die Größenfolge
verletzt werden könnte und die Zahl im Sechsersystem nicht
schreibbar wäre.
Nun kommt ein kühner Griff. Wir wollen
jetzt die besprochene Zahl im Sechsersystem aufschreiben.
Dazu ist gar nichts nötig, als die Koeffizienten einfach
nebeneinanderzustellen.
Dazu ist gar nichts nötig, als die
Koeffizienten einfach nebeneinanderzustellen. Und zwar
von der höchsten Potenz absteigend. Unsere Zahl lautet
also im Sechsersystem geschrieben 53.042.
Denn das heißt eben nichts anderes
als 2⋅6 ° + 4⋅6¹ + 0⋅6² + 3⋅6³ + 5⋅6⁴ !
Und wir stellen fest: 53.012 (Sechsersystem) ist gleich
7154 (Zehnersystem). Wir wollen zum Überfluß noch die
Probe machen und nun beide Zahlen in Reihen auflösen:

-------------- -------- ---------------------------------
Zehnersystem      7.154 4⋅10° + 5⋅10¹ + 1⋅10² + 7⋅10³
Sechsersystem    53.042 2⋅6° + 4*6¹ + 0⋅6² + 3⋅6³ + 5⋅6⁴
-------------- -------- ---------------------------------

4⋅1 + 5 ⋅ 1 0 + 1 ⋅ 100+ 7⋅ 1000 muß gleich sein
2⋅1 + 4⋅6 + 0⋅36 + 3⋅216 + 5⋅1296.

Natürlich stimmt die Rechnung. Denn sowohl die
erste Reihe als die zweite Reihe ergeben (dekadisch
geschrieben) als Resultat 7154.

Nun wollen wir uns aber von der Dekadik abwenden
und unsere Zahl 53.042 (Sechsersystcm) in eine Reihe
des eigenen Systems auflösen. Wir erhalten dann:
53.042 = 2⋅10° + 4⋅10¹ + 0⋅10² + 3⋅10³ + 5⋅10⁴, wobei
10 nicht mehr die Zehn des Zehnersystems, sondern dem
Werte nach die 6 des Zehnersystems bedeutet.

Wir wollen aber noch viel mehr. Wir wollen sehen, ob
sich auch das Sechsersystem als Algorithmus bewährt,
d. h. ob es geeignet ist, Rechenoperationen nach Art
unserer vertrauten Addition, Multiplikation usw. zu
gestatten. Zu diesem Behufe
<!-- TODO: sehr altmodisch; ersetze durch "zweck"-->
müssen wir uns aber noch
ein Hilfsmittel bereitstellen. Nämlich das „Einmaleins"
des Sechsersystems. Auf den ersten Blick sieht es wie
die Rechenübung eines soeben wahnsinnig Gewordenen
aus. Einiges Nachdenken und ein Blick auf die Ziffern-
reihen sowie die Überlegung, daß wir eben nur mit
sechs Ziffernzeichen operieren können, wird die Gemüter
bald wieder beruhigen.

Wir wagen also unser Hexeneinmaleins:

------- ------- ------- ------- -------
1⋅1=1   2⋅1=2   3⋅1=3   4⋅1=4   5⋅1=5
1⋅2=2   2⋅2=4   3⋅2=10  4⋅2=12  5⋅2=14
1⋅3=3   2⋅3=10  3⋅3=13  4⋅3=20  5⋅3=23
1⋅4=4   2⋅4=12  3⋅4=20  4⋅4=24  5⋅4=32
1⋅5=5   2⋅5=14  3⋅5=23  4⋅5=32  5⋅5=41
------- ------- ------- ------- -------

Wir werden nun addieren, subtrahieren, multiplizieren
und dividieren, als ob wir nie etwas vom
Zehnersystem gehört hätten. Zuerst eine Addition:

$$\begin{array}{rr}
    4325  \\
  \underline{+ 5041}  \\
   {1341} \\
\end{array}$$

Man muß stets, wenn zwei Zahlen zusammen 6 er-
geben, die Zehn denken. Also 1 und 5 gibt 10, bleibt
eins. Vier und eins sind fünf, plus zwei ist 11, bleibt eins.
Null plus eins ist eins, plus drei ist vier. Fünf plus
vier ist dreizehn. Natürlich dürfte man nicht zehn, elf
und nicht dreizehn sagen, sondern etwa sechs, einsechs
und dreisechs. Die Hauptschwierigkeit ist also eine
sprachliche. Wenn wir einmal Worte für die Stufenzahlen
haben, dann ist jedes System ebenso leicht zu
handhaben wie das dekadische.

Nun eine Subtraktion:

$$\begin{array}{rr}
    5201  \\
    \underline{-3544}  \\
    1213 \\
\end{array}$$

In Worten: Elf (einsechs) weniger vier gibt drei, bleibt
eins. Vier plus eins ist fünf. Fünf von zehn (sechs) ab-
gezogen, gibt eins, bleibt eins. Fünf plus eins ist zehn
(sechs). Dies abgezogen von zwölf (zweisechs) gibt zwei,
bleibt eins. Drei plus eins ist vier. Abgezogen von fünf
ist eins.

Jetzt die versprochene Multiplikation; wozu das
„Einmaleins" als Hilfsmittel dienen soll.

\begin{array}{rrrrrrrrr}
     & 3 & 4 & 2 & 5 & * & 3 & 1 \\ \hline
   1 & 5 & 1 & 2 & 3 &   &   & \\
     &   & 3 & 4 & 2& 5  &   & \\ \hline
   1 & 5 & 5 &0 & 5 & 5
\end{array}
