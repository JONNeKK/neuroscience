---
{"dg-publish":true,"permalink":"/7-notes/knowledge/motor-control/","tags":["uni/bcd","uni/fmb/mc"]}
---

# Functions of motor control
This is the way we interact with the environment:
- communication
- tool use
- moving
- modifying of the environment
# Types of movement
- voluntary: e.g. manipulating objects, speech under conscious control, involve choices incl. the choice not to act →  highly adaptive and complex, no external input required
- thythmic: e.g. breathing, walking → largely controlled autonomously but can also be controlled voluntarily
- reflexes: e.g. cough, [[7-notes/knowledge/knee-jerk reflex\|knee-jerk reflex]] → involuntary, triggered by external stimuli, relatively stereotyped
# Sensory motor loop
Motor control is adjusted through sensory feedback that can be either vision or proprioception.
![motorcontrol_loop.png](/img/user/7-notes/knowledge/images/motorcontrol_loop.png)
Arising problems are sensory delay, ranging from 80 to 150 ms for porprioceptive and visual feedback. Motor delay for eye and arm movement can be as short as 50ms and 300ms respectively.
This is to short for sensory feedback in the initial phase of movement.

In Addition there can be noise: perceptual and motor noise, as well as environmental uncertainty.
# Why is motor control difficult?
### learning and adaption
The relationship between the given motor commands and the motion of limbs changes:
- limbs, bones and muscle mass can change
- disease affecting muscles
- changed in tools, objects, etc..
→ constant learning and adaption is needed
### redundancy
A specified high-level task can be performed in various low-level detailed movements. The muscle activation pattern isn't specified in a symbolic task e.g. grabbing a mug.
### non-linear transformations
The transformation of a desired output into motor commands is non linear, e.g. a linear movement line does not entail linear motor commands.
### degrees of freedom
The human body has >600 muscles, every movement requires multiple of thos muscles. The number of different movement patterns increases exponentially
→ curse of dimensionality

[[7-notes/knowledge/feed-forward control\|feed-forward control]]
[[7-notes/knowledge/feed-back control\|feed-back control]]
[[7-notes/knowledge/optimal control\|optimal control]]
# Flashcards
What are the functions of motor control? :: communication, tool use, movement, modifying the environment
What types of movement are there? :: voluntary, rhythmic, reflexes
What is a voluntary movement? :: 