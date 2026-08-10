# Float-Hub

Shopify theme for Float Hub, managed with [Shopify CLI](https://shopify.dev/docs/api/shopify-cli).

## Prerequisites

- [Node.js](https://nodejs.org/) 18+
- [Shopify CLI](https://shopify.dev/docs/api/shopify-cli) (`npm install -g @shopify/cli @shopify/theme`)

## Setup

```bash
# Authenticate with Shopify
shopify auth login

# Link store (example)
shopify theme info --store=YOUR-STORE.myshopify.com
```

## Common commands

```bash
# Pull latest theme from Shopify
shopify theme pull

# Start a local development server
shopify theme dev --store=YOUR-STORE.myshopify.com

# Push theme changes
shopify theme push

# List themes
shopify theme list
```

## Project structure

```
assets/      # CSS, JS, images
config/      # Theme settings
layout/      # Theme layouts
locales/     # Translations
sections/    # Theme sections
snippets/    # Reusable snippets
templates/   # Page templates
```
