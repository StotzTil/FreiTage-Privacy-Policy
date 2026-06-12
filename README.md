<!--
VOR DER VERÖFFENTLICHUNG ALLE PLATZHALTER AUSFÜLLEN:
  [APP-NAME]                 – öffentlicher/Store-Name der App
  [VERANTWORTLICHER / FIRMA] – du oder dein Unternehmen (der/die „Verantwortliche")
  [POSTANSCHRIFT]            – für die DSGVO erforderlich (Impressums-/Kontaktanschrift)
  [KONTAKT-E-MAIL]           – funktionierende Datenschutz-Kontaktadresse
  [STAND-DATUM]              – Veröffentlichungsdatum
  [AUFSICHTSBEHÖRDE]         – deine zuständige Datenschutzaufsichtsbehörde (z. B. das Landes-DSB)
Anschließend die gerenderte Datei unter einer öffentlichen URL hosten und diese URL in App Store Connect und der
Google Play Console eintragen. Dieses Dokument ist eine Vorlage und keine Rechtsberatung — vor der Veröffentlichung
rechtlich prüfen lassen.
-->

# Datenschutzerklärung für [APP-NAME]

**Stand:** [STAND-DATUM]

Diese Erklärung beschreibt, welche Daten [APP-NAME] (die „App") verarbeitet, zu welchem Zweck und welche Rechte du
hast. Sie ist in erster Linie für Nutzer in der Europäischen Union / im EWR nach der
**Datenschutz-Grundverordnung (DSGVO)** verfasst; ein kurzer Hinweis für Nutzer außerhalb der EU findet sich in
Abschnitt 11.

**Verantwortlicher:**
[VERANTWORTLICHER / FIRMA], [POSTANSCHRIFT] — E-Mail: [KONTAKT-E-MAIL]

---

## 1. Zusammenfassung

[APP-NAME] ist ein Urlaubs- und Abwesenheitsplaner und ist datenschutzfreundlich aufgebaut:

- **Kein Nutzerkonto, kein Login, keine Registrierung.**
- **Keine Analyse-, Werbe- oder Tracking-SDKs.**
- **Deine Planungsdaten bleiben auf deinem Gerät.** Abwesenheiten, Einstellungen und Urlaubskontingente werden lokal
  gespeichert und **niemals an uns oder einen Server übertragen**.
- Wir setzen nur wenige **Drittanbieter** (Auftragsverarbeiter) für bestimmte Funktionen ein: In-App-Käufe,
  Absturzberichte sowie die Abfrage von Feiertagen/Schulferien. Diese sind in Abschnitt 5 aufgeführt.

---

## 2. Daten, die auf deinem Gerät bleiben

Deine Planerinhalte — Abwesenheitszeiträume, Titel/Notizen, Einstellungen zu Arbeitswoche und Urlaubskontingent,
ausgewähltes Bundesland, Einstellungen zu Erinnerungen und Kalendersynchronisierung — werden **lokal auf deinem
Gerät** gespeichert (über den Standardspeicher des Betriebssystems). Sie werden nicht an uns übertragen, und wir haben
keinen Zugriff darauf. Sie werden gelöscht, wenn du die entsprechenden Einträge entfernst oder die App deinstallierst.
Eine von dir erstellte Sicherungs-/Exportdatei liegt in deiner Verantwortung.

---

## 3. Daten, die wir verarbeiten, Zweck und Rechtsgrundlage

### 3.1 In-App-Käufe („Pro")
Für den Verkauf und die Wiederherstellung der optionalen **Pro**-Freischaltung nutzt die App **RevenueCat** zusammen
mit den Abrechnungssystemen des **Apple App Store** / **Google Play**. Beim Starten oder Wiederherstellen eines Kaufs
werden verarbeitet: eine von RevenueCat erzeugte **anonyme App-Nutzer-Kennung**, **Kauf-/Beleginformationen**, eine
**Gerätekennung**, die App-Version und dein **Store-Land**. **Name, E-Mail oder Konto** werden von uns nicht erhoben —
die Freischaltung ist anonym. Die Zahlung wickeln ausschließlich Apple/Google ab; wir erhalten keine Zahlungsdaten.
*Rechtsgrundlage: Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung).*

### 3.2 Absturz- und Fehlerberichte
Die App nutzt **Sentry**, um Abstürze und Fehler automatisch zu melden, damit wir sie beheben können. Ein Fehlerbericht
kann den **Fehler und den Stacktrace**, **Geräte- und Betriebssysteminformationen**, die **App-Version** sowie
**Breadcrumbs** enthalten (ein kurzes Protokoll der App-Ereignisse vor dem Fehler, das auch die genutzten
Datumsangaben/Bildschirme umfassen kann). Wir senden **nicht** absichtlich deinen Namen, deine E-Mail oder deinen
genauen Standort.
*Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an Stabilität und Sicherheit der App).*

