# Arroword
A simple arroword (swedish crossword) viewer - Ein einfacher Schwedenrätselbetrachter

## Verwendung:
- Grafik eines '16×16' Rätsel als png unter 'crosswords/' abspeichern.
- In Leserichtung (von links nach rechts, oben nach unten) alle Felder in eine Reihe schreiben, wobei Fragen und leere Felder durch eine Raute (#) ersetzt werden.
- In aufsteigender Reihenfolge die Koordinaten als Hexadezimalzahl (10=A,...15=F) der Lösungsfelder an diese Zeichenreihe anhängen. Das Feld links oben ist 00 und das Feld rechts unten ist FF.
- Die Zeichenreihe unter gleichem Namen wie die Grafik als txt unter 'crosswords/' abspeichern.
- In der 'index.htm' den Namen in die Array 'var files=[]' einfügen.
