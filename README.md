# SmartBet
Value bet tools
# Value Bets Analyzer

Project to identify value bets in sports betting using SQLite + Python.


Features:
Storage of matches and odds in SQLiteValue calculation = $(prob\_real \times odd) - 1$Filtering for positive EV (Expected Value) bets

Installation:
Clone the repo: git clone https://github.com/youruser/value-bets-analyzer.gitInstall 

dependencies: pip install -r requirements.txtRun the example: python src/value_calculator.pyDependenciesPython 3.10+pandaspyyaml (for config)

Data:
Uses free datasets: football-data.co.uk, The Odds API (free tier)

License
MIT
