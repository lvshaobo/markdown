##convex optimization problems
$$
\begin{align}
  \text{minimize} &\quad f(x)\\
  \text{s.t.} 	  &\quad x\in C\\
\end{align}
$$

where f is a convex function, C is a convex set, and x is the optimization variable. However,
since this can be a little bit vague, we often write it as

$$
\begin{align}
  \text{minimize} &\quad f(x)\\
  \text{s.t.} 	  &\quad g_i(x)\le 0, i=1,\cdots, m\\
                  &\quad h_i(x)=0, i=1,\cdots, p\\
\end{align}
$$

where $f$ is a convex function, $g_i$ are convex functions, and $h_i$ are affine functions, and $x$ is the optimization variable.
Is it imporant to note the direction of these inequalities: a convex function $g_i$ must be less than zero. ==[from the definition of *convex set*]==
