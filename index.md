[Русская версия](ru.html)

# SignalPoint Privacy Policy

Effective date: November 2, 2026

## Who we are

SignalPoint is an Android app that notifies you when a crypto asset reaches a price level you set. It is not a trading platform: you cannot buy or sell assets in it, it does not connect to exchange accounts and never asks for exchange API keys.

App operator: SignalPoint
Contact: signalpoint.app@gmail.com

## What data we process

There is no sign-up or sign-in. We do not ask for your name, email or phone number. The app has no ads, analytics or crash reporting.

On first launch the app creates a random installation ID. It is not linked to your identity and is used only so the server can tell your alerts apart from others.

**Stored on your phone:**

- your alerts: pair, exchange, price level, direction, status, creation and trigger time, note, colour;
- your watchlist (selected pairs);
- settings: language, notification sound, chart type, selected period and timeframe;
- the installation ID and the Firebase push token;
- internal sync state.

**Sent to our server** (for each alert, so it can fire even when the app is closed):

- the alert ID and the installation ID;
- the pair, its code on the exchange, the exchange and market type (e.g. "BTCUSDT, Binance, SPOT");
- the price level, status and whether the alert repeats;
- creation time, trigger time and the last known price;
- your Firebase Cloud Messaging token, the address our server uses to deliver the notification to your phone.

NOT sent to the server: alert notes, alert colours, your watchlist, app settings.

## Why

Only to check prices and notify you when your alerts trigger. We do not use the data for advertising, do not sell it and do not share it with ad networks.

## Where data is stored

- On your phone: the data listed above.
- On our server: the alert data listed above. The server and database run on Cloudflare (Cloudflare Workers, Cloudflare D1 database).

## Who receives data

- **Cloudflare** hosts our server and database. As with any internet connection, Cloudflare receives your device's IP address and technical request details when the app contacts the server. For this data Cloudflare acts as a service provider (processor) on our behalf. Our server does not write IP addresses to the alerts database or to its own logs. Cloudflare's policy: https://www.cloudflare.com/privacypolicy/
- **Google (Firebase Cloud Messaging)** delivers push notifications. Firebase uses the device token and the Firebase installation ID to decide which device to deliver a message to. A trigger notification contains the pair, the level and the current price, so this information passes through Firebase. Google collects service data about how the service works under its own terms: https://firebase.google.com/support/privacy
- **Public exchange APIs** (Binance, Hyperliquid, dYdX, Bybit, MEXC, KuCoin, Gate). To show prices and charts the app requests public market data for the pairs you choose. Exchanges see your device's IP address and which pairs are requested. We share no information about you with exchanges.

## How long we keep data

- Data on your phone is kept while the app is installed.
- An alert is deleted from the server when you delete it in the app or remove its pair from your watchlist. A one-time alert deletes itself after it triggers.
- We do not automatically delete inactive data. If you uninstall the app without deleting your alerts, they stay on the server until you ask us by email to delete them (see below).

## How to delete your data

- Delete an alert in the app and it is deleted from the server too.
- Remove a pair from your watchlist and its alerts are deleted with it, including on the server.
- Uninstalling the app erases the data on your phone but not on the server, so delete your alerts in the app before uninstalling it.
- If you have already uninstalled the app, email signalpoint.app@gmail.com, say you want your data deleted and list the pairs and levels of your alerts (for example, "BTCUSDT on Binance, 65,000"). We will use them to find and delete the records.

## Android backup

If Android backup is turned on for your phone, the system may copy the app data to your Google Drive and restore it on a new device. The backup is stored by Google; we have no access to it. You can turn backup off in your phone settings.

## One device

The app is designed for one device. To switch to a new one, create your alerts on it again and uninstall the app on the old one.

## Children

The app is intended for people aged 18 and over. We do not knowingly collect data from children.

## Security

Data is sent to the server over an encrypted connection (HTTPS).

## Changes

If this policy changes, we will update this page and the effective date.

## Contact

Questions about your data or deletion requests: signalpoint.app@gmail.com
