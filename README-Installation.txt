INDUSTRIEZEIT – INSTALLATION AUF ANDROID UND IPHONE

INHALT
index.html – Rechner
manifest.webmanifest – App-Informationen
sw.js – Offline-Cache
icons/ – App-Icons

1. VERÖFFENTLICHEN (EINMALIG)
Die Dateien müssen über HTTPS bereitgestellt werden. Eine ZIP-Datei direkt auf dem Handy zu öffnen reicht für die PWA-Installation nicht.

Einfach mit GitHub Pages:
- Kostenloses Konto auf https://github.com erstellen oder anmelden.
- Neues öffentliches Repository anlegen, z. B. industriezeit.
- Alle Dateien und den Ordner icons aus dieser ZIP ins Repository hochladen (nicht nur die ZIP).
- Unter Settings > Pages bei Build and deployment: Deploy from a branch wählen, Branch main und Ordner / (root) auswählen, speichern.
- Warten, bis GitHub Pages die URL anzeigt, meist https://BENUTZERNAME.github.io/industriezeit/

2. ANDROID
- Die HTTPS-Adresse in Chrome öffnen.
- Browser-Menü (drei Punkte) > App installieren oder Zum Startbildschirm hinzufügen wählen.

3. IPHONE
- Die HTTPS-Adresse in Safari öffnen.
- Teilen > Zum Home-Bildschirm > Hinzufügen auswählen (je nach iOS-Version kann der Menüpunkt anders liegen).

OFFLINE
Nach dem ersten vollständigen Laden werden die Dateien im Cache gespeichert. Danach funktioniert die App auch ohne Internet, solange die gespeicherten Website-Daten nicht gelöscht werden.

HINWEISE
- Eine PWA ist keine APK und keine IPA.
- Installation erfordert HTTPS (localhost ist eine Ausnahme für Entwicklung).
- Nach Änderungen ggf. die Cache-Version in sw.js erhöhen und Seite neu laden.
- Eingabe Industriezeit: 1,50 entspricht 01:30 Normalzeit.
- Eingabe Normalzeit: 01:30 entspricht 1,5 Industriestunden.
