# Ponder OAuth Redirect

This is a minimal public repository for handling Slack OAuth redirects for the Ponder macOS app.

## Setup

1. Create a new public GitHub repository (e.g., `ponder-oauth-redirect`)
2. Push this `docs` folder to the repo
3. Enable GitHub Pages:
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main`, Folder: `/docs`
4. Your redirect URL will be: `https://robertlenne.github.io/oauth-redirect/auth/slack/callback`

## What it does

When Slack redirects here after OAuth authorization, this page automatically redirects to the `ponder://` custom URL scheme, which opens the native Ponder app.

