# Snipers MT5 Bridge

A small Windows program that lets the Snipers Live Indicators Dashboard
read candle data from the MetaTrader 5 terminal on YOUR PC.

- Read-only: it only reads price candles from MT5.
- It never sees your MT5 login, password, balance, positions or orders.
- It listens only on your own PC (127.0.0.1:8765). Nothing is uploaded by the Bridge itself; your browser fetches candles from it and sends them to the dashboard.
- Educational tool only.

## How to use
1. Download SnipersBridge.exe from the latest Release (see "Releases" on the right).
2. Open MetaTrader 5 and log in to your broker account.
3. Double-click SnipersBridge.exe and keep its window open.
4. Open the dashboard and choose "MT5 via Bridge" as the source.

## Windows warning (SmartScreen)
The file is not code-signed yet, so Windows may show "Windows protected your PC".
Click "More info", then "Run anyway".

## Requirements
Windows PC with MetaTrader 5 installed and logged in.
Phones cannot use the Bridge (it runs on a PC).
© 2026 Chetan H Jariwala. All rights reserved.
