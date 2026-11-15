# Änderungen

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
