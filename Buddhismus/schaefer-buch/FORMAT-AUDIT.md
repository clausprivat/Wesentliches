# Format-Audit der Markdown-Seiten

**Stand:** 26.10.2026, 10:20  
**Grundlage:** 70 Seiten in `pages/` (`page_001.md` … `page_070.md`)  
**Geprüft:** Kursiv- und Fettmarker, Blockzitate, Überschriften, Fußnoten, Seitenmarker, Seitenzahlen, Dateinamen

## Kurzbefund

Die Seiten sind **nicht einheitlich**. Es gibt zwei klar getrennte Formatierungsschulen:

- **Stil A – Seiten 1–41:** Kursiv mit `*…*`, keine Fettschrift, keine Blockzitate, Überschriften als Klartext-Großbuchstaben, Fußnoten mit Unicode-Ziffern und `---`-Trenner.
- **Stil B – Seiten 42–70:** Kursiv mit `_…_`, Sprecher fett (`**FRITZ:**`), Blockzitate mit `>`, Überschriften mit `#`/`##`/`###`, Fußnoten mit `<sup>` und `***`-Trenner.

Beide Stile sind **in sich** weitgehend konsistent. Keine Seite mischt `*` und `_`. Die Inkonsistenz liegt also zwischen den beiden Bereichen, nicht innerhalb einer einzelnen Seite.

Die Seiten 61–70 sind während des Audits dazugekommen. Sie folgen bereits Stil B und sind in sich konsistent (Fußnoten 5–8 fortlaufend, Seitenmarker und Seitenzahlen vorhanden).

## Vergleich der Konventionen

| Merkmal | Stil A (Seiten 1–41) | Stil B (Seiten 42–70) |
|---|---|---|
| Kursiv | `*Text*` – 238 Stellen | `_Text_` – 107 Stellen |
| Fett | gar nicht verwendet | `**HANS:**` usw. – 145 Stellen |
| Zitate / Verse | inline, kursiv | `>`-Blockzitat |
| Überschriften | Großbuchstaben ohne `#` | `#` = Teil, `##` = Abschnitt, `###` = Unterabschnitt |
| Fußnoten im Text | Unicode-Ziffern (¹²) | `<sup>12</sup>` |
| Fußnoten-Trenner | `---` | `***` |
| Seitenmarker | vorhanden | vorhanden |
| Seitenzahl am Ende | vorhanden (außer Titel/Leerseiten 1–4) | vorhanden |
| Dateiname | `page_001.md` (3-stellig) | 42–50: `page_42.md` (2-stellig); 51–70: 3-stellig |

## Pro-Seite-Matrix

