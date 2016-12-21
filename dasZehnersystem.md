# Das Zehnersystem

Dabei stoßen wir zuerst auf die schon angedeutete ungeheure Einfachheit des
Systems. Zehn Ziffernsymbole sind eigentlich das ganze Material, womit wir es zu
tun haben. Wenn wir weiters ein paar Verknüpfungssymbole wie die Zeichen „plus",
„minus", „mal" und „dividiert durch" (+ , −, ×, ÷) <!-- korrekte Zeichen nutzen -->
und endlich das Gleichheitszeichen ( = ) hinzunehmen, beherrschen wir als
Lüchlige Algorithmiker bereits eine ganze Welt des Zahlenrechnens. Allerdings
gehört als eine der wichtigsten Voraussetzungen noch etwas Weiteres zu unserer
algorithmische Kunst, das uns selbstverständlich scheint, aber gerade der
Schlüssel des Geheimnisses ist: das sogenannte Stellenwertsystem.

Als drastisches Beispiel einer Schreibung ohne Stellenwert sollen die
sogenannten römischen Ziffern herangezogen werden. Ein „Algorithmiker" Roms
würde aufgefordert werden, etwa die Zahlen MDCCCXLIX und MMCXXIV auch nur zu
summieren. Er wird bei den Zehnern und Einern in größte Verlegenheit kommen, zum
Abacus, zum Rechenbrett greifen und zugeben müssen, daß er eigentlich keinen
Algorithmus besitzt. Der Algorithmiker des indischen Systems findet es nicht
einmal der Mühe wert, diese Zahlen 1849 und 2124 untereinanderzuschreiben. Nach
wenigen Sekunden verkündet er das Ergebnis 3973 als Summe.

Jetzt wollen wir aber unmittelbar auf das Problem losgehen. Unter
Stellenwertsystem verstehen wir eine Schreibweise von Zahlen, die jeder Ziffer
einen anderen Wert zuteilt, wenn sie an anderer Stelle steht. Auch wenn es
dieselbe *Ziffer* ist. Und zwar bedeutet, da das Gesetz der Größenfolge von
links nach rechts eingehalten wird, etwa eine 3 an letzter Stelle 3, an
vorletzter Stelle 30, an drittletzter Stelle 300, an viertletzter Stelle 3000
usw. Von sogenannten Dezimalbruchstellen sprechen wir noch nicht. Wir behandeln
vorläufig nur ganze Zahlen, eingedenk des Ausspruchs Kroneckers ^[Ergänzende Bemerkung: Kronecker war ein deutscher Mathematiker, der sich mit Zahlentheorie, Algebra und Logik beschäftigte], daß die ganzen
Zahlen von Gott stammen und alles übrige Menschenwerk sei. An unserem Beispiel
mit der Drei sehen wir schon, daß der Stellenwert sich von rechts nach links
jeweils verzehnfacht. Daher der Name Zehnersystem oder dekadisches System. Die
Zehn heißt dabei die Grundzahl des Systems.

