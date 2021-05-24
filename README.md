# Constant Proportion Portfolio Insurance (CPPI) Valuation

A constant proportion portfolio insurance (CPPI) is a trading strategy where an initial investment is dynamically reallocated between a risky asset and risk-free bond such that a minimum payoff is guaranteed at maturity. The risky asset could be from equities, funds, or commodities.

In upside markets, the strategy allocates more towards the risky asset whereas in downside, the strategy allocates more towards the safe asset. The capital protection feature makes CPPI one of the most popular derivative products. 

The CPPI strategy allows an investor to keep the upside potential of a risky asset by offering a capital guarantee against downside risk. In other words, it allows the investor to expose to upside while protecting against downside. 

As the CPPI strategy is inherently risky and the final payoff is principal-protected, the structure can somewhat be viewed as a zero coupon bond plus a call option on the CPPI strategy.

A notional Portfolio keeps track of any gains or losses from the strategy. Holdings in the notional portfolio are rebalanced on Calculation Dates, according to a predetermined formula. Here Calculation Dates could be beyond Maturity Date due to settlement delay.

A stream of Partial Principal Repayments (PPR) may be paid out of the CPPI structure at PPR Pay Dates over the life of the product. The size of these payments is determined as a fixed percentage of the Fund Account Value (FAV) excluding PPR or a fixed percentage of the Notional on each PPR Valuation Date
.
Due to the complexity of the payoff structure, Monte Carlo simulation is the only practical method for this product. 



References:

https://finpricing.com/lib/EqConvertible.html

https://bitbucket.org/cmrm11/eqcppi/downloads/EqCppi-19.pdf

