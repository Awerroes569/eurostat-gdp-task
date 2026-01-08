# Analiza PKB nominalnego krajów UE (2022)

Zadanie rekrutacyjne – pobranie danych z API Eurostatu i wizualizacja PKB dla wybranych krajów.

## Opis zadania

- Pobranie danych z datasetu `nama_10_gdp` (Eurostat API)
- Filtrowanie danych dla: Polska, Niemcy, Francja
- Rok: 2022
- Jednostka: miliony EUR (ceny bieżące)
- Wydruk DataFrame z wartościami PKB
- Wizualizacja w formie wykresów słupkowych

## Technologie

- Python 3.10
- pandas – przetwarzanie danych
- eurostat – pobieranie danych z API
- matplotlib – wizualizacja (wersja podstawowa)
- seaborn – wizualizacja (wersja statystyczna)
- plotly – wizualizacja (wersja interaktywna)

## Instalacja

```bash
# Klonowanie repozytorium
git clone <repo-url>
cd eurostat-gdp-task

# Utworzenie środowiska wirtualnego
python -m venv .venv

# Aktywacja (Windows)
.venv\Scripts\activate

# Aktywacja (Linux/Mac)
source .venv/bin/activate

# Instalacja zależności
pip install -r requirements.txt
```

## Uruchomienie

```bash
jupyter notebook gdp_analysis.ipynb
```

Lub w VS Code / Cursor: otwórz plik `gdp_analysis.ipynb` i uruchom wszystkie komórki.

## Struktura projektu

```
eurostat-gdp-task/
├── .venv/                  # środowisko wirtualne
├── gdp_analysis.ipynb      # główny notebook
├── requirements.txt        # zależności
└── README.md               # dokumentacja
```

## Autor

Arkadiusz Skóbel
