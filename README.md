# M114

[Tag 1](#Tag-1)

[Tag 2](#Tag-2)

[Tag 3](#Tag-3)

[Tag 4](#Tag-4)

[Tag 5](#Tag-5)

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

![Unbenanntes Diagramm drawio-1](https://github.com/MikkaWidmer/M114/assets/84330170/68d7b93d-e277-4a67-bfbd-968f384a3ca4)


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
habe ich gelernt, dass die Reduzierung der Bildgröße um die Hälfte zu einer viermal kleineren Datei führt. Die Verringerung der Farbauflösung auf 4 Bit halbiert die Dateigröße. Eine Halbierung der Bildwiederholrate spart 50% der Dateigröße ein. Die Reduzierung der Samplingrate von 44,1 kHz auf 8 kHz führt zu einer fünffach kleineren Datei, und die Verringerung der Amplitudenauflösung von 16 Bit auf 8 Bit halbiert die Dateigröße erneut. Diese Erkenntnisse sind in vielen Anwendungen hilfreich, um Speicherplatz zu sparen und Übertragungsgeschwindigkeiten zu verbessern, ohne signifikante Qualitätsverluste in Kauf nehmen zu müssen.

## B2.2. Eine Farbtabelle benutzen
habe ich gelernt, dass anstelle der Beschreibung jedes einzelnen Pixels mit den drei Grundfarben RGB in 3x8Bit auch eine Farbtabelle verwendet werden kann. Dadurch kann Speicherplatz eingespart werden. Mit Dithering können benachbarte Pixel mit unterschiedlichen Farbinformationen versehen werden, um aus der Distanz eine imaginäre Drittfarbe zu erzeugen. Ein Beispiel dafür ist ein GIF mit 8 Bit Farbauflösung, was 256 Farben ergibt.

## B2.3 Bei Video nur Differenzbilder speichern
habe ich gelernt, dass es möglich ist, in einem Videostream nach einem vollständigen Bild nur noch die Änderungen zum vorherigen Bild zu übermitteln. Dies ermöglicht eine erhebliche Reduzierung der Datenmenge. Es ist jedoch wichtig, regelmäßig ein vollständiges Bild zu übertragen, um eine Synchronisation bei Übertragungsfehlern zu ermöglichen. Dies wird als GOP-Sequenz (Group-of-Pictures) bezeichnet. Je nach Dynamik der Filmszene kann dies zu einer erheblichen Einsparung führen. Zum Beispiel könnte bei einer 10-minütigen Aufnahme einer geschlossenen Haustür ohne Action und einer GOP25-Konfiguration eine Datenreduktion von etwa 96% erzielt werden. Ein ähnliches Verfahren kennen wir auch bei Backups, wo zwischen Voll- und inkrementellem Backup unterschieden wird.

## B2.4.1. Das Helligkeits-Farbigkeits-Modell oder Luminanz/Chrominanz-Modell:
![grafik](https://github.com/MikkaWidmer/M114/assets/84330170/5d2fc56c-670a-49ef-87cf-1bf76b6c9ed4)

habe ich gelernt, dass das YCbCr-Helligkeits-Farbigkeits-Modell gemäß dem CCIR-601 bzw. IEC 601-Standard für das Digitalfernsehen entwickelt wurde. Es wird auch in der digitalen Bild- und Videoaufzeichnung, bei JPG-Bildern, MPEG-Videos und den meisten anderen digitalen Videoformaten verwendet. Das Modell teilt die Farbinformation in die Grundhelligkeit Y und die Farbigkeit, bestehend aus den Farbkomponenten Cb (Blue-Yellow Chrominance) und Cr (Red-Green Chrominance).

Die Aufteilung basiert auf der unterschiedlichen Wahrnehmung von Helligkeit und Farbe durch das menschliche Auge. Das Auge erkennt geringe Helligkeitsunterschiede besser als kleine Farbtonunterschiede und diese wiederum besser als kleine Farbsättigungsunterschiede. Daher kann ein Text mit grauer Schrift auf schwarzem Hintergrund gut gelesen werden, während blauer Text auf rotem Hintergrund bei gleicher Grundhelligkeit sehr schwer lesbar ist.

Die Verwendung des YCbCr-Modells nutzt diese Analogie zum menschlichen Sehsinn aus. Durch Farbunterabtastung (chroma subsampling) wird die Abtastrate und somit die Datenmenge der Farbkanäle Cb und Cr im Vergleich zum Luminanz-Kanal Y reduziert, ohne dass eine spürbare Qualitätsverschlechterung auftritt. Dies ermöglicht eine erhebliche Datenkompression, beispielsweise bei der JPEG-Komprimierung.

Es ist wichtig anzumerken, dass das YUV-Farbmodell der analogen Fernsehtechnik manchmal fälschlicherweise mit YCbCr für die digitale Darstellung von Farbvideosignalen gleichgesetzt wird. Für die folgenden Erklärungen verwenden wir das ähnliche YUV-Farbmodell. Für detailliertere Informationen empfiehlt es sich, Fachliteratur oder Wikipedia zu konsultieren.

## B2.4.2. Luminanzkanal: Die Umwandlung Farbbild zu Graustufenbild
![grafik](https://github.com/MikkaWidmer/M114/assets/84330170/d48f1f7e-7217-49a2-8214-e2e5e361bffb)

habe ich gelernt, dass es in bestimmten Fällen erforderlich ist, ein Farbbild in ein Graustufenbild umzuwandeln. Bei dieser Umwandlung werden die Farbanteile Rot, Grün und Blau unterschiedlich gewichtet. Dies hat einen historischen Hintergrund, der auf die Bedürfnisse des frühzeitlichen Menschen als Jäger und Sammler zurückzuführen ist. Das Auge war besonders auf eine hohe Auflösung im Grünbereich ausgerichtet, um Beute oder Gefahren in Wald- und Wiesenlandschaften besser erkennen zu können. Die Farbe Blau war seltener und daher weniger wichtig.

Bei der Umrechnung in Graustufen muss diese unterschiedliche Wahrnehmung des menschlichen Auges berücksichtigt werden. Grün wird heller wahrgenommen als Rot, und Rot wiederum heller als Blau. Diese Gewichtung wird in der folgenden Umrechnungsformel verwendet: Luminanz (Y) = 0.3 x Rot + 0.6 x Grün + 0.1 x Blau.
