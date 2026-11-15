# Änderungen

## 0.1.51

- Ganzer Baum: Die Äste rücken so dicht zusammen, wie es geht, ohne dass sich einer in einen anderen schiebt. Der Baum wird dadurch deutlich schmaler, und die Linien werden kürzer.
- Die eigene Ahnenlinie bleibt kurz und steht mittig zwischen den Familien von Vater und Mutter; Geschwister stehen dicht unter ihren Eltern.
- Eltern von Angeheirateten und Gruppen ohne belegte Verbindung bleiben bei ihrem Zweig, statt zwischen fremde Familien zu rutschen.
- Verbundene Bäume: Die Ansicht passt sich an, sobald der zweite Baum geladen ist. Passt der ganze Baum nicht auf den Bildschirm, steht die eigene Person im Blick.

## 0.1.50

- Stammbaum und Ahnen: Die Karte einer angeklickten Person lässt sich mit Esc schließen.
- Recherche-Import: Ein genaueres Heiratsdatum präzisiert eine noch unbestätigte Heirat, statt eine zweite anzulegen.
- Hat eine Person mehrere Partnerschaften und nennt ein Fund nicht, welche gemeint ist, meldet der Import das als Fehler, statt die Heirat an eine beliebige Partnerschaft zu hängen.

## 0.1.49

- Recherche-Import: Nennt eine Quelle dasselbe Datum für Geburt oder Tod wie ein noch unbestätigter Eintrag, ergänzt der Import nur den fehlenden Ort und die Quelle. Es entsteht kein zweites Ereignis.

## 0.1.48

- Einheitliches Bildformat: Jedes hochgeladene Bild wird als JPEG gespeichert (sRGB, richtig herum gedreht, längste Kante höchstens 4000 Pixel, Qualität 90). Aufnahmedaten (EXIF) bleiben erhalten. Gespeichert wird nur diese Fassung, die hochgeladene Datei selbst nicht. Ein JPEG, das schon so vorliegt, bleibt unverändert; animierte GIFs und alle Dokumente ebenfalls.
- Bereits vorhandene Bilder werden beim ersten Start einmalig im Hintergrund umgewandelt, die bisherigen Dateien danach entfernt. Vor dem Update bitte ein Backup des Datenordners anlegen.
- Uploads dürfen jetzt bis 200 MB groß sein (vorher 25 MB), damit auch große TIFF-Scans hineinpassen.

## 0.1.47

- Stammbaum und Ahnen: Beim Drüberfahren zeigt die Infokarte das Porträt der Person groß an. Läuft die Karte dadurch unten aus dem Bild, rückt sie nach oben.

## 0.1.46

- Duplikaterkennung für alle Uploads: Eine Datei, die im Stammbaum schon vorhanden ist (bytegleich), wird nicht noch einmal gespeichert, egal ob sie über die Galerie, die Personenseite oder „Dokumente“ kommt. Gehört der Upload zu einer Person, wird die vorhandene Datei mit ihr verknüpft. Die Seite sagt, welche Dateien schon da waren.
- Ältere Dateien bekommen beim Start einmalig nachträglich ihren Fingerabdruck, damit die Erkennung auch für sie gilt. Schon vorhandene doppelte Dateien bleiben unverändert.

## 0.1.45

- Die Galerie steht jetzt im Hauptmenü (auf dem iPhone als „Fotos“ in der Tableiste).
- Galerie: Die ganze Seite ist ein Ablagefeld. Oben steht ein sichtbares Feld „Fotos hierher ziehen“ (auch zum Anklicken), beim Ziehen wird die Seite eingerahmt.
- Foto: Der Knopf „Gesicht einrahmen“ ist auch am Rechner sichtbar. Wie bisher lässt sich ein Rahmen auch direkt mit der Maus ziehen.

## 0.1.44

- Ganzer Baum: Die Familie des Partners der zentrierten Person bekommt einen eigenen Block rechts neben Vater- und Mutterlinie, statt sich dazwischenzuschieben. Die Aufteilung richtet sich immer nach der gerade zentrierten Person.

## 0.1.43

- Personenseite: sichtbares Ablagefeld „Dateien hierher ziehen“ unter „Bilder und Dokumente“. Klicken öffnet die Dateiauswahl, mehrere Dateien auf einmal gehen.
- Neben Bildern und PDF lassen sich jetzt auch Word, Excel, OpenDocument, Text, Audio (MP3, M4A, WAV) und Video (MP4, MOV) hochladen. Eine abgelehnte Datei wird gemeldet, die übrigen werden trotzdem hochgeladen.
- Dokument-Kacheln zeigen die Dateiendung (DOCX, TXT …).
- Ganzer Baum: Die Linie des Vaters steht in jeder Generation links von der Linie der Mutter; Zweige rutschen nicht mehr in die andere Seite.
- Ahnen-Ansicht: Konten ohne verknüpfte Person sahen immer dieselbe Person (die erste im Baum). Jetzt startet sie bei der zuletzt im Stammbaum zentrierten Person, sonst bei der jüngsten Person mit den meisten Vorfahren.

