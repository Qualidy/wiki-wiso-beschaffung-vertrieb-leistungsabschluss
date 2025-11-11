# **Wirtschaftlichkeit von IT-Investitionen – TCO & ROI**

---

Eine Anschaffung ist nicht automatisch eine Investition.  
Und nicht jede Investition lohnt sich – zumindest nicht sofort.  
Im IT-Bereich müssen wir Entscheidungen treffen,  
die Jahre später noch Kosten oder Einsparungen verursachen können.

Deshalb betrachtet man Investitionen **nicht nur nach dem Kaufpreis**,  
sondern nach **allen entstehenden und zurückfließenden Werten** –  
mit Hilfe von TCO und ROI.

!!! quote
    „Was heute günstig wirkt, kann morgen teuer werden –  
    weil Kosten selten nur einmal entstehen.“

---

## Total Cost of Ownership (TCO)

Die **Total Cost of Ownership** („Gesamtkosten des Besitzes“)  
umfasst **alle direkten und indirekten Kosten**,  
die während der gesamten Nutzungsdauer einer Investition entstehen.

### Ziel:
Nicht nur den Kaufpreis betrachten,  
sondern auch Folgekosten wie Wartung, Schulung, Energie oder Ausfallzeiten.

### Typische Bestandteile:

| **Kostenart** | **Beispiele** |
|----------------|----------------|
| **Direkte Kosten** | Anschaffungspreis, Installationskosten, Schulung, Wartung, Lizenzen |
| **Indirekte Kosten** | Energie, Ausfallzeiten, Supportaufwand, Ersatzteile, Schulungskosten bei Personalwechsel |
| **Versteckte Kosten** | Organisationsaufwand, Einarbeitung, Systemausfälle, Datenmigration |

### Beispiel:

Ein IT-Systemhaus prüft zwei Optionen für seine Warenwirtschaft:

| Variante | Anschaffungskosten | Direkte Zusatzkosten | Indirekte Kosten | **TCO gesamt** |
|-----------|--------------------|----------------------|------------------|----------------|
| **Update** | 12.000 € | 5.000 € | 4.000 € | **21.000 €** |
| **Neue Software** | 90.000 € | 18.000 € | 32.000 € | **140.000 €** |

→ **TCO-Vergleich:** Update < Neuanschaffung → das Update ist wirtschaftlicher.

!!! note
Der TCO hilft, die **wahre Kostenseite** einer Entscheidung zu erkennen –  
nicht nur, was auf der Rechnung steht, sondern was langfristig gezahlt wird.

---

## Return on Investment (ROI)

Der **Return on Investment (ROI)** zeigt,  
wie schnell sich eine Investition durch Einsparungen oder Gewinne **amortisiert**.

\[
ROI = \frac{\text{Rückflüsse}}{\text{Investitionskosten}}
\quad \text{oder} \quad
ROI = \frac{\text{Ertrag} - \text{Kosten}}{\text{Kosten}}
\]

Wenn der ROI > 1 ist, bringt die Investition mehr Ertrag,  
als sie gekostet hat – sie hat sich also gelohnt.  
Ein ROI von 2 bedeutet: doppelte Rückflüsse gegenüber den Kosten.

---

### Beispielrechnung:

Ein Unternehmen kauft ein neues Archivsystem für 100.000 €.  
Durch geringere Wartung und Arbeitszeitersparnis spart es jährlich 67.000 €.  
Die Nutzungsdauer beträgt 3 Jahre.

\[
ROI = \frac{67.000 € \times 3}{100.000 €} = 2,01
\]

\[
\text{Amortisation} = \frac{36 \text{ Monate}}{2,01} = 17,9 \text{ Monate}
\]

→ Das System hat sich **nach etwa 1,5 Jahren bezahlt gemacht.**

---

## Entscheidung zwischen zwei Alternativen

Bei IT-Investitionen muss man häufig zwischen **Update** und **Neuanschaffung** entscheiden.  
Hier gilt: Je höher die TCO der neuen Lösung und je länger die Amortisationszeit,  
desto sorgfältiger sollte die Entscheidung getroffen werden.

| Kriterium | Update | Neuanschaffung |
|------------|----------|----------------|
| Investitionskosten | gering | hoch |
| Laufende Kosten | moderat | anfangs hoch, später evtl. geringer |
| Zukunftssicherheit | begrenzt | hoch |
| ROI | kurzfristig | langfristig |
| Risiko | gering | höher (Umstellung, Schulung) |

---

## Formel-Überblick

| Kennzahl | Formel | Bedeutung |
|-----------|---------|-----------|
| **TCO** | Anschaffung + alle direkten + indirekten + versteckten Kosten | Gesamtkosten über Nutzungsdauer |
| **ROI** | Rückflüsse ÷ Investitionskosten | Verhältnis von Gewinn zu Kosten |
| **Amortisationszeit** | Nutzungsdauer ÷ ROI | Zeit bis zur Kostendeckung |

---

## Beispielvergleich: Update vs. Neuanschaffung

| Kennzahl | **Update** | **Neuanschaffung** |
|-----------|-------------|---------------------|
| Investitionskosten | 15.000 € | 90.000 € |
| Jährliche Einsparungen | 10.000 € | 40.000 € |
| Laufzeit | 3 Jahre | 3 Jahre |
| **ROI** | (10.000 × 3) ÷ 15.000 = **2,0** | (40.000 × 3) ÷ 90.000 = **1,33** |
| **Amortisationszeit** | 36 ÷ 2,0 = **18 Monate** | 36 ÷ 1,33 = **27 Monate** |

→ Das **Update** amortisiert sich schneller,  
die **Neuanschaffung** ist langfristig zukunftssicherer.

---

## Reflexion

- Welche Risiken übersieht man, wenn man nur den ROI betrachtet?
- Warum kann eine teurere Lösung langfristig wirtschaftlicher sein?
- Welche Rolle spielt die Lebensdauer in der Entscheidung?

---

## Übung

{{ task(file="tasks/tco_roi.yaml") }}
