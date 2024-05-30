# Anleitung - Datei-Organizer-Skript

Dieses Batch-Skript organisiert Dateien aus dem Download-Ordner in entsprechende Verzeichnisse wie Musik, Videos, Bilder, Dokumente, Installationsprogramme, Zip-Dateien und Sonstiges.

## Funktionen
- Erstellt die notwendigen Verzeichnisse, falls sie nicht existieren.
- Verschiebt Dateien basierend auf ihren Erweiterungen in die entsprechenden Ordner.
- Vermeidet Dateinamenskonflikte, indem es eine Zufallszahl an den Dateinamen anhängt, wenn im Zielverzeichnis bereits eine Datei mit demselben Namen existiert.
- Bietet eine Zusammenfassung der verschobenen Dateien und zeigt diese in einem Meldungsfeld an.

## Ordner
- **Musik**: `.mp3`, `.wav`, `.wma`, `.aac`, `.ogg`, `.flac`
- **Dokumente**: `.pdf`, `.txt`, `.xlsx`, `.html`, `.doc`
- **Videos**: `.mov`, `.wmv`, `.mp4`, `.avi`, `.avchd`, `.flv`, `.mkv`
- **Bilder**: `.jpg`, `.png`, `.webp`, `.jpeg`, `.ico`, `.bmp`, `.tiff`, `.tif`, `.eps`, `.gif`
- **Installationsprogramme**: `.msi`, `.exe`
- **Zip-Dateien**: `.zip`
- **Sonstiges**: Alle anderen Dateitypen

## Nutzung
Führe die `DownloadCleaner.exe`-Datei aus. Es werden die notwendigen Verzeichnisse erstellt, falls sie nicht existieren, und Dateien aus dem Download-Ordner in die entsprechenden Verzeichnisse verschoben.

## Zusammenfassung im Meldungsfeld
Nach Abschluss des Skripts wird ein Meldungsfeld angezeigt, das die Anzahl und den Speicherort der verschobenen Dateien zusammenfasst.

## Mögliche Virenentdeckung
- **Nicht signierte Anwendung**:
  - Die .exe-Datei kann als Virus erkannt werden, da es sich um eine nicht signierte Anwendung handelt. Seien Sie versichert, dass dies ein falsch positiver Alarm ist.

## Lizenz
Dieses Skript wird unter einer MIT-Lizenz bereitgestellt.

## Autoren
Dieses Skript wurde von [FuZeee](https://github.com/FuZeee) erstellt.

## Versionshistorie
- Version 1.0: Erstveröffentlichung des Skripts.

## Unterstützung
Für Probleme oder Fragen wenden Sie sich bitte über den [GitHub-Link](https://github.com/FuZeee/RLVideoManager/issues).

Vielen Dank, dass Sie dieses Skript verwenden!
