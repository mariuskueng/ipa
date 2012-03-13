Analyse yatplaner
=================

Bestehende Features
-------------------

- Ansichten
    - Wochenansicht (wie bisher)
    - Personenübersicht
    - Monatsübersicht pro Person
    - Übersicht von allen Tasks

- Bedienung
    - Doppelklick auf Personentag öffnet Add Task Dialog
        - abschicken des Forms speichert die Task
    - Doppelklick auf Task öffnet Task Detailansicht
    - Verschiebung einer Task per Drag & Drop
        - Task in einen anderen Tag verschieben
        - Tasks innerhalb eines Tages sortieren
    - Wechsel zwischen Wochen per link (vor und zurück)
    - zusätzlich die nächsten 7 Tage anzeigen

Muss-Kriterien
--------------

- Ansichten
    - Ansicht der aktuellen Woche (Startseite)
    - Alle anderen Übersichten können in den Django-admin ausgelagert werden


- Bedienung
    - Doppelklick auf Personentag öffnet Add Task Dialog
        - abschicken des Forms speichert die Task
    - Doppelklick auf Task öffnet Task Detailansicht
    - Verschiebung einer Task per Drag & Drop
        - Task in einen anderen Tag verschieben
        - Tasks innerhalb eines Tages sortieren

Kann-Kriterien
--------------

- Doppelklick auf Task öffnet Dialog & Task kann direkt bearbeitet und abgespeichert werden
- Per Tastenkombination kann eine Task kopiert werden und neu eingefügt werden
- Löschen per delete taste