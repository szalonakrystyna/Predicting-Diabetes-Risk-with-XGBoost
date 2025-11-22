# Predicting-Diabetes-Risk-with-XGBoost
Analiza predykcyjna ryzyka cukrzycy typu 2 na podstawie danych klinicznych Pima Indians Diabetes Dataset.

## Cel projektu
Celem analizy jest zbudowanie modelu uczenia maszynowego (XGBoost), który przewidzi, czy pacjent ma podwyższone ryzyko cukrzycy, na podstawie danych takich jak:
- poziom glukozy,
- BMI,
- ciśnienie krwi,
- liczba ciąż,
- historia insulinowa.

## Technologie
- Python 3.10+
- pandas
- numpy
- scipy
- seaborn
- matplotlib
- scikit-learn
- XGBoost
- SHAP

## Etapy analizy
1. Wczytanie danych  
2. Analiza eksploracyjna  
3. Visualizacje medyczne (BMI, glucose, BP, korelacje)  
4. Przygotowanie danych  
5. Budowa modelu XGBoost  
6. Metryki: Accuracy, F1, AUC  
7. ROC Curve  
8. SHAP – interpretacja modelu  

## Wyniki
Wszystkie wykresy znajdują się w folderze `figures/`.

## Interpretacja SHAP
SHAP pozwala zobaczyć, jak cechy (glukoza, BMI itd.) wpływają na decyzje modelu.

## Zastosowania medyczne
- wsparcie decyzji klinicznych  
- wczesna identyfikacja pacjentów ryzyka  
- analiza czynników wpływających na cukrzycę  


