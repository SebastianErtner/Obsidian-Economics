# Deterministic setting
A strategic game consists of:
* a set of players $N$
* a set of actions $A_i$ for every player $i$
* a [[Preference relations|preference ordering]] $\succeq_i$ over all action profiles $A = \times_{j \in N} A_j$ for every player $i$

Often the preference ordering is replaced by a [[Utility function|utility function]] (requires additionally a finite action set or continuity, see there).

Examples: Chess, Tic-tac-toe

# Uncertain setting
In the presence of uncertainty, the consequences of an action profile are stochastic. There is an additional probability space $\Omega$. The conesuences of an action pair are then $g: A \times \Omega \rightarrow C$ and the preference ordering $\succeq_i$ must capture the preference of individual $i$ over the lotteries associated with action $a \in A_i$.

Usually, such situations are again approached utilizing utility functions under [[Subjective expected utility maximization|expected utility theory]].




Source: Osborne and Rubinstein, A Course in Game Theory