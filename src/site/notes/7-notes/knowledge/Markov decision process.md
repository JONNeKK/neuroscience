---
{"dg-publish":true,"permalink":"/7-notes/knowledge/markov-decision-process/","tags":["uni/bcd"]}
---

Each transformation of states with an action $a$ just depends on the last state.
![Markov decision process_conditional.png](/img/user/7-notes/knowledge/images/Markov%20decision%20process_conditional.png)


what cannot be done with MDPs:
- time dependent stuff
- computational cost

Discount factor $\gamma$ for continuous tasks:
- between 0 and 1
- Receiving future reward may matter less. 

action selection is defined by a [[7-notes/knowledge/policy\|policy]].