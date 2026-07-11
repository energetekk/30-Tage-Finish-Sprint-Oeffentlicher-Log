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

Mein eigenes Produkt hat mir gleich zwei Bugs geliefert. Erstens: die Login-Link-Mail kam erst am Folgemorgen statt direkt nach dem Accept — Timing korrigiert. Zweitens, subtiler: an einer Stelle wurde ein Status nicht zuverlässig gespeichert — ganz ohne Fehlermeldung. Genau die Sorte Bug, die keine Test-Suite findet, nur echtes Durchlaufen. Gefixt, bevor er jemanden treffen konnte.

*Tag 2: aus dem Prozess-Modell wird ein lauffähiger Einstieg — Intake-Formular + Bewertungsraster.*

---

# Tag 2 — Vom Modell zum lauffähigen Einstieg

**Datum:** Montag, 06.07.2026 · Silber, Tag 2/21

Aus dem Ablauf-Modell von gestern wird heute etwas, das läuft. Gebaut: ein **Tally-Intake-Formular** für Beta-Tester und eine **Notion-Bewertungstabelle** (ein Scoring pro Tester, Achsen: Antwortzeit, Feedback-Qualität, Zuverlässigkeit). Tally-Submit getestet — funktioniert. Damit steht der Supply-Sammelpunkt: Tester können rein, ich kann kuratieren.

**Überlegung:** Ob ein zusätzliches „Referenzen"-Feld in Tally die Seriosität der Tester absichern sollte. Bewusst noch nicht entschieden — dazu unten mehr an Tag 3.

## Fund des Tages

Der Daily Prompt kam um 07:00 Uhr — zu spät. Als Dev mit Fulltime-Job sprinte ich morgens **vor** der Arbeit, da war der Prompt noch nicht da. Also umgebaut: der Prompt für den nächsten Tag kommt jetzt schon am Vorabend gegen 20:00 — abends 2 Minuten lesen, morgens direkt bauen. Zweiter Fund: bei einem knappen Check-in schickte mir ein Fallback internen Rohtext statt sauber formatierter Prosa. Beides gefixt und deployed. Das Produkt lernt von seinem eigenen Nutzer.

*Tag 3: die zwei Werkzeuge verbinden — Formular und Bewertungstabelle sollen automatisch zusammenspielen.*

---

# Tag 3 — Die Teile greifen ineinander

**Datum:** Dienstag, 07.07.2026 · Silber, Tag 3/21

Gebaut: die **Tally→Notion-Automation**. Jede Tester-Einreichung landet jetzt automatisch als Zeile im Notion-Scoring-Sheet — alle Felder inklusive Email. Aus zwei getrennten Werkzeugen (Intake-Formular + Bewertungsraster) ist ein durchgehender Fluss geworden: Einreichung → automatischer Eintrag → kuratierbar. Der Intake läuft end-to-end.

Zur „Referenzen"-Frage von gestern: bewusst **weggelassen**. Ich habe noch keinen einzigen Tester durch den Prozess geschickt und weiß gar nicht, ob eine Seriositätsprüfung ein echtes Problem ist. Wenn ein Tester unbrauchbar ist, merke ich das beim ersten Feedback — dann ist das Feld in 10 Minuten ergänzt. Ship first, validieren dann.

## Fund des Tages (doppelt)

Extern: das Email-Feld landete zuerst nicht in Notion — ein Typ-Mismatch (Notion-Email-Property vs. Text-Property des Connectors). Behoben, jetzt schreiben alle Felder. Am eigenen Produkt: der heutige Daily Prompt kam **ohne konkrete Tagesaufgabe**, nur mit einer generischen Frage. Ursache: mein knapper — aber täglicher! — Check-in von gestern (19 Wörter) löste ein „Confidence Gate" aus, das auf Wortzahl filterte und den echten, personalisierten Prompt unterdrückte. Ein kurzer Check-in ist aber hohes Engagement, kein „low signal" — das ist exakt das Goodhart-Problem, gegen das MVP Builder positioniert, im eigenen Code. Wortzahl-Filter raus; der Fallback trägt jetzt zusätzlich die echte Aufgabe statt einer Floskel. Same-day gefixt.

*Tag 4–7: die eigentliche Menschen-Aufgabe beginnt — erste Tester wirklich sourcen (persönliche DMs, kein Spam). Dazwischen der Perfektionismus-Check. Die Scope-Entscheidung Warteliste bleibt bewusst offen, bis ein echter Tester durch den Prozess ist.*

---

# Tag 4 — Was der Tester tatsächlich in die Hand bekommt

**Datum:** Mittwoch, 08.07.2026 · Silber, Tag 4/21

Die letzten drei Tage bauten die Supply-Seite: Intake-Formular, Bewertungsraster, Automation dazwischen. Heute die andere Hälfte, ohne die der ganze Circle wertlos ist — **der Test-Auftrag selbst.** Ich habe den ersten standardisierten Test-Brief geschrieben und ihn im Trockenlauf durch einen Test-Empfänger geschickt, bevor ich einen echten Menschen damit behellige.

