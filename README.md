# Vereins-Stundenzettel · öffentliches Portal

Öffentliche Browser-Oberfläche des privaten Vereins-Stundenzettel-Projekts.
Dieses Repository enthält die fertige Browser-Oberfläche, die leere Vereinsvorlage
und ausdrücklich freigegebene verschlüsselte Trainerdateien unter `site/trainers/`.
Die gemeinsame Namensliste wird beim Öffnen auf jedem Gerät automatisch geladen.
Der Git-Verlauf des privaten Quellprojekts wurde nicht übernommen.

Nach erfolgreicher Pages-Veröffentlichung:
https://tomuhlig.github.io/Vereins-Stundenzettel-Portal/

## Nutzung ohne Installation

1. Portal öffnen.
2. Einen hinterlegten Namen auswählen und die zugehörige PIN eingeben.
3. Monat oder Jahr wählen und PDFs herunterladen.

Ein Backup-Import ist für veröffentlichte Trainer nicht erforderlich. Neue lokale
Trainer und Planänderungen können über „Trainerpaket für GitHub“ exportiert und
unter `site/trainers/` veröffentlicht werden. Die bestehende Namensliste dabei
zusammenführen. Speichern im Browser allein ändert die Repository-Dateien nicht.

Veröffentlichte Trainerdateien werden dauerhaft im Projekt gespeichert.
Zusätzliche lokale Trainerdaten liegen in der Browser-Datenbank des jeweiligen Geräts.
Die PIN ist ein einfacher lokaler Zugangsschutz, keine zentrale Anmeldung.
Verschlüsselung mit einer vierstelligen PIN schützt nicht zuverlässig vor
gezieltem Offline-Ausprobieren. Backups und fertige PDFs persönlich aufbewahren.

## Veröffentlichung

Kostenlos über GitHub Pages aus diesem öffentlichen Repository. Unter
Settings → Pages → Source „GitHub Actions“ auswählen, falls die automatische
Aktivierung nicht erlaubt ist. Anschließend den Workflow „Kostenloses
Trainerportal“ starten. Der Quellcode wird im separaten privaten Projekt gepflegt;
dieses Repository erhält die geprüfte öffentliche Build-Ausgabe und gezielt
freigegebene verschlüsselte Trainerdateien. Auch verschlüsselte Dateien sind
öffentlich herunterladbar. Mit einer bekannten PIN lassen sich ihre Inhalte
öffnen; eine vierstellige PIN ist kein belastbarer Schutz für Unterschriftsbilder.

## Adminseite

https://tomuhlig.github.io/Vereins-Stundenzettel-Portal/admin.html

Mit dem gewählten Adminpasswort öffnen. Marko ist bereits in den verschlüsselten
Verwaltungsdaten hinterlegt. Trainer lassen sich anlegen und bearbeiten.
Für dauerhafte Änderungen auf GitHub einmal einen Fine-grained Token für dieses
Repository mit Contents: Read and write in der Adminseite verbinden. Die
Schritt-für-Schritt-Anleitung steht direkt im Formular. Der Token wird nicht
im Repository gespeichert; eine gemerkte Kopie bleibt mit dem Adminpasswort
verschlüsselt im jeweiligen Browser.

Die Online-Verwaltungsdaten unter `site/admin/` und die Trainerdateien unter
`site/trainers/` sind maßgeblich. Bei Frontend-Updates niemals durch ältere
Seed-Dateien aus dem privaten Quellprojekt ersetzen.