Obwohl wir damit gewaltig vorgreifen, wollen wir zur Vereinfachung der folgenden
Ausführungen einen neuen Begriff einführen. Nämlich den der Potenz. Es handelt
sich dabei eigentlich um nichts anderes als um eine Multiplikation einer Zahl
mit sich selbst, für die man ein besonderes abgekürztes Zeichen schreibt. Wir
wollen aber vorläufig über das sogenannte „potenzieren" oder „zur Potenz
erheben" uns in keiner Weise verbreiten, sondern an Hand weniger Beispiele bloß
die Schreibart klarmachen. Zehn mal zehn nennt man zehn zur zweiten Potenz und
schreibt 10². Zehn mal zehn mal zehn heißt „zehn der Dritten" oder „zehn zur
Dritten" oder „zehn zur dritten Potenz" und wird 10³ geschrieben. 10×10×10×10=
10⁴; 10×10×10×10×10 = 10⁵« usw. Natürlich kann man diese Zahlen
auch ausrechnen. So ist 10² =100, 10⁵ = 100.000, 5² = 5 × 5 = 25 , 6³ = 6 ×
6 × 6 = 216 usf. Als erste Potenz einer Zahl bezeichnet man die Zahl selbst,
weil sie gleichsam nur einmal in der Multiplikation auftritt. Also 10¹ = 10, 5¹
= 5, 29¹ = 29 usw. Die erste Potenz, also der kleine Einser rechts oben, wird
gewöhnlich nicht geschrieben. Wir müssen aber noch eine Potenz einführen, deren
merkwürdiges Ergebnis an dieser Stelle nicht erklärt werden kann. Nämlich die
sogenannte nullte Potenz. Wir stellen also die Forderung, daß eine Zahl
überhaupt nicht als Faktor in einer Multiplikation mit sich selbst vorkommt. Das
bedeutet etwa 10°oder in Worten: zehn der nullten Potenz. Jeder wird mit Recht
erklären, daß eine solche Forderung ein vollendeter Unsinn ist. „Multipliziere
etwas überhaupt nicht mit sich selbst, mache eine Rechnung (noch dazu eine
Multiplikation), in der der einzige erlaubte Faktor, nämlich die bestimmte Zahl,
nullmal, also überhaupt nicht vorkommt. Und sage mir das Ergebnis." Das ist die
Fragestellung. Ich muß, wie erwähnt, vorläufig höflichst um Entschuldigung
bitten und mitteilen, daß jede, aber auch jede Zahl ^[0° ist davon ausgenommen,
da 0 in diesem Zusammenhang nicht als Zahl zu betrachten ist], zur nullten
Potenz erhoben, das Resultat eins gibt. Also ist 10⁰= 1, 25⁰ = 1, 275.859⁰= 1
usf. bis zu jeder Größe.

Also wiederholt: Irgendeine Zahl zur nullten Potenz gibt eins. Zur ersten Potenz
sich selbst. Zur zweiten Potenz die Zahl mit sich selbst multipliziert. Zur
dritten Potenz die Zahl mit sich selbst und noch einmal mit sich selbst
multipliziert usw. Insbesondere für die Zahl zehn: 10°= 1 ,10¹= 10, 10²= 100, 10 ³ = 1000, 10⁴ = 10.000

Ein Mensch mit gutem Blick wird bei Betrachtung dieser Zahlenfolge sogleich
merken, daß bei der Zehn die kleine Ziffer rechts oben (der sogenannte
Potenzanzeiger oder Potenzexponent) die Anzahl der Nullen angibt, die die
betreffende Zehnerpotenz besitzt. Sicherlich ein wichtiger und für das
Ziffernsystem aufschlußreicher Zusammenhang. Wir wollen uns aber nicht weiter
verlieren, sondern jetzt beherzt in die Tiefen und Höhen der Zahlensysteme
vorstoßen. Denn wir haben bereits das ganze Rüstzeug zur Durchforschung unseres
Ziffern-Algorithmus in der Hand.

Bei Betrachtung des Rechenbrettes wird es jedem klar geworden sein, daß. sich
eine beliebige Zahl des Zehnersystems aus einer gewissen Menge von Einern, von
Zehnern, Hundertern usw. zusammensetzt. Wir werden uns nun bemühen, eine
geeignete Schreibweise zu finden, die den inneren Bau jeder Zahl bloßlegt, ohne
daß wir hierzu den ungelenken Abacus (das Rechenbrett) zu Hilfe nehmen müßten.
Nach dem Vorhergegangenen dürfte es nicht allzu schwer sein, diese Schreibweise
zu entdecken. Es ist die sogenannte additive oder summatorische Reihe ^[In der
Mathematik heißt „Reihe" stets eine additive oder subtraktive Aneinanderreihung
von Zahlen oder Größen.], und zwar eine Potenzreihe. Die gelehrten Ausdrücke
mögen niemand abschrecken. Denn ein Beispiel wird den Vorgang sofort
verdeutlichen. Nehmen wir etwa an, wir hätten die Zahl 1,483.706 in eine solche
Reihe aufzulösen. Mit unseren bisherigen Kenntnissen sind wir dazu ohne weiteres
imstande. Wir schreiben also zuerst noch primitiv:

