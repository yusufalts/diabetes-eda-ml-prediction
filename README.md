# Diabetes – Explorative Datenanalyse & Machine Learning

## Projektziel
Diabetes ist eine weit verbreitete chronische Erkrankung, deren frühzeitige Erkennung einen erheblichen Einfluss auf die Lebensqualität der Betroffenen haben kann.

In diesem Projekt wird ein **Machine-Learning-Modell** entwickelt, das auf Basis medizinischer und demografischer Merkmale vorhersagt, **ob bei einer Person Diabetes vorliegt oder nicht**.  
Der Fokus liegt auf einem **praxisnahen Data-Science-Workflow**, der von der Datenexploration über Feature Engineering bis hin zur Modelloptimierung reicht.

---

## Datensatz
Der verwendete Datensatz basiert auf medizinischen Untersuchungsdaten und wird häufig in der Datenanalyse und im Machine Learning zur Diabetes-Erkennung eingesetzt.

Die Daten stammen von **erwachsenen Frauen (ab 21 Jahren)** und enthalten mehrere gesundheitsrelevante Messwerte, die im Zusammenhang mit Diabetes stehen.  
Der Datensatz eignet sich besonders gut, um Klassifikationsmodelle im medizinischen Kontext zu analysieren und zu vergleichen.

### Zielvariable
- **Outcome**
  - `1` → Diabetes diagnostiziert  
  - `0` → Keine Diabetes-Diagnose  

---

## Beschreibung der Merkmale
- **Pregnancies**: Anzahl der Schwangerschaften  
- **Glucose**: Glukosekonzentration im Blut nach einem oralen Glukosetoleranztest  
- **BloodPressure**: Diastolischer Blutdruck (mm Hg)  
- **SkinThickness**: Hautfaltendicke  
- **Insulin**: Insulinwert im Blut (µU/ml)  
- **DiabetesPedigreeFunction**: Kennzahl zur familiären Diabetesbelastung  
- **BMI**: Body-Mass-Index  
- **Age**: Alter der Person  
- **Outcome**: Zielvariable (1 = Diabetes, 0 = kein Diabetes)

---

## Methodisches Vorgehen
Das Projekt folgt einer klar strukturierten Vorgehensweise, um Transparenz und Nachvollziehbarkeit zu gewährleisten.

### 1. Datenverständnis und Vorbereitung
1. Import der relevanten Python-Bibliotheken  
2. Erste Sichtung und Strukturierung der Daten  
3. Laden des Datensatzes  
4. Explorative Datenanalyse (EDA)  

### 2. Explorative Datenanalyse
5. Trennung numerischer und kategorialer Variablen  
6. Analyse kategorialer Merkmale  
7. Analyse numerischer Merkmale  
8. Untersuchung der Merkmale in Bezug auf die Zielvariable  
9. Analyse von Verteilungen und Abhängigkeiten  
10. Korrelationsanalyse  
11. Identifikation relevanter Einflussfaktoren  

---

## Baseline-Modellierung
Zur Bestimmung einer Ausgangsleistung werden zunächst mehrere **Baseline-Modelle** ohne umfangreiches Feature Engineering trainiert.

### Eingesetzte Modelle
- Logistische Regression  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- AdaBoost  
- Gradient Boosting  
- XGBoost  
- LightGBM  

Die Modelle werden anhand gängiger Klassifikationsmetriken miteinander verglichen.

---

## Feature Engineering
Im nächsten Schritt wird die Datenqualität gezielt verbessert:

- Behandlung fehlender Werte  
- Analyse und Umgang mit Ausreißern  
- Ableitung neuer Merkmale  
- Kodierung geeigneter Variablen  
- Skalierung und Standardisierung numerischer Features  

---

## Modelltraining und Optimierung
Nach dem Feature Engineering werden die Modelle erneut trainiert.

Für ausgewählte Algorithmen erfolgt eine **Hyperparameter-Optimierung**, um die Modellleistung weiter zu steigern.  
Anschließend werden die Ergebnisse systematisch miteinander verglichen.

---

## Ergebnisse und Bewertung
- Vergleich der Modellleistung vor und nach Feature Engineering  
- Bewertung des Effekts der Hyperparameter-Optimierung  
- Identifikation des leistungsstärksten Modells  

Die Analyse zeigt, dass insbesondere **Ensemble-Methoden** robuste und stabile Ergebnisse liefern.

---

## Zentrale Erkenntnisse
- Bestimmte medizinische Merkmale haben einen starken Einfluss auf die Diabetes-Vorhersage  
- Sorgfältiges Feature Engineering verbessert die Modellqualität deutlich  
- Hyperparameter-Optimierung führt zu messbaren Leistungsgewinnen  
- Machine Learning eignet sich gut zur Unterstützung medizinischer Entscheidungsprozesse  

---

## Verwendete Technologien
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- XGBoost  
- LightGBM  

---

## Autor
**Yusuf Altaş**  
