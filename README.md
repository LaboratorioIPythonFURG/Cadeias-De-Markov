## Problema 

Sabendo que $s_0$ é a população inicial cidade e $r_0$ a do subúbio
$$
x_0=
\begin{bmatrix}
r_0\\
s_0
\end{bmatrix}
$$
e que a estimativa é que 5% da polpoulação da cidade se mova para o subúrbio
$$
\begin{bmatrix}
.95r_0\\
.05r_0
\end{bmatrix}
=
r_0
\begin{bmatrix}
.95\\
.05
\end{bmatrix}
$$
e que a população do subúrbio para a cidade
$$
\begin{bmatrix}
.97s_0\\
.03s_0
\end{bmatrix}
=
s_0
\begin{bmatrix}
.97\\
.03
\end{bmatrix}
$$
Logo,
$$
\left[\begin{array}{l}
r_1 \\
s_1
\end{array}\right]=r_0\left[\begin{array}{l}
.95 \\
.05
\end{array}\right]+s_0\left[\begin{array}{l}
.03 \\
.97
\end{array}\right]=\left[\begin{array}{ll}
.95 & .03 \\
.05 & .97
\end{array}\right]\left[\begin{array}{l}
r_0 \\
s_0
\end{array}\right]
$$
Assim, 
$$
x_k=A  x_{k+1}
$$
Ou, 
$$
x_kA^{-1}=x_{k+1}
$$
Sabendo que a população da cidade nos anos $2000$ era de $600000$ habitantes e do subúrbio $400000$. Qual será a previsão para o ano de $2002$?
