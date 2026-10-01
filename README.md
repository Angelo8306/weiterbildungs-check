# Weiterbildungs-Check

Fragebogen für Interessenten an einer geförderten Weiterbildung (Qualifizierungschancengesetz oder Bildungsgutschein). Er prüft Voraussetzungen und Interessen, schlägt passende Kurse vor und erstellt am Ende ein PDF mit allen Angaben für den Antrag.

Die Seite läuft komplett im Browser:

- Eingaben werden nicht an einen Server übertragen. Sie bleiben auf dem Gerät, bis der Interessent das PDF oder den Text selbst verschickt.
- Die Seite lädt nichts von fremden Servern.
- Am Handy öffnet „PDF senden“ das Teilen-Menü (z. B. WhatsApp), am Computer wird das PDF heruntergeladen.

`index.html` wird im Quellprojekt mit `build_standalone.py` gebaut und hier nur veröffentlicht.

## Enthaltene Fremdkomponenten

- jsPDF 3.0.1, MIT-Lizenz (Lizenztext im Kopf des eingebetteten Skripts)
- Schrift Arimo, Copyright 2020 The Arimo Project Authors, SIL Open Font License 1.1 (für das PDF, auf die benötigten Zeichen reduziert)
