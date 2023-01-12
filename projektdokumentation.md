# Projekt-Dokumentation

✍️ Keller

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   09.01.2023   | 0.0.1   | Punkt 4.1 gemacht |
|   10.01.2023    | 0.0.2   | Punkt 1,2,3,4.2,5 gemacht                                                             |
|       | 0.0.3   |                                                              |
|       | 0.0.4   |                                                              |
|       | 0.0.5   |                                                              |
|       | 0.0.6   |                                                              |
|       | 1.0.0   |                                                              |

# 0 Ihr Projekt

✍️ In diesem Projekt geht es darum, die ehemalige Fernsehsendung "Glücksrad" zu implementieren. Das Spiel ist änlich wie ein Kreuzworträtsel, es geht darum, Wörter oder Redewendungen in einem Gitter zu erraten und dabei so viel Geld wie möglich zu ergattern.

# 1 Analyse

✍️ Beschreiben Sie, auf welchem Tier Sie die dynamischen Elemente der Anwendung unterbringen möchten:

* Tier 1 (Presentation): Website/Interface zur anzeige der Loginseite/Highscore/Rätselwand.
* Tier 2 (Webserver): Entgegenname von Daten, überprüfen der Daten.
* Tier 3 (Application Server): 
* Tier 4 (Dataserver): Speichern der Einträge des Kandidaten in einer Datenbank von Firebase.

# 2 Technologie

✍️ REACT

# 3 Datenbank

✍️ Firebase

# 4.1 User Stories

✍️ Formulieren Sie klare Anforderungen in der Form von User Stories (*„als … möchte ich … damit …“*) und zu jeder Anforderung mindestens einen dazugehörigen Testfall (in Kapitel 4.2). 

✍️ Formulieren Sie weitere, eigene Anforderungen und Testfälle, wie Sie Ihre Applikation erweitern möchten. Geben Sie diesen statt einer Nummer einen Buchstaben (`A`, `B`, etc.)

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 0    |                 |      | Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️ |
| 1    |        Muss         |   Funktional   | Als Administrator möchte ich mich durch Benutzername und Passwort authentifizieren, damit ich auf Administrationsrechte zugreiffen kann.|
| 2    |        Muss         |   Funktional   | Als Administrator möchte ich Phrasen und Rätselwörter anlegen, ändern und löschen können, damit ich die Inhalte der App verwalten kann.|
| 3    |        Muss         |   Funktional   | Als Administrator möchte ich Kategorien anlegen und jedes Wort bzw. jede Frage einer Kategorie zuordnen können, damit ich die Inhalte der App strukturieren und organisieren kann.|
| 4    |        Muss         |   Funktional   | Als Administrator möchte ich einzelne Einträge der Highscore-Liste löschen können, damit ich die Integrität der Highscore-Liste gewährleisten kann.|
| 5    |        Muss         |   Funktional   | Als Kandidat möchte ich meinen Namen eingeben können, damit ich mich mit anderen Kandidaten vergleichen kann.|
| 6    |        Muss         |   Qualität   | Als kandidat möchte ich zu jederzeit meinen Kontostand sehen, damit ich weiss, wie viel Geld noch zur Verfügung steht und wie viel ich noch ausgeben kann.|
| 7    |        Muss         |   Qualität   | Als Kandidat möchte ich zu jederzeit meine noch vorhandenen Lebenspunkte sehen, damit ich weiss, wie viele Vokale ich noch kaufen kann.|
| 8    |        Muss         |   Funktional   | Als kandidat möchte ich informiert werden, ob die gegebene Antwort richtig oder falsch ist, damit ich weiss, ob ich ein Wort herausgefunden habe oder nicht.|
| 9    |        Muss         |   Funktional   | Als Kandidat möchte ich den Rang, der Name des Spielers, den Zeitpunkt des Spiels, den Geldbetrag und die Anzhal Spielrunden in der Highscore-Liste sehen, damit ich mich mit anderen Kandidaten vergleichen kann.|
| 10    |        Muss         |   Funktional   | Als Kandidat möchte ich, dass die Highscore-Liste nach Rang aufsteigend sortiert ist, damit ich weiss, wer der momentane Leader des Spiels ist.|
| 11    |        Muss         |   Funktional   | Als Entwickler möchte ich, dass keinem Kandidaten, die selbe Phrase mehr als einaml gestellt wird, damit das Spiel nicht an Schwierigkeitsgrad verliert.|
| 12    |        Muss         |   Funktional   | Als kandidat möchte ich jederzeit spielen, aufhören oder meinen Gewinn in die Highscore-Liste übernehmen können, damit gewisse Freiheiten bei der Bedienung der App habe.|
| 13    |        Muss         |   Funktional   | Als Entwickler möchte ich, dass das Spiel mit einer spielbaren Anzahl Wörtern und Fragen gefüllt wird, damit es gespielt werden kann.|
| 14    |        Muss         |   Funktional   | Als Kandidat möchte ich, dass die Anzahl Spielrundenen gezählt werden, damit ich weiss, wie oft schon gespielt wurde.|
| 15    |        Muss         |   Rand   | Als Administator möchte ich, dass einfache Formulareingaben, wie leere Textfelder client- und serverseitig geprüft werden, damit...|
| 16    |        Muss         |   Rand   | Als Entwickler möchte ich, dass eine Datenbankanbindung verwendet wird, die möglichst unabhängig vom tatsächlich eingesetzten Produkt ist, damit...|
| 17    |        Muss         |   Rand   | Als Entwickler möchte ich das Transaktionsmanagement einsetzten, damit Fehler rückgangig gemacht werden können.|
| 18    |        Muss         |   Rand   | Als Entwickler möchte ich, dass alle Sicherheitspuntke umgesetzt werden, damit...|



✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc. oder Zahl), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). 

# 4.2 Testfälle

| TC-№ | Vorbereitung | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |      App gestartet und Loginseite ist erfolgreich geöffnet        |    Benutzername und Passwort eingeben     |         Der Benutzer ist erfolgreich als Administrator eingeloggt.          |
| 2.1  |      App erfolgreich gestartet und als Administrator eingeloggt      |    Rätselwort oder Phrase eingeben und auf den Knopf "anlegen" drücken     |          Das Rätselwort oder die Phrase wird erstellt.         |
| 2.2  |      App erfolgreich gestartet und als Administrator eingeloggt      |    Rätselwort oder Phrase auswählen und auf den Knopf "ändern" drücken     |          Es wird das Interface geöffnet, um das Rätselwort oder die Phrase zu ändern.        |
| 2.3  |      App erfolgreich gestartet und als Administrator eingeloggt      |    Rätselwort oder Phrase auswählen und auf den Knopf "löschen" drücken     |         Das Rätselwort oder die Phrase wird gelöscht.          |
| 3.1  |       App erfolgreich gestartet und als Administrator eingeloggt       |    Eine kategorie anlegen + eine Frage/ein Wort dieser Kategorie zuordnen     |       Die Kategorie wird erfolgreich erstellt und die richtige Frage/das richtige Wort wird richtig zugeteilt            |
| 4.1  |      App erfolgreich gestartet und als Administrator eingeloggt + jemand muss bereits schon in der Highscore-Liste vorhanden sein       |    Einen Eintrag aus der Highscore-Liste auswählen und auf den Knopf "löschen" drücken.     |         Der Eintrag wird aus der Highscore-Liste gelöscht.          |
| 5.1  |       App erfolgreich gestartet und als Kandidat eingeloggt       |    Namen eingeben     |         Name wird auf der Highscore-Liste angezeigt.          |
| 6.1  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    keine     |         Kontostand wird auf der Seite angezeigt          |
| 7.1  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    keine     |         Lebenspunkte werden auf der Seite angezeigt          |
| 8.1  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    Eingeben einer Antwort     |         Es wird angezeigt, ob die Antwort richtig oder falsch gewesen ist          |
| 9.1  |      App erfolgreich gestartet und als Kandidat eingeloggt + Highscore-Liste offen        |    keine     |         Rang wird angezeigt          |
| 9.2  |      App erfolgreich gestartet und als Kandidat eingeloggt + Highscore-Liste offen        |    keine     |         Name wird angezeigt          |
| 9.3  |      App erfolgreich gestartet und als Kandidat eingeloggt + Highscore-Liste offen        |    keine     |         Zeitpunkt des Spiels wird angezeigt          |
| 9.4  |      App erfolgreich gestartet und als Kandidat eingeloggt + Highscore-Liste offen        |    keine     |         Geldbetrag wird angezeigt          |
| 9.5  |      App erfolgreich gestartet und als Kandidat eingeloggt + Highscore-Liste offen        |    keine     |         Anzahl Spielrunden wird angezeigt          |
| 10.1  |      App erfolgreich gestartet und als Kandidat oder Administrator eingeloggt + Highscore-Liste offen        |    keine     |         Highscore-Liste ist nach Rang aufsteigend sortiert          |
| 12.1  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    Auf den Knopf "spielen" drücken     |         Das Spiel wird gestartet          |
| 12.2  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    Auf den Knopf "beenden" drücken     |         Das Spiel wird beendet         |
| 12.3  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    Auf den Knopf "Gewinn übernehmen" drücken     |         Der gewonnene Betrag wird in die Highscore-Liste übernommen          |
| 14.1  |      App erfolgreich gestartet und als Kandidat eingeloggt        |    3-Mal spielen     |         Die Anzahl an Spielrunden werden gezählt und auf dem Bildschirm angezeigt          |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

# 5 Prototyp

✍️ Erstellen Sie Prototypen für das GUI (Admin-Interface und Quiz-Seite).
![grafik](https://user-images.githubusercontent.com/74292626/211563711-a1383ac8-8f9d-45ca-818f-0ea3987f9616.png)


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
