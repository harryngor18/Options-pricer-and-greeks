# Options Pricer & Greeks (Black-Scholes)

Petit projet Python où j'implémente le modèle de Black-Scholes pour pricer des options européennes (Call/Put) et calculer les Greeks (Delta, Gamma, Vega, Theta, Rho).

Je l'ai fait pour m'entraîner en dehors des cours (M1 Finance, IÉSEG), et pour appliquer un peu de code à des concepts qu'on voit en marchés financiers.

Dans un premier temps, pricing et Greeks sur un cas simple (S = K = 100, maturité 1 an, vol 20%), avec les graphiques qui montrent comment chaque Greek évolue quand le spot bouge.

Ensuite, je reprends tout ça sur des vraies données, en récupérant l'historique de NVIDIA avec yfinance, en estimant sa volatilité réelle, puis je price un Call et un Put dessus, avec le payoff à l'échéance.

## Stack

Python, NumPy, SciPy, Matplotlib, yfinance — le tout dans un notebook Jupyter.

## Pour lancer

```bash
pip install numpy scipy matplotlib yfinance jupyter
jupyter notebook Options_pricer_and_greeks.ipynb
```

---
Harry NGOR — [LinkedIn](http://www.linkedin.com/in/harry-ngor-a67311265)
