# Datenschutzerklärung

**Verantwortlicher Anbieter:**  
Stefanie Mangin  
info@solution-ninja.com

---

## 1. Art der verarbeiteten Daten
Die App verarbeitet insbesondere folgende Daten:
Nutzungsdaten in der App
Eingetragene Mahlzeiten (Textbeschreibung, Datum/Uhrzeit, berechnete Kalorien und Makronährstoffe)
Zielkalorien, Körpergewicht, Größe, Alter, Aktivitätsfaktor und Ziel (z. B. „Gewicht halten“)
Trinkmengen (Wasser‑Einträge)
Sprachdaten (Mikrofon)
Sprachaufnahmen, die du über das Mikrofon startest, um Mahlzeiten per Sprache zu beschreiben.
Diese Sprachaufnahmen werden lokal in Text umgewandelt (über die verwendete Speech‑to‑Text‑Bibliothek / das Betriebssystem) und anschließend als Text in der App weiterverarbeitet.
Technische Daten
Anfragen an den Nährwert‑Analyse‑Dienst (OpenAI API) mit deiner Mahlzeitenbeschreibung als Text.

## 2. Zwecke der Verarbeitung
Die Daten werden zu folgenden Zwecken verarbeitet:
Kalorien‑ und Nährwertberechnung
Analyse deiner eingegebenen (oder gesprochenen) Mahlzeiten, um Kalorien, Makronährstoffe und Obst‑/Gemüseeinheiten („5 am Tag“) abzuschätzen.
Verlaufs‑ und Tagesübersichten
Darstellung deiner Einträge im Verlauf (z. B. 7‑Tage‑Auswertung, Tagesübersicht, Wasser‑ und Gewichtstracking).
Sprachkomfort
Möglichkeit, Mahlzeiten bequem per Sprache einzugeben (Mikrofonfunktion).
Rechtsgrundlage (im Sinne der DSGVO, falls relevant) ist in der Regel Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung / Nutzung der App) bzw. lit. a (Einwilligung, z. B. Mikrofonzugriff).

## 3. Speicherung der Daten
Lokal auf deinem Gerät
Mahlzeiten, Kalorien, Makros, Obst-/Gemüseeinheiten, Wasser‑ und Gewichtseinträge sowie Zielkalorien und Profilwerte werden lokal auf deinem Gerät gespeichert (z. B. in SharedPreferences / lokalem Speicher).
Die Daten verlassen dein Gerät nur insoweit, wie dies für die Nährwert‑Analyse notwendig ist (siehe Punkt 4).
Keine eigene Cloud‑Synchronisation
Die App selbst synchronisiert deine Daten nicht automatisch mit einem eigenen Server oder Cloud‑Dienst.

## 4. Nutzung von OpenAI (Nährwert‑Analyse)
Zur Analyse von Mahlzeiten wird die OpenAI API genutzt (z. B. Modell gpt-4o-mini):
Es wird der Text deiner Mahlzeitenbeschreibung an die API übermittelt (z. B. „1 belegtes Brötchen mit Käse und Tomate, Kaffee mit Milch“).
Die API berechnet daraus:
Kalorien (kcal),
Gramm Protein/Kohlenhydrate/Fett,
geschätzte Obst‑/Gemüseeinheiten (nach „5 am Tag“-Regel),
sowie Metadaten wie „ist Getränk“ und geschätzte Wassermenge.
Wichtige Punkte:
Drittlandübermittlung
Die Verarbeitung durch OpenAI kann außerhalb der EU/EWR (z. B. in den USA) stattfinden.
Einzelheiten findest du in der Datenschutzerklärung von OpenAI:
https://openai.com/privacy.
Verantwortung / Auftragsverarbeitung
OpenAI agiert als externer Dienstleister zur Erbringung der Analysefunktion.
Es werden nur die für die Analyse erforderlichen Inhalte übermittelt (Mahlzeitenbeschreibung als Text, keine anderen personenbezogenen Daten wie Name/Adresse).

## 5. Mikrofon / Sprachaufnahmen
Die App verwendet die Berechtigung android.permission.RECORD_AUDIO, um Sprachbefehle/Sprachtexte für Mahlzeiten aufzunehmen.
Sprachaufnahmen werden nur dann erzeugt, wenn du aktiv auf das Mikrofon‑Symbol tippst.
Die Sprachdaten werden zum Zweck der Spracherkennung an die entsprechende Speech‑to‑Text‑Komponente (System oder verwendetes Speech‑Plugin) übergeben und anschließend in Text umgewandelt.
Die App speichert selbst nur den erkannten Text, nicht die Roh‑Audioaufnahme.
Du kannst die Mikrofonberechtigung jederzeit über die Systemeinstellungen deines Gerätes entziehen; die App ist dann weiterhin nutzbar, aber ohne Spracheingabe.

## 6. Weitergabe von Daten
Es erfolgt keine Weitergabe deiner lokal gespeicherten Einträge an Dritte, außer:
an den oben genannten Nährwert‑Analyservice (OpenAI) soweit für die Analyse notwendig,
ggf. an die vom Betriebssystem bereitgestellte Spracherkennungskomponente bei Nutzung des Mikrofons.
Es findet keine Weitergabe zu Werbe‑ oder Trackingzwecken statt.

## 7. Speicherdauer und Löschung
Deine Einträge verbleiben so lange auf dem Gerät, bis du:
die entsprechenden Einträge/Verläufe in der App löscht, oder
die App deinstallierst (damit werden die lokalen Daten i. d. R. entfernt).

## 8. Deine Rechte (sofern DSGVO anwendbar)
Soweit die EU‑Datenschutzgrundverordnung (DSGVO) Anwendung findet, hast du u. a. folgende Rechte:
Recht auf Auskunft (Art. 15 DSGVO)
Recht auf Berichtigung (Art. 16 DSGVO)
Recht auf Löschung (Art. 17 DSGVO)
Recht auf Einschränkung der Verarbeitung (Art. 18 DSGVO)
Recht auf Datenübertragbarkeit (Art. 20 DSGVO)
Recht auf Widerspruch (Art. 21 DSGVO)
Zur Wahrnehmung dieser Rechte oder bei Fragen zur Datenverarbeitung kannst du dich an die oben genannte Kontaktadresse wenden.

## 9. Änderungen dieser Datenschutzerklärung
Diese Datenschutzerklärung kann bei Bedarf angepasst werden, z. B. wenn sich die App‑Funktionen oder gesetzliche Vorgaben ändern.
Die jeweils aktuelle Version ist über die in der App bzw. im Store verlinkte URL abrufbar.
