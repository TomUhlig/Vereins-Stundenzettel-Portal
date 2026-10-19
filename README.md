# Vereins-Stundenzettel · öffentliches Portal

Öffentliche Browser-Oberfläche des privaten Vereins-Stundenzettel-Projekts.
Dieses Repository enthält ausschließlich die fertige allgemeine Oberfläche
und die leere Vereinsvorlage. Keine Trainerdateien und keine Unterschriftsbilder.
Der Git-Verlauf des privaten Projekts wurde nicht übernommen.

Nach erfolgreicher Pages-Veröffentlichung:
https://tomuhlig.github.io/Vereins-Stundenzettel-Portal/

## Nutzung ohne Installation

1. Portal öffnen.
2. Eigenen Trainer mit Wochenplan und selbst gewählter vierstelliger PIN anlegen,
   oder ein separat erhaltenes verschlüsseltes Backup importieren.
3. Namen auswählen, PIN eingeben, Monat oder Jahr wählen, PDFs herunterladen.

Trainerdaten werden in der Browser-Datenbank des jeweiligen Geräts gespeichert.
Die PIN ist ein einfacher lokaler Zugangsschutz, keine zentrale Anmeldung.
Verschlüsselung mit einer vierstelligen PIN schützt nicht zuverlässig vor
gezieltem Offline-Ausprobieren. Backups und fertige PDFs persönlich aufbewahren.

## Veröffentlichung

Kostenlos über GitHub Pages aus diesem öffentlichen Repository. Unter
Settings → Pages → Source „GitHub Actions“ auswählen, falls die automatische
Aktivierung nicht erlaubt ist. Anschließend den Workflow „Kostenloses
Trainerportal“ starten. Der Quellcode wird im separaten privaten Projekt gepflegt;
dieses Repository erhält nur die geprüfte öffentliche Build-Ausgabe.
