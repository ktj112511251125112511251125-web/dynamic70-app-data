# DYNAMIC70 App Data (Latest Only)

This PUBLIC repository is a tiny stateless feed for the Android app.

- `latest.json`: only the latest DYNAMIC70 strategy/market snapshot.
- No account cash, holdings, average purchase prices, or order quantities are published.
- No Telegram secret or PAT is published.
- No history CSV/Excel/PNG archive is stored.
- The private runner force-replaces `main` with a fresh root commit on each successful run.

The Android app should read `latest.json` from the raw GitHub URL.
