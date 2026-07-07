# Sprint #2 — Founder-Dogfood: 21 Tage durch das eigene Produkt

Sprint #1 in diesem Repo lief nach selbst auferlegten Regeln ([SPRINT_LOG.md](SPRINT_LOG.md)). Aus diesem Durchlauf ist [mvpbuilder.io](https://mvpbuilder.io) entstanden.

Sprint #2 dreht den Spieß um: **Der Gründer durchläuft sein eigenes Live-Produkt als ganz normaler User.** Die Regeln kommen diesmal nicht von mir — sie kommen vom System:

- **Silber-Tier, 21 Tage** (ehrlich gescored über die echte Bewerbungs-Pipeline: Profi + nur Idee)
- **Täglicher Prompt** morgens im Postfach → 30–45 Min arbeiten → Check-in
- **2× kein Check-in = automatische Pause** — auch für mich
- **Tag 13: Pflicht-Zwischennachweis (24h Frist) · Tag 21: Finale (48h Frist)**, beide mit manuellem Review

Einträge chronologisch, ein Eintrag pro Sprint-Tag. Ein dokumentierter Miss zählt genauso als Eintrag wie ein Erfolg.

---

# Tag 0 — Vorher-Snapshot: Der Gründer geht durch sein eigenes Produkt

**Datum:** Samstag, 04.07.2026 · **Sprint:** Silber, 21 Tage · **Start:** morgen, So 05.07.

---

## Was hier passiert

Ich betreibe MVP Builder — einen 30-Tage-Sprint mit menschlicher Accountability, damit Devs ihre fast fertigen Projekte wirklich live bringen. MVP Builder selbst ist in so einem Eigendurchlauf entstanden (dieses Repo war der Zeuge). Jetzt gehe ich den nächsten Schritt: **Ich durchlaufe mein eigenes Live-Produkt als ganz normaler User.** Bewerbung über die echte Pipeline, ehrliches Scoring (Profi + nur Idee → Silber, 21 Tage), echte Daily Prompts ab morgen, echtes Milestone-Enforcement an Tag 13 (Pflicht, 24h) und Tag 21 (Finale, 48h). Wenn ich 2× nicht einchecke, pausiert mein eigener Sprint mich automatisch. Keine Sonderbehandlung — genau das ist der Punkt.

## Das Projekt

Ein kuratierter Beta-Tester-Circle für Solo-Devs: echtes UI/UX-Feedback von handverlesenen Menschen innert 48 Stunden — statt Schnäppchenjäger-Kommentaren aus Verzeichnissen und Communities. Ich habe das Problem selbst erlebt: Bei meinem eigenen Dev-Tool dauerte es 6–8 Wochen bis zum ersten ernstzunehmenden Test-User. Devs bauen heute schneller, als sie validieren — weil Bauen Adrenalin ausschüttet und Validieren langweilig ist.

**Die kleinste lauffähige Version:** Eine Landing mit Waitlist, plus ich matche einen einzigen Dev manuell mit einem kuratierten Tester, der binnen 48h strukturiertes Feedback liefert. Kein Code-Monster, keine Plattform — ich bin am Anfang selbst der Matching-Algorithmus.

## Vorher-Snapshot (die Baseline, an der ich gemessen werde)

| Metrik | Stand heute |
|--------|-------------|
| Gebaute Zeilen Code | 0 |
| Landing / Waitlist | existiert nicht |
| Kuratierte Tester | 0 |
| Interessierte Devs | 0 |
| Durchgeführte Matches | 0 |
| Zahlende Kunden | 0 |
| Validierung | Ideen-Validierung abgeschlossen (Problem real, Markt existiert, größtes Risiko: beide Seiten gleichzeitig gewinnen) |

**Definition of Done, Tag 21:** Landing live · ≥15 Tester-Kandidaten kuratiert · ≥5 manuelle Matches mit 48h-Feedback · ≥1 öffentliche Success Story · Paid-Test real durchgeführt (jemand zahlt — oder ein ehrliches, dokumentiertes Nein).

## Ehrlichkeits-Klausel

Dieser Log ist der Zeuge. Jeder Sprint-Tag bekommt einen Eintrag. Wenn ich das Ziel verfehle, steht das hier genauso drin wie ein Erfolg — ein dokumentierter Miss ist mehr wert als stilles Verschwinden.

## Fund des Tages (Tag 0, noch vor dem Start)

Mein eigenes Produkt hat mir nach dem Accept eine Mail geschickt, deren Anweisung nicht auf mein Profil passte: „Öffne dein Projekt und schreibe auf, warum du aufgehört hast" — es gibt noch kein Projekt, ich habe nur eine Idee. Der Copy-Zweig kannte den Fall „Silber über Können statt über Fortschritt" nicht. Gefixt und deployed, bevor Tag 1 überhaupt angefangen hat. Erster Dogfood-Befund nach null Sprint-Tagen — genau dafür macht man das hier.

---

*Morgen, Tag 1: erster Daily Prompt landet im Postfach. Ab dann gilt: Email lesen, 30–45 Min arbeiten, einchecken. Jeden Tag.*

---

# Tag 1 — Der Prozess bekommt eine Form

**Datum:** Sonntag, 05.07.2026 · Silber, Tag 1/21

