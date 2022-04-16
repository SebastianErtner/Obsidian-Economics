A Nash equilibrium in a [[Strategic game|strategic game]] is an action profile $a^* \in A$ such that for all players $i$ and for all $a_i' \in A_i$:
$$(a_i^*, a_{-i}^*) \succeq_i (a_i', a_{-i}^*)$$
### Best response function
The best response function is the set-valued function
$$B_i(a_{-i}) = \{a_i \in A_i | (a_i,a_{-i}) \succeq_i (a_i',a_{-i}) ~\forall a_i' \in A_i\}$$
Then a Nash equilibrium is an action profile $a^*$ such that $a_i^* \in B_i(a_{-i}^*)$ for all $i \in N$.

### Existence of NE
Using a [[Math for microeconomics#Kakutani's fixed point theorem|fixed point theorem]]  it can be shown that under those conditions (convexity and compactness of $A$) a Nash equilibrium exists as a fixed point $a^* \in B(a^*)$ in the general best response function that is the Cartesian product of the individual best response functions.

There are different proofs for existence with different conditions, e.g. a finite action set.


## strict NE
A strict NE is a NE where no player can deviate to another alternative that gives them the same payoff.

## Equilibrium refinement
These constitute a further selection among equilibria that mainly put discipline on the off equilibrium path believes.

### Intuitive criterion
If an off-eq path action is dominated for one type of player and not for at least one other, then there can be no probability mass on believing that it is played by the first type.