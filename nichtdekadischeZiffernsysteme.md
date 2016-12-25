at# Nichtdekadische Ziffernsysteme

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

$$\begin{array}{rrrrrrrrr}
     & 3 & 4 & 2 & 5 & * & 3 & 1 \\ \hline
   1 & 5 & 1 & 2 & 3 &   &   & \\
     &   & 3 & 4 & 2& 5  &   & \\ \hline
   1 & 5 & 5 &0 & 5 & 5
\end{array}$$

Zur Multiplikation wollen wir durch Umrechnung in
das Zehnersystem die Probe machen.

3425 (Sechsersystem) = 5⋅6⁰ + 2⋅6¹ + 4⋅6² + 3⋅6³ = 809
(Zehnersystem)

31 (Sechsersystem) = 1⋅6° + 3⋅6¹ = 19 (Zehnersystem).

<!-- array environment -->
<!-- could be improved with http://tex.stackexchange.com/questions/11702/how-to-present-a-vertical-multiplication-addition -->

$$\begin{array}{rrrrrrrrr}
     &  & 8 & 0 & 9 & * & 1 & 9 \\
     & 7 & 2 & 8 & 1 &  &   & \\ \hline
   1 & 5 & 3 & 7 & 1 &  &   &
\end{array}$$

Wenn wir richtig gerechnet haben und wenn weiters
unsere Behauptung wahr ist, daß die Gesetze des
Algorithmus im Sechsersystem dieselben sind wie im
Zehnersystem, dann muß 15.371 (Zehnersystem) gleich
sein mit 155.055 (Sechsersystem), also in Reihen aufgelöst
1⋅10° + 7⋅10¹ + 3⋅10² + 5⋅10³ + 1⋅10⁴ =
5⋅6° + 5⋅6¹ + 5⋅6² + 5⋅6³ + 5⋅6⁴ + 1*6⁵

Zu unserer Freude besteht die erforderliche  Gleichheit der
beiden Reihen, wovon sich jeder leicht überzeugen kann. Wir
sind also nur noch die Division im Sechsersystem schuldig,
die wir sogleich nachtragen wollen. Wir sind kühn und haben
keine Scheu vor großen Zahlen. Also:
 $$ 2004013 ÷ 2413 (alles im Sechsersystem)
     3100
      1041
       2123
        000$$

Die Division ist, wie man sagt, aufgegangen. Natürlich
mußten wir uns auch bei der Division die ganze Zeit
über vor Augen halten, daß wir es mit dein Sechser-
system zu tun haben: schon bei der ersten Abschätzung,
die in jedem System beim Dividieren notwendig ist.
Wenn man beginnt, muß man sich bei der Division
fragen, wie oft der Divisor im Dividenden enthalten
sein kann bzw. im jeweiligen Teil der Zahl, die zu
dividieren ist. Konkret: Wie oft war 425 in der ersten
Gruppe 2004 enthalten? Im Zehnersystem hätte ich es
mit vier probiert. Im Sechsersystem muß ich bedenken,
daß die 20 wertmäßig soviel bedeutet wie 12, während
die 4 in beiden Systemen 4 bedeutet. Da nun nach
der 20 noch eine Null folgt, während nach der 4 eine 2
steht, lag die Sache für mich so, als ob ich (dekadisch
geschrieben) 120 durch 42 zu teilen gehabt hätte. Ich
*mußte* also zuerst mit 2 probieren. Für die zweite
Stelle ist 31 durch 4 zu probieren. 31 bedeutet aber 19
des Zehnersystems. Also schreibe ich probeweise 4 an
usf. Im übrigen kann und muß man, wie beim Zehner-
system, zu diesen Proben das jeweilige Einmaleins, in
unserem Falle also unser „Hexeneinmaleins", heran-
ziehen ^[wodurch es sich erübrigt, jedesmal beim Probieren
ins Zehnersystem zurückzurechnen].

Nun wollen wir aber, unersättlich wie wir schon geworden
sind, als frischgebackene Zahlentheoretiker noch
die unbedingte Gewähr haben, daß unsere Division
auch stimmt. Dazu haben wir zwei Wege. Erstens, wie
bei der Multiplikation, die Rückübertragung der ganzen
Rechnung ins Zehnersystem, in dem wir uns
begreiflicherweise sicherer fühlen. Wir sind aber diesmal zu
stolz, diesen banalen Weg zu gehen. Wir wollen nämlich
unserem Algorithmus noch stärker auf den Zahn fühlen,
wenn dieses schreckliche Bild erlaubt ist. Und wir
schließen so: Der geängstigte Elementarschüler, der
nicht weiß, ob seine Division richtig ist, macht einfach
die „Gegenprobe", indem er den Divisor mit dem
Quotienten multipliziert und hierauf zusieht, ob er
dadurch den Dividenden erhält. Schematisch:

