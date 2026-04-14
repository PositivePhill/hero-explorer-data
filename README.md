# 🦸 Hero Explorer Data

Remote JSON data source for the **Hero Explorer Ultimate** UWP application.

## 🌐 Live Data Endpoint

https://raw.githubusercontent.com/PositivePhill/hero-explorer-data/main/heroes.json

# hero-explorer-data
Hero Explorer data source (JSON) Used by HeroExplorer UWP app for remote loading.

## 📦 Data Schema

Each hero object contains:

- id (int)
- name (string)
- universe (string)
- powerLevel (int)
- strength / speed / intelligence / durability (string)
- description (string)
- summary (string)
- spotlightTitle (string)
- spotlightDescription (string)
- soundFile (string)
- thumbnail (object)
- small (string)
- large (string)

## ⚡ Features

- Supports remote loading in UWP app
- Fallback to local JSON if offline
- Extendable schema for future features

## 🛠 Used By

Hero Explorer Ultimate  
Built by Phillip Mattern

---

## 🚀 Future Ideas

- Live editing dashboard
- Versioned datasets (Marvel / DC toggle)
- API wrapper (Node / Azure Functions)
