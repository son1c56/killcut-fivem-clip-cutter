## Installation unter Windows

1. Öffne die Seite [Latest Release](https://github.com/son1c56/killcut-fivem-clip-cutter/releases/latest).
2. Lade ausschließlich die Datei `killcut-setup-[VERSION].exe` herunter.
3. Starte den heruntergeladenen Installer.
4. Wähle im Killcut-Installer **Installieren**.
5. Lege den gewünschten Installationsordner fest.
6. Schließe die Installation ab.

Spätere Updates verwenden automatisch denselben Installationspfad.

### Hinweis zu Windows Defender SmartScreen Warnung

Killcut besitzt derzeit noch kein kostenpflichtiges Code-Signing-Zertifikat. Windows kann deshalb beim ersten Start folgende Meldung anzeigen:

> Der Computer wurde durch Windows geschützt  
> Microsoft Defender SmartScreen hat den Start einer unbekannten App verhindert.

Wenn Killcut ausschließlich über das offizielle [GitHub-Repository](https://github.com/son1c56/killcut-fivem-clip-cutter/releases/latest) heruntergeladen wurde:

1. Klicke im SmartScreen-Fenster auf **Weitere Informationen**.
2. Kontrolliere, dass als App der heruntergeladene Killcut-Installer angezeigt wird.
3. Klicke auf **Trotzdem ausführen**.
4. Bestätige anschließend gegebenenfalls die Windows-Benutzerkontensteuerung.

Eine SmartScreen-Meldung **bedeutet nicht** automatisch, dass Schadsoftware gefunden wurde. **Sie kann erscheinen, wenn eine neue oder nicht digital signierte Anwendung noch keine ausreichende Microsoft-Reputation besitzt.**

Falls Windows Defender ausdrücklich einen Virus oder eine konkrete Bedrohung meldet, führe die Datei nicht einfach aus. Prüfe zuerst, ob sie aus dem offiziellen Repository stammt, und melde den Fund zur Überprüfung.

### Download überprüfen

Die SHA-256-Prüfsumme von Killcut 1.1.0 lautet:

`18932D71A5DA1281CC0C3F581A8671FBE8C1104441BFA4C8FF08713AE3B7C0E2`

**Überprüfung mit PowerShell:**

Öffne Powershell -> Füge den command unten ein und führe diesen aus!
Danach wird der Installer auf Schadsoftwäre überprüft

```powershell
Get-FileHash -Algorithm SHA256 "$env:USERPROFILE\Downloads\killcut-setup-1.1.2.exe"

```
> [!WARNING]
Sollte dieser Hash ( `18932D71A5DA1281CC0C3F581A8671FBE8C1104441BFA4C8FF08713AE3B7C0E2` ) nicht erscheinen, lösche den Installer und lade dir den [Offiziellen Killcut Installer hier herunter](https://github.com/son1c56/killcut-fivem-clip-cutter/releases/latest)
