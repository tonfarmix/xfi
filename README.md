# x-fi — Spot Margin Trading Protocol on TON

x-fi is a decentralized spot margin trading protocol built on the TON blockchain, enabling users to open long and short positions directly on DEX liquidity, using undercollateralized loans from KirkaFi lending pools.

## What is x-fi?

x-fi is part of the KirkaFi modular DeFi infrastructure. It allows users to:

Use assets like USDT, NOT, or tsTON as collateral
Borrow assets with partial collateral (~50–70%)
Execute leveraged spot trades on DEX pairs (long & short)
Maintain full self-custody and transparency via smart contracts

## How it works

Users deposit collateral into the smart contract (e.g., USDT)

The protocol calculates borrow power based on collateral ratio

Users open long or short positions using DEX liquidity and borrowed assets in any pair represented in x-fi

Positions are monitored via a Health Factor

Partial liquidation is triggered automatically if HF drops below 1

## Risk Management

Dynamic liquidation system (partial + fair refund)

Health Factor tracking

Automated notifications and risk thresholds

Protocol-level Treasury covers rare bad debt cases

## Features

- Fully on-chain and non-custodial
- Integrated with Farmix & Lendix lending pools
- Supports multiple collateral types (USDT, NOT, stTON, etc.)
- Alerts and simulations for safe position opening

## 📅 Roadmap

Smart contract testing Q2 2025
DEX integration (Ston.fi) Q2 2025
Launch on TON Mainnet (Summer 2025)
Audit Q3 2025

## 📚 Docs

Whitepaper (https://surf-find-d72.notion.site/Navigation-KirkaFi-1e0d3695ed868036acf3c5f42df19836?pvs=4)
Litepaper (https://surf-find-d72.notion.site/Litepaper-1e1d3695ed86805d9b71d29b70c95466?pvs=4)
API Reference (soon)
x-fi UI Demo (soon) 


## 📬 Contact
Telegram: @KirkaTON
Twitter: @TonKirkaFi
