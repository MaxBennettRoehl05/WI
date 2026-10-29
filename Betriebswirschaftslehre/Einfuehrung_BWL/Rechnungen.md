---
tags: [BWL, EBWL, Rechnungen, Formeln]
---
# Rechnungen & Formeln – Einführung in die BWL

> Alle Formeln mit Rechenweg. Übungsaufgaben dazu stehen am Ende jedes Kapitels, Lösungen in [[Loesungen]].

Verwandt: [[Definitionen]] · [[00_Index]]

## Kapitel 1 Gegenstand der Betriebswirtschaftslehre
*Zum Kapitel: [[01_Gegenstand_der_BWL]]*

### Produktivität, Wirtschaftlichkeit und Rentabilität
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=16|F. 32]] · Kapitel [[01_Gegenstand_der_BWL|1]]*

**Gesamtproduktivität** (mengenmäßig):
$$\text{Produktivität} = \frac{\text{Ausbringungsmenge}}{\text{Faktoreinsatzmengen}} = \frac{\text{mengenmäßiger Output}}{\text{mengenmäßiger Input}}$$

**Teilproduktivität** (z. B. Arbeitsproduktivität):
$$\text{Teilproduktivität} = \frac{\text{Ausbringungsmenge}}{\text{spezifische Faktoreinsatzmenge}}\quad(\text{z. B. } \tfrac{\text{Stück}}{\text{Arbeitsstunde}})$$

**Wirtschaftlichkeit** (wertmäßig):
$$\text{Wirtschaftlichkeit} = \frac{\text{wertmäßiger Output}}{\text{wertmäßiger Input}} = \frac{\text{Leistung}}{\text{Kosten}}$$
> Wirtschaftlichkeit > 1 → Leistung übersteigt Kosten.

**Merke:** Produktivität = *Mengen*, Wirtschaftlichkeit = *Werte* (€).

### Rentabilitätskennzahlen
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=17|F. 33]] · Kapitel [[01_Gegenstand_der_BWL|1]]*

$$\text{Gewinn} = \text{Umsatz} - \text{Kosten}\quad(\text{Betriebsergebnis})$$

| Kennzahl | Formel |
|---|---|
| **Eigenkapitalrentabilität** | $\dfrac{\text{Gewinn}}{\text{Eigenkapital}}\cdot 100\,[\%]$ |
| **Gesamtkapitalrentabilität** (F. 33) | $\dfrac{\text{Gewinn} + \text{Fremdkapitalzinsen}}{\text{Eigenkapital} + \text{Fremdkapital}}\cdot 100\,[\%]$ |
| **Umsatzrentabilität** | $\dfrac{\text{Gewinn}}{\text{Umsatz}}\cdot 100\,[\%]$ |
| **Operative Umsatzrendite** | $\dfrac{\text{EBIT}}{\text{Umsatz}}\cdot 100\,[\%]$ |
| **Kapitalumschlagshäufigkeit** | $KU = \dfrac{U}{GK}$ |
| **ROI** (F. 35, 99) | $ROI = \dfrac{G}{GK} = \dfrac{G}{U}\cdot\dfrac{U}{GK} = UR \cdot KU$ |

- $GK = EK + FK$ (Gesamtkapital)
- **EBIT** = Gewinn vor Steuern und Zinsen – *Zweck:* Gewinn von allen nicht durch die betriebliche Tätigkeit entstandenen Belastungen bereinigen.
- ⚠️ Auf F. 99 wird $R_{GK} = ROI = G/GK$ (ohne Zinsaddition) verwendet, auf F. 33 mit „+ Fremdkapitalzinsen“. In Klausur die Definition der **Vorlesung/Aufgabenstellung** verwenden; bei der Kennzahlenpyramide ($UR \cdot KU$) gilt $G/GK$.
- Beispiel Folie 34: Unternehmen verdienten 2018 im Schnitt 4,2 Cent je Euro Umsatz (= 4,2 % Umsatzrentabilität).

