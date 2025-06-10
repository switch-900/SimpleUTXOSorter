# Bitcoin UTXO Protocol Analyzer

A web-based tool for comprehensive analysis of Bitcoin UTXOs, supporting detection of all major protocols and rare satoshis.

## Features

- **Dual Analysis:** Uses both [ordinals.com](https://ordinals.com) for confirmed data and raw transaction parsing from [mempool.space](https://mempool.space).
- **Protocols Detected:**
  - Ordinals
  - Runes
  - Alkanes & Protorunes
  - Stamps (STAMP, SRC-20, SRC-721)
  - Bitmaps
  - Rare Sats (mythic, legendary, epic, rare, uncommon)
  - Consolidations
  - Unknown/structured protocols
- **Rare Sat Analysis:** Official ordinal theory rarity with degree notation.
- **Consolidation Detection:** Identifies UTXOs from consolidation transactions.
- **Bitmap & Rune Details:** Detects .bitmap patterns and rune balances.
- **Heuristic & Confirmed Results:** Combines confirmed protocol data with heuristic raw analysis.

## Usage

1. Open `index.html` in your browser.
2. Enter a Bitcoin address (e.g., `bc1p...` or legacy format).
3. Click "Analyze UTXOs".
4. Review the summary and detailed protocol analysis for each UTXO.

> **Note:**
> Some API calls may require a CORS browser extension for local testing.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection (to access ordinals.com and mempool.space APIs)

## Project Structure

- `index.html` – Main application file with all logic and UI.

## Disclaimer

This tool is for research and educational purposes. Always verify results with a trusted Bitcoin wallet or node.

---

MIT License
