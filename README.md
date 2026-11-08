# EGE trainer bot

Telegram bot for preparing for task 19 of the EGE profile-level math exam (number theory and logic problems). Final project of Yandex Lyceum.

## Features

- Theory on 15 topics: divisibility, remainders, GCD and LCM, Diophantine equations, invariants, game theory, graphs, the pigeonhole principle and more
- Practice mode with automatic answer checking and explanations for mistakes
- User profile with statistics and a top-10 leaderboard
- Links to official practice materials (FIPI open task bank, Reshu EGE) and curated channels
- Suggestions from users are saved to the database

## Tech stack

Python, pyTelegramBotAPI, SQLAlchemy, SQLite

## Running locally

```bash
pip install -r requirements.txt
export BOT_TOKEN="your-telegram-bot-token"
export WEATHER_API_KEY="your-weatherapi-key"   # optional, for the weather button
python init_db.py   # fill the database with theory and questions
python main3.py
```