## Kapitel 3 Basiskonzepte der BWL (Wissenschaftsprogramme & Entscheidungstheorie)
*Zum Kapitel: [[03_Basiskonzepte_und_Entscheidungstheorie]]*

### Nutzwertanalyse
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=29|F. 58]] · Kapitel [[03_Basiskonzepte_und_Entscheidungstheorie|3]]*

**Nutzwert der Alternative i:**
$$U_i = P_i = \sum_{k=1}^{p} g_k \cdot p_{ik}\qquad \text{mit}\quad \sum g_k = 1,\; 0 \le P_i \le 10$$
$g_k$ = Gewicht des Ziels $Z_k$, $p_{ik}$ = Punktwert (0 = kein, 10 = maximaler Zielbeitrag). **Wähle** $\max_i U_i$.

**Rechenschema (Tabelle):**

| Kriterium | $g_k$ | $p_{ik}$ | $g_k \cdot p_{ik}$ |
|---|---|---|---|
| … | … | … | … |
| **Summe** | 1,00 | | $U_i$ |

**Schritte:** 1. Gewichte prüfen (Summe = 1) → 2. je Kriterium $g \cdot p$ → 3. je Alternative aufsummieren → 4. Maximum wählen → 5. (optional) **Sensitivitätsanalyse**: Gewichte variieren, schauen ob sich die Rangfolge ändert.

⚠️ *Kompensationseffekt:* ein sehr guter Wert kann einen sehr schlechten Wert ausgleichen.

### Entscheidung bei Risiko (Erwartungswert)
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=31|F. 61]] · Kapitel [[03_Basiskonzepte_und_Entscheidungstheorie|3]]*

Wahrscheinlichkeiten $w_j$ der Situationen $S_j$ bekannt ($\sum w_j = 1$):
$$EW_i(u_i) = \sum_{j=1}^{n} w_j \cdot u_{ij}\quad\Rightarrow\quad \text{wähle } \max_i EW_i$$

**Rechenweg:** Zeile für Zeile Nutzenwert × Wahrscheinlichkeit der jeweiligen Spalte, summieren, Maximum wählen.

### Entscheidung bei Ungewissheit
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=31|F. 62]] · Kapitel [[03_Basiskonzepte_und_Entscheidungstheorie|3]]*

Wahrscheinlichkeiten **unbekannt**; Nutzenwerte $u_{ij}$ (Alternative $i$, Situation $j$):

| Regel | Einstellung | Rechenweg | Wahl |
|---|---|---|---|
| **Laplace** | risikoneutral | Summe (oder Mittelwert) der Zeile = alle Situationen gleich wahrscheinlich | max |
| **Minimax / Maximin** | risikoavers (pessimistisch) | **Zeilenminimum** je Alternative | **Maximum der Minima** |
| **Maximax** | risikofreudig, chancenorientiert | **Zeilenmaximum** je Alternative | **Maximum der Maxima** |
| **Hurwicz** | Mischung | $U_i = \alpha\,u_{i,max} + (1-\alpha)\,u_{i,min}$, $0\le\alpha\le1$ | max |

$\alpha$ = **Optimismusparameter** ($\alpha = 1$ → Maximax, $\alpha = 0$ → Maximin).

**Folienbeispiel (F. 62), Hurwicz α = 0,7:** $A_1$: 0,7·10 + 0,3·1 = **7,3** · $A_2$: 0,7·8 + 0,3·2 = 6,2 · $A_3$: 0,7·7 + 0,3·3 = 5,8 → $A_1$.

## Kapitel 4 Die Subsysteme eines Betriebes
*Zum Kapitel: [[04_Subsysteme_eines_Betriebes]]*

### Homogenitätsgrad und Cobb-Douglas
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=37|F. 73]] · Kapitel [[04_Subsysteme_eines_Betriebes|4]]*

**Definition:** $f(\lambda r_1, \dots, \lambda r_n) = \lambda^{\varepsilon}\, f(r_1,\dots,r_n)$ → homogen vom Grad $\varepsilon$.

