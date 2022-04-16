In a [[Strategic game|strategic game]], a strategy assignes an action to each information set of the player. The set of all possible pure strategies of a player is $S$.

## Possible properties
### Never best reply
A strategy $s_i \in S_i$ is a "never best reply" if there does not exist a strategy $s_{-i} \in \Delta S_{-i}$ for which $s_i$ is a best reply (best response).
### Rationalizable
A strategy $s_i$ is called "rationalizable", if it is not a "never best reply", i.e. if there exists a strategy $s_{-i} \in \Delta S_{-i}$ such that $s_i \in BR(s_j)$.
### Strictly dominated
A strategy $s_i \in S_i$ is called strictly dominated if there exists another strategy $s_i' \in \Delta S_i$ such that $u_i(s_i, s_j) < u_i(s_i',s_j)$ for all $s_j \in \Delta S_j$.
Being strictly dominated implies never being a best reply (but not the other way around).