# VaR Investigation


**The purpose of this Jupyter notebook is to understand Value-at-Risk backtesing methods employed in `Python`.** This is also the only project that is described (theoretically) in detail and that has a substantial amount of argumentation. Be aware that the main purpose was to learn `Python` and not on providing theoretically sound argumentation for the different plots and tables. 

Therefore, the general investigation leads to some simple conclusions that have been empirically observed before: More complex GARCH-based VaR models provides better adequate forecasts as opposed to the Gaussian distribution. Especially for the 99% VaR, the GARCH model passes the Basel Traffic-light test and provides with substantially less VaR violations than the Gaussian distribution. The analysis ends with a large-scale backtest investigation on more than 2000+ equities and further strengthens the same conclusions done in the prior analysis. 

The backtest functions are found under the *Supporting functions* in the Jupyter notebook. The traffic-light test is done ad-hoc and is nicely presented with a graph in the first part of the analysis. 
