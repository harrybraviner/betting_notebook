Kelly Betting in Common Misconception Quiz
==========================================

I made [this](./restricted_bets.ipynb) python notebook to experimentally test the idea that the 'Common Misconceptions' quiz at [clearerthinking.org](clearerthinking.org) does not assume the optimal policy for betting.

Specifically, you begin with 100 points. On each question you make stake between 0 and 10 points.
This evaluation at the end of the quiz seems to assume that you staked `2 p - 1` on each question when your confidence of getting the question correct was `p`.
This is almost certainly not the best strategy - betting a constant stake of 10 usually beats this.