**Cobb-Douglas:** $M = c\, r_1^{\alpha} r_2^{1-\alpha}$
$$c\,(\lambda r_1)^{\alpha}(\lambda r_2)^{1-\alpha} = \lambda^{\alpha + 1 - \alpha}\, c\, r_1^{\alpha} r_2^{1-\alpha} = \lambda^{1} M \;\Rightarrow\; \varepsilon = 1\text{ (linear-homogen)}$$

**Verallgemeinerung** 🔸 (nicht auf Folie): für $M = c\, r_1^{\alpha} r_2^{\beta}$ gilt $\varepsilon = \alpha + \beta$.

| $\varepsilon$ | Bezeichnung | Bedeutung |
|---|---|---|
| $> 1$ | progressiv-homogen | Output wächst überproportional (Produktivitätssteigerung) |
| $= 1$ | linear-homogen | Output wächst proportional |
| $< 1$ | degressiv-homogen | Output wächst unterproportional (Sättigung) |

### Kostenfunktion und Minimalkostenkombination
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=40|F. 79]] · Kapitel [[04_Subsysteme_eines_Betriebes|4]]*

**Kostenfunktion (Mengen × Preise):** $K = \sum_{i=1}^{n} r_i \cdot q_i$

**Fix + variabel:** $K(M) = K_f + K_v(M)$; bei proportionalem Verlauf $K(M) = k_v \cdot M + K_f$

| Größe | Formel |
|---|---|
| Stück-/Selbstkosten | $k(M) = \dfrac{K(M)}{M} = k_v + \dfrac{K_f}{M}$ (→ **Fixkostendegression**) |
| variable Stückkosten | $k_v = \dfrac{K_v(M)}{M}$ |
| Grenzkosten | $K'(M) = \dfrac{dK(M)}{dM}$ (bei linearem Verlauf $= k_v$) |
| Beschäftigungsgrad | $B = \dfrac{M}{M_{max}}\cdot 100\,[\%]$ |

**Minimalkostenkombination (zwei Faktoren):**
- Isokostengerade: $K = r_1 q_1 + r_2 q_2 \;\Leftrightarrow\; r_1 = \dfrac{K}{q_1} - \dfrac{q_2}{q_1}\, r_2$ (Steigung $-q_2/q_1$)
- **Praktischer Rechenweg bei diskreten Kombinationen:** für jede Kombination $(r_1, r_2)$ auf der *selben Isoquante* $K = r_1 q_1 + r_2 q_2$ ausrechnen → **kleinste Kosten = Minimalkostenkombination**.
- Grafisch: Isokostengerade, die die Isoquante **gerade berührt** (Tangentialpunkt).

## Kapitel 7 Konstitutive Entscheidungsfelder
*Zum Kapitel: [[07_Konstitutive_Entscheidungsfelder]]*

### Arbeitskosten je Stück
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=60|F. 120]] · Kapitel [[07_Konstitutive_Entscheidungsfelder|7]]*

$$\text{Arbeitskosten je Stück} = \frac{\text{Arbeitskosten je Stunde}}{\text{Produktivität (Stück je Stunde)}}$$

**Folienbeispiel:** 10 €/h bei 1 Stück/h → **10 €/Stück**; 45 €/h bei 3 Stück/h → **15 €/Stück**. Der Standort mit dem *höheren* Stundensatz kann *billiger* sein, wenn die Produktivität höher ist – **nicht** nur auf €/h schauen!

## Kapitel 8 Teilgebiete der Betriebswirtschaftslehre
*Zum Kapitel: [[08_Teilgebiete_der_BWL]]*

### ABC-Analyse
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=91|F. 181]] · Kapitel [[08_Teilgebiete_der_BWL|8]]*

**Ziel:** Materialarten nach Anteil am Gesamtverbrauchswert klassifizieren.

