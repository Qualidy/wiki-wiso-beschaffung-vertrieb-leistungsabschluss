# Quantitativer Angebotsvergleich - Bezugspreisrechnungen durchführen

---

Wenn ein Unternehmen Angebote erhält, reicht der reine Preis oft nicht aus,  
um zu entscheiden, **welches Angebot wirklich günstiger ist**.  
Neben dem Listenpreis müssen auch Rabatte, Skonto und Bezugskosten berücksichtigt werden.

Ziel ist es, den **Bezugspreis (Einstandspreis)** zu ermitteln – also den tatsächlichen Preis,  
den das Unternehmen am Ende **wirklich zahlen muss**, um die Ware in den Händen zu halten.

---

## Grundlagen

### Definition Bezugspreis

Der **Bezugspreis (Einstandspreis)** ist der endgültige Preis,  
den das Unternehmen nach Abzug aller Preisnachlässe und **zuzüglich der Bezugskosten** bezahlt.

\[
\text{Bezugspreis} = \text{Listeneinkaufspreis} - \text{Rabatt} - \text{Skonto} + \text{Bezugskosten}
\]

- **Listeneinkaufspreis:** Preis laut Angebot des Lieferanten (Katalogpreis)
- **Rabatt:** Preisnachlass, z. B. Mengen- oder Treuerabatt
- **Skonto:** Nachlass bei schneller Zahlung (z. B. innerhalb 7 oder 14 Tagen)
- **Bezugskosten:** Nebenkosten wie Transport, Verpackung, Versicherung

Umsatzsteuer wird **nicht** berücksichtigt,  
weil sie kein Kostenfaktor ist (Vorsteuer wird vom Finanzamt zurückerstattet).

---

## Beispiel – IT-Beschaffung

Ein IT-Unternehmen möchte 20 neue Notebooks kaufen.  
Zwei Anbieter machen ein Angebot:

| Anbieter | Listenpreis | Rabatt | Skonto | Bezugskosten |
|-----------|--------------|---------|---------|---------------|
| **PC Sander GmbH** | 350,00 € | 5 % | 3 % | 20,00 € |
| **PC-Markt AG** | 400,00 € | 20 % | 2 % | 50,00 € |

---

## Schritt-für-Schritt-Berechnung

### 1Rabatt abziehen
Der Rabatt wird **vom Listenpreis** abgezogen.

**Beispiel PC Sander:**
\[
350,00 € - 5 % = 350 € × 0,95 = 332,50 €
\]

### 2Skonto abziehen
Das Skonto wird **vom bereits rabattierten Preis** abgezogen.

\[
332,50 € - 3 % = 332,50 € × 0,97 = 322,52 €
\]

### Bezugskosten hinzufügen
\[
322,52 € + 20 € = 342,52 €
\]

**Bezugspreis PC Sander: 342,52 €**

---

### Vergleich mit PC-Markt AG:

1. Rabatt: 400 € × 0,80 = 320,00 €
2. Skonto: 320 € × 0,98 = 313,60 €
3. Bezugskosten: 313,60 € + 50 € = **363,60 €**

**Bezugspreis PC-Markt: 363,60 €**

---

## Vergleichstabelle

| Anbieter | Listenpreis | Rabatt | Skonto | Bezugskosten | Bezugspreis | Ergebnis |
|-----------|--------------|---------|---------|---------------|--------------|-----------|
| PC Sander GmbH | 350 € | 5 % | 3 % | 20 € | **342,52 €** | ✅ günstiger |
| PC-Markt AG | 400 € | 20 % | 2 % | 50 € | 363,60 € | ❌ teurer |

**Ersparnis pro Gerät:** 21,08 €  
**Gesamtersparnis bei 20 Geräten:** 421,60 €

---

## Warum ist das wichtig?

In IT-Unternehmen werden oft **mehrere Lieferanten** gleichzeitig angefragt.  
Wer nur den Listenpreis betrachtet, entscheidet möglicherweise **gegen das wirtschaftlichere Angebot**.

Der Bezugspreis zeigt den **realen finanziellen Aufwand** und ist Grundlage jeder professionellen Beschaffungsentscheidung.

---

## Praxisbeispiel (ERP & Excel)

In modernen Betrieben läuft der Angebotsvergleich über ERP- oder Kalkulationssysteme:

- ERP-Systeme wie **SAP**, **Lexware**, **Odoo** oder **Microsoft Dynamics**  
  berechnen Rabatte und Skonti automatisch.
- In der Ausbildung ist die Berechnung jedoch **per Hand oder Excel** Pflicht,
  um das Prinzip vollständig zu verstehen.

!!! example "Excel-Formelbeispiel"
    ```excel
    =B2*(1-C2)*(1-D2)+E2
    ```
    (B2 = Listenpreis, C2 = Rabatt, D2 = Skonto, E2 = Bezugskosten)
    → Diese Formel liefert den Bezugspreis direkt.

---

## Kontrollfragen zur Vertiefung

1. Warum darf man Skonto nicht vom Listenpreis berechnen?
2. Welche Kosten zählen **nicht** zu den Bezugskosten?
3. Wie wirkt sich ein höheres Skonto auf den Bezugspreis aus?
4. Warum ist der Bezugspreis eine sichere Grundlage für Investitionsentscheidungen?

---

!!! note "Merkmale eines guten Bezugspreises"
    **Der günstigste Bezugspreis ergibt sich erst,  
    wenn alle Preisnachlässe abgezogen und alle Nebenkosten addiert wurden.**

---

## Übung

### Aufgabe 1 – Bezugspreis berechnen
{{ task(file="tasks/angebotsvergleich_3.yaml") }}

### Zusatzübung – Bezugspreis mit Excel
Berechne mit einer Tabellenkalkulation den Bezugspreis für 3 Anbieter  
und stelle die Ergebnisse in einer **sortierten Tabelle** dar (günstigster Anbieter oben).

→ Verwende dazu die Formel aus dem Beispiel.

---

## Reflexion

- Warum kann ein höherer Listenpreis trotzdem das bessere Angebot sein?
- Wie verändert sich deine Entscheidung, wenn ein Anbieter schnellere Lieferzeiten oder besseren Support bietet?
- In welchen Situationen lohnt es sich, **nicht nur auf den Bezugspreis**, sondern auch auf qualitative Kriterien zu achten?
