LU decomposition presents a square matrix $A$ as a product of unit lower triangular matrix $L$ and upper triangular matrix $U$.
$$
A=LU=\begin{bmatrix}
1 & & & \\
l_{2,1} & 1 & &\\
\vdots & \ddots & \ddots & \\
l_{n,1} & \cdots & l_{n,n-1} & 1
\end{bmatrix}
\begin{bmatrix}
u_{1,1} & u_{1,2} & \cdots & u_{1,n} \\
& u_{2,2} & \cdots & u_{2,n} \\
& & \ddots & \vdots \\
& & & u_{n,n}
\end{bmatrix}
$$
Gaussian elimination without pivoting is equivalent to performing an LU decomposition of the coefficient matrix $A$.
$$
\begin{bmatrix}
a_{1,1}^{(1)} & a_{1,2}^{(1)} & \cdots & a_{1,n}^{(1)} \\
a_{2,1}^{(1)} & a_{2,2}^{(1)} & \cdots & a_{2,n}^{(1)} \\
\vdots & \vdots & & \vdots \\
a_{n,1}^{(1)} & a_{n,2}^{(1)} & \cdots & a_{n,n}^{(1)} \\
\end{bmatrix}
=
\left[
\begin{array}{c}
1 \\
\hline
m_{2,1} \\
\vdots \\
m_{n,1}
\end{array}
\right]
\left[
\begin{array}{c|ccc}
a_{1,1}^{(1)} & a_{1,2}^{(1)} & \cdots & a_{1,n}^{(1)}
\end{array}
\right]
+
\left[
\begin{array}{c|ccc}
0 & & O & \\
\hline
& a_{2,2}^{(2)} & \cdots & a_{2,n}^{(2)} \\
O & \vdots & & \vdots \\
& a_{n,2}^{(2)} & \cdots & a_{n,n}^{(2)}
\end{array}
\right]
$$
$$
\left[
\begin{array}{c|ccc}
0 & & O & \\
\hline
& a_{2,2}^{(2)} & \cdots & a_{2,n}^{(2)} \\
O & \vdots & & \vdots \\
& a_{n,2}^{(2)} & \cdots & a_{n,n}^{(2)}
\end{array}
\right]
=
\left[
\begin{array}{c}
0 \\
\hline
1 \\
\hline
m_{3,2} \\
\vdots \\
m_{n,2}
\end{array}
\right]
\left[
\begin{array}{c|c|ccc}
0 & a_{2,2}^{(2)} & a_{2,3}^{(2)} & \cdots & a_{2,n}^{(2)}
\end{array}
\right]
+
\left[
\begin{array}{c|c|c}
0 & 0 & O \\
\hline
0 & 0 & O \\
\hline
O & O & \begin{matrix}
  a_{3,3}^{(3)} & \cdots & a_{3,n}^{(3)} \\
  \vdots & & \vdots \\
  a_{n,3}^{(3)} & \cdots & a_{n,n}^{(3)}
  \end{matrix}
\end{array}
\right]
$$
$$
A^{(k)} =
\begin{bmatrix}
O_{k-1,k-1} & O_{k-1,n-k+1} \\
O_{n-k+1,k-1} & (a_{i,j}^{(k)} \mid k \le i, j \le n)
\end{bmatrix}
$$
$$
\boldsymbol{l}_k = (\overbrace{0, \cdots, 0}^{k-1}, 1, m_{k+1,k}, \cdots, m_{n,k})^\mathrm{T}
$$
$$
\boldsymbol{u}_k = (\overbrace{0, \cdots, 0}^{k-1}, a_{k,k}^{(k)} , a_{k,k+1}, \cdots, a_{n,k})^\mathrm{T}
$$
$$
A^{(k)} = \boldsymbol{l}_k \boldsymbol{u}_k^\mathrm{T} + A^{(k+1)}
$$
$$
A = \sum_{k=1}^{n} \boldsymbol{l}_k \boldsymbol{u}_k^\mathrm{T}
$$
%%
$$
A
=
\left[
\begin{array}{cccc}
\boldsymbol{l}_1 & \boldsymbol{l}_2 & \cdots & \boldsymbol{l}_n
\end{array}
\vphantom{
\begin{array}{c}
\boldsymbol{u}_1^\mathrm{T} \\
\hline
\boldsymbol{u}_2^\mathrm{T} \\
\hline
\vdots \\
\hline
\boldsymbol{u}_n^\mathrm{T}
\end{array}
}
\right]
\left[
\begin{array}{c}
\boldsymbol{u}_1^\mathrm{T} \\
\hline
\boldsymbol{u}_2^\mathrm{T} \\
\hline
\vdots \\
\hline
\boldsymbol{u}_n^\mathrm{T} \\
\makebox[0pt]{$\boldsymbol{x}_n^\mathrm{T}$}
\hphantom{
\begin{array}{cccc}
\boldsymbol{l}_1 & \boldsymbol{l}_2 & \cdots & \boldsymbol{l}_n
\end{array}
}
\end{array}
\right]
$$%%
$$
A
=
\left[
\begin{array}{cccc}
\boldsymbol{l}_1 & \boldsymbol{l}_2 & \cdots & \boldsymbol{l}_n
\end{array}
\vphantom{
\begin{array}{c}
\boldsymbol{u}_1^\mathrm{T} \\
\hline
\boldsymbol{u}_2^\mathrm{T} \\
\hline
\vdots \\
\hline
\boldsymbol{u}_n^\mathrm{T}
\end{array}
}
\right]
\left[
\begin{array}{c}
\qquad \quad \boldsymbol{u}_1^\mathrm{T} \qquad \quad \\
\hline
\boldsymbol{u}_2^\mathrm{T} \\
\hline
\vdots \\
\hline
\boldsymbol{u}_n^\mathrm{T} \\
\end{array}
\right]
$$
$$
A
=
\begin{bmatrix}
\boldsymbol{l}_1 & \boldsymbol{l}_2 & \cdots & \boldsymbol{l}_n \\
\end{bmatrix}
\begin{bmatrix}
\boldsymbol{u}_1^\mathrm{T} \\
\hline
\boldsymbol{u}_2^\mathrm{T} \\
\hline
\vdots \\
\hline
\boldsymbol{u}_n^\mathrm{T}
\end{bmatrix}
=
\begin{bmatrix}
1 & & & \\
m_{2,1} & 1 & & \\
\vdots & \ddots & \ddots & \\
m_{n,1} & \cdots & m_{n,n-1} & 1 \\
\end{bmatrix}
\begin{bmatrix}
a_{1,1}^{(1)} & a_{1,2}^{(1)} & \cdots & a_{1,n}^{(1)} \\
& a_{2,2}^{(1)} & \cdots & a_{2,n}^{(1)} \\
& & \ddots & \vdots \\
& & & a_{n,n}^{(n)}
\end{bmatrix}
$$
$$
|A|_{1\cdots k}^{1 \cdots k}
=
\prod_{i=1}^k a_{i,i}^{(i)} \quad (k = 1, \dots, n)
$$
$$
a_{k,k}^{(k)} \neq 0 \quad (k = 1, \dots, n)
\iff
|A|_{1 \dots k}^{1 \dots k} \neq 0 \quad (k=1, \dots, n)
$$
$$
l_{i,k}
=
|A|_{1, \dots, k-1,k}^{1, \dots, k-1, i}
/
|A|_{1, \dots, k}^{1, \dots, k}
\quad (i \gt k)
$$
$$
u_{k,j}
=
|A|_{1, \dots, k-1,j}^{1, \dots, k-1,k}
/
|A|_{1, \dots, k-1}^{1, \dots, k-1}
\quad (k \le j)
$$
