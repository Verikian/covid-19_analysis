# Analiza i predykcja liczby zarażeń na COVID-19 w Polsce 

Projekt wykonano w ramach przedmiotu Analiza Dużych Zbiorów Danych (ADD) na uczelni PJATK w Warszawie przez studentów:
- **Katarzyna Kleczkowska** ()
- **Adam Sitko** (Verikian)

### PL Opis projektu
Cel projektu:
- Analiza liczby zakażeń na COVID-19 w Polsce w latach 2020-2022.
- Wyznaczenie początku oraz końca poszczególnych fal pandemii wraz z ich podstawowymi wskaźnikami statystycznymi.
- Stworzenie modelu, który będzie przewidywał liczbę zakażeń w danym dniu w Polsce.

Dane historyczne, na podstawie których wykonano projekt, pochodzą z [Europejskiego Centrum ds. Zapobiegania i Kontroli Chorób ECDC](https://www.ecdc.europa.eu/en/publications-data/data-daily-new-cases-covid-19-eueea-country/).

Kod napisano w języku **Python** przy wykorzystaniu narzędzia **Jupyter Notebook**.

Wykorzystane biblioteki:
- `numpy` i `pandas`: analiza zbioru danych
- `matplotlib` i `seaborn`: wizualizacja danych ze zbioru oraz prezentacja predykcji z modeli
- `sklearn`: tworzenie modeli regresji wielorakiej i drzew regresyjnych, skalowanie danych, dzielenie danych na dane treningowe i testowe oraz wyliczanie metryk modeli
- `tensorflow` i `keras`: tworzenie modeli sieci neuronowej
- `pickle`
- `IPython`

Przetestowano na `Python 3.10.12`.
