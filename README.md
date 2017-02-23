#Index-Generator

Gesucht ist ein Pascal-Programm IndexGen, das für einen gegebenen Text (in einer Textdatei) einen Index erzeugt. Ein Index ist die lexikographisch sortierte Liste aller Wörter des Texts, wobei für jedes Wort in aufsteigend sortierter Reihenfolge die Nummern all jener Zeilen angegeben ist, in denen das Wort im Text vorkommt. Dabei ist zwischen Groß- und Kleinschreibung nicht zu unter- scheiden, alle Wörter können deshalb z. B. in Kleinbuchstaben umgesetzt werden.

###Beispiel:
Text:

Ach wie gut, dass niemand weiß,
dass ich Rumpelstilzchen heiß.

Index:
ach 1 
...
dass 1, 2 
...
wie 1

Ihr Programm muss mit
IndexGen InputFileName.txt aufgerufen werden können (der Name der Textdatei wird also in Form eines Kommandozeilen- Parameters übergeben) und muss den Index auf die Standardausgabe schreiben. Der Index kann dann bei Bedarf mit Hilfe von Ausgabeumleitung auch in eine Datei umgeleitet werden, z. B. mit

*IndexGen InputFileName.txt > IndexFileName.txt*

Verwenden Sie eine Hashtabelle zur Verwaltung der Einträge (= Wort mit seinen Zeilennummern). Vor Ausgabe des Ergebnisses sind die Wörter im Index mit Quicksort zu sortieren. Testen Sie Ihre Lösungen ausführlich, indem Sie für das Fachhochschul-Studiengesetz (in der Datei FHStG2011.txt im moodle-Kurs) einen Index generieren und vergleichen Sie Ihre Lösung auch mit jener von Kol- legInnen um festzustellen, welche effizienter ist. Dazu können Sie das Modul Timer (im moodle- Kurs) verwenden. Um längere Laufzeiten zu erhalten, sollten Sie sich auch (wieder einmal?) mit Franz Kafka beschäftigen (siehe Kafka.txt moodle-Kurs).
Bemerkungen: Da das Thema Dateibearbeitung noch nicht besprochen wurde, finden Sie im mood- le-Kurs in IndexGen.pas eine Vorlage für das zu erstellende Programm.