### 3.3 Feiertage und Schulferien
Zur Anzeige von Feiertagen und Schulferien fragt die App Daten von **feiertage-api.de** und **schulferien-api.de** ab
und sendet dabei nur das **Jahr** und den Code deines ausgewählten **Bundeslandes**. Wie bei jeder Internetanfrage ist
die **IP-Adresse** deines Geräts für diese Dienste technisch sichtbar. Planerinhalte werden nicht übermittelt.
*Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an der Kernfunktion).*

### 3.4 Regionserkennung beim ersten Start
**Nur beim ersten Start** ruft die App — sofern noch kein Bundesland gewählt wurde — **ipapi.co** auf, um anhand deines
ungefähren Standorts einen Vorschlag zu machen. Dabei wird die **öffentliche IP-Adresse** deines Geräts an ipapi.co
übertragen, die ein Land/eine Region zurückgibt. Das Ergebnis wird lokal gespeichert; du kannst es jederzeit in den
Einstellungen ändern, und der Aufruf wird danach **nicht** wiederholt.
*Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an einer komfortablen Ersteinrichtung); du kannst
das Ergebnis jederzeit überschreiben.*

### 3.5 Gerätekalender-Synchronisierung (optional)
Wenn du die Kalendersynchronisierung aktivierst, **schreibt** die App deine Abwesenheitseinträge (Titel, Daten,
optionale Notiz) in den von dir gewählten Gerätekalender. Dies erfordert die Kalenderberechtigung und ist
**standardmäßig deaktiviert**. Einmal geschrieben, werden die Einträge von deinem Kalenderanbieter (z. B. Apple,
Google) gemäß dessen Datenschutzerklärung verwaltet. Die App liest deine bestehenden Kalendereinträge nicht zu anderen
Zwecken.
*Rechtsgrundlage: Art. 6 Abs. 1 lit. a DSGVO (Einwilligung); widerrufbar durch Deaktivieren der Synchronisierung oder
der Systemberechtigung.*

### 3.6 Erinnerungen / Benachrichtigungen
Wenn du Erinnerungen aktivierst, plant die App **lokale Benachrichtigungen** auf deinem Gerät (z. B. vor einem Urlaub
oder bevor Resturlaub verfällt). Diese werden **vollständig auf dem Gerät** erzeugt und ausgeliefert; es verlassen
keine Benachrichtigungsdaten das Gerät und es ist kein Push-Server beteiligt.
*Rechtsgrundlage: Art. 6 Abs. 1 lit. a DSGVO (Einwilligung über die System-Benachrichtigungsberechtigung).*

---

## 4. App-Berechtigungen

**Android:**
- `INTERNET` — Käufe (RevenueCat), Fehlerberichte (Sentry) sowie Feiertags-/Regionsabfragen.
- `POST_NOTIFICATIONS` — Anzeige lokaler Erinnerungen (Android 13+).
- `RECEIVE_BOOT_COMPLETED` — erneutes Planen der Erinnerungen nach einem Neustart des Geräts.
- `READ_CALENDAR`, `WRITE_CALENDAR` — Schreiben deiner Abwesenheiten in den Gerätekalender (nur bei aktivierter
  Synchronisierung).

**iOS:**
- Kalenderzugriff — Schreiben deiner Abwesenheiten in den Gerätekalender (nur bei aktivierter Synchronisierung).
- Benachrichtigungen — Anzeige lokaler Erinnerungen (wird bei Aktivierung angefragt).