Der Brief ist bewusst ein fokussierter Einzel-Flow („finde für dieses konkrete Paar den besten Pool"), kein „schau dich mal um" — plus feste Rückgabe-Felder statt der Bitte um „strukturiertes Feedback". Genau da lag der Denkfehler, den ich zuerst selbst gemacht hatte: Wer „schick mir strukturiertes Feedback" schreibt und keine Struktur mitliefert, bekommt Fließtext. Also: geschafft ja/nein, wo hängengeblieben (mit Schritt-Nummer), Bug mit Screenshot, was war unklar und warum, und — beim Produkttyp entscheidend — würdest du dem Ergebnis echtes Geld anvertrauen. Feste Felder, 48-Stunden-Fenster.

## Fund des Tages

Der ehrlichere Befund kam nicht aus dem Brief, sondern über mich selbst. Der Brief war in einer Stunde fertig — und ich merkte, wie mich ein Teil lieber noch die Notion-Tabelle hübscher gemacht, ein weiteres Feld ergänzt, das Formular verfeinert hätte. Alles Arbeit auf der **bequemen Seite.** Die unbequeme Seite von Tag 4 ist eine einzige Sache: einen echten Menschen anschreiben und fragen, ob er testet. Kein Tooling der Welt ersetzt diese eine Bewegung, und genau deshalb ist sie so leicht zu umgehen. Das ist Perfektionismus als Prokrastination — Feilen am Prozess, um dem Sourcing auszuweichen. Notiert, benannt, damit es nicht die ganze Woche frisst. Der Brief steht; jetzt braucht er einen Empfänger, der kein Testkonto ist.

*Tag 5: die erste echte Ansprache — persönlich, ein Mensch, kein Verteiler.*

---

# Tag 5 — Fertig ist nicht verschickt

**Datum:** Donnerstag, 09.07.2026 · Silber, Tag 5/21

Gestern stand der generische Test-Brief. Heute habe ich ihn scharf gestellt: aus „schau dir das mal an" wurde ein konkreter, sofort versendbarer Auftrag für einen einzelnen realen Flow — den Wallet-Connect-Flow eines live DeFi-Produkts. Copy-pasteable, verständlich ohne dass ich je mit dem Empfänger gesprochen haben muss: Ziel, URL, eine Aufgabenbeschreibung in vier Sätzen, 48-Stunden-Fenster, feste Rückgabe-Felder (verbunden ja/nein, welche Wallets probiert, wo gezögert und was unklar war, Bug mit Screenshot, welche Wallet sich am reibungslosesten anfühlte — mit einem Satz Begründung). Der Auftrag ist an dem Punkt, an dem nichts mehr fehlt. Man könnte ihn jetzt abschicken.

Man könnte.

**Verschickt: 0.** Keinen einzigen echten Menschen heute angeschrieben.

## Fund des Tages

Gestern habe ich Perfektionismus als Prokrastination benannt — Feilen am Tooling, um dem Sourcing auszuweichen. Ich dachte, Benennen reicht. Tut es nicht. Heute trug dieselbe Vermeidung nur ein besseres Kostüm: statt die Tabelle hübscher zu machen, habe ich den Auftrag *produktspezifisch* gemacht — und das fühlte sich wie Fortschritt an, weil es tatsächlich besser ist. Genau das macht es gefährlicher. Ein vager Brief, an dem man endlos feilt, ist offensichtlich Ausweichen. Ein exzellenter, versandfertiger Auftrag, den man nicht verschickt, sieht aus wie Arbeit — ist es aber nicht. „Versandfertig" ist der Zustand direkt vor der einzigen Bewegung, die zählt, und heute bin ich genau dort stehen geblieben. Die ehrliche Zahl von Tag 5 ist eine 0, und sie steht hier, weil dieser Log der Zeuge ist. Ein fertiger Auftrag ohne Empfänger ist am Ende dasselbe wie kein Auftrag.

*Tag 6: keine neue Vorbereitung, kein weiteres Feld. Der Auftrag geht an echte Namen raus — oder das Muster gewinnt.*

---

# Tag 6 — Es hat das Gebäude verlassen

**Datum:** Freitag, 10.07.2026 · Silber, Tag 6/21

Gestern endete mit einer 0 und einem Versprechen: keine neue Vorbereitung, der Auftrag geht raus. Heute ist er raus. Kein weiteres Feld, keine hübschere Tabelle — stattdessen habe ich die Anfrage tatsächlich in die Welt gestellt: ein Kommentar unter einem Web3-UX-Artikel und ein Post in einer Ethereum-Dev-Community, in dem ich Devs suche, die den Wallet-Connect-Flow eines live DeFi-Produkts durchspielen. Öffentlich, mit meinem Namen dran, an einem Ort, an dem die Bitte ignoriert oder abgelehnt werden kann. Genau das ist heute auch passiert — und darin lag der Fund.

## Fund des Tages

Mein erster Post wurde vom Automod der Community sofort geflaggt: „Das hier ist kein Job Board." Erster Reflex: Unsinn, ich zahle doch gar nichts. Aber der Bot hatte recht über die *Form*. Ich hatte geschrieben: „Ich suche jemanden, der für mich testet — das bekommst du dafür." Eine einseitige Bitte um die Zeit eines Fremden, mit einer Belohnungsliste garniert, liest sich wie eine ausgeschriebene Gig — auch wenn kein Geld fließt. Es fühlt sich für den Empfänger nach Extraktion an.

Der Fix war nicht kosmetisch. Ich habe die Anfrage umgedreht: aus „teste meins" wurde „lass uns tauschen — ich laufe einen 30-Minuten-Durchgang durch deinen Connect-Flow, du durch meinen, gleiches Format in beide Richtungen." Damit war es kein Aushang mehr, sondern ein Austausch unter Gleichrangigen — und ging durch. Die Lektion, die über Reddit-Regeln hinausgeht: Wenn ich einen Fremden um seine Zeit bitte, ist Gegenseitigkeit keine nette Geste, sondern das, was die Bitte überhaupt legitim macht. Genau der Reflex, den ich fünf Tage lang vermieden habe — jemanden ansprechen — wird leichter, sobald ich nicht *nehme*, sondern *tausche*.

Und die ehrliche Einordnung, weil dieser Log der Zeuge ist: Die 0 ist gebrochen, aber ein öffentlicher Post ist ein *Angebot*, kein Abschluss. Verschickt heißt noch nicht: jemand hat zugesagt. Die Tür ist auf — durchgegangen ist noch niemand. Das ist der Unterschied zwischen Tag 6 und Tag 7.

*Tag 7: Ende der ersten Woche. Kommt eine erste Antwort — und was zeigt der ehrliche Wochenrückblick, wenn ich Gebautes gegen Verschicktes halte?*

---

# Tag 7 — Wochenbilanz: Das Ziel war zu leicht

**Datum:** Samstag, 11.07.2026 · Silber, Tag 7/21

Ende der ersten Woche, also erst die nackte Bilanz — Gebautes gegen Verschicktes: **sechs Bausteine gebaut** (Matching-Prozess, Intake mit Bewertungsraster, Automation, Test-Brief, versandfertiger Auftrag, Feedback-Template in zwei Sprachen), **zwei Anfragen öffentlich**, **null Antworten, null echte Durchläufe.** Die Bau-Seite dieser Woche war stark, die Menschen-Seite hat erst am sechsten Tag begonnen. Das ist die ehrliche Form von „Woche 1 geschafft".

Dann kam der Wochen-Checkpoint meines eigenen Produkts — und lag einmal falsch und einmal richtig.

**Falsch lag er hier:** „Kein Stack, kein Prozess, keine technische Grundlage." Sechs Tage Aufbauarbeit, und der Prompt behauptete, es gebe nichts davon. Ursache gefunden: Die tägliche KI sah immer nur den *letzten* Check-in — der handelte von Outreach, also existierte für sie nur Outreach. Eine Wochen-Bilanz, die über sieben Tage urteilt und dabei einen Tag Daten hat, halluziniert nicht aus Böswilligkeit, sondern aus Datenmangel. Same-day gefixt: Die KI bekommt jetzt den kumulativen Verlauf aller Check-ins, und Bilanz-Tage müssen über die vollständige Liste urteilen statt über den jüngsten Eintrag.

**Richtig lag er hier:** bei der Scope-Frage. Nur hatte sie zwei Antwortrichtungen — Kurs halten oder reduzieren. Meine ehrliche Antwort war die dritte, die es nicht gab: **Das Ziel war zu leicht.** Ich hatte an Tag 0 die „kleinste lauffähige Version" definiert — und dann genau diesen Mindestumfang als 21-Tage-Ziel eingefroren. Ein Ziel, das der Prozess an Tag 7 faktisch erfüllt hätte, wenn ein einziger Mensch geantwortet hätte. Es lag sogar unter dem, was mein eigenes Tag-13-Enforcement verlangt hätte.

## Fund des Tages

Systeme korrigieren nach unten. Jeder Anpassungsmechanismus in meinem Produkt — und, ehrlich, in meinem Kopf — zeigte in dieselbe Richtung: kürzen, reduzieren, absichern. Ein vorsichtig gesetztes Ziel plus ein System, das nur Runter-Korrektur kennt, produziert die gefährlichste Form von Erfolg: **man schließt erfolgreich ab, ohne dass sich etwas verändert hat.** Das Häkchen stimmt, die Transformation fehlt. Deshalb heute die Korrektur nach oben, offiziell und verbindlich: Landing + Waitlist live, mindestens 15 Tester kontaktiert und bewertet, mindestens 3 echte Matches mit 48h-Feedback — und einmal echt nach Geld fragen. Ein dokumentiertes Nein zählt als Ergebnis; die Frage nicht zu stellen zählt nicht. Ein Rauf-Pfad für den Wochen-Checkpoint steht jetzt auf der Produkt-Liste.

Und weil Tag 7 auch der Upgrade-Entscheid war: Gold (mehr Laufzeit) geprüft und verneint. Null Antworten sind keine Traktion, und mehr Zeit wäre nur die eleganteste Form des Ausweichens.

*Tag 8: Landing + Waitlist. Die Tür ist offen — jetzt bekommt sie eine Adresse.*
