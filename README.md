# Persönliches Projekt-Portfolio — Tarik T. 

Dieses Repository dokumentiert Projekte, die ich eigeninitiativ in meiner Freizeit umsetze.  
Der Fokus liegt auf der praktischen Anwendung und Vertiefung von Kenntnissen aus den Bereichen **Datenanalyse, Python** — ergänzend zu meiner Ausbildung.

```
Sprachen:      Python · SQL
Bibliotheken:  Pandas · NumPy · Matplotlib · Seaborn
Tools:         Git · GitHub · Power BI · Excel
```

---

## Projekte

### Global Tech Startups 2026 — Analyse

> Mehrstufige Analyse von 25.000 globalen Tech-Startups — von der Datenvorbereitung über Kennzahlenberechnung, Gruppenanalysen und KI-Adoption bis hin zu einem vollständigen Visualisierungs-Dashboard und der Identifikation kritischer Risikogruppen.

**Technologien:** Python · Pandas · Matplotlib

**Dataset:** `global_tech_startups_2026.csv` — 25.000 Zeilen · 21 Spalten  
**Schwierigkeit:** Intermediate+

**Schwerpunkte:**
- Daten laden & erkunden: `.info()`, `.describe()`, `.nunique()`, `.isnull().sum()`
- Neue Kennzahlen berechnen: Layoff-Rate, Valuation-Multiple, Burn-Multiple, Startup-Alter — mit `.apply(lambda ...)`
- Gruppenanalyse nach Branche (Domain): Top-5 nach Ø Valuation — *Generative AI führt mit Ø 885 Mio. USD*
- Layoff-Analyse 2024/2025: 9.710 von 25.000 Startups hatten Entlassungen — Auswertung nach Domain, Funding-Stage und Land
- Startup-Überlebensanalyse: Vergleich Independent / Closed / Acquired / IPO nach Runway, Revenue und Layoff-Rate
- Zeitanalyse: Gründungsjahr-Trends, Generative-AI-Boom ab 2020, Ø Alter bei Series C+ / Pre-IPO
- KI-Adoption & Effizienz: Pivot-Tabelle (`pivot_table()`) — AI-Level × Funding-Stage × Ø Revenue
- Visualisierungs-Dashboard: 4 Subplots (Balken, Linie, Horizontalbalken, Kreisdiagramm), exportiert als `dashboard.png`
- Kritische Startups filtern: Zombie Startups, Top-Performer (Tier-1 + kein Layoff), KI-Boom-Kandidaten — mit `.isin()`

**Neu gelernt in diesem Projekt:**

| Methode | Anwendung |
|---|---|
| `.apply(lambda ...)` | Zeilenweise Berechnung mit Bedingungen |
| `.agg({'col': 'func'})` | Mehrere Aggregationen in einem Schritt |
| `.rename(columns={...})` | Professionelle Spaltenbenennung |
| `.pivot_table()` | Kreuztabellen — Standard-Tool jedes Analysten |
| `plt.subplots(2, 2)` | Dashboard mit 4 Plots |
| `plt.savefig()` | Grafik als Datei exportieren |
| `.isin([...])` | Filter auf mehrere Werte gleichzeitig |

---

### Verkaufsanalyse eines fiktiven Online-Shops

> Vollständige Analyse der Verkaufsdaten eines fiktiven Online-Shops — von der Datenvorbereitung über statistische Auswertung bis hin zur Visualisierung und Zeitreihenanalyse.

**Technologien:** Python · Pandas · Matplotlib

**Schwerpunkte:**
- Daten laden, erkunden und auf fehlende Werte prüfen
- Berechnung neuer Kennzahlen (Umsatz = Menge × Preis)
- Grundlegende Statistiken: Gesamtumsatz, Durchschnitt pro Bestellung, Produktvielfalt
- Gruppenanalysen nach Produkt und Kategorie (Top-Umsatz, meiste Verkäufe)
- Zeitanalyse: Datum-Konvertierung, monatlicher Umsatz, stärkster Verkaufsmonat
- Visualisierungen: Balkendiagramm, Liniendiagramm, Kuchendiagramm
- Filteranalysen: Hochumsatz-Bestellungen, Monatsfilter, Bestellmengen-Analyse


---

### Pharmaceutical Sales Data Analysis

> Analyse eines Pharmadatensatzes zur Identifikation von Verkaufstrends, Top-Produkten und regionalen Leistungsunterschieden.

**Technologien:** Python · Pandas · Matplotlib 

**Schwerpunkte:**
- Datenbereinigung und strukturierte Aufbereitung mit Pandas
- Visualisierung von Verkaufsdaten nach Produkt, Region und Zeitraum
- Analyse saisonaler Muster und Identifikation von Ausreißern

**Links:**
- [Projektbeschreibung auf Roadmap.sh](https://roadmap.sh/projects/pharmaceutical-sales-data)

---

### Clean the Netflix Dataset
> Learn to clean the Netflix dataset using Python and Pandas effectively.

**Technologien:** Python · Pandas 

**Schwerpunkte:**
- Datenbereinigung und strukturierte Aufbereitung mit Pandas

**Links:**
- [Projektbeschreibung auf Roadmap.sh](https://roadmap.sh/projects/cleaning-netflix-dataset )


*Dieses Portfolio wird kontinuierlich mit neuen Projekten erweitert.*
