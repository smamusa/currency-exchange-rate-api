# Currency Exchange Rate Scraper for Croatian Banks
[![License: MIT](https://img.shields.io/github/license/smamusa/exchange-rate-scraper)](https://github.com/smamusa/exchange-rate-scraper/blob/master/LICENSE.md) 
![Last commit](https://img.shields.io/github/last-commit/smamusa/exchange-rate-scraper)
![Top language](https://img.shields.io/github/languages/top/smamusa/exchange-rate-scraper)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
![Code size](https://img.shields.io/github/languages/code-size/smamusa/exchange-rate-scraper)
![Repo size](https://img.shields.io/github/repo-size/smamusa/exchange-rate-scraper)

## Screenshot

![Screenshot](https://github.com/smamusa/exchange-rate-scraper/blob/55dde89d2063d789ce416e2c432b1294a55efcf1/Screenshot.png)


## Banks

- [x] OTP
- [] ZABA
- [ ] Erste
- [ ] HPB
- [ ] PBZ

## To-Do

- [ ] Save rates in a txt or csv file
- [ ] Correct HTML not being parsed in time
- [ ] Add other rates

### Installation

:warning: Note, the first time you ever run the render() method, it will download Chromium into your home directory (e.g. ~/.pyppeteer/).

:exclamation: pyppeteer requires Python >= 3.6

:exclamation: This only happens once.

Clone the repo

```cmd
    git clone https://github.com/smamusa/exchange-rate-scraper.git
```

Switch into repo directory

```cmd
    cd exchange-rate-scraper
```

Create a new virtual environment

```cmd
   python -m venv myvenv
```

Run the venv activation script. Which one you run depends on your OS and terminal

```cmd
   cd myenv/Scripts
   activate.bat
```

Install all requirements

```cmd
    pip install -r requirements.txt
```

Finally run the app by calling scrape.py

```cmd
    python scrape.py
```
