***

# California Housing Analysis

Repozytorium zawiera analizę eksploracyjną (EDA) oraz model regresyjny przygotowany na potrzeby rekrutacji do koła naukowego DataTeam. Projekt skupia się na przewidywaniu mediany wartości domów w Kalifornii na podstawie danych geograficznych i demograficznych.

## Struktura projektu
* `analysis.ipynb` - Jupyter Notebook z pełnym procesem analizy, wizualizacjami i budową modelu.
* `analysis.html` - Wyeksportowana wersja analizy do szybkiego podglądu.
* `pyproject.toml` / `uv.lock` - Pliki konfiguracyjne środowiska wykonawczego.

*** 

## Zakres analizy
1. Eksploracja danych: sprawdzenie struktur, typów danych oraz weryfikacja brakujących wartości.
2. Analiza statystyczna: badanie korelacji między cechami a zmienną objaśnianą (MedHouseVal).
3. Wizualizacja danych: rozkłady cech, mapy korelacji oraz zależności liniowe.
4. Preprocessing: czyszczenie danych, obsługa wartości odstających oraz podział na zbiory treningowy i testowy.
5. Modelowanie: implementacja modelu regresji liniowej.
6. Ewaluacja: ocena modelu przy użyciu metryk MAE, RMSE oraz R2.

***

## Technologia i środowisko
Projekt został przygotowany w języku Python z wykorzystaniem menedżera pakietów uv. 

Kluczowe biblioteki:
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

***

## Instrukcja uruchomienia
Wymagane jest zainstalowane narzędzie `uv`.
pip install uv

1. Sklonuj repozytorium:
git clone https://github.com/jawanat/california-housing-regression

2. Zainstaluj zależności i aktywuj środowisko:
uv sync

3. Uruchom notebooka:
uv run jupyter lab
