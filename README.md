# Time Series Methods for Forecasting Volatility

Jeffrey Fowler and Raunak Sood · Time Series Analysis · June 2024

Compares classical volatility forecasting against a deep-learning alternative: exponential
smoothing, a GARCH model, and an LSTM, evaluated on the same equity.

## Finding

**The naive methods win.** For the stock analysed, exponential smoothing and GARCH
outperformed the LSTM. This is the useful result rather than the disappointing one: volatility
is strongly mean-reverting and highly autocorrelated, which is exactly the structure GARCH was
designed around, and a sequence model with far more parameters had no more signal to find.

Reported as measured rather than tuned until the neural model won.

## Files

- `Final Paper 174.pdf` — background, methodology, results
