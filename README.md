# Autoscout24-Data-Analytics-and-ML-Models

Dieses Repository enthält eine umfassende Analyse von Daten von Autoscout24. 

Es umfasst die folgenden Hauptkomponenten:
Datenanalyse: Ausführliche Analyse der Autoscout24-Daten, um wichtige Trends und Muster zu identifizieren.
Visualisierung: Erstellung interaktiver Visualisierungen mit Tableau, um die Erkenntnisse ansprechend zu präsentieren.
Machine Learning Modelle: Training, Testen und Vergleich mehrerer Machine Learning-Modelle, um die besten Vorhersageergebnisse zu erzielen.

Die Zielsetzung dieses Projekts ist es, wertvolle Einsichten in den Automobilmarkt zu gewinnen und die Leistungsfähigkeit verschiedener ML-Modelle zu evaluieren.


## Inhaltsverzeichnis

- [Einführung](#einführung)
- [Datenbeschreibung](#datenbeschreibung)
- [Vorbereitung](#vorbereitung)
- [Visualisierungen](#visualisierungen)
- [Datenanalyse](#datenanalyse)
- [Maschinelles Lernen](#maschinelles-lernen)
- [Ergebnisse](#ergebnisse)
- [Installation](#installation)
- [Benutzung](#benutzung)


## Einführung

Dieses Projekt zielt darauf ab, Einblicke in die Verkaufsdaten von Autos zu gewinnen und
Vorhersagemodelle zu erstellen, um den Preis von Fahrzeugen auf der Grundlage bestimmter Merkmale zu schätzen.

## Datenbeschreibung

Die Daten werden aus einer CSV-Datei (`autoscout24.csv`) geladen, die folgende Spalten enthält:

- **mileage**: Kilometerstand des Fahrzeugs
- **price**: Verkaufspreis
- **hp**: PS (Pferdestärken)
- **year of sale**: Jahr des Verkaufs
- **make**: Marke des Fahrzeugs

## Vorbereitung

Die Daten werden vorbereitet, indem:

1. **Null-Werte** entfernt werden.
2. **Einen sauberen Datensatz** in einer neuen CSV-Datei (`autoscout24_clean.csv`) gespeichert wird.
3. **Statistische Informationen** über die numerischen Merkmale bereitgestellt werden.

## Visualisierungen

Das Projekt enthält mehrere Visualisierungen zur Analyse der Daten, darunter:

- **Histogramme** für jede numerische Spalte
- **Korrelationsmatrix** für die numerischen Merkmale
- **Liniendiagramm** der verkauften Autos pro Jahr

## Datenanalyse

Die Datenanalyse umfasst:

- Die Anzahl der verkauften Autos pro Jahr (2011 - 2021)
- Die häufigsten Marken
- Korrelationen zwischen den numerischen Merkmalen
- Durchschnittspreise für die fünf meistverkauften Automarken

## Maschinelles Lernen

Das Projekt implementiert verschiedene maschinelle Lernmodelle, um den Verkaufspreis von Autos vorherzusagen. Folgende Modelle werden verwendet:

- **Lineare Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**

## Ergebnisse

Die Ergebnisse der Modelle werden mit verschiedenen Metriken ausgewertet:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R²-Score**

Die Modelle zeigen verschiedene Leistungen, und eine detaillierte Analyse der Ergebnisse wird durchgeführt, um die beste Modellanpassung zu identifizieren.

## Installation

Um das Projekt auszuführen, stelle sicher, dass du die folgenden Bibliotheken installiert hast:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn pandas-profiling
```

## Benutzung

1. Klone das Repository oder lade die Dateien herunter.
2. Stelle sicher, dass sich die `autoscout24.csv` im gleichen Verzeichnis befindet.
3. Führe das Skript in einer Python-Umgebung (z.B. Jupyter Notebook) aus.

