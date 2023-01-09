# Projekt-Dokumentation

✍️ Keller

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | 0.0.2   |                                                              |
|       | 0.0.3   |                                                              |
|       | 0.0.4   |                                                              |
|       | 0.0.5   |                                                              |
|       | 0.0.6   |                                                              |
|       | 1.0.0   |                                                              |

# 0 Ihr Projekt

✍️ Beschreiben Sie Ihr Projekt in einem griffigen Satz.

# 1 Analyse

✍️ Beschreiben Sie, auf welchem Tier Sie die dynamischen Elemente der Anwendung unterbringen möchten:

* Tier 1 (Presentation): ...
* Tier 2 (Webserver):
* Tier 3 (Application Server):
* Tier 4 (Dataserver):

# 2 Technologie

✍️ Beschreiben Sie für dieselben Tiers, welche Programmiersprache bzw. Technologie Sie verwenden möchten.

# 3 Datenbank

✍️ Wie steuern Sie Ihre Datenbank an? Wie ist das Interface aufgebaut? 

# 4.1 User Stories

✍️ Formulieren Sie klare Anforderungen in der Form von User Stories (*„als … möchte ich … damit …“*) und zu jeder Anforderung mindestens einen dazugehörigen Testfall (in Kapitel 4.2). 

✍️ Formulieren Sie weitere, eigene Anforderungen und Testfälle, wie Sie Ihre Applikation erweitern möchten. Geben Sie diesen statt einer Nummer einen Buchstaben (`A`, `B`, etc.)

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 0    |                 |      | Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️ |
| 1    |                 |      | Als Administrator möchte ich mich durch Benutzername und Passwort authentifizieren, damit ich auf Administrationsrechte zugreiffen kann.|
| 2    |                 |      | Als Administrator möchte ich Phrasen und Rätselwörter anlegen, ändern und löschen können, damit ich die Inhalte der App verwalten kann.|
| 3    |                 |      | Als Administrator möchte ich Kategorien anlegen und jedes Wort bzw. jede Frage einer Kategorie zuordnen können, damit ich die Inhalte der App strukturieren und organisieren kann.|
| 4    |                 |      | Als Administrator möchte ich einzelne Einträge der Highscore-Liste löschen können, damit ich die Integrität der Highscore-Liste gewährleisten kann.|
| 5    |                 |      | Als Kandidat möchte ich meinen Namen eingeben können, damit ich mich mit anderen Kandidaten vergleichen kann.|
| 6    |                 |      | Als kandidat möchte ich zu jederzeit meinen Kontostand sehen, damit ich weiss, wie viel Geld noch zur Verfügung steht und wie viel ich noch ausgeben kann.|
| 7    |                 |      | Als Kandidat möchte ich zu jederzeit meine noch vorhandenen Lebenspunkte sehen, damit ich weiss, wie viele Vokale ich noch kaufen kann.|
| 8    |                 |      | Als kandidat möchte ich informiert werden, ob die gegebene Antwort richtig oder falsch ist, damit ich weiss, ob ich ein Wort herausgefunden habe oder nicht.|
| 9    |                 |      | Als Kandidat möchte ich den Rang, der Name des Spielers, den Zeitpunkt des Spiels, den Geldbetrag und die Anzhal Spielrunden in der Highscore-Liste sehen, damit ich mich mit anderen Kandidaten vergleichen kann.|
| 10    |                 |      | Als Kandidat möchte ich, dass die Highscore-Liste nach Rang aufsteigend sortiert ist, damit ich weiss, wer der momentane Leader des Spiels ist.|
| 11    |                 |      | Als Entwickler möchte ich, dass keinem Kandidaten, die selbe Phrase mehr als einaml gestellt wird, damit das Spiel nicht an Schwierigkeitsgrad verliert.|
| 12    |                 |      | Als kandidat möchte ich jederzeit spielen, aufhören oder meinen Gewinn in die Highscore-Liste übernehmen können, damit gewisse Freiheiten bei der Bedienung der App habe.|
| 13    |                 |      | Als Entwickler möchte ich, dass das Spiel mit einer spielbaren Anzahl Wörtern und Fragen gefüllt wird, damit es gespielt werden kann.|
| 14    |                 |      | Als Kandidat möchte ich, dass die Anzahl Spielrundenen gezählt werden, damit ich weiss, wie oft schon gespielt wurde.|
| 15    |                 |      | Als Administator möchte ich, dass einfache Formulareingaben, wie leere Textfelder client- und serverseitig geprüft werden, damti...|
| 16    |                 |      | Als Entwickler möchte ich, dass eine Datenbankanbindung verwendet wird, die möglichst unabhängig vom tatsächlich eingesetzten Produkt ist, damit...|
| 17    |                 |      | Als Entwickler möchte ich das Transaktionsmanagement einsetzten, damit...|
| 18    |                 |      | Als Entwickler möchte ich, dass alle Sicherheitspuntke umgesetzt werden, damit...|



✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc. oder Zahl), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). 

# 4.2 Testfälle

| TC-№ | Vorbereitung | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

# 5 Prototyp

✍️ Erstellen Sie Prototypen für das GUI (Admin-Interface und Quiz-Seite).

# 6 Implementation

✍️ Halten Sie fest, wann Sie welche User Story bearbeitet haben

| User Story | Datum | Beschreibung |
| ---------- | ----- | ------------ |
| ...        |       |              |

# 7 Projektdokumentation

| US-№ | Erledigt? | Entsprechende Code-Dateien oder Erklärung |
| ---- | --------- | ----------------------------------------- |
| 1    | ja / nein |                                           |
| ...  |           |                                           |

# 8 Testprotokoll

✍️ Fügen Sie hier den Link zu dem Video ein, welches den Testdurchlauf dokumentiert.

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

# 9 `README.md`

✍️ Beschreiben Sie ausführlich in einer README.md, wie Ihre Applikation gestartet und ausgeführt wird. Legen Sie eine geeignete Möglichkeit (Skript, Export, …) bei, Ihre Datenbank wiederherzustellen.

# 10 Allgemeines

- [ ] Ich habe die Rechtschreibung überprüft
- [ ] Ich habe überprüft, dass die Nummerierung von Testfällen und User Stories übereinstimmen
- [ ] Ich habe alle mit ✍️ markierten Teile ersetzt
