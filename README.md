# 🧠 Niat Memory System

Ett lokalt minnessystem för ChatGPT i samarbete med användaren. Projektet syftar till att skapa:

- ✍️ Redigerbara minnesfiler ("chunks")
- 🔍 Semantisk sökning med vektorindexering
- 🧠 Självreflektion och etikettering
- 🌐 Flask-server för API-åtkomst
- 💻 React-dashboard för visuell överblick

## Struktur

- `chunks/` – Minnesfragment
- `server/` – Flask-baserad lokalserver (`niat_server.py`)
- `dashboard/` – React-gränssnitt för interaktion
- `docs/` – Dokumentation och designidéer

## Kom igång

```bash
git clone https://github.com/staffantastiskafantasmer/niat-memory.git
cd niat-memory
python server/niat_server.py
