# My demo page



## input
````{code} markdown
```{tikz}
\draw[thick,->] (0,0) -- (1,2);
\draw[thick,->] (0,0) -- (1,-1);
```
````


## result

```{tikz}
\draw[thick,->] (0,0) -- (1,2);
\draw[thick,->] (0,0) -- (1,-1);
```

```{tikz}
\begin{tikzpicture}
\node[name=node1] {$x$};
\node[left=of node1] {$y$};
\end{tikzpicture}
```

```{tikz}
\tikzset{
  custom_elipse/.style={draw, ellipse}
}
\begin{tikzpicture}
\node[custom_elipse,name=node1] {$x$};
\node[custom_elipse,right=of node1] {$y$};
\end{tikzpicture}
```