Dividend ÷ Divisor = Quotient,
Divisor × Quotient = Dividend.

Da wir, wie schon erwähnt, das Zehnersystem überhaupt nicht mehr heranziehen wollen und uns als
Elementarschüler des Sechsersystems betrachten,
multiplizieren wir (alles im Sechsersystem) die Zahlen

$$ 2413 ⋅ 425
  14500
    5230
    21313
  2004013
$$

Wir sind befriedigt. Denn die Gegenprobe ist gelungen
und wir haben richtig den Dividenden erhalten.
Unser Widersacher hat uns aber auf die Finger gesehen
und bezichtigt uns einer Unkorrektheit. Er macht uns
nämlich darauf aufmerksam, daß wir nicht, wie im
Schema, Divisor mal Quotient, sondern Quotient mal
Divisor angeschrieben haben. Obwohl nun jeder uns
beistehen und sagen wird, daß dies gleichgültig sei, weil
ja auch 5-4 dasselbe Ergebnis liefert wie 4-5, sind wir
unserem Widersacher gleichwohl dankbar und ergreifen
die Gelegenheit zu einen kleinen Abschweifung.
Addition und Multiplikation sind die sogenannten
aufbauenden Rechnungsarten. Sie fügen zusammen,
vermehren. Erzeugen eine Zusammensetzung, eine Synthese.
Und heißen deshalb, streng wissenschaftlich, die
*synthetischen* oder einfacher die *thetischen* Operationen.

Subtraktion und Division dagegen lösen auf, vermindern,
bauen ab. Man nennt sie *analytische* oder, auch
einfacher, die *lytischen* Operationen. Es ist klar oder,
vorsichtiger gesagt, wahrscheinlich, daß sowohl die
Gruppe der aufbauenden als auch die Gruppe der lösenden Rechnungsarten gewisse gemeinsame Gruppeneigenschaften
haben werden. Wir wollen aber an dieser
Stelle durchaus noch nicht tiefer dringen. Wir wollen
den Einwand unseres Widersachers nur dazu benutzen,
festzustellen, daß Addition und Multiplikation im
Gegensatz zu Subtraktion und Division eine sehr
wichtige Gruppengemeinschaft besitzen, die jeder kennt:
Ihre Einzelbestandteile, Glieder, Posten , oder wie man
es nennen will, sind vertauschbar, ohne daß sich das
Ergebnis ändert. <!-- 38 -->
5 + 4 + 7 = 4 + 7 + 5 = 7 4 - 4 + 5 usw.
Ebenso 4⋅5⋅7 = 5⋅7⋅4 = 7⋅5⋅4 usw. Regel: Bei den
aufbauenden (lytischen) Rechnungsarten herrscht das
Prinzip der Vertauschbarkeit der Bestandteile
(Prinzip der Kommulativität). Bei den auflösenden
(lytischen) Rechnungsarten, die nebenbei bemerkt
auf unserer Stufe auch stets nur aus zwei
Posten bestehen, gilt dieses Prinzip auf keinen Fall.
Sie sind gleichsam einseitig gerichtet.
Es ist grundverschieden, ob ich von 5 die 4
oder von der 4 die 5 abziehe. Ebenso verschieden ist
es, ob ich 12 durch 3 dividiere oder 3 durch 12. Ich
gebe zu, daß diese Abschweifung auf unserer Stufe noch
wie das überflüssige Breittreten einer
Selbstverständlichkeit aussieht. Ich deute deshalb
an, daß es noch einige höhere thetische (aufbauende)
 und lytische (lösende) Rechnungsarten gibt,
 bei denen alles nicht mehr so einfach liegt und deshalb
 der Untersuchung wert ist.

 Wir wollen aber jetzt wieder zu unseren  Zahlensystemen
