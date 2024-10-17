
# Autoscout24 Data Analytics and Machine Learning Models

## Projektübersicht

In diesem Projekt werden Verkaufsdaten von Autos aus AutoScout24 analysiert und visualisiert. Ziel ist es, interessante Erkenntnisse über die Verkaufszahlen, Preisentwicklung und mögliche Korrelationen zwischen verschiedenen Eigenschaften der Fahrzeuge zu gewinnen. Zudem werden Machine Learning-Modelle entwickelt, um den Verkaufspreis von Autos basierend auf ihren Merkmalen vorherzusagen.

## Business Intelligence

In Tableau werden Visualisierungen von Daten und Verteilungen präsentiert. 

**Tableau-Profil:** [Philips Tableau-Profil](https://public.tableau.com/app/profile/philip.hackl/vizzes)

**Projekt:** Autoscout24


## Inhaltsverzeichnis

- [Projektübersicht](#projektübersicht)
- [Business Intelligence](#business-intelligence)
- [Projektziele](#projektziele)
- [Projektinhalt](#projektinhalt)
- [Datenbeschreibung](#datenbeschreibung)
- [Maschinelles Lernen](#maschinelles-lernen)
- [Ergebnisse](#ergebnisse)
- [Technologien](#technologien)
- [Installation](#installation)
- [Benutzung](#benutzung)
- [Fazit](#fazit)

### Projektziele

Die Hauptziele dieses Projekts sind:

1. **Datenanalyse und Visualisierung**: 
   - Ermittlung der Anzahl verkaufter Autos und des Zeitraums der Verkäufe.
   - Analyse der erfassten Automarken.
   - Untersuchung von Korrelationen zwischen numerischen Merkmalen.
   - Identifikation von Trends über die Jahre.
   - Entwicklung weiterer relevanter Fragestellungen basierend auf den Daten.

2. **Machine Learning**:
   - Bestimmung der fünf meistverkauften Automarken und Durchführung einer detaillierten Analyse dieser Hersteller.
   - Entwicklung und Training eines Modells zur Vorhersage des Verkaufspreises von Autos unter Verwendung geeigneter Features.
   - Evaluierung der Modellgüte mithilfe geeigneter Metriken wie Mean Absolute Error (MAE) und R²-Score.

3. **Dashboard-Erstellung**:
   - Erstellung eines interaktiven Dashboards (z.B. mit Streamlit oder Tableau), um die gewonnenen Erkenntnisse visuell ansprechend und intuitiv darzustellen.

### Projektinhalt

- **Datenvorbereitung**: 
  - Bereinigung der Daten von Nullwerten und Export der bereinigten Datensätze.
  
- **Explorative Datenanalyse**:
  - Erstellung von Histogrammen, Scatterplots und Boxplots zur Veranschaulichung der Datenverteilung und möglicher Zusammenhänge.

- **Modellentwicklung**:
  - Implementierung und Evaluierung verschiedener Machine Learning-Modelle, einschließlich Linear Regression und Decision Tree Regression, zur Preisvorhersage.

- **Visualisierung**:
  - Erstellung von ansprechenden Visualisierungen zur Unterstützung der Analyseergebnisse.

## Datenbeschreibung

Die verwendeten Daten stammen aus einer CSV-Datei (`autoscout24.csv`) und enthalten folgende Spalten:

- **mileage**: Kilometerstand des Fahrzeugs
- **price**: Verkaufspreis
- **hp**: PS (Pferdestärken)
- **year of sale**: Jahr des Verkaufs
- **make**: Marke des Fahrzeugs

## Maschinelles Lernen

Das Projekt implementiert verschiedene Machine Learning-Modelle zur Vorhersage des Verkaufspreises von Autos. Folgende Modelle werden verwendet:

- **Lineare Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**

Die Modelle werden mit verschiedenen Metriken ausgewertet, darunter:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R²-Score

## Ergebnisse

Die Ergebnisse der Modelle werden analysiert, um die beste Modellanpassung zu identifizieren und verschiedene Leistungen zu vergleichen.

## Technologien

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Tableau

## Installation

Um das Projekt auszuführen, stellen Sie sicher, dass Sie die folgenden Bibliotheken installiert haben:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn pandas-profiling
```

## Benutzung

Hinweis: Wenn Sie den Code nur ansehen und nicht verwenden möchten, klicken Sie einfach auf "autoscout24_code.ipynb".

Zum Bearbeiten:

1. Klonen Sie das Repository oder laden Sie die Dateien herunter.
2. Stellen Sie sicher, dass sich die `autoscout24.csv` im gleichen Verzeichnis befindet.
3. Führen Sie das Skript in einer Python-Umgebung (z.B. Jupyter Notebook) aus, um die Daten zu analysieren, Machine Learning-Modelle zu trainieren und das Dashboard zu erstellen.

### Fazit

Dieses Projekt bietet einen umfassenden Einblick in die Verkaufsdaten von Autos und zeigt, wie Datenanalysen und Machine Learning kombiniert werden können, um wertvolle Erkenntnisse zu gewinnen. Es dient auch als Grundlage für weitere Analysen und das Experimentieren mit unterschiedlichen Modellen und Visualisierungstechniken.

