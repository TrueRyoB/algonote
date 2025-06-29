[[状態圧縮]]と[[メモ化]]を伴う
漸化式を作ろう
$$
\begin{equation} 
	E = 
	\begin{cases} 
		\frac{1}{p} \\ 
		\sum_{i=0}^k a_i P[c_i] \\
		p_i (E[i-k]+1)
	\end{cases} 
\end{equation} 
$$

この方程式に従えばあんまりミスることない
[[アーベルの総和公式]]で計算しやすくいしょう