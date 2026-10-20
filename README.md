<p align="center">
  <a href="https://jpnote.de"><img src="https://jpnote.de/img/icon-192.png" alt="JP Note" width="96" height="96"></a>
</p>

<h1 align="center">JP Note</h1>

<p align="center">
  Dein Notizzettel am Bildschirmrand.<br>
  Aufgaben, Notizen und Termine in einem Dock, das mit <kbd>Alt</kbd> + <kbd>N</kbd> erscheint.
</p>

<p align="center">
  <a href="https://jpnote.de/download/"><b>Download</b></a> ·
  <a href="https://jpnote.de/funktionen/">Funktionen</a> ·
  <a href="https://jpnote.de/neuigkeiten/">Neuigkeiten</a> ·
  <a href="https://jpnote.de/hilfe/">Hilfe</a> ·
  <a href="#english">English</a>
</p>

---

In diesem Repository liegen die fertigen Installationsdateien von JP Note. Der Quellcode wird hier nicht veröffentlicht. Am einfachsten lädst du JP Note über die [Download-Seite](https://jpnote.de/download/), dort ist die passende Datei für dein System schon ausgewählt.

## Aktuelle Version laden

| System | Datei | Hinweis |
|---|---|---|
| Windows 10 und 11 (64 Bit) | [JP-Note-Setup.exe](https://github.com/JanReich/jp-note-releases/releases/latest/download/JP-Note-Setup.exe) | Installer, Updates per Klick in der App |
| Windows ohne Installation | [JP-Note-Portable.exe](https://github.com/JanReich/jp-note-releases/releases/latest/download/JP-Note-Portable.exe) | z. B. vom USB-Stick, Daten liegen neben der Datei |
| macOS 12 oder neuer | [JP-Note-Mac.dmg](https://github.com/JanReich/jp-note-releases/releases/latest/download/JP-Note-Mac.dmg) | Apple Silicon und Intel in einer Datei |
| Linux (x64) | [JP-Note-Linux.AppImage](https://github.com/JanReich/jp-note-releases/releases/latest/download/JP-Note-Linux.AppImage) | läuft auf den meisten Distributionen, aktualisiert sich selbst |
| ChromeOS, Intel/AMD | [JP-Note-ChromeOS.deb](https://github.com/JanReich/jp-note-releases/releases/latest/download/JP-Note-ChromeOS.deb) | braucht die Linux-Entwicklungsumgebung (Beta) |
| ChromeOS, ARM | [JP-Note-ChromeOS-ARM.deb](https://github.com/JanReich/jp-note-releases/releases/latest/download/JP-Note-ChromeOS-ARM.deb) | falls die Intel/AMD-Datei nicht passt |
| iPhone und Android | [app.jpnote.de](https://app.jpnote.de) | Handy-App direkt aus dem Browser, ohne App-Store |

Ältere Versionen findest du unter [Releases](https://github.com/JanReich/jp-note-releases/releases).

## Installation

**Windows:** Installer starten. Meldet Windows „Der Computer wurde durch Windows geschützt“, auf *Weitere Informationen* und dann *Trotzdem ausführen* klicken. Die Meldung erscheint, weil JP Note noch neu ist und Microsoft den Herausgeber noch nicht kennt.

**macOS:** Die .dmg öffnen und JP Note in *Programme* ziehen. Lässt sich die App beim ersten Start nicht öffnen: *Systemeinstellungen → Datenschutz & Sicherheit* → bei JP Note *Trotzdem öffnen*.

**Linux:** Datei ausführbar machen und starten:

```bash
chmod +x JP-Note-Linux.AppImage
./JP-Note-Linux.AppImage
```

Fehlt FUSE (häufig unter neueren Ubuntu-Versionen): `sudo apt install libfuse2t64`

**ChromeOS:** Unter *Einstellungen → Info zu ChromeOS → Entwickler* die Linux-Entwicklungsumgebung einschalten, dann die .deb in der App *Dateien* doppelklicken und *Installieren* wählen.

Ausführliche Anleitungen mit Bildern stehen auf der [Download-Seite](https://jpnote.de/download/).

## Dateien prüfen

Jede Version enthält eine Datei `SHA256SUMS.txt` mit den Prüfsummen aller Downloads. So vergleichst du sie:

```powershell
# Windows (PowerShell oder Eingabeaufforderung)
certutil -hashfile JP-Note-Setup.exe SHA256
```

```bash
# macOS und Linux
shasum -a 256 JP-Note-Mac.dmg
```

Die ausgegebene Zeichenfolge muss mit dem Eintrag in [SHA256SUMS.txt](https://github.com/JanReich/jp-note-releases/releases/latest/download/SHA256SUMS.txt) übereinstimmen. Lade JP Note nur über jpnote.de oder dieses Repository.

## Was JP Note kann

- **Dock am Bildschirmrand:** mit <kbd>Alt</kbd> + <kbd>N</kbd> ein- und ausblenden, Schnellerfassen mit <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd>
- **Aufgaben:** Fälligkeit, Erinnerung, Wiederholung, Unteraufgaben, Priorität, Wochen- und Monatsübersicht
- **Notizen:** Listen, Checklisten, Tabellen, Bilder und Dateien unter jeder To-do-Liste
- **Sync:** Ende-zu-Ende verschlüsselt zwischen PC, Mac, Linux und Handy
- **Offline:** alles funktioniert ohne Internet und gleicht sich später ab
- **Fokus-Timer** mit Lo-Fi-Musik, **Literaturverwaltung** und **Passwort-Notiz** (Pro)

JP Note ist kostenlos auf einem Gerät. Pro gibt es als Einmalkauf ohne Abo, die ersten 14 Tage kannst du alle Pro-Funktionen testen. Details: [Funktionen und Preise](https://jpnote.de/funktionen/#preise)

## Updates

Die installierte Version (Windows-Installer, macOS, AppImage) prüft selbst auf Updates und installiert sie per Klick. Was sich geändert hat, steht unter [Neuigkeiten](https://jpnote.de/neuigkeiten/).

## Hilfe und Feedback

- Antworten auf häufige Fragen: [jpnote.de/hilfe](https://jpnote.de/hilfe/)
- Fehler melden und Wünsche einreichen: [jpnote.de/feedback](https://jpnote.de/feedback/)
- E-Mail: [info@jpnote.de](mailto:info@jpnote.de)

Bitte schick nie Passwörter oder Wiederherstellungsschlüssel, auch nicht an uns.

## Rechtliches

[Impressum](https://jpnote.de/impressum/) · [Datenschutz](https://jpnote.de/datenschutz/) · [AGB](https://jpnote.de/agb/)

© 2026 JP Note. Alle Rechte vorbehalten. Die Dateien in diesem Repository dürfen zur eigenen Nutzung heruntergeladen und installiert werden.

---

<a id="english"></a>

## English

JP Note is a notepad at the edge of your screen: tasks, notes and dates in one dock that appears with <kbd>Alt</kbd> + <kbd>N</kbd>. This repository contains the installation files only.

**Download:** [jpnote.de/en/download](https://jpnote.de/en/download/) picks the right file for your system. Direct links are in the table above (Windows 10/11 64-bit, macOS 12+, Linux AppImage x64, ChromeOS .deb). The phone app runs in your browser at [app.jpnote.de](https://app.jpnote.de).

**First start:** Windows may show “Windows protected your PC”: click *More info* → *Run anyway*. On macOS go to *System Settings → Privacy & Security* → *Open Anyway*. Both warnings appear because JP Note is still new, not because the file is harmful.

**Verify:** compare the SHA-256 checksum of your download with `SHA256SUMS.txt` in the release (see the commands above).

Free on one device. Pro is a one-time purchase, no subscription, with a 14-day trial. Help: [jpnote.de/en/help](https://jpnote.de/en/help/) · Feedback: [jpnote.de/en/feedback](https://jpnote.de/en/feedback/)
