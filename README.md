# Diabetes Prediction – Machine Learning Project

Projekt uczenia maszynowego mający na celu przewidzenie wystąpienia cukrzycy na podstawie danych medycznych (Pima Indians Diabetes Dataset). Projekt został zrealizowany w środowisku Jupyter Notebook z użyciem biblioteki `scikit-learn`.

## 📁 Dane

Użyty zbiór danych pochodzi z repozytorium UCI i jest dostępny także na Kaggle:
- https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

Plik: [`diabetes.csv`](./diabetes.csv)  
Zawiera dane dotyczące 768 kobiet z plemienia Pima w wieku powyżej 21 lat.

## 🎯 Cel projektu

Celem projektu było stworzenie modeli klasyfikacyjnych, które na podstawie danych takich jak poziom glukozy, ciśnienie krwi, BMI itp. będą przewidywać, czy dana osoba ma cukrzycę (`Outcome = 1`) czy nie (`Outcome = 0`).

## 🔧 Technologie i biblioteki

- Python 3
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

## ⚙️ Kroki analizy

1. **Załadowanie i wstępna analiza danych**
2. **Wykrycie i uzupełnienie błędnych wartości (zamiana zer na mediany)**
3. **Eksploracyjna analiza danych (EDA): rozkłady, korelacje**
4. **Podział danych na zbiór treningowy i testowy**
5. **Trenowanie modeli:**
   - Drzewo decyzyjne
   - Regresja logistyczna
6. **Porównanie skuteczności modeli (accuracy)**

## 📊 Wyniki

| Model                | Accuracy |
|---------------------|----------|
| Drzewo decyzyjne    | ~72%     |
| Regresja logistyczna| ~75%    |

## ✅ Wnioski

- Oba modele osiągnęły przyzwoitą skuteczność bez zaawansowanego strojenia parametrów.
- Najważniejszymi cechami okazały się: poziom glukozy, BMI i wiek.
- Projekt pokazał, jak w prosty sposób można zbudować model klasyfikacyjny w Pythonie.

## 📂 Zawartość repozytorium

- `diabetes.csv` – dane wejściowe
- `diabetes.ipynb` – kod i analiza
- `README.md` – opis projektu

## 👩‍💻 Autor

Projekt wykonany w ramach ćwiczeń z przedmiotu *Sztuczna inteligencja / Uczenie maszynowe*.

