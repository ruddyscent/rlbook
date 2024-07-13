# Exercise 2.1: ε-greedy action selection

In ε-greedy action selection, the algorithm chooses the greedy action with a probability of \(1 - \varepsilon + \frac{\varepsilon}{\text{number of actions}}\) and selects a non-greedy (exploratory) action with a probability of \(\frac{\varepsilon}{\text{number of actions}}\).

For the case of two actions (\(\text{number of actions} = 2\)) and \(\varepsilon = 0.5\), the probability of selecting the greedy action is:

\[1 - \varepsilon + \frac{\varepsilon}{\text{number of actions}}\]

Substitute the values:

\[1 - 0.5 + \frac{0.5}{2} = 1 - 0.5 + 0.25 = 0.75\]

So, when ε is 0.5 and there are two actions, the probability of selecting the greedy action is 0.75 or 75%.