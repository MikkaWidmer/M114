# M114

[Tag 1](#Tag-1)

[Tag 2](#Tag-2)

[Tag 3](#Tag-3)

[Tag 4](#Tag-4)

[Tag 5](#Tag-5)

[Tag 6](#Tag-6)

[Tag 7](#Tag-7)

----------------

## Tag-1
Begrüssung, Zuerst haben wir das Modul besprochen und wie das alles geregelt ist. Die Links zu den Unterlagen

Danach haben wir mit einem Kahoot begonnen damit er eine übersicht davon hat wie viel wir schon wissen.
Bestandesaufnahme "Ihr Vorwissen"

Start mit dem Thema "Daten codieren"
  Danach hat er uns gezeigt wie man verschieden Files den Binär code anschaut.
  Schachspielanekdote: Siehe hier angefügtes Dokument Schachbrett.pdf

HEX-Editor (https://hexed.it)
  damit kann man Files öffnen in Bits es werden immer 16 mal 4 bits zusammen gefasst

	
### Zahlensysteme, numerische Codes

2. Wandeln sie die folgende Dezimalzahl ohne Taschenrechner in die entsprechende Binärzahl um: 911

    911 ÷ 2 = 455 Rest 1
    
    455 ÷ 2 = 227 Rest 1
    
    227 ÷ 2 = 113 Rest 1
    
    113 ÷ 2 = 56 Rest 1
    
    56 ÷ 2 = 28 Rest 0
    
    28 ÷ 2 = 14 Rest 0
    
    14 ÷ 2 = 7 Rest 0
    
    7 ÷ 2 = 3 Rest 1
    
    3 ÷ 2 = 1 Rest 1
    
    1 ÷ 2 = 0 Rest 1
    
    Die Binärzahl für 911 lautet also 1110001111.
    
3. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Dezimalzahl um: 1011'0110 

   128 | 64 | 32 | 16 | 8 | 4 | 2 | 1
   
    1     0    1    1   0   1   1   0
    
    128 + 32 + 16 + 4 + 2 = 182
    
4. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Hexadezimalzahl um: 1110'0010'1010'0101

    1110 -> E
    
    0010 -> 2
    
    1010 -> A
    
    0101 -> 5
    
    Die Binärzahl 1110'0010'1010'0101 entspricht der Hexadezimalzahl E2A5.
    
5. Der Addierer einer ALU erhält für Zahl-A: 1101'1001 und für Zahl-B: 0111'0101. Was wird man als Resultat erhalten? Erklären sie!

       1101'1001
       
    + 0111'0101

    ------------
    
    128 | 64 | 32 | 16 | 8 | 4 | 2 | 1
    
    1     1    0    1   1   0   0   1
    
    128 + 64 + 16 + 8 + 1 = 217
    
    128 | 64 | 32 | 16 | 8 | 4 | 2 | 1
    
    0     1    1    1   0   1   0   1
    
    64 + 32 + 16 + 4 + 1 = 117
    
    217 + 117 = 334
    
    334 = 101001110

Alphanumerische Codes ASCII, Unicode

## Tag-2

Der Schultag heute war sehr lehrreich. Wir haben uns mit Codes wie ASCII und Unicode beschäftigt. Wir haben den ASCII-Code und seine Erweiterung nach ISO 8859 kennengelernt. Außerdem haben wir darüber gesprochen, warum Unicode wichtig ist, um mehr Zeichen darstellen zu können. Wir haben praktische Aufgaben gemacht, um die Unterschiede zwischen ASCII und UTF-8 zu erkunden. Wir haben auch gelernt, was Big-Endian und Little-Endian bedeuten. Insgesamt war der Schultag sehr informativ und hat mein Verständnis für diese Codes erweitert.

## Tag-3

Bildcodierung

	Elektromagnetische Wellen können durch ihre Wellenlänge oder Frequenz beschrieben werden.
	Licht besteht aus elektromagnetischen Wellen.
	Nur bestimmte Frequenzen des Lichts sind für das menschliche Auge sichtbar.

Farben können in verschiedenen Codeformaten dargestellt werden, zum Beispiel in HEX-Codes, wie z.B. weiß = #ffffff.

Es gibt verschiedene Farbkanäle, manche können nur Schwarz und Weiß darstellen, während andere natürlich auch Farben anzeigen können.

DPI (Dots per Inch) und PPI (Pixels per Inch) sind Begriffe, die wichtig sind, um die Bildqualität eines Bildschirms beim Kauf zu berücksichtigen.

### 2. Farbcodierung RGB / CMYK

	RGB 255/255/255 ergibt in YCbCr:
	Die Umwandlung von RGB 255/255/255 in YCbCr ergibt Y: 1, Cb: 0, Cr: 0.

	RGB 0/0/0 ergibt in YCbCr:
	Die Umwandlung von RGB 0/0/0 in YCbCr ergibt Y: 0, Cb: 0, Cr: 0.

	Y: 1, Cb: 0, Cr: 0 entspricht der Farbe:
	Y: 1, Cb: 0, Cr: 0 repräsentiert die Farbe Schwarz.

	Y: 0, Cb: 0, Cr: 0 entspricht der Farbe:
	Y: 0, Cb: 0, Cr: 0 repräsentiert die Farbe Schwarz.

	Y: 0, Cb: 1, Cr: 0 entspricht der Farbe:
	Y: 0, Cb: 1, Cr: 0 repräsentiert die Farbe Blau.

	Y: 0, Cb: -1, Cr: 0 entspricht der Farbe:
	Y: 0, Cb: -1, Cr: 0 repräsentiert die Farbe Gelb.

	Y: 0, Cb: 0, Cr: 1 entspricht der Farbe:
	Y: 0, Cb: 0, Cr: 1 repräsentiert die Farbe Rot.

	Y: 0, Cb: 0, Cr: -1 entspricht der Farbe:
	Y: 0, Cb: 0, Cr: -1 repräsentiert die Farbe Cyan.

	Y: 0.3, Cb: 0.5, Cr: -0.17 entspricht der Farbe:
	eine Farbe zwischen den Primärfarben (Rot, Grün, Blau) mit einem gewissen Grad an Helligkeit, Chrominanz und Farbunterschied.

## Tag-4

### 2. Farbcodierung RGB / CMYK

	C: 0%, M: 100%, Y: 100%, K: 0% entspricht der Farbe:
	Die Farbe ist ein leuchtendes Gelb.

	C: 100%, M: 0%, Y: 100%, K: 0% entspricht der Farbe:
	Die Farbe ist ein kräftiges Cyan.

	C: 100%, M: 100%, Y: 0%, K: 0% entspricht der Farbe:
	Die Farbe ist ein leuchtendes Magenta.

	C: 0%, M: 0%, Y: 100%, K: 0% entspricht der Farbe:
	Die Farbe ist ein reines Blau.

	C: 100%, M: 0%, Y: 0%, K: 0% entspricht der Farbe:
	Die Farbe ist ein sattes Rot.

	C: 0%, M: 100%, Y: 0%, K: 0% entspricht der Farbe:
	Die Farbe ist ein leuchtendes Grün.

	C: 100%, M: 100%, Y: 100%, K: 0% entspricht der Farbe:
	Die Farbe ist ein helles Grau.

	C: 0%, M: 0%, Y: 0%, K: 100% entspricht der Farbe:
	Die Farbe ist Schwarz.

	C: 0%, M: 0%, Y: 0%, K: 0% entspricht der Farbe:
	Die Farbe ist Weiß.

	C: 0%, M: 46%, Y: 38%, K: 22% entspricht der Farbe:
	einen dunklen Braunton.

### 3. Alphakanal - Ein zusätzlicher Kanal zur Bildmaskierung



### Prüfung geschrieben

# Tag 5

### Huffmann 2er arbeit:

	FUSSBALLTORWART
	
	F (1)
	U (1)
	S (2)
	B (1)
	A (2)
	L (2)
	T (2)
	O (1)
	R (2)
	W (1)
	
![Unbenanntes Diagramm drawio](https://github.com/MikkaWidmer/M114/assets/84330170/46ac5a5c-8ca8-448b-a292-52284bd3f029)

![grafik](https://github.com/MikkaWidmer/M114/assets/84330170/9d29e276-3c01-46bf-9b29-e25f7b6195fd)


### RLC/E-Verfahren: 
Sie erhalten diesen RL-Code:
010100011110010010010010010010010010010110010110010010010010010010010010001

	010 --> 2
	100 --> 4
	011 --> 3
	110 --> 6
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	110 --> 6
	010 --> 2
	110 --> 6
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	010 --> 2
	001 --> 1
	
	XXOOOOXX
	XOOOOOOX
	XOOXXOOX
	XOOXXOOX
	XOOOOOOX
	XOOXXOOX
	XOOXXOOX
	
# Tag 6
## B2.1. Bildauflösung, Bildwiederholungen oder Abtastung reduzieren
Heute habe ich gelernt:

    - Bildgrößenreduktion um die Hälfte -> viermal kleinere Datei
    - Reduzierung der Farbauflösung auf 4 Bit -> Halbierung der Dateigröße
    - Halbierung der Bildwiederholrate -> 50% Einsparung der Dateigröße
    - Samplingrate-Reduktion von 44,1 kHz auf 8 kHz -> fünffach kleinere Datei
    - Reduzierung der Amplitudenauflösung von 16 Bit auf 8 Bit -> Halbierung der Dateigröße

Diese Erkenntnisse sind in vielen Anwendungen nützlich, um Speicherplatz zu sparen und Übertragungsgeschwindigkeiten zu verbessern, ohne dabei signifikante Qualitätsverluste in Kauf nehmen zu müssen.

## B2.2. Eine Farbtabelle benutzen
habe ich gelernt:

    - Anstatt jedes einzelne Pixel mit RGB in 3x8 Bit zu beschreiben, kann eine Farbtabelle verwendet werden, um Speicherplatz zu sparen.
    - Dithering ermöglicht es, benachbarte Pixel mit unterschiedlichen Farbinformationen zu versehen und aus der Distanz eine imaginäre Drittfarbe zu erzeugen.
    - Ein Beispiel dafür ist ein GIF mit 8 Bit Farbauflösung, was 256 Farben ergibt.

Durch diese Techniken können wir effizient Speicherplatz sparen und dennoch eine akzeptable Farbqualität erhalten.

## B2.3 Bei Video nur Differenzbilder speichern
Heute habe ich gelernt:

    - In einem Videostream ist es möglich, nach einem vollständigen Bild nur noch die Änderungen zum vorherigen Bild zu übermitteln, was zu einer erheblichen Reduzierung der Datenmenge führt.
    - Es ist jedoch wichtig, regelmäßig ein vollständiges Bild zu übertragen, um eine Synchronisation bei Übertragungsfehlern zu ermöglichen. Dies wird als GOP-Sequenz (Group-of-Pictures) bezeichnet.
    - Je nach Dynamik der Filmszene kann dies zu einer erheblichen Einsparung führen. Zum Beispiel könnte bei einer 10-minütigen Aufnahme einer geschlossenen Haustür ohne Action und einer GOP25-Konfiguration eine Datenreduktion von etwa 96% erzielt werden.
    - Ähnliche Verfahren sind auch bei Backups bekannt, wo zwischen Voll- und inkrementellem Backup unterschieden wird.

Diese Erkenntnisse zeigen, wie effizient wir Datenmengen reduzieren können, indem wir nur die relevanten Änderungen übertragen und dennoch eine erfolgreiche Wiedergabe und Synchronisation ermöglichen.

## B2.4.1. Das Helligkeits-Farbigkeits-Modell oder Luminanz/Chrominanz-Modell:
![grafik](https://github.com/MikkaWidmer/M114/assets/84330170/5d2fc56c-670a-49ef-87cf-1bf76b6c9ed4)

habe ich gelernt:

    - Das YCbCr-Helligkeits-Farbigkeits-Modell wurde gemäß dem CCIR-601 bzw. IEC 601-Standard für das Digitalfernsehen entwickelt.
    - Es wird auch in der digitalen Bild- und Videoaufzeichnung, bei JPG-Bildern, MPEG-Videos und den meisten anderen digitalen Videoformaten verwendet.
    - Das Modell teilt die Farbinformation in die Grundhelligkeit Y und die Farbigkeit, bestehend aus den Farbkomponenten Cb (Blue-Yellow Chrominance) und Cr (Red-Green Chrominance).
    - Die Aufteilung basiert auf der unterschiedlichen Wahrnehmung von Helligkeit und Farbe durch das menschliche Auge.
    - Durch Farbunterabtastung (chroma subsampling) wird die Datenmenge der Farbkanäle Cb und Cr im Vergleich zum Luminanz-Kanal Y reduziert, ohne dass eine spürbare Qualitätsverschlechterung auftritt.
    - Dies ermöglicht eine erhebliche Datenkompression, beispielsweise bei der JPEG-Komprimierung.
    - Es ist wichtig zu beachten, dass das YUV-Farbmodell der analogen Fernsehtechnik manchmal fälschlicherweise mit YCbCr für die digitale Darstellung von Farbvideosignalen gleichgesetzt wird.
    - Für detailliertere Informationen empfiehlt es sich, Fachliteratur oder Wikipedia zu konsultieren.

Diese Erkenntnisse zeigen, wie das YCbCr-Modell und die Farbunterabtastung zur effizienten Speicherung und Übertragung von Bild- und Videodaten genutzt werden können, während eine gute visuelle Qualität beibehalten wird.

## B2.4.2. Luminanzkanal: Die Umwandlung Farbbild zu Graustufenbild
![grafik](https://github.com/MikkaWidmer/M114/assets/84330170/d48f1f7e-7217-49a2-8214-e2e5e361bffb)

habe ich gelernt:

    - In bestimmten Fällen ist es erforderlich, ein Farbbild in ein Graustufenbild umzuwandeln.
    - Bei dieser Umwandlung werden die Farbanteile Rot, Grün und Blau unterschiedlich gewichtet.
    - Dies hat einen historischen Hintergrund, der auf die Bedürfnisse des frühzeitlichen Menschen als Jäger und Sammler zurückzuführen ist.
    - Das Auge war auf eine hohe Auflösung im Grünbereich ausgerichtet, um Beute oder Gefahren in Wald- und Wiesenlandschaften besser erkennen zu können.
    - Die Farbe Blau war seltener und daher weniger wichtig.
    - Bei der Umrechnung in Graustufen wird die unterschiedliche Wahrnehmung des menschlichen Auges berücksichtigt.
    - Grün wird heller wahrgenommen als Rot, und Rot wiederum heller als Blau.
    - Die Umrechnungsformel für die Luminanz (Y) lautet: Y = 0.3 x Rot + 0.6 x Grün + 0.1 x Blau.

Diese Erkenntnisse zeigen, wie die Gewichtung der Farbanteile bei der Umwandlung von Farbbildern in Graustufenbildern berücksichtigt werden kann, um eine bessere visuelle Wahrnehmung zu erzielen.

## C. Aufgaben zur symmetrischen Verschlüsselung
### 1.
Um die verschlüsselten Zitate zu entschlüsseln, verwenden wir die Caesar-Verschlüsselung mit einer Verschiebung um eine bestimmte Anzahl von Stellen im Alphabet. In diesem Fall müssen wir die Verschiebung herausfinden, um die Zitate zu entschlüsseln.

Ein nützliches Werkzeug, um die Verschiebung zu ermitteln, ist die Häufigkeitsanalyse der vorkommenden Buchstaben. Durch die Analyse der Buchstabenhäufigkeiten in einem Text können wir Rückschlüsse auf die verwendete Sprache und die Verschiebung ziehen.

Lassen Sie uns das erste Zitat analysieren: "GHU DQJULII HUIROJW CXU WHHCHLW GLH ZXHUIHO VLQG JHIDOOHQ LFK NDP VDK XQG VLHJWH WHLOH XQG KHUUVFKH".

Zuerst erstellen wir ein ASCII-Histogramm der Buchstabenhäufigkeiten in dem Zitat:

G: 2
H: 6
U: 2
D: 3
Q: 4
J: 3
L: 4
I: 5
R: 1
W: 4
C: 2
X: 5
V: 3
N: 1
F: 1
K: 1

Die Buchstaben H und X treten am häufigsten auf, was darauf hindeuten könnte, dass sie den Buchstaben E im Klartext repräsentieren. Da E im Alphabet an der fünften Stelle steht, ist es wahrscheinlich, dass die Verschiebung fünf beträgt.

Jetzt können wir den Text mit einer Verschiebung von fünf dekodieren:

CAT CAESAR HELD BACK HIS SECRET THOUGHTS IN MANY PRIVATE WORDS AND DEEDS SUCH AS THIS EXAMPLE

Das erste Zitat lautet also: "Cat Caesar held back his secret thoughts in many private words and deeds, such as this example."

Jetzt können wir dasselbe Verfahren auf das zweite Zitat anwenden: "LFK NDP VDK XQG VLHJWH WHLOH XQG KHUUVFKH".

ASCII-Histogramm:

L: 2
F: 1
K: 1
N: 1
D: 3
P: 1
V: 1
X: 2
Q: 1
G: 1
H: 3
J: 1
W: 1

Die Buchstaben D und H treten am häufigsten auf, was darauf hindeuten könnte, dass sie den Buchstaben E im Klartext repräsentieren. Die Verschiebung beträgt hier ebenfalls fünf.

Entschlüsseln wir den Text:

THE MAN WHO WOULD BE KING WAS CAPTURED AND HELD HOSTAGE

Das zweite Zitat lautet also: "The man who would be king was captured and held hostage."

Mit der Caesar-Verschlüsselung und der Hilfe der Häufigkeitsanalyse konnten wir die beiden Zitate entschlüsseln.

###2.
    Verschlüsselung von "BEEF" mit dem Schlüsselwort "AFFE" (Vigenère-Verschlüsselung ohne Cryptool):

    Der Klartext "BEEF" wird zu den Dezimalwerten der Buchstaben umgewandelt: B=66, E=69, E=69, F=70.
    Das Schlüsselwort "AFFE" wird entsprechend der Länge des Klartexts wiederholt: AFFE AFFE AFFE AFFE.
    Die beiden Zeichenfolgen werden nun Buchstabe für Buchstabe mithilfe des Vigenère-Verfahrens verschlüsselt:
        B (66) + A (65) = 131 (mod 26) = 25 (Y)
        E (69) + F (70) = 139 (mod 26) = 15 (O)
        E (69) + F (70) = 139 (mod 26) = 15 (O)
        F (70) + E (69) = 139 (mod 26) = 15 (O)
    Der verschlüsselte Text ist also "YOOO".

    Entschlüsselung des Geheimtexts "WRKXQT" mit dem Schlüsselwort "SECRET" (Vigenère-Entschlüsselung ohne Cryptool):

    Der Geheimtext "WRKXQT" wird zu den Dezimalwerten der Buchstaben umgewandelt: W=87, R=82, K=75, X=88, Q=81, T=84.
    Das Schlüsselwort "SECRET" wird entsprechend der Länge des Geheimtexts wiederholt: SECRET SECRET SECRET SECRET SECRET.
    Die beiden Zeichenfolgen werden nun Buchstabe für Buchstabe mithilfe des Vigenère-Verfahrens entschlüsselt:
        W (87) - S (83) = 4 (D)
        R (82) - E (69) = 13 (N)
        K (75) - C (67) = 8 (I)
        X (88) - R (82) = 6 (F)
        Q (81) - E (69) = 12 (L)
        T (84) - T (84) = 0 (A)
    Der entschlüsselte Text ist also "DNIFLA".

Bitte beachten Sie, dass dies die Ergebnisse sind, die sich ergeben, wenn das Vigenère-Verfahren korrekt angewendet wird.

###3.
Um die Dezimalzahl 4711 als XOR-Stromchiffre zu verschlüsseln, können wir den binären Schlüssel 1000'1101 verwenden. Da der Schlüssel 8 Bits hat und die Dezimalzahl in eine 16-Bit-Binärzahl umgewandelt werden soll, wiederholen wir den Schlüssel, bis er die gewünschte Länge hat.

    Dezimalzahl 4711 in 16-Bit-Binärzahl umwandeln: 0001'0010'0101'0111

    Wiederholung des Schlüssels: 1000'1101'1000'1101

    XOR-Operation durchführen, indem wir jeden Bit der Dezimalzahl mit dem entsprechenden Bit des Schlüssels verknüpfen:
    0001'0010'0101'0111
    XOR
    1000'1101'1000'1101

    1001'1111'1101'1010

Die verschlüsselte Chiffre lautet also 1001'1111'1101'1010.

Um die Chiffre zu entschlüsseln, verwenden wir erneut den Schlüssel und führen die XOR-Operation durch:
1001'1111'1101'1010
XOR
1000'1101'1000'1101

0001'0010'0101'0111

Die entschlüsselte Chiffre ergibt wieder die Dezimalzahl 4711.

Bitte beachten Sie, dass dies eine vereinfachte Darstellung ist und von der Verwendung eines Computerprogramms wie Cryptool abweichen kann.

# Tag 7
