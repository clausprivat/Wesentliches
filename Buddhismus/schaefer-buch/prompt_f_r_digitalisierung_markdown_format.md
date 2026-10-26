# Standard-Prompt für die Digitalisierung (PDF-Scan zu Markdown-ZIP)

Kopiere diesen Prompt und füge ihn zusammen mit deinem nächsten PDF-Scan (z. B. Seiten 81 bis 90) im Chat ein.

---

### Prompt:

> **Bitte verarbeite die angehängte PDF-Datei (Seiten XXX bis YYY) exakt nach folgenden Regeln und erstelle direkt das ZIP-Archiv zum Download:**
>
> 1. **Dateien & Volltext:** Jede Buchseite wird zu einer eigenen Datei `page_XXX.md` (z. B. `page_081.md`). Der Text muss 100 % vollständig, ungekürzt und zeichengenau extrahiert werden.
> 2. **Page-Marker:**
>    - Datei-Beginn: `<!-- PAGE_START: XXX -->`
>    - Datei-Ende: Seitenzahl `XXX` gefolgt von `<!-- PAGE_END: XXX -->`
> 3. **Typografie & Stilregeln:**
>    - **Sprecherrollen:** Rollen wie **FRITZ:**, **HANS:**, **RUTH:** immer in Fettdruck (`**NAME:**`).
>    - **Pāli-Begriffe & Buchtitel:** Alle Pāli-Wörter (z. B. _nibbāna_, _mettā_, _pema_, _citta_), Quellentitel (z. B. _M 60_, _S 42,11_) und Werktitel strikt kursiv (`_Text_`).
>    - **Zitate & Lehrreden:** Blockquotes (`>`) für alle strukturierten Zitate, Verse, Lehrreden-Passagen und Gedichte.
>    - **Fußnoten:** HTML-Hochzahlen (`<sup>1</sup>`, `<sup>2</sup>`) im Fließtext und unten über der Seitenzahl.
> 4. **Ausgabe:** Generiere das ZIP-Archiv direkt im Python-Code, damit der grafische Download-Button in der Benutzeroberfläche angezeigt wird.