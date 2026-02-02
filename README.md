# SmartBet
Value bet tools
# Value Bets Analyzer

Projeto para identificar **value bets** em apostas desportivas usando SQLite + Python.

## Funcionalidades
- Armazenamento de jogos e odds em SQLite
- Cálculo de value = (prob_real * odd) - 1
- Filtro de bets com EV positivo

## Instalação
1. Clone o repo: `git clone https://github.com/teuuser/value-bets-analyzer.git`
2. Instala dependências: `pip install -r requirements.txt`
3. Corre o exemplo: `python src/value_calculator.py`

## Dependências
- Python 3.10+
- pandas
- pyyaml (para config)

## Dados
- Usa datasets free: football-data.co.uk, The Odds API (free tier)

## Licença
MIT
