---
{"dg-publish":true,"permalink":"/7-notes/knowledge/ion-channel/","tags":["uni/fmb/signalling"]}
---

###### What they are
- Lipid protein molecules (hydrophobic from the inside) which span the [[membrane\|membrane]] and form pores or gates through which ions can pass
- They can open and close to control the movement of ions through the channel
- only specific ions (anions or cations) pass through a specific channel (e.g. sodium or potassium)

###### patch clamp recording
Basically isolating with a gigaohm seal one ion channel with a pipette and recording the current passing through. This can be changed by changing the voltage across the patch of membrane.
→ There are ion channel transitions that occur between open and closed states (basically instantaneous). The time a channel is open are seemingly random and it is possible to have open states with more than one current level
Can be approximated by an [[Markov model\|Markov model]]


###### modes of channel activation
Either by physical changes in the membrane or by attaching [[7-notes/knowledge/ligand\|ligand]]. The latter can happen on both sides of the membrane. Physical changes can be for instance stretching of the membrane (e.g. in mechanoreceptors in the skin) or voltage-activation (e.g. voltage-sensitive sodium channels, important for the rising phase of [[7-notes/knowledge/action potential\|APs]]). This classification is not rigid and multiple activation modes can exist for the same channel.


###### effect of membrane potential on channel current
![ion channel_ohmic.png](/img/user/7-notes/knowledge/images/ion%20channel_ohmic.png)
Looking at a potassium channel with equal concentration of potassium on both sides of the channel we recognize a linear (or 'ohmic') dependence between channel current (I) and [[7-notes/knowledge/membrane potential\|membrane potential]] as voltage (V):
$$
I=gV.
$$
$g$ is the channel conductance (a characteristic), measured in Siemens \[S=A/V]. It depends on two main factors:
- channel permeability
- concentration of ions in the region of the channel

Changing the balance of ion concentration on both sides makes a significant difference:
![ion channel_unequal concentration.png](/img/user/7-notes/knowledge/images/ion%20channel_unequal%20concentration.png)
The dependence is no longer ohmic and has an [[7-notes/knowledge/equilibrium potential\|equilibrium potential]]. Approximating the relationship between current $I_\text{K}$, channel conductance $g_\text{K}$, membrane potential $V_\text{m}$ and equilibrium potential $E_\text{K}$ as linear near the equilibrium potential:
$$
I_{\text{K}}= g_{\text{K}}(V_{\text{m}}-E_{\text{K}}).
$$

