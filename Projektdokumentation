# Projekt-Dokumentation

Samuel Lucena Losada 

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 01.05 | 0.0.1   | Projekt Start |
|       | ...     |                                                              |
| 21.06 | 1.0.0   |  Projekt Ende                                                |

## 1 Informieren

### 1.1 Ihr Projekt

Eine C# Applikation die mit Hilfe von einer MongoDb Datenbank ein Pokemonkampf simulieren kann

In diesem Projekt möchte ich einen Pokémon Kampfsimulator entwickeln, der Spieler ermöglicht, Pokemons gegeneinander antreten zu lassen. Ich hoffe, meine Fähigkeiten in der C#-Programmierung zu vertiefen und gleichzeitig praktische Erfahrungen mit der Integration und Nutzung einer MongoDB-Datenbank zu sammeln. Besonders interessieren mich die Implementierung von rundenbasierten Spielmechaniken, die Gestaltung einer benutzerfreundlichen Oberfläche und die Optimierung der Datenbankabfragen für eine reibungslose Spielerfahrung.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss |  F    | Als ein Spieler möchte ich, dass mir zu Beginn des Spiels drei zufällige Pokémon zugewiesen werden, damit ich mein Team für den Kampf bereit habe. |
| 2    |Muss |  F    |  Als ein Spieler möchte ich, dass mein Pokémon eine Auswahl an Attacken hat, damit ich der Kampf immer anders aufgebaut ist.   |
| 3 | Muss | F |Als ein Spieler möchte ich, dass der Kampf rundenbasiert abläuft, damit Spieler1 und Spieler2 abwechselnd Angriffe und Aktionen ausführen können. |
| 4 | Muss | F  | Als ein Spieler möchte ich, dass die HP meines Pokémon nach einem Angriff korrekt berechnet und angezeigt werden, damit ich den Zustand meines Pokémon immer im Blick habe.|
| 5| Muss | Q | Als ein Spieler möchte ich, dass die Benutzeroberfläche intuitiv und übersichtlich gestaltet ist, damit ich einfach durch das Spiel navigieren und meine Aktionen ausführen kann.|
| 6 | Kann | R |: Als ein Spieler möchte ich, dass ich während des Kampfes Heilungs- oder andere Items einsetzen kann, damit das Spiel taktische Vorteile nutzen kann.|
| 7 | Muss | F  | Als ein Spieler möchte ich, dass das Spiel den Kampf korrekt beendet und den Gewinner anzeigt, damit ich weiß, wer den Kampf gewonnen hat.|
| 8 | Muss| F  |Als ein Entwickler möchte ich, dass die Daten aus MongoDB korrekt in das Spiel geladen werden, damit alle Pokémon, Moves und Items entsprechend ihrer Datenbankeinträge dargestellt werden.|
| 9 | Kann | Q  |  Als ein Spieler möchte ich, dass das Spiel flüssig und ohne Verzögerungen läuft, damit man den Stand des Spiels genau sieht.|
| 10| Muss | F |Als ein Spieler möchte ich, dass das Spiel die verbleibende HP meiner Pokémon nach jeder Runde anzeigt, damit ich das Spiel strategisch darauf Items benutzen kann.|



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1  | Überprüfe, ob bei Spielstart jedem Spieler genau drei Pokémon zufällig zugewiesen werden.| Spiel starten| Jeder Spieler hat eine Liste mit drei unterschiedlichen Pokémon.|
| 2 |Simuliere einen Angriff eines Pokémon auf ein gegnerisches Pokémon und überprüfe die Berechnung des Schadens.| Spiel starten|Die HP des gegnerischen Pokémon werden um den korrekten Schadenswert reduziert.|
| 3 |Wende ein Heilungsitem auf ein eigenes Pokémon an und überprüfe die Aktualisierung der HP.| Spiel gestartet|Die HP des Pokémon werden entsprechend des Heilungseffekts erhöht.|
| 4|Simuliere einen Kampf, bis alle Pokémon eines Spielers keine HP mehr haben, und überprüfe die Endbedingung des Kampfes.| Spiel gestartet |Das Spiel beendet den Kampf korrekt und gibt den Gewinner oder ein Unentschieden aus.|
| 5|Überprüfe die korrekte Verbindung und Abfrage von Pokémon-Daten aus der MongoDB-Datenbank.| Spiel gestartet |Die im Spiel angezeigten Pokémon, Moves und Items entsprechen den in der Datenbank gespeicherten Informationen.|



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1  |21.06|Samuel Lucena| Daten eingauen|2 Lekt.       |
| 2 |21.06|Samuel Lucena| Datenbank verbinden|  3 Lekt.  |
| 3 |21.06|Samuel Lucena| CRUD implementation | 5 Lekt. |
| 4 |21.06|Samuel Lucena| Spielmechanik | 10 Lekt. |

Total: 20 Lektionen

## 3 Entscheiden

Ich habe mich dazu entschieden dieses Projekt zu machen da es mir sicher viel künftig mit Datenbanken helfen wird. Ausserdem Denke ich das es eine lustige Art wird dies zu implementieren.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1    | 17.05 |Samuel Lucena | 2 Lekt.    | 2 Lekt.           |
| 2    | 24.05  |Samuel Lucena | 3 Lekt.    |  4 Lekt.          |
|3     | 14.06 |Samuel Lucena| 5 Lekt. | 7 Lekt. |
|4     |21.06  |Samuel Lucena| 10 Lekt. | 10+ Lekt. (unvollständig) |

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1  |       |   unvollständig     |Samuel Lucena |
| 2 |       |unvollständig|Samuel Lucena |
| 3 | |unvollständig|Samuel Lucena |
| 4 | |unvollständig|Samuel Lucena |
| 5 | |unvollständig (ging eninmal) |Samuel Lucena |
| 7 | |ok |Samuel Lucena |
| 8 | |ok |Samuel Lucena |
| 9 | |unvollständig |Samuel Lucena |
| 10 | |unvollständig |Samuel Lucena |

Ich weiss nicht ob ich mir die Ziele zu hoch gesetzt habe oder ich einfach nicht sehr effektiv gearbeitet habe, oder beides.
## 6 Auswerten

Ersichtlich in meinem Portfolioeintrag auf Mahara
