---
{"dg-publish":true,"permalink":"/7-notes/knowledge/monte-carlo-methods/","tags":["uni/bcd"]}
---


![Monte-Carlo methods_loop.png](/img/user/7-notes/knowledge/images/Monte-Carlo%20methods_loop.png)
The first-visit MC method estimates v⇡(s) as the average of the returns following first visits to s, whereas the every-visit MC method averages the returns following all visits to s. These two Monte Carlo (MC) methods are very similar but have slightly di↵erent theoretical properties. First-visit MC has been most widely studied, dating back to the 1940s, and is the one we focus on in this chapter. Every-visit MC extends more naturally to function approximation and eligibility traces, as discussed in Chapters 9 and 12. First-visit MC is shown in procedural form in the box. Every-visit MC would be the same except without the check for St having occurred earlier in the episode.