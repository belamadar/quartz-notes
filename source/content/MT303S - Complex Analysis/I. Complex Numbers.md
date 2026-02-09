### Definition 1.1
**Complex numbers** are objects taking the form $a+ib$, where $a,b\in \mathbb R$ and $i$ satisfies the equation $i^2 = -1$. 
- $a$ is called the **real part** of $a+ib$, written $Re(a+ib)$
- $b$ is called the **imaginary part** $a+ib$, written $Im(a+ib)$
The set of all complex numbers is denoted $\mathbb C$.

$$
\begin{align}
\text{Arithmetic Addition: }& 
(a+ib) + (c+id) = (a+c) + i(b+c) \\
\text{Multiplication: }& (a+ib)\times(c+id) = ac + iad + ibc + i^2 bd
\end{align}
$$

### Definition 1.2
If $z = a+ib$, then the **conjugate** of z, denoted $\overline z$ is $a-ib$.

### Definition 1.3
The **modulus** of $z = a+ib$, denoted $|z|$ is $|z| = \sqrt{a^2 + b^2}$. 
##### Remark:
$|z|$ is the distance of $z$ from $0$ in the Argand diagram (by Pythagoras).

### Lemma 1.4
$z \overline{z} = |z^2|$ 
##### Proof: 
$$
\begin{align}
z \overline{z} =& (a+ib)(a-ib) \\
=& a^2 + iab - iab - i^2 b^2 \\
=& a^2 + b^2 = |z|^2
\end{align}
$$

$$
\begin{align}
&\text{What is } \frac{z}{w} \text{, where } z,w\in \mathbb{C}, w \neq 0? \\
&\text{Starting with the equation } \\
&\frac{\overline w}{\overline w} = 1 \\
&\text{we have} \\
&\frac{z}{w} = \frac{z}{w} \times 1 = \frac{z \overline{w}}{w \overline{w}} = \frac{z \overline{w}}{|w|^2} \\
&\boxed{\therefore \frac{z}{w} = \frac{z \overline{w}}{|w|^2}}
\end{align} 
$$