| Seite | Stil | Kursiv | Fett | Zitat | Überschrift | Fußnote | Marker | Seitenzahl | Dateiname | Auffällig |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | A | `*` (2) | – | – | – | – | ✓ | – | ✓ | – |
| 2 | A | – | – | – | – | – | ✓ | – | ✓ | – |
| 3 | A | – | – | – | – | – | ✓ | – | ✓ | – |
| 4 | A | – | – | – | – | – | ✓ | – | ✓ | – |
| 5 | A | `*` (2) | – | – | – | – | ✓ | ✓ | ✓ | – |
| 6 | A | `*` (7) | – | – | – | – | ✓ | ✓ | ✓ | – |
| 7 | A | `*` (19) | – | – | – | – | ✓ | ✓ | ✓ | ` - ` statt `–` (1×) |
| 8 | A | `*` (6) | – | – | – | – | ✓ | ✓ | ✓ | ` - ` statt `–` (1×) |
| 9 | A | `*` (8) | – | – | Klartext (4) | Unicode + `---` (3) | ✓ | ✓ | ✓ | ` - ` statt `–` (1×); Überschrift als Klartext (4) |
| 10 | A | `*` (12) | – | – | – | Unicode + `---` (3) | ✓ | ✓ | ✓ | ` - ` statt `–` (1×) |
| 11 | A | `*` (9) | – | – | – | Unicode + `---` (4) | ✓ | ✓ | ✓ | ` - ` statt `–` (6×) |
| 12 | A | `*` (3) | – | – | – | Unicode + `---` (2) | ✓ | ✓ | ✓ | – |
| 13 | A | `*` (1) | – | – | – | Unicode + `---` (3) | ✓ | ✓ | ✓ | ` - ` statt `–` (3×) |
| 14 | A | `*` (3) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | ` - ` statt `–` (2×) |
| 15 | A | `*` (1) | – | – | – | Unicode + `---` (3) | ✓ | ✓ | ✓ | ` - ` statt `–` (3×) |
| 16 | A | `*` (4) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | – |
| 17 | A | `*` (10) | – | – | – | Unicode + `---` (3) | ✓ | ✓ | ✓ | – |
| 18 | A | `*` (9) | – | – | – | Unicode + `---` (5) | ✓ | ✓ | ✓ | – |
| 19 | A | `*` (21) | – | – | – | Unicode + `---` (9) | ✓ | ✓ | ✓ | – |
| 20 | A | `*` (9) | – | – | – | Unicode + `---` (5) | ✓ | ✓ | ✓ | – |
| 21 | A | `*` (12) | – | – | – | Unicode + `---` (5) | ✓ | ✓ | ✓ | Fußnote 43 nicht hochgestellt |
| 22 | A | `*` (9) | – | – | – | Unicode + `---` (6) | ✓ | ✓ | ✓ | – |
| 23 | A | `*` (1) | – | – | – | Unicode + `---` (2) | ✓ | ✓ | ✓ | – |
| 24 | A | `*` (7) | – | – | – | Unicode + `---` (5) | ✓ | ✓ | ✓ | – |
| 25 | A | `*` (5) | – | – | – | Unicode + `---` (2) | ✓ | ✓ | ✓ | – |
| 26 | A | `*` (3) | – | – | – | Unicode + `---` (2) | ✓ | ✓ | ✓ | – |
| 27 | A | `*` (1) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | – |
| 28 | A | `*` (2) | – | – | – | Unicode + `---` (4) | ✓ | ✓ | ✓ | – |
| 29 | A | `*` (3) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | – |
| 30 | A | `*` (2) | – | – | Klartext (1) | – | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 31 | A | `*` (4) | – | – | Klartext (1) | Unicode + `---` (3) | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 32 | A | `*` (1) | – | – | Klartext (1) | – | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 33 | A | `*` (6) | – | – | Klartext (1) | Unicode + `---` (1) | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 34 | A | `*` (6) | – | – | – | Unicode + `---` (2) | ✓ | ✓ | ✓ | – |
| 35 | A | `*` (16) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | – |
| 36 | A | `*` (5) | – | – | Klartext (1) | Unicode + `---` (1) | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 37 | A | – | – | – | Klartext (1) | Unicode + `---` (3) | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 38 | A | – | – | – | – | Unicode + `---` (6) | ✓ | ✓ | ✓ | – |
| 39 | A | `*` (13) | – | – | Klartext (1) | Unicode + `---` (4) | ✓ | ✓ | ✓ | Überschrift als Klartext (1) |
| 40 | A | `*` (10) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | – |
| 41 | A | `*` (6) | – | – | – | Unicode + `---` (1) | ✓ | ✓ | ✓ | – |
| 42 | B | `_` (15) | Sprecher (11) | `>` (4) | – | – | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 43 | B | `_` (3) | Sprecher (1) + sonstige (1) | – | `##` | `<sup>` + `***` (2) | ✓ | ✓ | ✗ | Dateiname ohne führende Null; `##`-Überschrift; `**S 42,7**` fett |
| 44 | B | `_` (3) | Sprecher (8) | – | – | `<sup>` + `***` (2) | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 45 | B | `_` (10) | Sprecher (8) | `>` (5) | – | `<sup>` + `***` (3) | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 46 | B | `_` (12) | Sprecher (5) | `>` (12) | – | – | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 47 | B | – | Sprecher (4) | – | – | `<sup>` + `***` (3) | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 48 | B | `_` (6) | Sprecher (4) | – | – | `<sup>` + `***` (1) | ✓ | ✓ | ✗ | Dateiname ohne führende Null; Fußnote 105 fehlt |
| 49 | B | `_` (2) | Sprecher (2) | – | – | `<sup>` + `***` (7) | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 50 | B | `_` (3) | Sprecher (1) | `>` (1) | – | – | ✓ | ✓ | ✗ | Dateiname ohne führende Null |
| 51 | B | `_` (3) | Sprecher (7) | – | `#` + `##` | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |
| 52 | B | `_` (9) | Sprecher (4) + sonstige (1) | `>` (6) | – | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | `**S 3,8 – MALLIKĀ**` fett |
| 53 | B | `_` (1) | Sprecher (19) | – | – | – | ✓ | ✓ | ✓ | – |
| 54 | B | `_` (3) | Sprecher (4) | `>` (5) | `###` | – | ✓ | ✓ | ✓ | – |
| 55 | B | `_` (6) | – | `>` (11) | – | – | ✓ | ✓ | ✓ | – |
| 56 | B | `_` (8) | Sprecher (2) | `>` (15) | – | – | ✓ | ✓ | ✓ | – |
| 57 | B | – | Sprecher (9) | – | – | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |
| 58 | B | `_` (3) | Sprecher (2) | – | – | – | ✓ | ✓ | ✓ | – |
| 59 | B | – | – | – | – | – | ✓ | ✓ | ✓ | – |
| 60 | B | `_` (1) | Sprecher (6) | – | – | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |
| 61 | B | – | Sprecher (2) | `>` (5) | `###` | – | ✓ | ✓ | ✓ | – |
| 62 | B | `_` (6) | Sprecher (14) | – | – | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |
| 63 | B | `_` (2) | Sprecher (11) | – | – | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |
| 64 | B | `_` (2) | Sprecher (3) | `>` (5) | – | – | ✓ | ✓ | ✓ | – |
| 65 | B | `_` (2) | Sprecher (2) | `>` (5) | – | – | ✓ | ✓ | ✓ | – |
| 66 | B | `_` (3) | Sprecher (5) | `>` (5) | `###` | – | ✓ | ✓ | ✓ | – |
| 67 | B | `_` (1) | Sprecher (5) | – | – | – | ✓ | ✓ | ✓ | – |
| 68 | B | `_` (2) | Sprecher (4) | `>` (1) | `###` | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |
| 69 | B | `_` (1) | – | `>` (15) | – | – | ✓ | ✓ | ✓ | – |
| 70 | B | – | Sprecher (2) | `>` (10) | – | `<sup>` + `***` (1) | ✓ | ✓ | ✓ | – |

