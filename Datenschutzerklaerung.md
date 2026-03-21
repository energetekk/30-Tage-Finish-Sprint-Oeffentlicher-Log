# Datenschutzerklärung — MVP Builder

**Version:** 1.1
**Stand:** März 2026

---

## 1. Kontakt und Verantwortlicher

Verantwortlich für die Datenverarbeitung im Sinne des schweizerischen Datenschutzgesetzes (DSG) und der EU-Datenschutz-Grundverordnung (DSGVO):

Dejan Potocnik
Alpsteinstrasse 3
8570 Weinfelden
Schweiz

E-Mail: energetekk@proton.me
Website: https://mvpbuilder.io

Da der Anbieter in der Schweiz ansässig ist und die Schweiz von der Europäischen Kommission als Land mit angemessenem Datenschutzniveau anerkannt ist, gilt die DSGVO für EU-ansässige Nutzer ergänzend.

---

## 2. Welche Daten wir erheben und warum

### 2.1 Bewerbung (Formular auf mvpbuilder.io/pipeline)

**Erhobene Daten:**
- Vorname oder Nickname
- E-Mail-Adresse
- Skill-Level (selbst angegeben: Anfänger / Fortgeschritten / Profi)
- Projektphase (selbst angegeben)
- Projektbeschreibung und Sprint-Ziel (Freitext)
- Zeitzone (automatisch aus Browser-Einstellung, kein Standort-Tracking)
- Zeitstempel der Bewerbung

**Zweck:** Bewerbungsprüfung, Tier-Zuteilung (Bronze/Silber/Gold), Kommunikation der Entscheidung.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragsanbahnung) und Art. 6 Abs. 1 lit. a DSGVO (Einwilligung durch freiwillige Bewerbung).

**Speicherdauer:** Abgelehnte Bewerbungen: 6 Monate. Angenommene Bewerbungen: Dauer des Sprints plus 2 Jahre danach (für Feedback- und Qualitätszwecke).

---

### 2.2 Dashboard-Nutzung während des Sprints

**Erhobene Daten:**
- Login-Zeitstempel (`last_login_at`)
- Checkin-Einträge (Datum, Status)
- Eingereichte Proof-of-Work-Nachweise (Links, Screenshots oder Videos)
- Fortschrittsdaten (welcher Tag im Sprint, welcher Tier)

**Zweck:** Sprint-Durchführung, Inaktivitätserkennung (Benachrichtigung bei verpassten Meilensteinen), Sprint-Abschluss-Bestätigung.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung).

**Speicherdauer:** 2 Jahre nach Sprint-Ende, danach Löschung oder Anonymisierung.

---

### 2.3 E-Mail-Kommunikation

**Erhobene Daten:**
- E-Mail-Adresse
- Öffnungs- und Klick-Tracking (sofern vom E-Mail-Provider erhoben — siehe Abschnitt 3.2)
- Inhalte eingehender E-Mails (bei direkter Antwort an uns)

**Zweck:** Versand täglicher Prompts, Benachrichtigungen (Meilenstein-Erinnerungen, Inaktivitäts-Hinweise, Sprint-Abschluss), Beantwortung von Anfragen.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung) für transaktionale E-Mails. Art. 6 Abs. 1 lit. a DSGVO (Einwilligung) für optionale Newsletter-Kommunikation.

**Speicherdauer:** Wie in 2.1 und 2.2. E-Mail-Korrespondenz: 2 Jahre.

---

### 2.4 Technische Zugriffsdaten (Server-Logs)

Beim Besuch unserer Website werden automatisch folgende Daten erhoben:

**Erhobene Daten:**
- IP-Adresse (anonymisiert nach 24 Stunden)
- Browser-Typ und Betriebssystem
- Aufgerufene URL
- Datum und Uhrzeit des Abrufs
- Referrer-URL (von wo du gekommen bist)

**Zweck:** Technischer Betrieb, Fehlerbehebung, Sicherheit.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse am sicheren Betrieb der Website).

**Speicherdauer:** 7 Tage, danach automatische Löschung.

---

### 2.5 Analytics (Vercel Analytics)

Wir nutzen Vercel Web Analytics für anonymisierte Nutzungsstatistiken.

