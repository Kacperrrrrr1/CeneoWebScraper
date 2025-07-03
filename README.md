# 🕷️ CENEO Web Scrapper

**CENEO Web Scrapper** to aplikacja służąca do automatycznego pobierania opinii o produktach ze strony [ceneo.pl](https://www.ceneo.pl). Umożliwia analizę recenzji i ocen użytkowników na podstawie identyfikatora produktu.

## 📌 Funkcje

- Pobieranie opinii z wielu stron wyników
- Zapis danych do pliku JSON lub CSV
- Czyszczenie i standaryzacja tekstu opinii
- Eksport danych do dalszej analizy (np. w Pythonie, Excelu)
- Możliwość filtrowania opinii według oceny lub daty

## 🔧 Wymagania

- Python 3.8+
- Biblioteki:
  - `requests`
  - `BeautifulSoup4`
  - `pandas`
  - `lxml` *(opcjonalnie dla lepszej wydajności)*

Zainstaluj wymagane biblioteki:

```bash
pip install -r requirements.txt
```

## 🚀 Jak uruchomić

1. Skopiuj lub pobierz repozytorium:

```bash
git clone https://github.com/twoj-uzytkownik/CENEO-Web-Scrapper.git
cd CENEO-Web-Scrapper
```

2. Uruchom aplikację:

```bash
python ceneo_scraper.py
```

3. Wprowadź **ID produktu Ceneo**, np. `12345678`.

4. Aplikacja pobierze wszystkie dostępne opinie i zapisze je do pliku `opinie.json` lub `opinie.csv`.

## 📝 Przykład użycia

```python
>>> Podaj ID produktu Ceneo: 85721645
Znaleziono 5 stron z opiniami.
Pobrano 124 opinie.
Dane zapisane do pliku: opinie_85721645.json
```

## 📁 Struktura projektu

```
CENEO-Web-Scrapper/
├── ceneo_scraper.py       # Główna logika aplikacji
├── utils.py               # Pomocnicze funkcje (parsowanie, czyszczenie danych)
├── requirements.txt       # Lista wymaganych bibliotek
├── README.md              # Dokumentacja
└── data/                  # Folder na zapisane dane (opinie)
```

## ⚠️ Uwaga prawna

Ten projekt ma charakter edukacyjny. Przed długotrwałym lub zautomatyzowanym użyciem scraperów upewnij się, że nie łamiesz regulaminu strony [ceneo.pl](https://www.ceneo.pl/Regulamin).

## 📬 Kontakt

Masz pytania lub sugestie? Skontaktuj się:

📧 Mail:
🐙 GitHub:

---

⭐ Jeśli projekt Ci się podoba, zostaw ⭐ na GitHubie!
