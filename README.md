# Product Price Monitor

A Streamlit prototype for comparing a product price with prices found on competitor product pages.

## Features

- Accepts one own-product URL and multiple competitor URLs
- Extracts prices from Open Graph metadata, schema markup, JSON-LD, and common HTML patterns
- Retries selected blocked requests with browser-like headers
- Highlights cheaper, equal, and more expensive competitor offers
- Runs as an interactive Streamlit app

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## Responsible use

Only request pages you are allowed to access. Respect website terms, robots policies, and reasonable request limits.

