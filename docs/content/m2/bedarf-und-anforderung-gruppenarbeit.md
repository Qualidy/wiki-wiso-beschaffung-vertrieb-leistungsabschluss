# JIKU – Neuer Arbeitsplatz für Kunde X
## Bedarfs- und Anforderungsanalyse in der Praxis

---

Bevor ein IT-Projekt umgesetzt werden kann, muss klar sein, **was der Kunde wirklich braucht**, **welche Rahmenbedingungen bestehen** und **welche Anforderungen daraus abgeleitet werden**.  
In dieser Gruppenarbeit wenden Sie Ihr Wissen aus der Theorie an und führen eine vollständige Bedarfs- und Anforderungsanalyse für ein realistisches Szenario durch.

---

## Szenario: Der Auftrag

Das **Systemhaus JIKU IT-Solutions** betreut mehrere mittelständische Kunden.  
Einer davon – die **Kanzlei Dr. Bergmann & Partner** – wächst und möchte für eine neue Mitarbeiterin einen vollständigen Arbeitsplatz einrichten.  
Die Anfrage kommt per E-Mail:

>Guten Tag,

>wir bekommen zum 1. des nächsten Monats eine neue Kollegin im Bereich Mandantenverwaltung.
Sie soll direkt mitarbeiten können – also bitte einen kompletten Arbeitsplatz vorbereiten.

>Da sie teilweise im Homeoffice arbeiten wird, muss der Zugriff auf unsere Systeme auch von außen möglich sein.
Bisher nutzen wir dafür ein VPN, aber das läuft nicht immer stabil.

>Außerdem hatten wir vor einigen Wochen einen Serverausfall, bei dem Daten verloren gingen – eventuell sollte die Sicherungslösung überarbeitet werden.

>Die Kollegin wird mit sensiblen Mandantendaten arbeiten (Steuerunterlagen, Rechnungen, Verträge), daher muss alles datenschutzkonform und sicher sein.

>Ansonsten bitte so einrichten wie bei den anderen Arbeitsplätzen – wobei ich mir nicht sicher bin, was wir da zuletzt geändert hatten.

>Wegen des Umzugs in den neuen Gebäudeteil ist noch nicht ganz klar, wo der Arbeitsplatz genau stehen wird, aber vermutlich im 2. OG, Raum 214.

>Die neue Kollegin fängt am ersten Montag des Monats an, also bitte bis spätestens Ende nächster Woche alles fertigstellen, damit wir vorab testen können.

>Wenn Sie Rückfragen haben, erreichen Sie mich vormittags telefonisch oder per E-Mail – am besten mit konkreten Punkten, damit ich sie intern abstimmen kann.

>Vielen Dank und viele Grüße
>Claudia Bergmann
>Kanzlei Dr. Bergmann & Partner
>Abteilung Mandantenverwaltung

Das klingt einfach.  
Doch der Fachinformatiker weiß: Hinter dieser Nachricht stecken viele **offene Fragen**.  
Was genau heißt „komplett“?  
Welche Software wird benötigt?  
Gibt es Sicherheitsrichtlinien?  
Soll vorhandene Hardware ersetzt oder erweitert werden?

Ihre Aufgabe ist es, genau das herauszufinden.

---

## Ziel der Gruppenarbeit

Nach Abschluss dieser Einheit können Sie:

- aus einer Anfrage systematisch den **Bedarf** erkennen,
- daraus **technische Anforderungen** ableiten,
- die Anforderungen nach **MUSS / SOLL / KANN** priorisieren,
- und Ihre Ergebnisse **verständlich dokumentieren und präsentieren**.

!!! info
    Sie arbeiten im Team (3–4 Personen, Breakout Room).  
    Ihre Rolle: internes Projektteam bei JIKU IT-Solutions.  
    Ziel: ein **Anforderungskatalog**, der an den Vertrieb übergeben werden kann.

---

## Arbeitsauftrag

### **Phase 1 – Bedarfsermittlung (ca. 20 Minuten)**

Lesen Sie die Kundenanfrage und erarbeiten Sie gemeinsam:

- Welche Informationen fehlen?
- Welche Rückfragen müssten Sie stellen?
- Welche Nutzerziele oder Probleme erkennen Sie?

**Ergebnis:** Liste offener Fragen zur Bedarfsklärung.  
Notieren Sie diese im OneNote- oder Word-Dokument Ihres Teams.

{{ task(file="tasks/jiku_bedarfsermittlung.yaml") }}

---

### **Phase 2 – Anforderungen formulieren (ca. 25 Minuten)**