Erster Daily Prompt im Postfach, wie versprochen. Gebaut habe ich heute den Kern, bevor irgendetwas „Produkt" wird: eine Notion-Tabelle **„Matching Prozess v1"** — die Ablauf-Stationen von der Aufgaben-Einreichung des Owners bis zur Lieferung des Tester-Feedbacks, mit klaren Schritten. Kein Code, keine Plattform. Der Prozess zuerst, ich bin die Engine.

**Offene Frage (ehrlich, nicht gelöst):** Braucht die fertige V1 eine Warteliste? Ich weiß noch nicht, wie lange das Sourcing der ersten 3 qualifizierten Tester dauert — und genau das entscheidet, ob eine Warteliste an dieser Stelle sinnvoll ist oder nur Ballast. Die Antwort kommt empirisch, sobald ich anfange zu sammeln, nicht durch Vorausplanen.

## Fund des Tages

Mein eigenes Produkt hat mir gleich zwei Bugs geliefert. Erstens: die Login-Link-Mail kam erst am Folgemorgen statt direkt nach dem Accept — Timing korrigiert. Zweitens, und ernster: mein Check-in-Enforcement war unter der Row-Level-Security der Datenbank ein **stiller No-Op** — Schreibzugriffe auf die User-Tabelle liefen ins Leere, ganz ohne Fehler. Heißt konkret: der Mechanismus, der mich bei zwei verpassten Check-ins automatisch pausieren soll, hätte gar nicht ausgelöst. Genau die Sorte Bug, die keine Test-Suite findet — nur echtes Durchlaufen. Gefixt.

*Tag 2: aus dem Prozess-Modell wird ein lauffähiger Einstieg — Intake-Formular + Bewertungsraster.*

---

# Tag 2 — Vom Modell zum lauffähigen Einstieg

**Datum:** Montag, 06.07.2026 · Silber, Tag 2/21

Aus dem Ablauf-Modell von gestern wird heute etwas, das läuft. Gebaut: ein **Tally-Intake-Formular** für Beta-Tester und eine **Notion-Bewertungstabelle** (ein Scoring pro Tester, Achsen: Antwortzeit, Feedback-Qualität, Zuverlässigkeit). Tally-Submit getestet — funktioniert. Damit steht der Supply-Sammelpunkt: Tester können rein, ich kann kuratieren.

**Überlegung:** Ob ein zusätzliches „Referenzen"-Feld in Tally die Seriosität der Tester absichern sollte. Bewusst noch nicht entschieden — dazu unten mehr an Tag 3.

## Fund des Tages

Der Daily Prompt kam um 07:00 Uhr — zu spät. Als Dev mit Fulltime-Job sprinte ich morgens **vor** der Arbeit, da war der Prompt noch nicht da. Also umgebaut: der Prompt für den nächsten Tag kommt jetzt schon am Vorabend gegen 20:00 — abends 2 Minuten lesen, morgens direkt bauen. Zweiter Fund: bei einem knappen Check-in schickte ein Fallback rohen KI-Template-Input an mich raus (Handlebars, interne Labels) statt sauberer Prosa. Beides gefixt und deployed. Das Produkt lernt von seinem eigenen Nutzer.

*Tag 3: die zwei Werkzeuge verbinden — Formular und Bewertungstabelle sollen automatisch zusammenspielen.*

---

# Tag 3 — Die Teile greifen ineinander

**Datum:** Dienstag, 07.07.2026 · Silber, Tag 3/21

Gebaut: die **Tally→Notion-Automation**. Jede Tester-Einreichung landet jetzt automatisch als Zeile im Notion-Scoring-Sheet — alle Felder inklusive Email. Aus zwei getrennten Werkzeugen (Intake-Formular + Bewertungsraster) ist ein durchgehender Fluss geworden: Einreichung → automatischer Eintrag → kuratierbar. Der Intake läuft end-to-end.

Zur „Referenzen"-Frage von gestern: bewusst **weggelassen**. Ich habe noch keinen einzigen Tester durch den Prozess geschickt und weiß gar nicht, ob eine Seriositätsprüfung ein echtes Problem ist. Wenn ein Tester unbrauchbar ist, merke ich das beim ersten Feedback — dann ist das Feld in 10 Minuten ergänzt. Ship first, validieren dann.

## Fund des Tages (doppelt)

Extern: das Email-Feld landete zuerst nicht in Notion — ein Typ-Mismatch (Notion-Email-Property vs. Text-Property des Connectors). Behoben, jetzt schreiben alle Felder. Am eigenen Produkt: der heutige Daily Prompt kam **ohne konkrete Tagesaufgabe**, nur mit einer generischen Frage. Ursache: mein knapper — aber täglicher! — Check-in von gestern (19 Wörter) löste ein „Confidence Gate" aus, das auf Wortzahl filterte und den echten, personalisierten Prompt unterdrückte. Ein kurzer Check-in ist aber hohes Engagement, kein „low signal" — das ist exakt das Goodhart-Problem, gegen das MVP Builder positioniert, im eigenen Code. Wortzahl-Filter raus; der Fallback trägt jetzt zusätzlich die echte Aufgabe statt einer Floskel. Same-day gefixt.

*Tag 4–7: die eigentliche Menschen-Aufgabe beginnt — erste Tester wirklich sourcen (persönliche DMs, kein Spam). Dazwischen der Perfektionismus-Check. Die Scope-Entscheidung Warteliste bleibt bewusst offen, bis ein echter Tester durch den Prozess ist.*