6×1 + 0×10 + 7×(10×l0) + 3×(10×l0×l0) + 8×(10×10×10×10) + 4 × (10×10×10×10×10) + + 1×(10×10×10×10×10×10).

Dazu wird zuerst bemerkt, daß jede Zahl, mit der
Null multipliziert, wieder 0 gibt und daß ich daher
umgekehrt jede Null als Produkt irgendeiner Zahl mit
der 0 auffassen kann. Wir benützen diese Umkehrung
hier bewußt zur systematischen Ergänzung der Reihe
bezüglich der Zehnerstelle. Außerdem wollen wir nun
weitere Vereinfachungen vornehmen. Zuerst werden wir
das lästige schiefe Kreuz (×) für die Multiplikation
fallen lassen und dafür den Punkt anwenden, wie dies
in der Mathematik allgemein üblich ist. Dann werden
wir die Ausdrücke in den Klammern als richtige Potenzen darstellen. Und schließlich werden wir anmerken,
daß man innerhalb einer solchen Reihe die Ziffern, die
vor den Potenzen stehen, die „Koeffizienten" nennt.
6, 0, 7, 3, 8, 4, 1 — kurz die Ziffern, ans denen unsere
Zahl besteht — erscheinen in der Potenzreihe nur mehr
als „Koeffizienten". Dieser Begriff ist vorläufig zur
Notiz zu nehmen. Mehr kann an dieser Stelle darüber
noch nicht gesagt werden.

Wir schreiben also jetzt, mathematisch korrekt:
1,483.706 = 6⋅10° + 0⋅10¹ + 7 ⋅ 10² + 3 ⋅ 10³ + 8 ⋅ 10⁴ +
+4-10⁵+ 1⋅1O⁶.

Damit ist der innere Bau des Zehnersystems mit
Stellenwert vollständig und eindeutig bloßgelegt. Ich
will daher die sogenannte „Diskussion", die Erörterung
der Angelegenheit, au! die Gefahr hin zu langweilen,
nicht dem Leser überlassen, sondern sie mit ihm gemeinsam durchführen. Wir sehen zuerst, daß die sogenannte
Größenfolge eingehalten ist. Die Potenzen von zehn
folgen einander in der Reihe als 10°, 10 1 , 10®, 10« usf.
Daran ändern auch die Koeffizienten nichts. Denn selbst
9-10° (also 9-1 = 9) muß stets kleiner sein als 0-10 1
(also 0 - 1 0 = 0 ) , weil diese Null an der Zehnerstelle
nichts anderes bedeutet, als daß in der Zahl mindestens
10 Zehner vorhanden sind, da ja eine Zahl nie mit der
Null beginnen darf. Als Beispiel diene die Zahl 109,
die als Reihe geschrieben 9-10°+0-lO 1 ^-1 -10® lauten
würde. Daß 10° gleich 1 ist, wurde schon erwähnt. Es
ist nun weiter klar, daß die Reihe theoretisch ins
Unendliche fortsetzbar ist. Das heißt, es gibt keine noch
so große Zahl, die nicht in Form einer solchen Reihe
aufsteigender, mit Koeffizienten versehener Zehnerpotenzen geschrieben werden könnte. Natürlich ist
umgekehrt jede solche Reihe wieder in eine dekadische
Zahl rückübertragbar. 5-10°+7- 1 0 x + 0 - 1 0 2 + 8 - 1 0 s +
+ 9 - 1 0 4 + 3 - 1 0 « ist nichts anderes als die Zahl 398.075,
nämlich noch einmal zum Überdruß in Worten: 5 Einer,
7 Zehner, 0 Hunderter, 8 Tausender, 9 Zehnlausender
und 3 Hunderttausender. Mit Absicht wird erst hier
erwähnt, daß ein vollkommenes Ziffernsystem noch
voraussetzt, daß die sogenannten Stufenzahlen (die
Zehnerpotenzen) rein sprachlich mit eigenen Worten
bezeichnet werden können (zehn, hundert, tausend
usw.). Streng durchgeführt ist die Sache in unserem

<!-- P28 -->
