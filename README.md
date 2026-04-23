# tgbot
telegram bot，每天自动收集科技变化和热点新闻，分析金融市场走势（注重于a股）
telegram-finance-bot/
│
├── bot/
│   ├── __init__.py
│   ├── config.py
│   ├── telegram_sender.py
│
├── data/
│   ├── news.py
│   ├── stock.py
│
├── analysis/
│   ├── summarize.py
│   ├── market.py
│
├── scheduler/
│   ├── jobs.py
│
├── main.py
├── requirements.txt
├── Dockerfile
├── README.md
├── .env.example