**Was Vercel Analytics nicht tut:**
- Kein Cookie-Tracking
- Keine Fingerprinting-Techniken
- Keine persönlich identifizierbaren Daten

**Was erhoben wird:**
- Anonymisierte Seitenaufrufe
- Gerätetyp (Desktop/Mobile), Land (nicht präziser Standort)
- Referrer (von wo Besucher kommen)

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an anonymisierter Nutzungsanalyse). Da keine personenbezogenen Daten verarbeitet werden, ist keine Cookie-Einwilligung erforderlich.

---

## 3. Drittanbieter und Datenübermittlung in die USA

Wir nutzen folgende externe Dienstleister für den Betrieb von MVP Builder. Diese Anbieter verarbeiten Daten in unserem Auftrag als Auftragsverarbeiter (Art. 28 DSGVO). Mit jedem haben wir einen Auftragsverarbeitungsvertrag (AVV / Data Processing Agreement) abgeschlossen.

---

### 3.1 Supabase (Datenbankhosting)

**Anbieter:** Supabase Inc., 970 Toa Payoh North #07-04, Singapore 318992
**Serverstandort:** Primär USA (us-east-1 auf AWS)
**Verarbeitete Daten:** Alle in Abschnitt 2.1 und 2.2 genannten Daten (Benutzerprofil, Bewerbungsdaten, Checkins, Fortschrittsdaten, Zeitstempel)
**Zweck:** Datenbankbetrieb, Authentifizierung, Dashboard-Backend
**Rechtsgrundlage für Drittlandübermittlung:** EU-Standardvertragsklauseln (SCC) gemäss Durchführungsbeschluss (EU) 2021/914
**Datenschutzinformationen:** https://supabase.com/privacy
**AVV:** https://supabase.com/legal/dpa

---

### 3.2 Resend (E-Mail-Versand)

**Anbieter:** Resend, Inc., USA
**Serverstandort:** USA
**Verarbeitete Daten:** E-Mail-Adresse, Vorname, Tier-Zuordnung, tägliche Prompt-Inhalte, Benachrichtigungstexte
**Zweck:** Versand aller transaktionalen E-Mails (Zusage, Absage, tägliche Prompts, Meilenstein-Erinnerungen, Sprint-Abschluss)
**Rechtsgrundlage für Drittlandübermittlung:** EU-Standardvertragsklauseln (SCC)
**Datenschutzinformationen:** https://resend.com/privacy
**AVV:** https://resend.com/legal/dpa

---

### 3.3 Vercel (Hosting und Deployment)

**Anbieter:** Vercel Inc., 440 N Barranca Ave #4133, Covina, CA 91723, USA
**Serverstandort:** USA (primär), mit globalem CDN
**Verarbeitete Daten:** IP-Adressen bei Seitenaufrufen, Anfrage-Logs, Deploy-Logs
**Zweck:** Hosting der Website und API-Endpunkte
**Rechtsgrundlage für Drittlandübermittlung:** EU-Standardvertragsklauseln (SCC) und Vercel ist zertifiziert unter dem EU-US Data Privacy Framework
**Datenschutzinformationen:** https://vercel.com/legal/privacy-policy
**AVV:** https://vercel.com/legal/dpa

---

### 3.4 Stripe (Zahlungsabwicklung — ab Cohort #2)

Dieser Abschnitt gilt ab dem Zeitpunkt, an dem kostenpflichtige Cohorts angeboten werden.

**Anbieter:** Stripe, Inc., 510 Townsend Street, San Francisco, CA 94103, USA
**Verarbeitete Daten:** Zahlungsinformationen (Kreditkarte/Bankkonto), Rechnungsadresse, E-Mail
**Zweck:** Zahlungsabwicklung für kostenpflichtige Cohorts
**Hinweis:** Stripe ist für Zahlungsdaten teilweise eigenständig Verantwortlicher. Wir haben keinen Zugriff auf vollständige Zahlungsmittelinformationen.
**Datenschutzinformationen:** https://stripe.com/privacy
**AVV:** https://stripe.com/legal/dpa

---

## 4. Deine Rechte

### 4.1 Rechte nach DSGVO (EU-Nutzende) und DSG (Schweizer Nutzende)

**Auskunftsrecht:** Du kannst jederzeit Auskunft darüber verlangen, welche Daten wir über dich gespeichert haben.

