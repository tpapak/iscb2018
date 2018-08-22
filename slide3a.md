<span class="heading">
projection $\mathbf{H}$ matrix
</span>
<span class="content">

- Resembles the **hat matrix** in a linear regression model
- Each row $h\_{AB}$ refers to a single comparison

$\hat{\theta}^N = \mathbf{H} \hat{\theta}^D$

$
\left(
\begin{matrix}
\hat{\theta}\_{AB}^N \\\ 
\hat{\theta}\_{AC}^N \\\ 
\hat{\theta}\_{AD}^N \\\ 
\hat{\theta}\_{BC}^N \\\ 
\hat{\theta}\_{BD}^N \\\ 
\hat{\theta}\_{CD}^N
\end{matrix}
\right)
=
\left(
\begin{matrix}
h\_{AB}^{AB} & h\_{AC}^{AB} & h\_{AD}^{AB} & h\_{BD}^{AB} & h\_{CD}^{AB}  \\\
h\_{AB}^{AC} & h\_{AC}^{AC} & h\_{AD}^{AC} & h\_{BD}^{AC} & h\_{CD}^{AC}  \\\
h\_{AB}^{AD} & h\_{AC}^{AD} & h\_{AD}^{AD} & h\_{BD}^{AD} & h\_{CD}^{AD}  \\\
h\_{AB}^{BC} & h\_{AC}^{BC} & h\_{AD}^{BC} & h\_{BD}^{BC} & h\_{CD}^{BC}  \\\
h\_{AB}^{BD} & h\_{AC}^{BD} & h\_{AD}^{BD} & h\_{BD}^{BD} & h\_{CD}^{BD}  \\\
h\_{AB}^{CD} & h\_{AC}^{CD} & h\_{AD}^{CD} & h\_{BD}^{CD} & h\_{CD}^{CD}
\end{matrix}
\right)
\times
\left(
\begin{matrix}
\hat{\theta}\_{AB} \\\ 
\hat{\theta}\_{AC} \\\ 
\hat{\theta}\_{AD} \\\ 
\hat{\theta}\_{BD} \\\ 
\hat{\theta}\_{CD}
\end{matrix}
\right)
$

</span>

<footer>
Theodore Papakonstantinou - ISCB 2018 - 3a
</footer>