zurückkehren. Unsere Versuche im  Sechsersystem haben uns
neugierig gemacht.  Und wir glauben zwar, daß mit einer
Grundzahl  unterhalb von zehn der ganze Zauber des
Algorithmus, der wahren Kabbala,  stimmt, daß es aber durch
nichts bewiesen ist, ob sich eine Grundzahl, die größer als
zehn ist, auch für ein Stellenwertsystem eignet. Wir dürfen
aus rein rechenökonomischcn Gründen nicht ins Uferlose
schweifen und etwa [50 als Grundzahl wählen. Natürlich wäre
es möglich. Aber die Potenzen von 50 wachsen so schwindelnd
schnell, daß wir jeden Überblick verlieren würden. Außerdem
brauchen wir bekanntlich stets so- viel einzelne Zahlzeichen
als die Grundzahl Einheiten anzeigt. Woher sollen wir diese
Zeichen nehmen, wenn wir nicht allein Tage aufwenden wollen
um sie zu erfinden und zu erlernen?

Wir begnügen uns also mit der Tatsache, daß die
Grundzahl größer als zehn sein soll, und wählen als
echte Kabbalisten die Zahl 13. Mit der Nebenabsicht,
zu zeigen, daß sich auch eine sogenannte Primzahl, eine
durch keine andere ganze Zahl teilbare Zahl, zur
Grundzahl eines Systems eignet, Hierzu sei wieder eine
Bemerkung eingeschaltet. Unsere dekadische Grund-
zahl 10 ist nur durch 5 und durch 2 teilbar. Die Zahl
12 aber durch 2, 3, 4 und 6. Deshalb hat man schon
mehr als einmal ganz ernsthaft vorgeschlagen, das
Zehnersystem zu verlassen und zum Zwölfersystem
überzugehen. Es hätte für das Münzwesen, die Maß-
und Gewichtseinteilung geradezu unschätzbare Vorteile,
abgesehen davon, daß die Einteilung des Tages
(Ziffernblatt der Uhr) und die Winkelteilung des
Kreises mit dem Zwölfersystem leicht zu vereinen wäre.
Als Gegengründe gegen das Zwölfersystem sprechen
hauptsächlich die Naturtatsachen unserer Fingerzahl
und unseres sonstigen Körperbaues, der in grollen Um-
rissen stets die Fünfheit und die Zweiheit bevorzugt
(Augen, Ohren, Anne, Beine, Finger, Zehen). Außerdem
ist das ganze Metermaßsystem mit all seinen Ausläufern
in dezimaler Art mit der Erde verbunden, da der
Meter seit der französischen Revolution als der zehn-
millionste Teil des Erdmeridianquadranten definiert ist.
Alle anderen Maße wie Liter, Kilogramm usw. sind aber
wieder mit dem Meter dezimal gekoppelt. Und schließlich
ist durch einen kosmischen Zufall die wichtigste
Weltgröße, die sogenannte Lichtgeschwindigkeit, pro
Zeitsekunde fast genau 300.000 Kilometer ^[Hätte ich selbst
 den Meter im Zwölfersystem als 10,000.000ten
 Teil des Meridianquadranten definiert, so wäre die
 Lichtgeschwindigkeit pro Sekunde im Zwölfersystem
 26mal to groß, also 260.000 „Kilometer" des Zwölfersystems.
 Somit eine weniger „runde" Zahl.].
 <!-- TODO: 26mal so groß wie die Erde oder was? -->

Es ist sonach wenig Aussicht, daß wir in absehbarer
Zeit auf ein anderes Ziffernsystem umlernen müssen.
Gleichwohl werden wir uns weniger aus praktischen als
aus sehr wichtigen prinzipiellen Gründen noch ein
bißchen mit unserem Dreizehnersystem beschäftigen.
Wieder wollen wir vorerst die ersten Zahlen, diesmal
die ersten dreißig, im dekadischen und im
Dreizehnersystem zu Vergleichszwecken untereinander
schreiben.


$$\begin{array}{rrrrrrrrrrrrrrr}
     Zehnersystem & 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 10 & 11 & 12 & 13 & 14 & 15
     Dreizehnersystem & 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & A & B & C & 10 & 11 & 12
\end{array}$$

$$\begin{array}{rrrrrrrrrrrrrrr}
     Zehnersystem & 16 & 17 & 18 & 19 & 20 & 21 & 22 & 23 & 24 & 25 & 26 & 27 & 28 & 29 & 30
     Dreizehnersystem & 13 & 14 & 15 & 16 & 17 & 18 & 19 & 1A & 1B & 1C & 20  & 21 & 22 &23 & 24  
\end{array}$$

Wie man merkt, haben wir, da wir im Dreizehnersystem, einschließlich der Null, dreizehn einfache
Ziffernzeichen brauchen, die großen lateinischen
Buchstaben A, B und C als Ziffern herangezogen. Während
beim Sechsersystem Ziffern des dekadischen Systems
übersprungen wurden und einfach nicht vorkommen
(6, 7, 8, 9), ist es hier genau umgekehrt. Das Zehnersystem überspringt drei Ziffern des Dreizehnersystems (A, B, C)

Wir könnten nun auch hier ein Hexeneinmaleins anschreiben,
in dem etwa 5⋅8 = 31 und 7⋅7 = 3A usw. wäre, wollen aber
diese Fleißaufgabe sowie die Erkenntnis, daß im
Dreizehnersystem A⋅B = 86 , jenen Lesern zur Durchführung
überlassen, die tiefer in die Ziffernsysteme eindringen
wollen.

Gleichwohl müssen wir unser Dreizehnersystem
irgendwie rechtfertigen. Wir wählen hierzu eine
Multiplikation. Und zwar die Multiplikation der Zahlen
92B und A7, was im Rotwelsch des Dreizehnersystems
etwa Neunhundert*be*undzwanzig mal Siebenund*a*zig
auszusprechen wäre. Also:

$$92B⋅A7
  7126
   4C6C
  761CC$$