**Berichtigungsrecht:** Du kannst die Korrektur unrichtiger Daten verlangen.

**Löschungsrecht:** Du kannst die Löschung deiner Daten verlangen, sofern keine gesetzlichen Aufbewahrungspflichten entgegenstehen. Schreibt uns einfach an: energetekk@proton.me — und wir löschen dein Konto und alle damit verbundenen Daten innerhalb von 30 Tagen.

**Recht auf Einschränkung der Verarbeitung:** Du kannst verlangen, dass wir deine Daten nur noch speichern, aber nicht weiter verarbeiten.

**Recht auf Datenübertragbarkeit:** Du kannst deine Daten in maschinenlesbarem Format anfordern.

**Widerspruchsrecht:** Du kannst der Verarbeitung deiner Daten auf Basis berechtigter Interessen widersprechen.

**Widerruf der Einwilligung:** Soweit die Verarbeitung auf deiner Einwilligung basiert, kannst du diese jederzeit mit Wirkung für die Zukunft widerrufen.

### 4.2 Wie du deine Rechte ausübst
Sende eine E-Mail an: energetekk@proton.me

**Antwortzeit:** Innerhalb von 30 Tagen (DSGVO-Frist). In der Regel früher.

### 4.3 Beschwerderecht
Du hast das Recht, dich bei einer Datenschutz-Aufsichtsbehörde zu beschweren:

**Schweiz:** Eidgenössischer Datenschutz- und Öffentlichkeitsbeauftragter (EDÖB)
https://www.edoeb.admin.ch
Feldeggweg 1, CH-3003 Bern

**EU:** Bei der zuständigen Datenschutzbehörde in deinem Wohnsitzland.

---

## 5. Datensicherheit

- Alle Verbindungen zu mvpbuilder.io sind mit TLS/SSL verschlüsselt.
- Passwörter werden nicht gespeichert — Authentifizierung erfolgt über Magic Links (zeitlich begrenzte, einmalig gültige Login-Links).
- Datenbankzugriffe sind durch Row-Level Security (RLS) in Supabase abgesichert — jeder Nutzer sieht nur seine eigenen Daten.
- Wir speichern keine Zahlungsmittelinformationen selbst — diese werden direkt von Stripe verarbeitet.

Kein System ist zu 100% sicher. Im Falle einer Datenpanne werden wir betroffene Nutzer schnellstmöglich informieren und, soweit gesetzlich erforderlich, die zuständige Aufsichtsbehörde innerhalb von 72 Stunden benachrichtigen.

---

## 6. Cookies und Tracking

**Cookies:** Wir verwenden nur technisch notwendige Cookies für die Session-Verwaltung (Login-Status). Es werden keine Tracking-Cookies von Drittanbietern eingesetzt.

**Analytics:** Wir nutzen Vercel Analytics — eine cookielose Analyse-Lösung ohne persönliche Identifizierung (siehe Abschnitt 2.5).

**UTM-Parameter:** Wenn du über einen Link mit UTM-Parametern (z.B. ?utm_source=reddit) auf unsere Seite kommst, speichern wir diese Parameter anonymisiert um zu verstehen, welche Kanäle Besucher bringen. Keine Zuordnung zu einzelnen Personen.

---

## 7. Minderjährige

MVP Builder richtet sich ausschliesslich an Personen ab 18 Jahren. Wir erheben wissentlich keine Daten von Personen unter 18 Jahren. Solltest du Kenntnis davon haben, dass eine minderjährige Person Daten an uns übermittelt hat, kontaktiere uns bitte.

---

## 8. Änderungen dieser Datenschutzerklärung

Wir behalten uns vor, diese Datenschutzerklärung zu aktualisieren. Die aktuelle Version ist immer unter mvpbuilder.io/privacy abrufbar. Bei wesentlichen Änderungen werden aktive Nutzer per E-Mail informiert. Das Datum der letzten Aktualisierung ist oben angegeben.

---

## 9. Kontakt bei Datenschutzfragen

**E-Mail:** energetekk@proton.me
**Betreff:** "Datenschutzanfrage — [dein Anliegen]"
**Antwortzeit:** In der Regel innerhalb von 48 Stunden

---

*MVP Builder — mvpbuilder.io*
*Verantwortlicher: Dejan, Schweiz*
