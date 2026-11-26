# Anforderungskatalog – Mathe-Macher

## Funktionale Anforderungen

| ID | Anforderung | Priorität | Status |
|---|---|---|---|
| F-001 | Das System stellt einen festen Aufgabenpool mit vorgegebenen mathematischen Aufgaben bereit. | Hoch | Offen |
| F-002 | Der Aufgabenpool umfasst die vier Grundrechenarten: Addition, Subtraktion, Multiplikation und Division. | Hoch | Offen |
| F-003 | Aufgaben werden unterschiedlichen Schwierigkeitsgraden und Kompetenzstufen zugeordnet. | Hoch | Offen |
| F-004 | Nutzer können ein persönliches Benutzerkonto mit Benutzername und Passwort erstellen. | Hoch | Offen |
| F-005 | Nutzer können sich mit ihren Zugangsdaten anmelden und abmelden. | Hoch | Offen |
| F-006 | Das System ermöglicht die Bearbeitung mathematischer Aufgaben über eine Eingabemöglichkeit. | Hoch | Offen |
| F-007 | Eingereichte Lösungen werden automatisch auf ihre Richtigkeit überprüft. | Hoch | Offen |
| F-008 | Nutzer erhalten unmittelbar nach der Bearbeitung einer Aufgabe eine Rückmeldung über die Richtigkeit ihrer Lösung. | Hoch | Offen |
| F-009 | Für bearbeitete Aufgaben erhalten Nutzer abhängig von Schwierigkeit und Richtigkeit Erfahrungspunkte (XP). | Hoch | Offen |
| F-010 | Das System berechnet anhand der gesammelten XP das externe Spielerlevel eines Nutzers. | Hoch | Offen |
| F-011 | Das Spielerlevel dient der Darstellung des allgemeinen Fortschritts und ist unabhängig von den freigeschalteten Aufgaben. | Hoch | Offen |
| F-012 | Das System verwaltet für jeden Nutzer individuelle Kompetenzstufen für die vier Grundrechenarten. | Hoch | Offen |
| F-013 | Die individuelle Kompetenzstufe bestimmt, welche Aufgaben ein Nutzer bearbeiten kann. | Hoch | Offen |
| F-014 | Neue Kompetenzstufen werden abhängig von der nachgewiesenen Rechenleistung freigeschaltet. | Hoch | Offen |
| F-015 | Das System speichert die Bearbeitungsversuche eines Nutzers mit Aufgaben-ID, Nutzer-ID, Zeitpunkt und Ergebnis. | Hoch | Offen |
| F-016 | Falsch beantwortete Aufgaben werden für spätere Wiederholungen vorgemerkt. | Hoch | Offen |
| F-017 | Eine falsch beantwortete Aufgabe bleibt so lange im Wiederholungssystem, bis sie dreimal korrekt beantwortet wurde. | Hoch | Offen |
| F-018 | Korrekt beantwortete Aufgabenversuche werden nach einer festgelegten Aufbewahrungsdauer aus der Bearbeitungshistorie gelöscht. | Mittel | Offen |
| F-019 | Das System ermöglicht die Einsicht in den persönlichen Fortschritt und den aktuellen Erfahrungsstand. | Mittel | Offen |
| F-020 | Nutzer können zwischen den verfügbaren Aufgabenbereichen wählen. | Mittel | Offen |

## Nicht-funktionale Anforderungen

| ID | Anforderung | Beschreibung |
|---|---|---|
| NF-001 | Sicherheit | Passwörter müssen sicher gehasht gespeichert werden. Nutzerdaten und Anfragen müssen vor unbefugtem Zugriff geschützt sein. |
| NF-002 | Bedienbarkeit | Die Anwendung muss intuitiv, übersichtlich und ohne längere Einarbeitung nutzbar sein. |
| NF-003 | Erweiterbarkeit | Neue Aufgaben, Schwierigkeitsgrade, Kompetenzstufen und Funktionen müssen ohne grundlegende Überarbeitung der bestehenden Architektur ergänzt werden können. |
| NF-004 | Performance | Aufgaben, Eingaben und Rückmeldungen müssen ohne spürbare Verzögerungen verarbeitet werden. |
| NF-005 | Kompatibilität | Die Anwendung muss auf gängigen modernen Webbrowsern und unterschiedlichen Bildschirmgrößen funktionieren. |
| NF-006 | Zuverlässigkeit | Die Anwendung muss Aufgaben korrekt überprüfen und XP sowie Fortschrittsdaten konsistent speichern. |
| NF-007 | Datenschutz | Personenbezogene Daten dürfen nur im erforderlichen Umfang erhoben und müssen entsprechend den geltenden Datenschutzbestimmungen verarbeitet werden. |
| NF-008 | Verfügbarkeit | Die Anwendung soll zuverlässig erreichbar sein und gespeicherte Nutzerdaten dauerhaft verfügbar halten. |

## Nicht-Ziele

- Kein Ersatz für den regulären Mathematikunterricht.
- Keine ausführlichen mathematischen Erklärungen oder vollständigen Unterrichtseinheiten.
- Keine klassische Nachhilfeplattform.
- Keine soziale Lernplattform mit Chats, Freundeslisten oder Nutzerkommunikation.
- Keine unnötig komplexen Gamification-Systeme.
- Keine KI-generierte Aufgabenerstellung.
- Keine dynamische Generierung mathematischer Aufgaben.
- Keine umfangreiche Lernplattform mit Kursen, Lernvideos oder Unterrichtsmaterialien.
- Keine verpflichtenden Wettbewerbe oder Ranglisten.
