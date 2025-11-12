# TazaProxy-Troxy

**TazaProxy-Troxy** is an educational proxy repository that provides working proxies with automatic updates every 12 hours. This repository is intended **only for learning and educational purposes**.  

> ⚠️ **Disclaimer:** Use responsibly. This repository is not intended for any illegal activities or abuse.  

---

## Features

- ✅ Working proxies updated every **12 hours**  
- 🌐 Available in **TXT** and **JSON** formats  
- 🛠 Simple & ready-to-use for educational experiments  
- 📚 Perfect for learning proxy handling, automation, or scraping  

---

## Proxy Files

| Format | URL |
|--------|-----|
| TXT    | [working_proxies.txt](https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.txt) |
| JSON   | [working_proxies.json](https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.json) |

---

# TazaProxy-Troxy

![Last Update](https://img.shields.io/github/last-commit/abusaeeidx/TazaProxy-Troxy)
![Python](https://img.shields.io/badge/python-3.11-blue)
![License](https://img.shields.io/github/license/abusaeeidx/TazaProxy-Troxy)

**TazaProxy-Troxy** is an educational proxy repository providing working proxies that are **auto-updated every 12 hours**. This project is intended **only for educational purposes**.

> ⚠️ **Disclaimer:** Use responsibly. This repository is not intended for illegal activities or abuse.  

---

## Features

- ✅ Working proxies updated every **12 hours**  
- 🌐 Available in **TXT** and **JSON** formats  
- 🛠 Simple & ready-to-use for educational experiments  
- 📚 Perfect for learning proxy handling, automation, or scraping  
- ⚡ Auto-verified for **live status** and **latency**  

---

## Proxy Files

| Format | URL |
|--------|-----|
| TXT    | [working_proxies.txt](https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.txt) |
| JSON   | [working_proxies.json](https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.json) |

---

## Proxy Statistics

> Updated every 12 hours. Numbers may vary.

| Type   | Count |
|--------|-------|
| HTTP   | ~1200 |
| HTTPS  | ~950  |
| SOCKS4 | ~400  |
| SOCKS5 | ~500  |

---

## How It Works

1. Proxies are collected from multiple sources.  
2. Verified automatically for **live status**, **type**, and **latency**.  
3. Every **12 hours**, the list is automatically updated with working proxies.  
4. Users can directly download or fetch the proxies using the provided URLs.  

---

## Usage Example (Python)

```python
import requests

# Fetch working proxies (TXT)
txt_url = "https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.txt"
proxies = requests.get(txt_url).text.splitlines()
print(f"Total working proxies fetched: {len(proxies)}")
print(proxies[:10])  # Show first 10 proxies

# Fetch working proxies (JSON)
json_url = "https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.json"
proxies_json = requests.get(json_url).json()
print(proxies_json[:10])  # Show first 10 proxies in JSON

## How It Works

1. Proxies are collected from multiple sources and verified for live status.  
2. Every **12 hours**, the list is automatically updated to include only **working proxies**.  
3. Users can directly download or fetch the proxies using the provided URLs.  

---

## Usage Example (Python)

```python
import requests

# Example: Fetch working proxies
txt_url = "https://raw.githubusercontent.com/abusaeeidx/TazaProxy-Troxy/refs/heads/main/working_proxies.txt"
proxies = requests.get(txt_url).text.splitlines()
print(f"Total working proxies fetched: {len(proxies)}")
print(proxies[:10])  # Show first 10 proxies













---.''"
