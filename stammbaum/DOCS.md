# Stammbaum

Ein Familienstammbaum für Home Assistant: Personen mit Fotos und Dokumenten, Ereignisse
(Geburt, Hochzeit, Umzug …), Quellen mit Zuverlässigkeit, und die Ansichten Stammbaum, Ahnen,
Zeitstrahl und Weltkarte mit Wanderungen.

## Anmeldung

Es gibt kein eigenes Login. Der Stammbaum öffnet sich in der Seitenleiste von Home Assistant,
und Home Assistant sagt dem Add-on, welcher Benutzer angemeldet ist.

- **Verwalter**: Wer unter „Verwalter“ in der Konfiguration steht (Login-Name des HA-Benutzers).
  Ist die Liste leer, wird der erste Benutzer, der den Stammbaum öffnet, Verwalter.
- **Alle anderen** Home-Assistant-Benutzer bekommen die „Rolle für alle Home-Assistant-Benutzer“
  (Standard: nur ansehen).
- In der App unter **Verwaltung** lassen sich weitere Stammbäume anlegen, Rollen pro Baum und
  Benutzer vergeben und Benutzer zu Verwaltern machen. Jeder Benutzer erscheint dort, sobald er den
  Stammbaum einmal geöffnet hat.

Der Stammbaum ist nur über Home Assistant erreichbar (kein eigener Port). Über die Home-Assistant-App
auf dem Handy funktioniert er genauso.

## Daten übernehmen

Unter **Verwaltung → Import** lässt sich eine GEDCOM-Datei (z. B. aus Ancestry, MyHeritage,
Gramps) importieren. Unter **Verwaltung → Export** gibt es GEDCOM und ein Vollbackup als JSON.

## Datensicherung

Datenbank, Fotos und Dokumente liegen im Datenordner des Add-ons und sind damit Teil jeder
Home-Assistant-Datensicherung. Während einer Sicherung wird das Add-on kurz angehalten, damit die
Datenbank vollständig gesichert wird.

## Datenschutz

Alle Daten bleiben auf deinem Home-Assistant-Gerät. Nach außen geht nur die Ortssuche für die Karte
(Ortsnamen an OpenStreetMap). Sie lässt sich in der Konfiguration abschalten.
