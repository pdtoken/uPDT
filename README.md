<p align="center">
  <img src="https://pdtoken.github.io/uPDT/logo-128.png" alt="uPDT Logo" width="96" height="96"/>
</p>

<h1 align="center">PDToken (uPDT)</h1>

<p align="center">
  <em>Official Token Assets & Metadata Repository</em>
</p>

<p align="center">
  <!-- Badges -->
  <a href="https://testnet.bscscan.com/token/0x7D44Df6F8b9294EB9242B2FFF4c942E416Fd8481">
    <img src="https://img.shields.io/badge/BSC-Verified-green?logo=binance" alt="BSC Testnet Verified">
  </a>
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  <img src="https://img.shields.io/badge/Status-Testnet-orange.svg" alt="Testnet Status">
</p>

---

## 📌 Overview

This repository hosts the official **token assets, metadata, and tokenlist.json** for **PDToken (uPDT)**.

- ✔️ Logo assets in multiple sizes (`128px`, `256px`, `512px`, `1024px`)
- ✔️ ERC20 tokenlist (`updt.tokenlist.json`)
- ✔️ License: MIT (free use for wallets/explorers)
- ✔️ Verified contract on **BSC Testnet**  
  [`0x7D44Df6F8b9294EB9242B2FFF4c942E416Fd8481`](https://testnet.bscscan.com/token/0x7D44Df6F8b9294EB9242B2FFF4c942E416Fd8481)  

# uPDT
This repository hosts the official token assets and metadata for **PDToken (uPDT)**   Deployed on BSC Testnet only. More details about Mainnet will be updated soon.

# 🪙 PDToken (uPDT) — Official Token Assets

This repository hosts the **official token assets and metadata** for **PDToken (uPDT)**.  
It is designed for use by wallets, block explorers, DEX frontends, and token list aggregators (such as TrustWallet, PancakeSwap, CoinGecko, and CMC).

---

## 📂 Repository Structure

updt-token-assets/

│

├── LICENSE

├── README.md ← this file

├── updt.tokenlist.json ← ERC20 token list definition

└── assets/

└── uPDT/

├── logo-128.png

├── logo-256.png ← ⭐ primary logo used in tokenlists

├── logo-512.png

└── logo-1024.png (master/original)


- **`assets/uPDT/`** → Token logos in multiple resolutions  
- **`updt.tokenlist.json`** → JSON definition used by wallets/DEX UIs to identify the token  (name, symbol, decimals, logoURI, etc.)  
- **`LICENSE`** → MIT License, to allow open usage of logos in wallets & explorers  

---

## 🔗 Contract Information

**Testnet (BSC Testnet – ChainId 97):**
- Token Contract: [`0x7D44Df6F8b9294EB9242B2FFF4c942E416Fd8481`](https://testnet.bscscan.com/address/0x7D44Df6F8b9294EB9242B2FFF4c942E416Fd8481)
- LP (uPDT/WBNB Pair): [`0x1c1A5180365D5ca67152CBbE2b116762298550d1`](https://testnet.bscscan.com/address/0x1c1A5180365D5ca67152CBbE2b116762298550d1)

**Mainnet (BSC – ChainId 56):**
- Token Contract: _will be added after mainnet deployment_  
- LP Contract: _will be added after mainnet deployment_  

---

## 📐 Logo Guidelines

Logos are provided in the following standard sizes:
- `128 × 128` (lightweight, mobile use)
- `256 × 256` (**primary size required by TrustWallet, CoinGecko, and most UIs**)
- `512 × 512` (hi‑res for DEXs/marketing)
- `1024 × 1024` (original/master, can be scaled down)

All logos are `PNG` with a **transparent background**.

---

## 📜 Token List Example

Token entry (from `updt.tokenlist.json`):

```json
{
  "chainId": 97,
  "address": "0x7D44Df6F8b9294EB9242B2FFF4c942E416Fd8481",
  "name": "PDToken",
  "symbol": "uPDT",
  "decimals": 18,
  "logoURI": "https://raw.githubusercontent.com/pdtoken/uPDT/main/assets/uPDT/logo-256.png"
}