## 0.1.42

- Neu: Galerie (unter „Mehr“). Viele Fotos auf einmal hochladen, etwa einen Ordner digitalisierter Dias: per Drag and Drop oder über „Fotos hochladen“. Schon vorhandene Dateien werden erkannt und nicht doppelt gespeichert.
- Gesichter werden auf den Fotos automatisch gefunden und als Vorschlag eingerahmt. Die Suche läuft auf dem eigenen Server, es wird nichts an fremde Dienste geschickt. Du wählst nur noch den Namen; fehlende Gesichter rahmst du mit der Maus (oder nach „Gesicht einrahmen“ mit dem Finger) selbst ein.
- Markierte Fotos erscheinen auf der Personenseite. Ein markiertes Gesicht lässt sich mit einem Klick als Porträt der Person übernehmen.
- Galerie filtern: nach Person, ohne Personen, mit offenen Gesichtern; Suche nach Titel, Datum und Namen.

## 0.1.40

- Die linke Leiste lässt sich einklappen (Knopf oben in der Leiste oder Taste „["). Eingeklappt bleibt ein schmaler Streifen mit dem Baum-Zeichen und den Ansichten als senkrechte Wörter. Der Zustand wird pro Browser gemerkt.
- Stammbaum, Ahnen, Zeitstrahl und Karte laden Änderungen automatisch nach, etwa nach einem Import oder wenn jemand anderes etwas einträgt. Ausschnitt und Zoom bleiben dabei stehen.

## 0.1.39

- Personenseite: Bilder und PDFs lassen sich per Drag and Drop hochladen. Auf das Porträt gezogen wird das erste Bild zum Porträt, sonst landen die Dateien bei den Bildern und Dokumenten (hat die Person noch kein Porträt, wird das erste Bild dazu).

## 0.1.38

- Ahnen-Ansicht: mit der Maus über eine Person fahren zeigt jetzt wie im Stammbaum die Detailkarte (Verwandtschaft, Lebensdaten, Orte).

## 0.1.37

- Generationsleiste: beim Zoomen gehen die Bezeichnungen fließend in die Striche über und bleiben dabei an derselben Stelle, statt zu springen.

## 0.1.36

- Handy: die Generationsbezeichnungen links im Baum sind wieder zu sehen. Sie stehen jetzt in der Lücke über der jeweiligen Reihe, damit sie keine Karte verdecken. Weit herausgezoomt bleiben es dünne Striche.

## 0.1.35

- Ganzer Baum / Verbundene Bäume: die Anordnung achtet wieder auf kurze Linien und eine kompakte Breite, statt die Generationen treppenartig auseinanderzuziehen.
- Nicht verbundene Gruppen (z. B. die Lynker aus Lüdenscheid) stehen neben der Person mit demselben Familiennamen, ohne dass eine Verknüpfung angelegt wird.
- Neuer Layout-Test mit anonymisierten Beispieldaten läuft in der CI.

## 0.1.34

- Personenseite: Zurück-Knopf, Esc führt ebenfalls zurück. Der Baum öffnet sich danach wieder mit derselben Ansicht, Position und Zoomstufe.
- Baumkarten: lange Datumszeilen werden kürzer geschrieben (z. B. „1959–2019 (~60)“) und ragen nicht mehr über den Kartenrand.

## 0.1.33

- Recherche-Import: ein neues Kind der Eltern, die schon eine gemeinsame Familie haben, kommt in diese Familie statt in eine doppelte.

## 0.1.32

- Ganzer Baum: die Reihenfolge wird gründlicher gesucht, damit jede Familie unter ihren Eltern steht und Linien sich kaum kreuzen (z. B. Cousins im Kutschera-Baum).
- Personen ohne sichtbare Eltern oder Kinder stehen neben ihrer Reihe statt weit abseits.

## 0.1.31

- Ganzer Baum: Geschwister bleiben nebeneinander, auch wenn eine Schwester in eine andere Familie eingeheiratet hat; weniger lange Querlinien.

## 0.1.30

- Recherche-Import: ein genaueres Datum für ein bestätigtes Lebensereignis legt kein zweites an, sondern einen Beleg und eine Prüfaufgabe.

## 0.1.29

- Karte: Ereignisse ohne Datum erscheinen im Zeitverlauf erst ab dem Geburtsjahr der Person.

## 0.1.28

- Erste Version als Home-Assistant-Add-on: Anmeldung über Home Assistant, Daten im Add-on-Ordner.
