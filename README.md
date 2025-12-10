# UOIA-Quiz
Lern-Quiz für die Prüfung. Einfach und unkompliziert lernen von überall.

Das UOIA-Quiz ist ein webbasiertes Lern-Tool für die Ausbildung im Bereich Umweltverwaltung.
Aufruf erfolgt über:
https://thecaptainlost.github.io/UOIA-Quiz/quiz_online.html

# Funktionen:
– Multiple-Choice-Fragen mit Einfach- und Mehrfachauswahl
– Themenauswahl (z. B. BImSchG, KrWG, WHG, VwVfG)
– Auswertung mit Punkteanzeige und Erläuterungen

# Kurze Anleitung: UOIA-Quiz

# 1. Aufruf der „App“

Quiz im Browser öffnen unter:
https://thecaptainlost.github.io/UOIA-Quiz/quiz_online.html

Smartphone:

Seite im Browser öffnen

Über das Browser-Menü → „Zum Startbildschirm hinzufügen“ / „Zum Home-Bildschirm“

Dann erscheint ein Icon wie eine App.

PC/Laptop:

Seite im Browser öffnen

In Edge/Chrome → „Als App installieren“ / „Verknüpfung erstellen“ möglich.

# 2. Fragen beantworten

Oben ein Themengebiet auswählen (z. B. BImSchG, KrWG, WHG, VwVfG, Technologie, Sonstiges).

Eine Frage wird angezeigt, darunter 4 Antwortmöglichkeiten (A–D).

Je nach Hinweis:

„Einfachauswahl“ → genau eine Antwort ankreuzen.

„Mehrfachauswahl“ → es können mehrere Antworten richtig sein.

Auf „Antwort prüfen“ klicken:

richtige/falsche Antworten werden farbig markiert,

eine Erläuterung zur Lösung wird eingeblendet.

Mit „Nächste Frage“ zur nächsten Frage springen.
Oben wird die aktuelle Punktzahl angezeigt.

# 3. Fragen bewerten (Daumen hoch / runter) (Benutzen falls Frage falsch oder verbesserungswürdig)

Unter der Frage gibt es „Frage bewerten“ mit
👍 (gut) und 👎 (überarbeiten).

Ein Klick speichert die Bewertung nur lokal im aktuellen Browser-Fenster.

Über „Bewertungen als CSV“ können alle abgegebenen Bewertungen als Datei heruntergeladen werden (für die spätere Auswertung in Excel).

# 4. Neue Fragen vorschlagen

Unten im Quiz gibt es den Bereich:

„Neue Frage vorschlagen / in den Pool aufnehmen“

Vorgehen:

Bereich aufklappen (anklicken).

Thema auswählen
(z. B. BImSchG, VwVfG, KrWG, WHG, Technologie, Sonstiges).

Fragentyp wählen:

„Einfachauswahl“ (eine richtige Antwort) oder

„Mehrfachauswahl“ (mehrere richtige Antworten).

Frage und die vier Antworten A–D eintragen.

Bei „Richtige Antwort(en)“:

nur A, B, C oder D eingeben,

bei mehreren richtigen Antworten mit Semikolon trennen, z. B. A;C.

Optional eine Erläuterung zur Lösung ergänzen.

Mit „Frage zum Vorschlag-Pool hinzufügen“ speichern.
(Die Vorschläge bleiben zunächst lokal im Browser.)

Über „Vorschläge als CSV“ können alle Vorschläge als Datei heruntergeladen und später in den offiziellen Fragenpool übernommen werden.

## Hinweise für Kolleginnen und Kollegen: Fragelisten und Bewertungen hochladen

Damit wir das UOIA-Quiz gemeinsam verbessern können, gibt es im Repository zwei Ordner:

- `vorschlaege_neu` – hier werden **Vorschlags-Listen** für neue Fragen abgelegt  
- `bewertungen_neu` – hier werden **Bewertungs-Listen** (Daumen hoch/Daumen runter) abgelegt  

Bitte geht wie folgt vor:

---

### 1. Neue Frageliste (Fragevorschläge) aus dem Quiz exportieren und hochladen

1. Das Quiz im Browser öffnen:  
   `https://thecaptainlost.github.io/UOIA-Quiz/quiz_online.html`
2. Unten den Bereich **„Neue Frage vorschlagen / in den Pool aufnehmen“** öffnen.
3. **Thema** auswählen (z. B. BImSchG, VwVfG, KrWG, WHG, Technologie, Sonstiges).
4. **Fragentyp**, **Frage**, die vier Antworten **A–D**, richtige Antwort(en) und **Erläuterung** ausfüllen.  
   - WICHTIG: Richtige Antwort(en) nur als **A, B, C oder D** angeben,  
     bei mehreren mit Semikolon trennen, z. B. `A;C`.
5. Mit **„Frage zum Vorschlag-Pool hinzufügen“** speichern.  
   (Mehrere Fragen können nacheinander ergänzt werden.)
6. Wenn alle Vorschläge eingetragen sind, auf **„Vorschläge als CSV“** klicken.  
   → Es wird eine Datei mit allen vorgeschlagenen Fragen heruntergeladen.
7. Diese Datei im GitHub-Repository hochladen:
   - Im Repo auf den Ordner **`vorschlaege_neu`** klicken  
   - Oben auf **„Add file → Upload files“**  
   - Die CSV-Datei auswählen  
   - Dateinamen z. B. `Vorschlaege_Vorname_YYYY-MM-DD.csv` wählen  
   - Commit-Notiz eintragen (z. B. „Fragevorschläge Vorname 10.12.2025“)  
   - **„Commit changes“** klicken

Die eingegangenen Vorschläge werden später geprüft, fachlich angepasst und bei Eignung in den offiziellen Fragenpool übernommen.

---

### 2. Bewertungen aus dem Quiz exportieren und hochladen

1. Das Quiz im Browser öffnen:  
   `https://thecaptainlost.github.io/UOIA-Quiz/quiz_online.html`
2. Fragen normal bearbeiten und bei Bedarf mit **👍 / 👎** bewerten.
3. Unten auf **„Bewertungen als CSV“** klicken.  
   → Es wird eine Datei heruntergeladen, z. B. `QuizBewertungen_YYYY-MM-DD.csv`.
4. Diese Datei im GitHub-Repository hochladen:
   - Im Repo auf den Ordner **`bewertungen_neu`** klicken  
   - Oben auf **„Add file → Upload files“**  
   - Die CSV-Datei auswählen  
   - Dateinamen z. B. `Bewertungen_Vorname_YYYY-MM-DD.csv` wählen  
   - Commit-Notiz eintragen (z. B. „Bewertungen Vorname 10.12.2025“)  
   - **„Commit changes“** klicken

Die Dateien werden später zentral in Excel ausgewertet (z. B. welche Fragen besonders viele 👎 erhalten haben).

---

### 3. Allgemeine Hinweise

- Bitte **keine personenbezogenen Daten** in Fragen, Erläuterungen oder Dateinamen verwenden.  
- Die zentrale Pflege und Auswertung des Fragenpools erfolgt später getrennt (Excel/CSV-Auswertung).  
- Rückfragen oder Hinweise bitte an die Person richten, die das UOIA-Quiz betreut.

