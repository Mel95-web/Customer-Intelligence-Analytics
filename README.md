# Customer Intelligence & Predictive Marketing Analytics

## Projektübersicht

Dieses Projekt untersucht das Kaufverhalten, die Kundenzufriedenheit und mögliche Kundensegmente anhand eines Datensatzes mit 1.000 Kunden.

Ziel ist es, datenbasierte Erkenntnisse für Marketingentscheidungen zu gewinnen und die Möglichkeiten sowie Grenzen prädiktiver Modelle im Customer Analytics zu bewerten.

## Projektziele

- Explorative Analyse des Kundenverhaltens und der Kaufmuster
- Untersuchung der Kundenzufriedenheit und Customer Experience
- Kundensegmentierung mithilfe von K-Means-Clustering
- Vorhersage des beobachteten Einkaufsbetrags mit Regressionsmodellen
- Entwicklung datenbasierter Marketingempfehlungen
- Erstellung eines Business-Intelligence-Reports mit Excel-PivotTables und Diagrammen

## Datengrundlage

Der analysierte Datensatz enthält 1.000 Kundenbeobachtungen mit 28 Merkmalen, darunter demografische Informationen, Einkaufsverhalten, Kaufbeträge, Kundenzufriedenheit und Marketinginteraktionen.

## Methodik

### 1. Datenaufbereitung und explorative Datenanalyse

Bereinigung und Aufbereitung der Daten sowie deskriptive und visuelle Untersuchung wichtiger Kundenmerkmale.

### 2. Kundensegmentierung

Anwendung von K-Means-Clustering zur explorativen Identifikation von Kundengruppen. Die Ergebnisse werden unter Berücksichtigung der begrenzten Clustertrennung interpretiert.

### 3. Predictive Analytics

Vergleich von drei Regressionsmodellen zur Schätzung des beobachteten Einkaufsbetrags:

- DummyRegressor als Baseline
- Ridge Regression
- Random Forest Regressor

Die Modellbewertung erfolgt anhand von MAE, RMSE und R².

### 4. Customer Satisfaction & Experience

Analyse der Kundenzufriedenheit und Entwicklung eines ergänzenden Fragebogens zur vertiefenden Untersuchung der Customer Experience. Der Fragebogen wurde konzipiert, jedoch nicht durchgeführt.

### 5. Business Intelligence mit Excel

Erstellung von PivotTables und Diagrammen zur Darstellung von:

- Durchschnittlichem Einkaufsbetrag nach Einkaufskanal
- Durchschnittlicher Kundenzufriedenheit nach Einkommensniveau

## Zentrale Ergebnisse

- Der durchschnittliche Einkaufsbetrag beträgt rund **275,06 USD**.
- Das K-Means-Clustering liefert explorative Kundensegmente, jedoch nur eine schwache Trennung zwischen den Gruppen.
- Die getesteten Regressionsmodelle besitzen eine sehr geringe Vorhersagekraft. Ridge Regression erzielt mit einem R² von ungefähr **0,002** das beste Ergebnis.
- Der durchschnittliche Einkaufsbetrag unterscheidet sich zwischen den Einkaufskanälen nur geringfügig.
- Die Ergebnisse verdeutlichen die Bedeutung einer kritischen Modellbewertung und einer vorsichtigen Interpretation datenbasierter Marketinganalysen.

## Verwendete Technologien

- Python
- pandas und NumPy
- Matplotlib, Seaborn und Plotly
- scikit-learn
- Jupyter Notebook
- Microsoft Excel (PivotTables und Diagramme)

## Projektdateien

- Jupyter Notebook mit Datenanalyse, Visualisierungen und Modellen
- Excel-Arbeitsmappe mit Business-Intelligence-Auswertungen
- README.md als Projektdokumentation
- Excel-Customer_Behavior
- csv-Customer_Behavior

## Einschränkungen

Die Ergebnisse beruhen auf dem vorliegenden Datensatz und lassen sich nicht ohne Weiteres auf andere Kundengruppen übertragen. Die geringe Vorhersagekraft der Regressionsmodelle zeigt, dass die verfügbaren Merkmale den Einkaufsbetrag kaum erklären. Die Kundensegmentierung ist explorativ und sollte nicht als eindeutig validierte Kundenklassifikation interpretiert werden.

## Fazit

Das Projekt verbindet explorative Datenanalyse, Kundensegmentierung, Predictive Analytics, Customer Experience und Business Intelligence. Es zeigt sowohl praktische Einsatzmöglichkeiten datenbasierter Marketinganalysen als auch die Notwendigkeit, Modellgrenzen transparent zu kommunizieren.
