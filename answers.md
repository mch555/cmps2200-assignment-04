# CMPS 2200 Assignment 4
## Answers

**Name:**____Maeren Hay_____________________






- **1a.**
$Θ(log_d n)$

- **1b.**
delete min work: $Θ(d log_d n)$
insert work: $Θ(log_d n)$

- **1c.**
$Θ(|E| * log_d|V| + |V| * d log_d |V|)$
- **1d.**
pick $d=m/n$ to make delete min and insert costs equal. Total work is $Θ(2m log_m/n n) = Θ(m*logn/log(m/n))$.
so $Θ(m * 1/ε)=Θ(m)$


- **2a.**
- 
$$\mathbf{k=-1} \quad W = \begin{pmatrix} 0 & -2 & 2 \\ \infty & 0 & 1 \\ \infty & 2 & 0 \end{pmatrix}$$

$$\mathbf{k=0} \quad APSP(i, j, 0) = \begin{pmatrix} 0 & -2 & 2 \\ \infty & 0 & 1 \\ \infty & 2 & 0 \end{pmatrix}$$

$$\mathbf{k=1} \quad APSP(i, j, 1) = \begin{pmatrix} 0 & -2 & -1 \\ \infty & 0 & 1 \\ \infty & 2 & 0 \end{pmatrix}$$

$$\mathbf{k=2} \quad APSP(i, j, 2) = \begin{pmatrix} 0 & -2 & -1 \\ \infty & 0 & 1 \\ \infty & 2 & 0 \end{pmatrix}$$

- **2b.**
relation- The APSP is either the best path that uses intermediates {0,1} or a path that goes through vertex 2, with both subpaths constrained to {0,1}

APSP Formla- APSP(i,j,2)=min(APSP(i,j,1), PASP(i,2,1)+APSP(2,j,1) with only vals from k=0 and k=1

- **2c.**

- **2d.**

- **2e.**



- **3a.**


- **3b.**


- **3c.**
