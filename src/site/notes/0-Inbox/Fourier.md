---
{"dg-publish":true,"permalink":"/0-inbox/fourier/","tags":["uni/qm1"]}
---

# The concept
Since in neuroscience there are often oscillating signals (think EEG, the brain-wave oscillations of $\theta$-, $\gamma$-rhythms etc...), we want to know what frequencies are represented in the given signal. And as a practical 'application', remember the Neurophysiology course where we had to do exactly that. 
# The basis
Before thinking about Neurophysiology too long, think about a vector: $\begin{pmatrix}a\\ b\end{pmatrix}$. Hopefully at some point you learned that we can also write this vector as
$$
\begin{pmatrix}a\\ b\end{pmatrix}=a\cdot\begin{pmatrix}1\\ 0\end{pmatrix} + b\cdot\begin{pmatrix}0\\ 1\end{pmatrix}.
$$
In fact every 2-dimensional vector can be written like that. So every vector only relies on two vectors: $\begin{pmatrix}1\\ 0\end{pmatrix}$ and $\begin{pmatrix}0\\ 1\end{pmatrix}$. Those two vectors form a basis, e.g. every vector can be uniquely written as a linear combination of these two. For a 3-dimensional vector we need a basis with three vectors in it ($\begin{pmatrix}1\\ 0\\0\end{pmatrix}$,$\begin{pmatrix}0\\ 1\\0\end{pmatrix}$ and $\begin{pmatrix}0\\ 0\\1\end{pmatrix}$), For 4-dimensi... you get the point. To come back to our EEG-signal: it would be nice to write our signal as a unique combination of different frequencies.
# The frequencies
To get on the same page what a frequency means, we defined is as $\omega$ [Hz] and visualize it with the help of cosines as $\cos(\omega t)$. So for $\omega = 0.5,1,2$:
![Fourier_cosines.png](/img/user/7-notes/knowledge/images/Fourier_cosines.png)
So our unique combination of different frequencies for our signal $f(x)$ would look like this:
$$
f(t)=a+b\cdot\cos(\omega_{1}t) + c\cdot\cos(\omega_{2}t) + d\cdot\cos(\omega_{3}t) + ...
$$
When comparing this to our vector basis, we have an additional constant factor $a$, and instead of vectors we have cosines. To make our lives a bit easier we say that $\omega_{1}=1\cdot\omega$, $\omega_{2}=2\cdot\omega$, $\omega_{3}=3\cdot\omega$, etc... and instead of $a$, $b$, etc... we enumerate these constants:
$$
f(t)=C_{0}+C_{1}\cdot\cos(1\cdot\omega t) + C_{2}\cdot\cos(2\cdot\omega t) + ... = C_{0} + \sum\limits_{n=1}^{\infty}C_{n}\cdot\cos(n\cdot\omega t+\theta_{n}).
$$
To be extra fancy we also let the individual cosines move to the left or right by adding the factors $\theta_{n}$. The amplitudes of each cosine are defined by $C_{n}$.
### Does that really work?
Yeah it does:
![Fourier_proof.png](/img/user/7-notes/knowledge/images/Fourier_proof.png)
For some functions you just need infinitely many cosines.
# The Fourier-series
We already have the cosine-Fourier-series:
$$
f(t)=C_{0} + \sum\limits_{n=1}^{\infty}C_{n}\cdot\cos(n\cdot\omega t+\theta_{n}).
$$
There are other equal forms including one with cosines and sines:
$$
f(t)=C_{0}+\sum\limits_{n=1}^{\infty}C_{n}\cdot \cos(n\cdot\omega t) + \sum\limits_{n=1}^{\infty}D_{n}\cdot\sin(n\cdot\omega t),
$$
where there is no need to put in the phase. However an interesting one is where we replace the cosine with an exponential:
cos

