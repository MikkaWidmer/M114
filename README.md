# M114

[Tag 1](#Tag-1)

[Tag 2](#Tag-2)

[Tag 3](#Tag-3)

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


