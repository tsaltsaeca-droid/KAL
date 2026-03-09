1. Buatlah 4 persamaan linear dengan 4 variable hingga nilai $x_1=1, x_2=2, x_3=3, x_4=4$

$x_1 + x_2 + x_3 + x_4 = 10\\
x_1 + x_2 + x_3 - x_4 = 2\\
x_1 + x_2 + x_3 + x_4 = 4\\
x_1 - x_2 + x_3 + x_4 = 6$

$$
\begin{aligned}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
1&1&1&-1&2\\
1&1&-1&1&4\\
1&-1&1&1&6
\end{array}
\right]

&\xrightarrow{R_2-R_1}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&0&0&-2&-8\\
1&1&-1&1&4\\
1&-1&1&1&6
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_3-R_1}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&0&0&-2&-8\\
0&0&-2&0&-6\\
1&-1&1&1&6
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_4-R_1}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&0&0&-2&-8\\
0&0&-2&0&-6\\
0&-2&0&0&-4
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_2 \leftrightarrow R_4}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&-2&0&0&-4\\
0&0&-2&0&-6\\
0&0&0&-2&-8
\end{array}
\right]

\\[10pt]

&\xrightarrow{-\frac12R_2}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&1&0&0&2\\
0&0&-2&0&-6\\
0&0&0&-2&-8
\end{array}
\right]

\\[10pt]

&\xrightarrow{-\frac12R_3}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&1&0&0&2\\
0&0&1&0&3\\
0&0&0&-2&-8
\end{array}
\right]

\\[10pt]

&\xrightarrow{-\frac12R_4}

\left[
\begin{array}{cccc|c}
1&1&1&1&10\\
0&1&0&0&2\\
0&0&1&0&3\\
0&0&0&1&4
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_1-R_2-R_3-R_4}

\left[
\begin{array}{cccc|c}
1&0&0&0&1\\
0&1&0&0&2\\
0&0&1&0&3\\
0&0&0&1&4
\end{array}
\right]

\end{aligned}
$$

2. Buatlah 5 persamaan linear dengan 5 variable hingga nilai $x_1=1, x_2=2, x_3=3, x_4=4, x_5=5$

$x_1 + x_2 + x_3 + x_4 + x_5 = 15\\
x_1 + x_2 + x_3 + x_4 - x_5 = 5\\
x_1 + x_2 + x_3 - x_4 + x_5 = 7\\
x_1 + x_2 - x_3 + x_4 + x_5 = 9\\
x_1 - x_2 + x_3 + x_4 + x_5 = 11$

$$
\begin{aligned}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
1&1&1&1&-1&5\\
1&1&1&-1&1&7\\
1&1&-1&1&1&9\\
1&-1&1&1&1&11
\end{array}
\right]

&\xrightarrow{R_2-R_1}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
0&0&0&0&-2&-10\\
1&1&1&-1&1&7\\
1&1&-1&1&1&9\\
1&-1&1&1&1&11
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_3-R_1}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
0&0&0&0&-2&-10\\
0&0&0&-2&0&-8\\
1&1&-1&1&1&9\\
1&-1&1&1&1&11
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_4-R_1}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
0&0&0&0&-2&-10\\
0&0&0&-2&0&-8\\
0&0&-2&0&0&-6\\
1&-1&1&1&1&11
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_5-R_1}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
0&0&0&0&-2&-10\\
0&0&0&-2&0&-8\\
0&0&-2&0&0&-6\\
0&-2&0&0&0&-4
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_2 \leftrightarrow R_5,\; R_3 \leftrightarrow R_4}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
0&-2&0&0&0&-4\\
0&0&-2&0&0&-6\\
0&0&0&-2&0&-8\\
0&0&0&0&-2&-10
\end{array}
\right]

\\[10pt]

&\xrightarrow{-\frac12R_2,\;-\frac12R_3,\;-\frac12R_4,\;-\frac12R_5}

\left[
\begin{array}{ccccc|c}
1&1&1&1&1&15\\
0&1&0&0&0&2\\
0&0&1&0&0&3\\
0&0&0&1&0&4\\
0&0&0&0&1&5
\end{array}
\right]

\\[10pt]

&\xrightarrow{R_1-R_2-R_3-R_4-R_5}

\left[
\begin{array}{ccccc|c}
1&0&0&0&0&1\\
0&1&0&0&0&2\\
0&0&1&0&0&3\\
0&0&0&1&0&4\\
0&0&0&0&1&5
\end{array}
\right]

\end{aligned}
$$