1. **Verbrauchswert** je Materialart bestimmen (Menge × Preis) und **Gesamtverbrauchswert** summieren.
2. **Prozentanteil** je Art: $\dfrac{\text{Verbrauchswert}_i}{\text{Gesamtwert}}\cdot 100$.
3. **Sortieren** absteigend nach Anteil (Rang 1 = größter Wert).
4. **Kumulieren** der Wertanteile *und* der Anteile an der Artenzahl (jede Art = 100 % / Anzahl Arten).
5. **Einteilen** (Faustregel der Folie 182): **A** ≈ erste 20 % der Arten (≈ 80 % des Wertes) · **B** ≈ nächste 30 % der Arten · **C** ≈ restliche 50 % der Arten (geringer Wert).

*Konsequenz:* A-Güter intensiv bewirtschaften (genaue Bedarfsplanung, mehrere Lieferanten), C-Güter pauschal/einfach beschaffen.

### Optimale Bestellmenge (Andler)
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=92|F. 184]] · Kapitel [[08_Teilgebiete_der_BWL|8]]*

**Variablen:** $M$ Jahresbedarf · $x$ Bestellmenge · $n = M/x$ Anzahl Bestellungen · $p$ Einstandspreis · $k_{bf}$ fixe Kosten je Bestellung · $q$ Zins-/Lagerkostensatz in %

| Kosten | Formel |
|---|---|
| Lagerkosten | $K_L = \dfrac{1}{2}\, x\, p\,\dfrac{q}{100}$ (durchschnittlicher Lagerbestand $\tfrac12 x$) |
| Bestellkosten | $K_B = k_{bf}\cdot \dfrac{M}{x}$ |
| Gesamtkosten | $K(x) = \dfrac{1}{2}\,x\,p\,\dfrac{q}{100} + k_{bf}\dfrac{M}{x} \;\to\; \min$ |

**Herleitung:** 1. Ableitung nach $x$ gleich Null setzen:
$$\frac{dK}{dx} = \frac{p\,q}{200} - \frac{k_{bf}\,M}{x^2} = 0 \;\Rightarrow\; x_{opt} = \sqrt{\frac{200\cdot M\cdot k_{bf}}{p\cdot q}}$$

(Ohne Restriktion, daher $n \in \mathbb{R}$; in der Praxis auf ganze Bestellzahl runden.)

**Probe:** Im Optimum gilt $K_L = K_B$ (Schnittpunkt der Kurven, Minimum der Gesamtkosten).

### Lineare Abschreibung
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=98|F. 196]] · Kapitel [[08_Teilgebiete_der_BWL|8]]*

$$A_t = \frac{AK}{n}\qquad(AK = \text{Anschaffungskosten},\; n = \text{Nutzungsjahre})$$
**Folienbeispiel:** $A_t = \dfrac{12.000\,€}{6} = 2.000\,€$ pro Jahr.

**Restbuchwert nach $t$ Jahren:** $RBW_t = AK - t \cdot A_t$.

### EBIT und EBITDA
*[[20261013_BWL_Einfuehrung_BWL_Einfuehrung.pdf#page=102|F. 204]] · Kapitel [[08_Teilgebiete_der_BWL|8]]*

Rückwärts vom Jahresüberschuss (JÜ) zum operativen Gewinn:

| Schritt | |
|---|---|
| Jahresüberschuss | JÜ |
| **+** Ertragsteuern | |
| **+** Zinsaufwand | |
| **= EBIT** | |
| **+** Abschreibungen | |
| **= EBITDA** | |

⚠️ Auf Folie 204 stehen die Zeilen mit „./.“ (Minus). Da man vom Überschuss zum EBIT **zurückrechnet**, müssen Steuern und Zinsen **addiert** werden: $EBIT = JÜ + \text{Steuern} + \text{Zinsen}$; $EBITDA = EBIT + \text{Abschreibungen}$. Die Folie zeigt vermutlich die Richtung „von EBIT zum JÜ“ bzw. ein Vorzeichen-Problem → bitte in der Vorlesung/Übung bestätigen.
