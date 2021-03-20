Combinatorial Optimization: finite but large number of possible solutions

exact vs. heuristic solutions: focus on exact solutions
 - focus on CO algorithms that automatically perform learning on a chosen implicit distribution of problems, by incorporating machine learning components
 - MO/CO might internally use different heuristics - we want to use ML to decide which one: similar instances -> similar solving
 - assumption: real world data is usually somewhat structured
 
 ML techniques:
 - demonstration: Supervised learning/imitation. You can only get as good as your training data
  - optimization goal: minimize distance to expert responses (== ground truth?)
 - experience: reinforcement learning. Is a markov chain (next state depends on current state (and reward). Can discover own strategies. Mostly good if there are no local optima, because it might get stuck?
  - optimization goal: maximize reward
