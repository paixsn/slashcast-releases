# SlashCast – Beta

SlashCast ist ein Makro-Editor für World of Warcraft: Makros schreiben, prüfen, erklären lassen und auf all deinen Geräten gleich halten. Das hier ist die Beta für Freunde und Familie.

## Herunterladen

| Gerät | So bekommst du es |
|---|---|
| **iPhone, iPad, Mac** | Über TestFlight: **https://testflight.apple.com/join/awkTkc47** (erst die App „TestFlight“ aus dem App Store laden, dann den Link öffnen) |
| **Windows** | [SlashCast-Windows-Setup.exe](https://github.com/paixsn/slashcast-releases/releases/latest/download/SlashCast-Windows-Setup.exe) – Installer mit allem drin (empfohlen, neu)<br>Falls der Installer nicht klappt: [SlashCast-Windows.zip](https://github.com/paixsn/slashcast-releases/releases/latest/download/SlashCast-Windows.zip) (braucht Java) |
| **Linux** (Arch/CachyOS, Ubuntu, Fedora …) | [SlashCast-Linux.tar.gz](https://github.com/paixsn/slashcast-releases/releases/latest/download/SlashCast-Linux.tar.gz) |
| **WoW-Addon** (optional) | [SlashCast-Addon.zip](https://github.com/paixsn/slashcast-releases/releases/latest/download/SlashCast-Addon.zip) |

## Installieren

**Windows – Installer (empfohlen)**
1. `SlashCast-Windows-Setup.exe` starten. Java ist schon dabei.
2. Windows warnt evtl. „Der Computer wurde durch Windows geschützt“ (die App ist noch nicht signiert): **Weitere Informationen → Trotzdem ausführen**.
3. Danach findest du SlashCast im Startmenü.

Der Installer ist neu – falls er bei dir nicht klappt, nimm die ZIP-Variante und sag kurz Bescheid.

**Windows – ZIP (Ausweichweg)**
1. ZIP entpacken, den Ordner `SlashCast` an einen festen Platz legen (z. B. Dokumente).
2. Einmal Java installieren – Terminal öffnen und eingeben: `winget install EclipseAdoptium.Temurin.21.JRE`
3. `SlashCast.bat` doppelklicken. Tipp: Verknüpfung auf den Desktop legen.

**Linux**
```
tar xzf SlashCast-Linux.tar.gz
sudo sh slashcast-linux/install.sh          # für alle Benutzer
# oder ohne sudo nur für dich:  sh slashcast-linux/install.sh --user
```
Das Skript installiert Java, falls es fehlt, und legt SlashCast ins App-Menü. Entfernen: dasselbe mit `--remove`.

**iPhone, iPad, Mac:** TestFlight-Link öffnen → „Installieren“. Updates kommen automatisch über TestFlight.

## Was ist wofür?

- **Die App** – Makros schreiben (als Text oder Zeile für Zeile als „Bausteine“), Fehler sehen, Erklärungen in Klartext, Zauber-Vorschläge, Vorlagen.
- **Synchronisierung** – hält deine Makros auf allen Geräten gleich, ohne Konto und ohne Server: Am PC unter *Einstellungen → Synchronisierung* „Handy und andere Geräte … abgleichen“ einschalten, am Handy den QR-Code scannen. Abgeglichen wird, solange beide Apps im selben WLAN offen sind. (Linux mit Firewall: die App zeigt den einen Befehl, der nötig ist.)
- **Spielordner** (PC/Mac) – liest deine Makros direkt aus WoW und schreibt sie zurück.
- **Addon** (optional) – bringt Makros zuverlässig ins Spiel und sagt der App, welche Zauber deine Charaktere kennen. Am einfachsten über die App installieren: *Spielordner → Addon installieren*. Von Hand: `SlashCast-Addon.zip` nach `World of Warcraft/_retail_/Interface/AddOns/` entpacken. Im Spiel: `/slashcast`.
- **Pro** – Übersetzen zwischen Spielsprachen, Spielordner, Sicherungen, unbegrenzt Charaktere. Auf Windows/Linux per Lizenzschlüssel (*Menü ⋯ → SlashCast Pro → Schlüssel einfügen → Aktivieren*), auf iPhone/Mac in TestFlight kostenlos „kaufen“ (Testkauf, es wird nichts abgebucht).

## Probleme?

Einfach in unserem Discord melden – am besten mit Gerät, was du gemacht hast und einem Screenshot.

SlashCast ist eine inoffizielle Fan-App und steht in keiner Verbindung zu Blizzard Entertainment.
