# Causal-inference-using-a-novel-instrumental-variable

This paper was my master's thesis paper at University of Wisconsin - Madison.

The objective of this paper is to address the issue of simultaneity between monetary policy
action and contemporaneous stock market returns, to estimate the magnitude of causality.
This paper makes inference from a structural vector autoregression (SVAR) model which includes
variables for monetary policy and stock returns. External instruments are used for
identification; I use the information in the volatility index (VXO) of the Chicago Board Options
Exchange, to instrument for stock market returns, in a monetary policy rule. This identifies
the response of monetary policy to contemporaneous stock returns. Next, the structural
(monetary) shock estimates obtained in the previous equation are used as external instruments
for the monetary policy variable, to identify the response of stock prices to monetary policy
actions. These two estimates are then imposed in a structural VAR with short run restrictions,
to estimate the relationship between the federal funds rate, stock prices, and other macroeconomic
variables. I find a significant negative relationship between tightening of policy rate
and stock price movement in the short run.
