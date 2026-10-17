
# ShoppingBot

Ein Telegram-Bot zur Erstellung und Verwaltung von Einkaufslisten.

## Funktionen

- Einkaufslisten erstellen
- Produkte zur Liste hinzufügen
- Vorhandene Produkte bearbeiten
- Gekaufte Produkte markieren
- Interaktive Telegram-Tastaturen verwenden
- Benutzerinteraktionen mit einer Finite-State Machine (FSM) verwalten

## Technologien

- Python
- aiogram 3
- Asynchrone Programmierung mit asyncio
- Telegram Bot API
- python-dotenv zur Verwaltung von Umgebungsvariablen

## Technische Umsetzung

Der Bot verarbeitet Nachrichten und Callback-Queries über aiogram.
Der aktuelle Zustand und die Einkaufsliste werden mit FSMContext verwaltet.

Das Bot-Token wird über eine `.env`-Datei geladen und nicht direkt im Quellcode gespeichert.

## Ausführen

1. Python installieren.
2. Abhängigkeiten installieren:

   ```bash
   py -m pip install aiogram python-dotenv
   ```

3. Eine `.env`-Datei im Projektordner erstellen:

   ```env
   BOT_TOKEN=dein_telegram_bot_token
   ```

4. Das Python-Skript starten.

## Hinweis

Der Bot läuft aktuell lokal auf dem Computer, auf dem das Skript ausgeführt wird.
Für einen dauerhaften Betrieb ist ein Hosting erforderlich.
