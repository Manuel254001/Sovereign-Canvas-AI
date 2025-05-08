# Sovereign Canvas AI

## Overview

Sovereign Canvas AI is a lightweight, AI-powered mini-app designed to run within a creator's LUKSO Universal Profile on The Grid. It transforms static digital identities into dynamic, personalized showcases of LSP-based assets (art, music, collectibles, writing, etc.), enabling decentralized monetization and deep identity-aware engagement.

Built on the principles of digital self-sovereignty, this project aims to break the creator economy free from platform constraints, empowering creators to fully own, display, and monetize their work—directly from their Universal Profiles.

## Features

### AI-Powered Curation: A smart client-side module organizes and personalizes asset display based on metadata.

### LSP Integration: Fetches and displays LSP4 metadata and LSP8 digital assets from the creator's Universal Profile.

### Self-Sovereign Identity: Runs entirely within the LUKSO ecosystem using @lukso/up-provider and The Grid.

### Token-Gated Access: Placeholder logic for checking LSP7 token balances for unlocking exclusive content.

### Monetization Ready: Buy/Unlock placeholders simulate LSP8 sales and fan support.

### Grid Simulation: Tailwind-powered layout visually mimics The Grid's layout system.


## Project Structure

Below is the file and folder structure of the Sovereign Canvas AI project:
```
sovereign-canvas-ai/
├── public/
│   └── index.html        # Entry HTML file
├── src/
│   ├── components/
│   │   └── AssetCard.jsx # Component to display each asset
│   ├── data/
│   │   └── mockAssets.js # Mock asset data (LSP-like)
│   ├── App.jsx           # Main app logic
│   └── main.jsx          # Entry point for React
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.js        # Vite bundler configuration
├── package.json          # Project metadata and dependencies
├── README.md             # Project overview and instructions
└── ARCHITECTURE.md       # System design and component breakdown
```


# Getting Started

## Prerequisites

Node.js (v18 or newer)

Yarn or npm

# Installation
## Install dependencies
$ yarn install

# Start the development server
$ yarn dev

# # Usage

Connect your Universal Profile using the LUKSO browser extension.

The mini-app will fetch mock assets (replaceable with real smart contract queries).

AI logic sorts assets by type or dummy popularity.

Interact with the placeholders for purchase or unlocking gated content.

# Technologies

1. React

2. Vite

3. Tailwind CSS

4. @lukso/up-provider

5. viem (blockchain interaction)

6. LUKSO LSP Standards

7. Identity-Centric Innovation

# This app leverages:

* LSP0: Universal Profile management

* LSP4: Rich metadata for assets

* LSP7: Fungible tokens (for token-gating or tipping)

* LSP8: Unique digital assets (NFTs)

# Demo Screenshots
## Sovereign Canvas AI Logo
![Sovereign Canvas AI Logo](sovereign-canvas-ai/src/Components/Screenshots/Logo.png)

The official logo representing the Sovereign Canvas AI project, visually identifying the mini-app.

## Account Connection
![Account Connection Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Accountconnect.png) 

Demonstrates the process of connecting a LUKSO Universal Profile to the mini-app via the @lukso/up-provider.
This image shows the initial step where a user links their decentralized identity to the mini-app.

## Connected Account
![Connected Account Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Connectedaccount.png) 

Shows the mini-app successfully connected to the user's Universal Profile, displaying basic profile information.
This confirms the successful integration, indicating the mini-app is ready to interact with the user's profile and assets.

## Creative Assets Overview
![Creative Assets Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Creativeassets.png)

Provides a view of the creator's digital assets fetched from their Universal Profile.
This screenshot gives a glimpse into the creator's full collection of owned digital works displayed within the app.

## NFT Showcase 
![NFT Showcase Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Nfts.png) 

Highlights the display of individual LSP8 NFT assets within the mini-app's interface on The Grid.
This image specifically focuses on how unique digital collectibles are presented to visitors.

## AI-Powered Curation
![Recommendations Content Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Recomendationscontent.png)

Illustrates the concept of the AI-like logic curating and ordering content for a personalized view (placeholder visualization).
This visual suggests how the AI tailors the displayed content based on different factors for each viewer.

## Subscriptions (Placeholder)
![Subscriptions Placeholder Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Subscriptions.png)

Shows a potential interface for offering subscription options, possibly tied to LSP7 token ownership.
This image depicts a feature allowing creators to offer recurring access or benefits to their audience.

## Direct Support (Placeholder)
![Direct Support Placeholder Screenshot](sovereign-canvas-ai/src/Components/Screenshots/Directsupport.png)

Demonstrates a possible interface for visitors to provide direct financial support to the creator via token transfers.
This screenshot shows a simple way for fans to send tokens directly to the creator's Universal Profile.


# License

MIT License

# Acknowledgements

LUKSO's Universal Profiles, LSP standards, and The Grid.

### Inspired by a mission to break platform lock-in and build a creator-first future.

#### Built with ❤️ during the LUKSO Hackathon 2025.

"Sovereign Canvas AI isn't just an app. It's a declaration of digital independence."

# God Bless Sovereign Canvas AI

