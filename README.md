Hier ist der Text in einer "Sie"-Formulierung:

```markdown
# Autoscout24 Data Analytics and Machine Learning Models

## Projektübersicht

In diesem Projekt werden Verkaufsdaten von Autos aus AutoScout24 analysiert und visualisiert. Ziel ist es, interessante Erkenntnisse über die Verkaufszahlen, Preisentwicklung und mögliche Korrelationen zwischen verschiedenen Eigenschaften der Fahrzeuge zu gewinnen. Zudem werden Machine Learning-Modelle entwickelt, um den Verkaufspreis von Autos basierend auf ihren Merkmalen vorherzusagen.

## Inhaltsverzeichnis

- [Projektübersicht](#projektübersicht)
- [Datenbeschreibung](#datenbeschreibung)
- [Vorbereitung](#vorbereitung)
- [Visualisierungen](#visualisierungen)
- [Datenanalyse](#datenanalyse)
- [Maschinelles Lernen](#maschinelles-lernen)
- [Ergebnisse](#ergebnisse)
- [Technologien](#technologien)
- [Installation](#installation)
- [Benutzung](#benutzung)
- [Fazit](#fazit)

## Datenbeschreibung

Die verwendeten Daten stammen aus einer CSV-Datei (`autoscout24.csv`) und enthalten folgende Spalten:

- **mileage**: Kilometerstand des Fahrzeugs
- **price**: Verkaufspreis
- **hp**: PS (Pferdestärken)
- **year of sale**: Jahr des Verkaufs
- **make**: Marke des Fahrzeugs

## Vorbereitung

Die Daten werden vorbereitet durch:

1. Entfernen von Null-Werten.
2. Speichern eines sauberen Datensatzes in einer neuen CSV-Datei (`autoscout24_clean.csv`).
3. Bereitstellung statistischer Informationen über die numerischen Merkmale.

## Visualisierungen

Das Projekt enthält mehrere interaktive Visualisierungen, die mit Tableau erstellt wurden, darunter:

- Histogramme für jede numerische Spalte
- Korrelationsmatrix für die numerischen Merkmale
- Liniendiagramm der verkauften Autos pro Jahr

## Datenanalyse

Die Datenanalyse umfasst:

- Verkaufsstatistiken: Wie viele Autos wurden pro Jahr verkauft (2011 - 2021)?
- Die häufigsten Marken in den Daten.
- Korrelationen zwischen den numerischen Merkmalen.
- Durchschnittspreise für die fünf meistverkauften Automarken.

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