---

## 5. Drittanbieter (Auftragsverarbeiter)

| Anbieter | Zweck | Datenschutzerklärung |
|---|---|---|
| RevenueCat, Inc. | Verwaltung von In-App-Käufen | https://www.revenuecat.com/privacy/ |
| Functional Software, Inc. (Sentry) | Absturz-/Fehlerberichte | https://sentry.io/privacy/ |
| Apple Inc. | App-Store-Abrechnung, Gerätekalender | https://www.apple.com/legal/privacy/ |
| Google LLC | Google-Play-Abrechnung, Gerätekalender | https://policies.google.com/privacy |
| feiertage-api.de | Feiertagsdaten | https://feiertage-api.de/ |
| schulferien-api.de | Schulferiendaten | https://schulferien-api.de/ |
| ipapi.co | Regionserkennung beim ersten Start (IP) | https://ipapi.co/privacy/ |

---

## 6. Übermittlung in Drittländer

Einige der oben genannten Anbieter (z. B. RevenueCat, Sentry, ipapi.co, Apple, Google) verarbeiten Daten
möglicherweise auf Servern **außerhalb der EU/des EWR**, unter anderem in den USA. Soweit dies geschieht, stützen sie
sich auf geeignete Garantien wie die EU-Standardvertragsklauseln und/oder geltende Angemessenheitsrahmen, wie in ihren
jeweiligen Datenschutzerklärungen beschrieben.

---

## 7. Speicherdauer

- **Daten auf dem Gerät** bleiben gespeichert, bis du sie löschst oder die App deinstallierst.
- **Kaufdaten** werden von RevenueCat / Apple / Google so lange aufbewahrt, wie es zur Bereitstellung und
  Wiederherstellung deines Kaufs erforderlich ist.
- **Fehlerberichte** werden von Sentry für einen begrenzten Zeitraum gemäß dessen Aufbewahrungseinstellungen
  gespeichert.
- Die Feiertags-/Regionsdienste erhalten nur vorübergehende Anfragen; wir selbst führen dazu keine serverseitigen
  Protokolle.

---

## 8. Deine Rechte (DSGVO)

Du hast das Recht auf **Auskunft**, **Berichtigung**, **Löschung**, **Einschränkung** und **Datenübertragbarkeit**
sowie das Recht, der auf berechtigten Interessen beruhenden Verarbeitung zu **widersprechen**. Da wir **kein
Kontosystem** betreiben und keine serverseitige Kopie deiner Planerdaten vorhalten, liegen die meisten Daten direkt in
deiner Kontrolle auf dem Gerät (Einträge löschen oder App deinstallieren). 

---

## 9. Kinder

[APP-NAME] ist eine Produktivitäts-App für ein allgemeines Publikum und **richtet sich nicht an Kinder** unter dem in
deiner Rechtsordnung erforderlichen Einwilligungsalter. Wir erheben wissentlich keine Daten von Kindern.

---

## 10. Änderungen dieser Erklärung

Wir können diese Erklärung anpassen, wenn sich die App ändert. Die aktuelle Fassung ergibt sich aus dem oben genannten
**Stand**. Wesentliche Änderungen werden hier vor ihrem Inkrafttreten dargestellt.

---

## 11. Hinweis für Nutzer außerhalb der EU/des EWR

Es gelten weltweit dieselben Praktiken: Wir betreiben kein Konto, führen keine Analysen durch, belassen deine
Planerdaten auf deinem Gerät und nutzen nur die in Abschnitt 5 genannten Anbieter für Käufe, Fehlerberichte und
Feiertagsabfragen. Je nach Land (z. B. UK, Schweiz, Kalifornien/USA oder andere Regionen) hast du möglicherweise
ähnliche Rechte auf Auskunft oder Löschung; kontaktiere uns unter **[KONTAKT-E-MAIL]**, um sie auszuüben.

---

## 12. Kontakt

[VERANTWORTLICHER / FIRMA]
[POSTANSCHRIFT]
E-Mail: [KONTAKT-E-MAIL]