Übertragen Sie die ermittelten Informationen in konkrete Anforderungen.  
Achten Sie auf messbare Formulierungen:

| Unklar | Besser formuliert |
|--------|------------------|
| „Schneller PC“ | „Rechner mit mindestens 16 GB RAM und SSD 1 TB“ |
| „Datensicherung“ | „Tägliche Sicherung auf zentralem NAS mit 30 Tage Retention“ |

**Ergebnis:** vollständige Anforderungsliste (technisch + organisatorisch).

{{ task(file="tasks/jiku_anforderungen.yaml") }}

---

### **Phase 3 – Priorisierung (ca. 15 Minuten)**

Ordnen Sie Ihre Anforderungen nach Wichtigkeit:

| Kategorie | Bedeutung | Beispiel |
|------------|------------|----------|
| **MUSS** | unbedingt erforderlich | PC, Monitor, Benutzerkonto |
| **SOLL** | sinnvoll, aber notfalls aufschiebbar | Headset, Dockingstation |
| **KANN** | Komfort / Option | höhenverstellbarer Tisch |

**Ergebnis:** priorisierte Liste für Angebot / Pflichtenheft.

{{ task(file="tasks/muss_soll_kann.yaml") }}

---

### **Phase 4 – Dokumentation (ca. 15 Minuten)**

Erstellen Sie eine kurze **Kundenakte** oder **Anforderungstabelle**.  
Sie soll folgende Punkte enthalten:

1. Kundendaten (Name, Branche, Ansprechpartner)
2. Anlass des Projekts
3. Bedarf (Ziel, Nutzen, Problem)
4. Anforderungen (technisch, organisatorisch, rechtlich)
5. Priorisierung (MUSS/SOLL/KANN)
6. Offene Punkte / Risikohinweise

Diese Akte wird am Nachmittag vorgestellt.

{{ task(file="tasks/jiku_anforderungskatalog.yaml") }}

---

## Hilfestellung und Leitfragen

!!! question
    - Wer ist die eigentliche Nutzerin der neuen IT-Arbeitsumgebung?  
    - Welche bestehenden Systeme müssen integriert werden?  
    - Welche Sicherheits- und Datenschutzanforderungen gelten in einer Kanzlei?  
    - Wer nimmt den Arbeitsplatz später ab?  
    - Was könnte schiefgehen, wenn Informationen fehlen?

!!! tip 
    Arbeiten Sie **nicht zu schnell in Lösungen hinein** – erst verstehen, dann entscheiden.  
    Gute Analysen entstehen durch Fragen, nicht durch Annahmen.

---

## Bewertung & Feedback (für Präsentationsphase)

Nach der Gruppenarbeit stellt jedes Team seine Ergebnisse vor (max. 5 Minuten).  
Beachten Sie dabei folgende Kriterien:

| Kriterium | Beschreibung |
|------------|--------------|
| **Vollständigkeit** | Sind alle relevanten Aspekte abgedeckt? |
| **Nachvollziehbarkeit** | Sind Anforderungen klar und messbar formuliert? |
| **Struktur** | Ist der Aufbau logisch und priorisiert? |
| **Bezug zum Bedarf** | Wird deutlich, welches Problem gelöst wird? |
| **Kommunikation** | Verständliche Darstellung, angemessene Fachsprache |

Jede Gruppe gibt anschließend **Peer-Feedback** an eine andere Gruppe.

{{ task(file="tasks/jiku_feedbackbogen.yaml") }}

---

## Reflexion

„_Wer den Bedarf nicht versteht, wird vom Ergebnis überrascht._“

Diskutieren Sie im Plenum:

- Welche Informationen waren besonders schwer zu ermitteln?
- Wo haben sich Meinungen im Team unterschieden?
- Wie hätten Sie mit dem echten Kunden kommuniziert, um Klarheit zu schaffen?
- Was haben Sie über Ihre eigene Fragetechnik gelernt?

---

## Transfer zum weiteren Verlauf der Woche

Diese Gruppenarbeit bildet das **praktische Fundament** für:

- **Mittwoch:** Kalkulation (Kosten & Stundensätze)
- **Donnerstag:** Angebotsvergleich & Beschaffung
- **Freitag:** Lieferung & Abnahme

Alle folgenden Schritte bauen auf Ihrer heutigen Analyse auf.  
Je genauer Sie heute sind, desto realistischer werden Ihre Berechnungen und Entscheidungen später.

---

!!! success "Ergebnisziel"
    Jedes Team hat am Ende ein strukturiertes Dokument, das als  
    *Mini-Pflichtenheft* für den Arbeitsplatz „Kunde X“ verwendet werden kann.