## Einzelfehler / konkrete Abweichungen

| Seite(n) | Befund | Soll |
|---|---|---|
| 42–50 | Dateinamen ohne führende Null (`page_42.md` statt `page_042.md`) | 3-stellig, wie 1–41 und 51–70 |
| 43 | `## VIII. …` als Markdown-Überschrift, obwohl die Abschnitte I–VII auf Seiten 30–39 Klartext sind | einheitlich: alle Abschnitte `##` oder alle Klartext |
| 43 | `**S 42,7**` fett mitten im Satz; im Buch eine eigene, zentrierte Quellenzeile ohne Fettung | eigener Absatz, nicht fett |
| 52 | `**S 3,8 – MALLIKĀ**` fett mitten im Satz | eigener Absatz, nicht fett |
| 48 | Fußnote 105 fehlt (Referenz `…Familie<sup>105</sup>` vorhanden, Fußnotentext nicht) | Fußnote 105 ergänzen |
| 21 | Fußnote `43 MyliusLit., S. 9.` mit normaler Ziffer statt `⁴³` | `⁴³` |
| 7, 8, 9, 10, 11, 13, 14, 15 | Gedankenstrich als ` - ` statt `–` (1–6× pro Seite) | `–` |
| 9, 30, 31, 32, 33, 36, 37, 39 | Abschnittsüberschriften als Klartext, nicht als `#`/`##` | einheitliche Überschriften-Hierarchie |
| alle A-Seiten mit Dialogen (25 Seiten, 147 Sprecherzeilen) | Sprecher nicht fett (`FRITZ:`), während B `**FRITZ:**` verwendet | eine Konvention |
| alle B-Seiten | `_` statt `*`, `<sup>` statt Unicode, `***` statt `---`, `>`-Zitate | eine Konvention |

## Inhaltliche Auffälligkeiten (nur Randnotiz, keine Formatprüfung)

Auf Seite 42 (Scan liegt vor) sind Kursivstellen und Zeichen verloren gegangen:

- Zeilenanfang: `gahapati und »gahapatikās«` – das öffnende `»` fehlt, `gahapati` ist nicht kursiv, `gahapatikās` ist ein Tippfehler (richtig: `gahapatikā`).
- `Zuflucht` ist im Scan kursiv, im MD nicht.
- `»upāsaka/upāsika«` ist im Scan kursiv, im MD nicht.
- `anu-sari` statt `anu-sārī`.

## Empfehlung

Vor dem Weiterarbeiten sollte **eine** Konvention festgelegt werden. Zwei sinnvolle Varianten:

1. **Stil B fortführen** (empfohlen, weil er die Buchtypografie besser abbildet: Sprecher fett, lange Zitate als Block):
   - Seiten 1–41: Sprecher fett setzen, Überschriften auszeichnen, lange Zitate als `>`-Block.
   - Seiten 42–50: Dateinamen auf 3 Stellen umbenennen.
   - Fußnoten einheitlich auf `<sup>` + `***` oder auf Unicode + `---` festlegen.

2. **Stil A fortführen** (weniger Eingriffe in den bereits fertigen Teil 1–41):
   - Seiten 42–70: `_` → `*`, Fettungen entfernen, `>`-Blöcke auflösen, Fußnoten auf Unicode + `---` umstellen.
   - Dafür geht die im Buch vorhandene Fettung der Sprecher verloren.

Ich würde Variante 1 empfehlen, aber erst nach deiner Entscheidung normalisieren.
