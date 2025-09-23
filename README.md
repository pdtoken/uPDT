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
  "logoURI": "https://raw.githubusercontent.com/pktoken/uPDT/main/assets/uPDT/logo-256.png"
}
