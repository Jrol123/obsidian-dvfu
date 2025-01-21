---
author: Громыко Артём Артурович
group: Б9122-02.03.01сцт
tags:
  - Study
---
# Диффуры IDZ 1 (796-812)
## 796 
$$
\begin{cases}
\mathsf{x'=x-y+z} \\
\mathsf{y'=x+y-z} \\
\mathsf{z'=2x - y}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{1-\lambda} && \mathsf{-1} && \mathsf{1} \\
\mathsf{1} && \mathsf{1-\lambda} && \mathsf{-1} \\
\mathsf{2} && \mathsf{-1} && \mathsf{-\lambda}
\end{pmatrix}
$$
$$\lambda_1=1\quad \lambda_2=2\quad \lambda_3 = - 1$$
$$(1)
\begin{cases}
\mathsf{-\beta+\gamma=0} \\
\mathsf{\alpha-\gamma=0} \\
\mathsf{2\alpha-\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\beta=\gamma} \\
\mathsf{\alpha=\gamma} \\
\mathsf{2\alpha-\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-\alpha-\beta+\gamma=0} \\
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{2\alpha-\beta-2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=\gamma} \\
\mathsf{\beta=0} \\
\mathsf{2\alpha-2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$

$$(3)
\begin{cases}
\mathsf{2\alpha-\beta+\gamma=0} \\
\mathsf{\alpha+2\beta-\gamma=0} \\
\mathsf{2\alpha-\beta+\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{-5\beta+3\gamma=0} \\
\mathsf{3\alpha+\beta=0} 
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=-1} \\
\mathsf{\beta=3} \\
\mathsf{\gamma=5}
\end{cases}
$$

$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{1}\\ {1}\\ {1}\end{pmatrix} e^{t} + 
C_1 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} e^{2t} + 
C_2 \begin{pmatrix}{-1}\\ {3}\\ {5}\end{pmatrix} e^{-t}
$$
## 797

$$
\begin{cases}
\mathsf{x'=x-2y-z} \\
\mathsf{y'=-x+y+z} \\
\mathsf{z'=x - z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{1-\lambda} && \mathsf{-2} && \mathsf{-1} \\
\mathsf{-1} && \mathsf{1-\lambda} && \mathsf{1} \\
\mathsf{1} && \mathsf{0} && \mathsf{-1-\lambda}
\end{pmatrix}
$$
$$\lambda_1=0\quad \lambda_2=2\quad \lambda_3 = - 1$$
$$(1)
\begin{cases}
\mathsf{\alpha-2\beta-\gamma=0} \\
\mathsf{-\alpha+\beta+\gamma=0} \\
\mathsf{\alpha-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-\alpha-2\beta-\gamma=0} \\
\mathsf{-\alpha-\beta+\gamma=0} \\
\mathsf{\alpha-3\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=3} \\
\mathsf{\beta=-2} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(3)
\begin{cases}
\mathsf{2\alpha-2\beta-\gamma=0} \\
\mathsf{-\alpha+2\beta+\gamma=0} \\
\mathsf{\alpha=0}
\end{cases} \iff
\begin{cases}
\mathsf{-2\beta-\gamma=0} \\
\mathsf{\alpha=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=-2}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} + 
C_1 \begin{pmatrix}{3}\\ {-2}\\ {1}\end{pmatrix} e^{2t} + 
C_2 \begin{pmatrix}{0}\\ {1}\\ {-2}\end{pmatrix} e^{-t}
$$
## 798

$$
\begin{cases}
\mathsf{x'=2x-y+z} \\
\mathsf{y'=x+2y-z} \\
\mathsf{z'=x-y+2z}
\end{cases}
$$

$$\begin{pmatrix}
\mathsf{2-\lambda} && \mathsf{-1} && \mathsf{1} \\
\mathsf{1} && \mathsf{2-\lambda} && \mathsf{-1} \\
\mathsf{1} && \mathsf{-1} && \mathsf{2-\lambda}
\end{pmatrix}
$$
$$\lambda_1=1\quad \lambda_2=2\quad \lambda_3 = 3$$
$$(1)
\begin{cases}
\mathsf{\alpha-\beta+\gamma=0} \\
\mathsf{\alpha+\beta-\gamma=0} \\
\mathsf{\alpha-\beta+\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-\beta+\gamma=0} \\
\mathsf{\alpha-\gamma=0} \\
\mathsf{\alpha-\beta=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(3)
\begin{cases}
\mathsf{-\alpha-\beta+\gamma=0} \\
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{\alpha-\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{0}\\ {1}\\ {1}\end{pmatrix} e^{t} + 
C_1 \begin{pmatrix}{1}\\ {1}\\ {1}\end{pmatrix} e^{2t} + 
C_2 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} e^{3t}
$$
## 799
$$
\begin{cases}
\mathsf{x'=3x-y+z} \\
\mathsf{y'=x+y+z} \\
\mathsf{z'=4x-y+4z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{3-\lambda} && \mathsf{-1} && \mathsf{1} \\
\mathsf{1} && \mathsf{1-\lambda} && \mathsf{1} \\
\mathsf{4} && \mathsf{-1} && \mathsf{4-\lambda}
\end{pmatrix}
$$
$$\lambda_1=1\quad \lambda_2=2\quad \lambda_3 = 5$$
$$(1)
\begin{cases}
\mathsf{2\alpha-\beta+\gamma=0} \\
\mathsf{\alpha+\gamma=0} \\
\mathsf{4\alpha-\beta+3\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=-1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{\alpha-\beta+\gamma=0} \\
\mathsf{\alpha-\beta+\gamma=0} \\
\mathsf{4\alpha-\beta+2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha-\beta+\gamma=0} \\
\mathsf{3\alpha+\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=-2} \\
\mathsf{\gamma=-3}
\end{cases}
$$
$$(3)
\begin{cases}
\mathsf{-2\alpha-\beta+\gamma=0} \\
\mathsf{\alpha-4\beta+\gamma=0} \\
\mathsf{4\alpha-\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=\beta} \\
\mathsf{4\alpha-\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=3}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{1}\\ {1}\\ {-1}\end{pmatrix} e^{t} + 
C_1 \begin{pmatrix}{1}\\ {-2}\\ {-3}\end{pmatrix} e^{2t} + 
C_2 \begin{pmatrix}{1}\\ {1}\\ {3}\end{pmatrix} e^{5t}
$$
## 800
$$
\begin{cases}
\mathsf{x'=-3x+4y-2z} \\
\mathsf{y'=x+z} \\
\mathsf{z'=6x-6y+5z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{-3-\lambda} && \mathsf{4} && \mathsf{-2} \\
\mathsf{1} && \mathsf{-\lambda} && \mathsf{1} \\
\mathsf{6} && \mathsf{-6} && \mathsf{5-\lambda}
\end{pmatrix}
$$
$$\lambda_1=1\quad \lambda_2=2\quad \lambda_3 = -1$$
$$(1)
\begin{cases}
\mathsf{-4\alpha+4\beta-2\gamma=0} \\
\mathsf{\alpha-\beta+\gamma=0} \\
\mathsf{6\alpha-6\beta+4\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=0}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-5\alpha+4\beta-2\gamma=0} \\
\mathsf{\alpha-2\beta+\gamma=0} \\
\mathsf{6\alpha-6\beta+3\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=2}
\end{cases}
$$
$$(3)
\begin{cases}
\mathsf{-2\alpha+4\beta-2\gamma=0} \\
\mathsf{\alpha+\beta+\gamma=0} \\
\mathsf{6\alpha-6\beta+6\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=-1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{1}\\ {1}\\ {0}\end{pmatrix} e^{t} + 
C_1 \begin{pmatrix}{0}\\ {1}\\ {2}\end{pmatrix} e^{2t} + 
C_2 \begin{pmatrix}{-1}\\ {0}\\ {1}\end{pmatrix} e^{-t}
$$
## 801
$$
\begin{cases}
\mathsf{x'=x-y-z} \\
\mathsf{y'=x+y} \\
\mathsf{z'=3x+z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{1-\lambda} && \mathsf{-1} && \mathsf{-1} \\
\mathsf{1} && \mathsf{1-\lambda} && \mathsf{0} \\
\mathsf{3} && \mathsf{0} && \mathsf{1-\lambda}
\end{pmatrix}
$$
$$\lambda_1=1\quad \lambda_{2,3}=1\pm 2i$$
$$(1)
\begin{cases}
\mathsf{-\beta-\gamma=0} \\
\mathsf{\alpha=0} \\
\mathsf{3\alpha=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=-1} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-2i\alpha-\beta-\gamma=0} \\
\mathsf{\alpha-2i\beta=0} \\
\mathsf{3\alpha-2i\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=2i} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=3}
\end{cases}
$$
$$
\begin{pmatrix}{2i}\\ {1}\\ {3}\end{pmatrix} e^{(1+2i)t}= 
\begin{pmatrix}{2i}\\ {1}\\ {3}\end{pmatrix} e^{t}\cdot(\cos 2t+i\sin 2t)
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{0}\\ {-1}\\ {1}\end{pmatrix} e^{t} + 
C_1 \begin{pmatrix}{-2\sin 2t}\\ {\cos 2t}\\ {3\cos 2t}\end{pmatrix} e^{t} + 
C_2 \begin{pmatrix}{2\cos 2t}\\ {\sin 2t}\\ {3\sin 2t}\end{pmatrix} e^{t}
$$
## 802
$$
\begin{cases}
\mathsf{x'=2x+y} \\
\mathsf{y'=x+3y-z} \\
\mathsf{z'=-x+2y+3z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{2-\lambda} && \mathsf{1} && \mathsf{0} \\
\mathsf{1} && \mathsf{3-\lambda} && \mathsf{-1} \\
\mathsf{-1} && \mathsf{2} && \mathsf{3-\lambda}
\end{pmatrix}
$$
$$\lambda_1=2\quad \lambda_{2,3}=3\pm i$$
$$(1)
\begin{cases}
\mathsf{\beta=0} \\
\mathsf{\alpha+\beta-\gamma=0} \\
\mathsf{-\alpha+2\beta+\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{(-1-i)\alpha+\beta=0} \\
\mathsf{\alpha-i\beta-\gamma=0} \\
\mathsf{-\alpha+2\beta-i\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1+i} \\
\mathsf{\gamma=2-i}
\end{cases}
$$
$$
\begin{pmatrix}{1}\\ {1+i}\\ {2-i}\end{pmatrix} e^{(3+i)t}= 
\begin{pmatrix}{1}\\ {1+i}\\ {2-i}\end{pmatrix} e^{3t}\cdot(\cos t+i\sin t)
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} e^{2t} + 
C_1 \begin{pmatrix}{\cos t}\\ {\cos t - \sin t}\\ {2\cos t + \sin t}\end{pmatrix} e^{3t} + 
C_2 \begin{pmatrix}{\sin t}\\ {\sin t + \cos t}\\ {2\sin t - \cos t}\end{pmatrix} e^{3t}
$$
## 803
$$
\begin{cases}
\mathsf{x'=2x-y+2z} \\
\mathsf{y'=x+2z} \\
\mathsf{z'=-2x+y-z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{2-\lambda} && \mathsf{-1} && \mathsf{2} \\
\mathsf{1} && \mathsf{-\lambda} && \mathsf{2} \\
\mathsf{-2} && \mathsf{1} && \mathsf{-1-\lambda}
\end{pmatrix}
$$
$$\lambda_1=1\quad \lambda_{2,3}=\pm i$$
$$(1)
\begin{cases}
\mathsf{\alpha-\beta+2\gamma=0} \\
\mathsf{\alpha-\beta+2\gamma=0} \\
\mathsf{-2\alpha+\beta-2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=2} \\
\mathsf{\gamma=1}
\end{cases}$$
$$(2)
\begin{cases}
\mathsf{(2-i)\alpha-\beta+2\gamma=0} \\
\mathsf{\alpha-i\beta+2\gamma=0} \\
\mathsf{-2\alpha+\beta-(1+i)\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{(1-i)\alpha=(1+i)\beta} \\
\mathsf{\alpha-i\beta+2\gamma=0} \\
\mathsf{-2\alpha+\beta-(1+i)\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1+i} \\
\mathsf{\beta=1-i} \\
\mathsf{\gamma=-2-i}
\end{cases}$$
$$\begin{pmatrix}{1+i}\\ {1-i}\\ {-2-i}\end{pmatrix} e^{it}= 
\begin{pmatrix}{1+i}\\ {1-i}\\ {-2-i}\end{pmatrix} \cdot(\cos t+i\sin t)$$
$$\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{0}\\ {2}\\ {1}\end{pmatrix} e^{t} + 
C_1 \begin{pmatrix}{\cos t-\sin t}\\ {\cos t + \sin t}\\ {\sin t - 2\cos t}\end{pmatrix} + 
C_2 \begin{pmatrix}{\sin t + \cos t}\\ {\sin t - \cos t}\\ {-2\sin t - \cos t}\end{pmatrix}$$
## 804
$$
\begin{cases}
\mathsf{x'=4x-y-z} \\
\mathsf{y'=x+2y-z} \\
\mathsf{z'=x-y+2z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{4-\lambda} && \mathsf{-1} && \mathsf{-1} \\
\mathsf{1} && \mathsf{2-\lambda} && \mathsf{-1} \\
\mathsf{1} && \mathsf{-1} && \mathsf{2-\lambda}
\end{pmatrix}
$$
$$\lambda_1=2\quad \lambda_{2}=\lambda_{3}=3$$
$$(1)
\begin{cases}
\mathsf{2\alpha-\beta-\gamma=0} \\
\mathsf{\alpha-\gamma=0} \\
\mathsf{\alpha-\beta=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{\alpha-\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=0}
\end{cases} \quad and \quad
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{1}\\ {1}\\ {1}\end{pmatrix} e^{2t} + 
C_1 \begin{pmatrix}{1}\\ {1}\\ {0}\end{pmatrix} e^{3t} + 
C_2 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} e^{3t}
$$
## 805
$$
\begin{cases}
\mathsf{x'=2x-y-z} \\
\mathsf{y'=3x-2y-3z} \\
\mathsf{z'=2x-4y}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{2-\lambda} && \mathsf{-1} && \mathsf{-1} \\
\mathsf{3} && \mathsf{-2-\lambda} && \mathsf{-3} \\
\mathsf{2} && \mathsf{4} && \mathsf{-\lambda}
\end{pmatrix}
$$
$$\lambda_1=0\quad \lambda_{2}=\lambda_{3}=1$$
$$(1)
\begin{cases}
\mathsf{2\alpha-\beta-\gamma=0} \\
\mathsf{3\alpha-2\beta-3\gamma=0} \\
\mathsf{2\alpha+4\beta=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=-2} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=-5}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{3\alpha-3\beta-3\gamma=0} \\
\mathsf{2\alpha+4\beta-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=-5} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=-6}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1 t + \beta_1}\\ {\alpha_2 t + \beta_2}\\ {\alpha_3 t + \beta_3}\end{pmatrix} e^{t}
$$
$$
\begin{pmatrix}{x'}\\ {y'}\\ {z'}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1t+\beta_1+\alpha_1}\\ {\alpha_2t+\beta_2+\alpha_2}\\ {\alpha_3t+\beta_3+\alpha_3}\end{pmatrix} e^{t}
$$
$$
\begin{cases}
\mathsf{(2\alpha_1-\alpha_2-\alpha_3)t+2\beta_1-\beta_2-\beta_3=\alpha_1t+\beta_1+\alpha_1} \\
\mathsf{(3\alpha_1-2\alpha_2-3\alpha_3)t+3\beta_1-2\beta_2-3\beta_3=\alpha_2t+\beta_2+\alpha_2} \\
\mathsf{(2\alpha_1+4\alpha_2)t+2\beta_1+4\beta_2=\alpha_3t+\beta_3+\alpha_3}
\end{cases}
$$
$$
\begin{cases}
\mathsf{2\alpha_1-\alpha_2-\alpha_3=\alpha_1} \\
\mathsf{2\beta_1-\beta_2-\beta_3=\alpha_1+\beta_1} \\
\mathsf{3\alpha_1-2\alpha_2-3\alpha_3=\alpha_2} \\
\mathsf{3\beta_1-2\beta_2-3\beta_3=\alpha_2+\beta_2} \\
\mathsf{2\alpha_1+4\alpha_2=\alpha_3} \\
\mathsf{2\beta_1+4\beta_2=\alpha_3+\beta_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1-\alpha_2-\alpha_3=0} \\
\mathsf{\beta_1-\beta_2-\beta_3=\alpha_1} \\
\mathsf{3\beta_1-3\beta_2-3\beta_3=\alpha_2} \\
\mathsf{2\alpha_1+4\alpha_2-\alpha_3=0} \\
\mathsf{2\beta_1+4\beta_2-\beta_3=\alpha_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1=5C_0} \\
\mathsf{\alpha_2=C_0} \\
\mathsf{\alpha_3=4C_0} \\
\mathsf{\beta_1=-C_0-5C_1} \\
\mathsf{\beta_2=C_1} \\
\mathsf{\beta_3=-6C_0-6C_1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{-2}\\ {1}\\ {-5}\end{pmatrix} + 
\begin{pmatrix}{5C_0t-C_0-5C_1}\\ {C_0t+C_1}\\ {4C_0t-6C_0-6C_1}\end{pmatrix} e^{t}
$$
## 806
$$
\begin{cases}
\mathsf{x'=-2x+y-2z} \\
\mathsf{y'=x-2y+2z} \\
\mathsf{z'=3x-3y+5z}
\end{cases}
$$
$$\begin{pmatrix}
\mathsf{-2-\lambda} && \mathsf{1} && \mathsf{-2} \\
\mathsf{1} && \mathsf{-2-\lambda} && \mathsf{2} \\
\mathsf{3} && \mathsf{-3} && \mathsf{5-\lambda}
\end{pmatrix}
$$
$$\lambda_1=3\quad \lambda_{2}=\lambda_{3}=-1$$
$$(1)
\begin{cases}
\mathsf{-5\alpha+\beta-2\gamma=0} \\
\mathsf{\alpha-5\beta+2\gamma=0} \\
\mathsf{3\alpha-3\beta+2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=-1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=3}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-\alpha+\beta-2\gamma=0} \\
\mathsf{\alpha-\beta+2\gamma=0} \\
\mathsf{3\alpha-3\beta+6\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=2} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=-1}
\end{cases}\quad and \quad
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=2} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{-1}\\ {1}\\ {3}\end{pmatrix} e^{3t} + 
C_1 \begin{pmatrix}{2}\\ {0}\\ {-1}\end{pmatrix} e^{-t} + 
C_2 \begin{pmatrix}{0}\\ {2}\\ {1}\end{pmatrix} e^{-t}
$$
## 807
$$
\begin{cases}
\mathsf{x'=3x-2y-z} \\
\mathsf{y'=3x-4y-3z} \\
\mathsf{z'=2x-4y}
\end{cases}
$$
$$
\begin{pmatrix}
\mathsf{3-\lambda} && \mathsf{-2} && \mathsf{-1} \\
\mathsf{3} && \mathsf{-4-\lambda} && \mathsf{-3} \\
\mathsf{2} && \mathsf{-4} && \mathsf{-\lambda}
\end{pmatrix}$$
$$\lambda_1=\lambda_2=2\quad \lambda_{3}=-5$$
$$(1)
\begin{cases}
\mathsf{\alpha-2\beta-\gamma=0} \\
\mathsf{3\alpha-6\beta-3\gamma=0} \\
\mathsf{2\alpha-4\beta-2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=2} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=0}
\end{cases} \quad and \quad \begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{8\alpha-2\beta-\gamma=0} \\
\mathsf{3\alpha+\beta-3\gamma=0} \\
\mathsf{2\alpha-4\beta+5\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=-1} \\
\mathsf{\beta=2} \\
\mathsf{\gamma=2}
\end{cases}
$$

$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{2}\\ {1}\\ {0}\end{pmatrix} e^{2t} + 
C_1 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} e^{2t} + 
C_2 \begin{pmatrix}{-1}\\ {2}\\ {2}\end{pmatrix} e^{-5t}
$$
## 808
$$
\begin{cases}
\mathsf{x'=x-y+z} \\
\mathsf{y'=x+y-z} \\
\mathsf{z'=-y+2z}
\end{cases}
$$
$$
\begin{pmatrix}
\mathsf{1-\lambda} && \mathsf{-1} && \mathsf{1} \\
\mathsf{1} && \mathsf{1-\lambda} && \mathsf{-1} \\
\mathsf{0} && \mathsf{-1} && \mathsf{2-\lambda}
\end{pmatrix}$$
$$\lambda_1=\lambda_2=1\quad \lambda_{3}=2$$
$$(1)
\begin{cases}
\mathsf{-\beta+\gamma=0} \\
\mathsf{\alpha-\gamma=0} \\
\mathsf{-\beta+\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1 t + \beta_1}\\ {\alpha_2 t + \beta_2}\\ {\alpha_3 t + \beta_3}\end{pmatrix} e^{t}
$$
$$
\begin{pmatrix}{x'}\\ {y'}\\ {z'}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1t+\beta_1+\alpha_1}\\ {\alpha_2t+\beta_2+\alpha_2}\\ {\alpha_3t+\beta_3+\alpha_3}\end{pmatrix} e^{t}
$$
$$
\begin{cases}
\mathsf{(\alpha_1-\alpha_2+\alpha_3)t+\beta_1-\beta_2+\beta_3=\alpha_1t+\beta_1+\alpha_1} \\
\mathsf{(\alpha_1+\alpha_2-\alpha_3)t+\beta_1+\beta_2-\beta_3=\alpha_2t+\beta_2+\alpha_2} \\
\mathsf{(-\alpha_2+2\alpha_3)t-\beta_2+2\beta_3=\alpha_3t+\beta_3+\alpha_3}
\end{cases}
$$
$$
\begin{cases}
\mathsf{\alpha_1-\alpha_2+\alpha_3=\alpha_1} \\
\mathsf{\beta_1-\beta_2+\beta_3=\alpha_1+\beta_1} \\
\mathsf{\alpha_1+\alpha_2-\alpha_3=\alpha_2} \\
\mathsf{\beta_1+\beta_2-\beta_3=\alpha_2+\beta_2} \\
\mathsf{-\alpha_2+2\alpha_3=\alpha_3} \\
\mathsf{-\beta_2+2\beta_3=\alpha_3+\beta_3}
\end{cases} \iff
\begin{cases}
\mathsf{-\alpha_2+\alpha_3=0} \\
\mathsf{-\beta_2+\beta_3=\alpha_1} \\
\mathsf{\alpha_1-\alpha_3=0} \\
\mathsf{\beta_1-\beta_3=\alpha_2} \\
\mathsf{-\alpha_2+\alpha_3=0} \\
\mathsf{-\beta_2+\beta_3=\alpha_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1=C_0} \\
\mathsf{\alpha_2=C_0} \\
\mathsf{\alpha_3=C_0} \\
\mathsf{\beta_1=C_0+C_1} \\
\mathsf{\beta_2=C_1-C_0} \\
\mathsf{\beta_3=C_1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-\alpha-\beta+\gamma=0} \\
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{-\beta=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{C_0t+C_0+C_1}\\ {C_0t+C_1-C_0}\\ {C_0t+C_1}\end{pmatrix} e^{t} +
C_2 \begin{pmatrix}{1}\\ {0}\\ {1}\end{pmatrix} e^{2t}
$$
## 809
$$
\begin{cases}
\mathsf{x'=-x+y-2z} \\
\mathsf{y'=4x+y} \\
\mathsf{z'=2x+y-z}
\end{cases}
$$
$$
\begin{pmatrix}
\mathsf{-1-\lambda} && \mathsf{1} && \mathsf{-2} \\
\mathsf{4} && \mathsf{1-\lambda} && \mathsf{0} \\
\mathsf{2} && \mathsf{1} && \mathsf{-1-\lambda}
\end{pmatrix}$$
$$\lambda_1=1\quad \lambda_2=\lambda_{3}=-1$$
$$(1)
\begin{cases}
\mathsf{-2\alpha+\beta-2\gamma=0} \\
\mathsf{4\alpha=0} \\
\mathsf{2\alpha+\beta-2\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=2} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{\beta-2\gamma=0} \\
\mathsf{4\alpha+2\beta=0} \\
\mathsf{2\alpha+\beta=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=-2} \\
\mathsf{\gamma=-1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1 t + \beta_1}\\ {\alpha_2 t + \beta_2}\\ {\alpha_3 t + \beta_3}\end{pmatrix} e^{-t}
$$
$$
\begin{pmatrix}{x'}\\ {y'}\\ {z'}\end{pmatrix} = 
\begin{pmatrix}{-\alpha_1t-\beta_1+\alpha_1}\\ {-\alpha_2t-\beta_2+\alpha_2}\\ {-\alpha_3t-\beta_3+\alpha_3}\end{pmatrix} e^{-t}
$$
$$
\begin{cases}
\mathsf{(-\alpha_1+\alpha_2-2\alpha_3)t-\beta_1+\beta_2-2\beta_3=-\alpha_1t-\beta_1+\alpha_1} \\
\mathsf{(4\alpha_1+\alpha_2)t+4\beta_1+\beta_2=-\alpha_2t-\beta_2+\alpha_2} \\
\mathsf{(2\alpha_1+\alpha_2-\alpha_3)t+2\beta_2+\beta_2-\beta_3=-\alpha_3t-\beta_3+\alpha_3}
\end{cases}
$$
$$
\begin{cases}
\mathsf{-\alpha_1+\alpha_2-2\alpha_3=-\alpha_1} \\
\mathsf{-\beta_1+\beta_2-2\beta_3=\alpha_1-\beta_1} \\
\mathsf{4\alpha_1+\alpha_2=-\alpha_2} \\
\mathsf{4\beta_1+\beta_2=\alpha_2-\beta_2} \\
\mathsf{2\alpha_1+\alpha_2-2\alpha_3=-\alpha_3} \\
\mathsf{2\beta_1+\beta_2-2\beta_3=\alpha_3-\beta_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_2-2\alpha_3=0} \\
\mathsf{\beta_2-2\beta_3=\alpha_1} \\
\mathsf{2\alpha_1+\alpha_2=0} \\
\mathsf{4\beta_1+2\beta_2=\alpha_2} \\
\mathsf{2\alpha_1+\alpha_2-\alpha_3=0} \\
\mathsf{2\beta_1+\beta_2-\beta_3=\alpha_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1=C_0} \\
\mathsf{\alpha_2=-2C_0} \\
\mathsf{\alpha_3=-C_0} \\
\mathsf{\beta_1=-C_0-C_1} \\
\mathsf{\beta_2=C_0+2C_1} \\
\mathsf{\beta_3=C_1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
C_0 \begin{pmatrix}{0}\\ {2}\\ {1}\end{pmatrix} e^{t} + 
\begin{pmatrix}{C_0t-C_0-C_1}\\ {-2C_0t+C_0+2C_1}\\ {-C_0t+C_1}\end{pmatrix} e^{-t}
$$
## 810
$$
\begin{cases}
\mathsf{x'=2x+y} \\
\mathsf{y'=2y+4z} \\
\mathsf{z'=x-z}
\end{cases}
$$
$$
\begin{pmatrix}
\mathsf{2-\lambda} && \mathsf{1} && \mathsf{0} \\
\mathsf{0} && \mathsf{2-\lambda} && \mathsf{4} \\
\mathsf{1} && \mathsf{0} && \mathsf{-1-\lambda}
\end{pmatrix}$$
$$\lambda_1=\lambda_2=0\quad \lambda_{3}=3$$

$$(1)
\begin{cases}
\mathsf{2\alpha+\beta=0} \\
\mathsf{2\beta+4\gamma=0} \\
\mathsf{\alpha-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=-2} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1 t + \beta_1}\\ {\alpha_2 t + \beta_2}\\ {\alpha_3 t + \beta_3}\end{pmatrix}
$$
$$
\begin{pmatrix}{x'}\\ {y'}\\ {z'}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1}\\ {\alpha_2}\\ {\alpha_3}\end{pmatrix}
$$
$$
\begin{cases}
\mathsf{(2\alpha_1+\alpha_2)t+2\beta_1+\beta_2=\alpha_1} \\
\mathsf{(2\alpha_2+4\alpha_3)t+2\beta_2+4\beta_3=\alpha_2} \\
\mathsf{(\alpha_1-\alpha_3)t+\beta_1-\beta_3=\alpha_3}
\end{cases}
$$
$$
\begin{cases}
\mathsf{2\alpha_1+\alpha_2=0} \\
\mathsf{2\beta_1+\beta_2=\alpha_1} \\
\mathsf{2\alpha_2+4\alpha_3=0} \\
\mathsf{2\beta_2+4\beta_3=\alpha_2} \\
\mathsf{\alpha_1-\alpha_3=0} \\
\mathsf{\beta_1-\beta_3=\alpha_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1=С_0} \\
\mathsf{\alpha_2=-2С_0} \\
\mathsf{\alpha_3=С_0} \\
\mathsf{\beta_1=С_1} \\
\mathsf{\beta_2=С_0-2С_1} \\
\mathsf{\beta_3=С_1-С_0}
\end{cases}
$$
$$(2)
\begin{cases}
\mathsf{-\alpha+\beta=0} \\
\mathsf{-\beta+4\alpha=0} \\
\mathsf{\alpha-4\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=4} \\
\mathsf{\beta=4} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{C_0t+C_1}\\ {-2C_0t+С_0-2С_1}\\ {С_0t+С_1-С_0}\end{pmatrix} +
C_2 \begin{pmatrix}{4}\\ {4}\\ {1}\end{pmatrix} e^{3t}
$$
## 811
$$
\begin{cases}
\mathsf{x'=2x-y-z} \\
\mathsf{y'=2x-y-2z} \\
\mathsf{z'=-x+y+2z}
\end{cases}
$$
$$\lambda_1=\lambda_2=\lambda_{3}=1$$
$$
\begin{pmatrix}
\mathsf{2-\lambda} && \mathsf{-1} && \mathsf{-1} \\
\mathsf{2} && \mathsf{-1-\lambda} && \mathsf{-2} \\
\mathsf{-1} && \mathsf{1} && \mathsf{2-\lambda}
\end{pmatrix}$$

$$(1)
\begin{cases}
\mathsf{\alpha-\beta-\gamma=0} \\
\mathsf{2\alpha-2\beta-2\gamma=0} \\
\mathsf{-\alpha+\beta+\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=1} \\
\mathsf{\gamma=0}
\end{cases} \quad and \quad
\begin{cases}
\mathsf{\alpha=0} \\
\mathsf{\beta=0} \\
\mathsf{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1 t + \beta_1}\\ {\alpha_2 t + \beta_2}\\ {\alpha_3 t + \beta_3}\end{pmatrix} e^{t}
$$
$$
\begin{pmatrix}{x'}\\ {y'}\\ {z'}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1t+\beta_1+\alpha_1}\\ {\alpha_2t+\beta_2+\alpha_2}\\ {\alpha_3t+\beta_3+\alpha_3}\end{pmatrix} e^{t}
$$
$$
\begin{cases}
\mathsf{(2\alpha_1-\alpha_2-\alpha_3)t+2\beta_1-\beta_2-\beta_3=\alpha_1t+\beta_1+\alpha_1} \\
\mathsf{(2\alpha_1-\alpha_2-2\alpha_3)t+2\beta_1-\beta_2-2\beta_3=\alpha_2t+\beta_2+\alpha_2} \\
\mathsf{(-\alpha_1+\alpha_2+2\alpha_3)t-\beta_1+\beta_2+2\beta_3=\alpha_3t+\beta_3+\alpha_3}
\end{cases}
$$
$$
\begin{cases}
\mathsf{2\alpha_1-\alpha_2-\alpha_3=\alpha_1} \\
\mathsf{2\beta_1-\beta_2-\beta_3=\alpha_1+\beta_1} \\
\mathsf{2\alpha_1-\alpha_2-2\alpha_3=\alpha_2} \\
\mathsf{2\beta_1-\beta_2-2\beta_3=\alpha_2+\beta_2} \\
\mathsf{-\alpha_1+\alpha_2+2\alpha_3=\alpha_3} \\
\mathsf{-\beta_1+\beta_2+2\beta_3=\alpha_3+\beta_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1-\alpha_2-\alpha_3=0} \\
\mathsf{\beta_1-\beta_2-\beta_3=\alpha_1} \\
\mathsf{2\beta_1-2\beta_2-2\beta_3=\alpha_2} \\
\mathsf{-\beta_1+\beta_2+\beta_3=\alpha_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1=C_0} \\
\mathsf{\alpha_2=-2C_0} \\
\mathsf{\alpha_3=3C_0} \\
\mathsf{\beta_1=C_1} \\
\mathsf{\beta_2=C_2} \\
\mathsf{\beta_3=C_1-C_2-C_0}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{C_0t+C_1}\\ {-2C_0t+C_2}\\ {3C_0t+C_1-C_2-C_2}\end{pmatrix} e^{t}
$$
## 812
$$
\begin{cases}
\mathsf{x'=4x-y} \\
\mathsf{y'=3x+y-z} \\
\mathsf{z'=x+z}
\end{cases}
$$
$$\lambda_1=\lambda_2=\lambda_{3}=2$$
$$
\begin{pmatrix}
\mathsf{4-\lambda} && \mathsf{-1} && \mathsf{0} \\
\mathsf{3} && \mathsf{1-\lambda} && \mathsf{-1} \\
\mathsf{1} && \mathsf{0} && \mathsf{1-\lambda}
\end{pmatrix}$$
$$(1)
\begin{cases}
\mathsf{2\alpha-\beta=0} \\
\mathsf{3\alpha-\beta-\gamma=0} \\
\mathsf{\alpha-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{2\alpha-\beta=0} \\
\mathsf{\alpha-\gamma=0}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha=1} \\
\mathsf{\beta=2} \\
\mathsf{\gamma=1}
\end{cases} 
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{\alpha_1 t^2 + \beta_1 t + \gamma_1}\\ {\alpha_2 t^2 + \beta_2t+\gamma_2}\\ {\alpha_3 t^2 + \beta_3t+\gamma_3}\end{pmatrix} e^{2t}
$$
$$
\begin{pmatrix}{x'}\\ {y'}\\ {z'}\end{pmatrix} = 
\begin{pmatrix}{2\alpha_1 t^2 + (2\alpha_1+2\beta_1)t+\beta_1+2\gamma_1}\\ {2\alpha_2 t^2 + (2\alpha_2+2\beta_2)t+\beta_2+2\gamma_2}\\ {2\alpha_3 t^2 + (2\alpha_3+2\beta_3)t+\beta_3+2\gamma_3}\end{pmatrix} e^{2t}
$$
$$
\begin{cases}
\mathsf{4\alpha_1-\alpha_2=2\alpha_1} \\
\mathsf{4\beta_1-\beta_2=2\alpha_1+2\beta_1} \\
\mathsf{4\gamma_1-\gamma_2=\beta_1+2\gamma_1} \\
\mathsf{3\alpha_1+\alpha_2-\alpha_3=2\alpha_2} \\
\mathsf{3\beta_1+\beta_2-\beta_3=2\alpha_2+2\beta_2} \\
\mathsf{3\gamma_1+\gamma_2-\gamma_3=\beta_2+2\gamma_2} \\
\mathsf{\alpha_1+\alpha_3=2\alpha_3} \\
\mathsf{\beta_1+\beta_3=2\alpha_3+2\beta_3} \\
\mathsf{\gamma_1+\gamma_3=\beta_3+2\gamma_3}
\end{cases} \iff
\begin{cases}
\mathsf{2\alpha_1-\alpha_2=0} \\
\mathsf{2\beta_1-\beta_2=2\alpha_1} \\
\mathsf{2\gamma_1-\gamma_2=\beta_1} \\
\mathsf{3\alpha_1-\alpha_2-\alpha_3=0} \\
\mathsf{3\beta_1-\beta_2-\beta_3=2\alpha_2} \\
\mathsf{3\gamma_1-\gamma_2-\gamma_3=\beta_2} \\
\mathsf{\alpha_1-\alpha_3=0} \\
\mathsf{\beta_1-\beta_3=2\alpha_3} \\
\mathsf{\gamma_1-\gamma_3=\beta_3}
\end{cases} \iff
\begin{cases}
\mathsf{\alpha_1=C_0} \\
\mathsf{\alpha_2=2C_0} \\
\mathsf{\alpha_3=C_0} \\
\mathsf{\beta_1=C_1} \\
\mathsf{\beta_2=2C_1-2C_0} \\
\mathsf{\beta_3=C_1-2C_0} \\
\mathsf{\gamma_1=C_2} \\
\mathsf{\gamma_2=2C_2-C_1} \\
\mathsf{\gamma_3=C_2-C_1+2C_0}
\end{cases}
$$
$$
\begin{pmatrix}{x}\\ {y}\\ {z}\end{pmatrix} = 
\begin{pmatrix}{C_0t^2+C_1t+C_2}\\ {2C_0t^2+2(C_1-C_0)t+2C_2-C_1}\\ {C_0t^2+(C_1-2C_0)t+C_2-C_1+2C_0}\end{pmatrix} e^{2t}
$$
# Диффуры IDZ 2 (815-818)
## 815
$$
\begin{cases}
{x''=2y} \\
{y''=-2x}
\end{cases}
$$
$$
\begin{cases}
{x''-2y=0} \\
{y''+2x=0}
\end{cases}
$$
$$
\begin{vmatrix}
{\lambda^2} && {-2} \\
{2} && {\lambda^2}
\end{vmatrix}=\lambda^4+4=0
$$
$$\lambda_{1,2}=1\pm i\quad \lambda_{3,4}=-1\pm i$$
$$(1, 2)
\begin{cases}
{2i\alpha-2\beta=0} \\
{2\alpha+2i\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=1} \\
{\beta=i}
\end{cases}
$$
$$(3, 4)
\begin{cases}
{-2i\alpha-2\beta=0} \\
{2\alpha-2i\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=i} \\
{\beta=1}
\end{cases}
$$
$$
\begin{pmatrix}
{x} \\
{y} 
\end{pmatrix} =
C_0 \begin{pmatrix}
{\cos t} \\
{-\sin t} 
\end{pmatrix} e^{t}+
C_1 \begin{pmatrix}
{\sin t} \\
{\cos t} 
\end{pmatrix} e^{t}
+C_2 
\begin{pmatrix}
{-\sin t} \\
{\cos t} 
\end{pmatrix} e^{-t} + 
C_3
\begin{pmatrix}
{\cos t} \\
{\sin t} 
\end{pmatrix} e^{-t}
$$
## 816
$$
\begin{cases}
{x''-3x+y+z=0} \\
{x+y''-3y+z=0} \\
{x+y+z''-3z=0}
\end{cases}
$$
$$
\begin{vmatrix}
{\lambda^2-3} && {1} && {1} \\
{1} && {\lambda^2-3} && {1} \\
{1} && {1} && {\lambda^2-3}
\end{vmatrix}= (\lambda^2-3)^3 -3 (\lambda^2-3) + 2
=0
$$
$$
(\lambda^2-3)^3 -3 (\lambda^2-3) + 2=(\lambda^2-3)((\lambda^2-3)^2-1)-2(\lambda^2-4)=
$$
$$
=(\lambda^2-3)(\lambda^2-4)(\lambda^2-2)-2(\lambda^2-4)=
$$
$$
=(\lambda-2)(\lambda+2)(\lambda^4-5\lambda^2+4)=(\lambda-2)^2(\lambda+2)^2(\lambda-1)(\lambda+1)
$$
$$\lambda_{1, 2}=2\quad\lambda_{3, 4}=-2\quad\lambda_{5,6}=\pm1$$
$$(1, 2, 3, 4)
\begin{cases}
{\alpha+\beta+\gamma=0} \\
{\alpha+\beta+\gamma=0} \\
{\alpha+\beta+\gamma=0}
\end{cases}\implies
\begin{cases}
{\alpha=-1} \\
{\beta=1} \\
{\gamma=0}
\end{cases} \quad and \quad 
\begin{cases}
{\alpha=-1} \\
{\beta=0} \\
{\gamma=1}
\end{cases}
$$
$$(5, 6)
\begin{cases}
{-2\alpha+\beta+\gamma=0} \\
{\alpha-2\beta+\gamma=0} \\
{\alpha+\beta-2\gamma=0}
\end{cases}\implies
\begin{cases}
{\alpha=1} \\
{\beta=1} \\
{\gamma=1}
\end{cases}
$$
$$
\begin{pmatrix}
{x} \\
{y} \\
{z}
\end{pmatrix} =
C_0 \begin{pmatrix}
{-1} \\
{0} \\
{1}
\end{pmatrix} e^{2t}+
C_1 \begin{pmatrix}
{-1} \\
{1} \\
{0}
\end{pmatrix} e^{-2t} + 
C_0 \begin{pmatrix}
{-1} \\
{0} \\
{1}
\end{pmatrix} e^{-2t}+
C_1 \begin{pmatrix}
{-1} \\
{1} \\
{0}
\end{pmatrix} e^{2t} +
C_0 \begin{pmatrix}
{1} \\
{1} \\
{1}
\end{pmatrix} e^{t}+
C_1 \begin{pmatrix}
{1} \\
{1} \\
{1}
\end{pmatrix} e^{-t}
$$
## 817
$$
\begin{cases}
{2x'+x-5y'-4y=0} \\
{3x'-2x-4y'+y=0}
\end{cases}
$$
$$
\begin{vmatrix}
{2\lambda+1} && {-5\lambda-4} \\
{3\lambda-2} && {-4\lambda+1}
\end{vmatrix}=-8\lambda^2-2\lambda+1+15\lambda^2+2\lambda-8=7\lambda^2-7=0
$$
$$\lambda_{1, 2}=\pm 1$$
$$(1)
\begin{cases}
{3\alpha-9\beta=0} \\
{\alpha-3\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=3} \\
{\beta=1}
\end{cases}
$$
$$(2)
\begin{cases}
{-\alpha+\beta=0} \\
{-5\alpha+5\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=1} \\
{\beta=1}
\end{cases}
$$
$$
\begin{pmatrix}
{x} \\
{y} 
\end{pmatrix} =
C_0 \begin{pmatrix}
{3} \\
{1} 
\end{pmatrix} e^{t}+
C_1 \begin{pmatrix}
{1} \\
{1} 
\end{pmatrix} e^{-t}
$$
## 818
$$
\begin{cases}
{x''+x'+y'-2y=0} \\
{x'+x-y'=0}
\end{cases}
$$
$$
\begin{vmatrix}
{\lambda^2+\lambda} && {\lambda-2} \\
{\lambda+1} && {-\lambda}
\end{vmatrix}=-\lambda^3-\lambda^2-\lambda^2+\lambda+2=-\lambda^3-2\lambda^2+\lambda+2=(\lambda-1)(\lambda+1)(\lambda+2)=0
$$
$$\lambda_{1, 2}=\pm1\quad\lambda_3=-2$$
$$(1)
\begin{cases}
{2\alpha-\beta=0} \\
{2\alpha-\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=1} \\
{\beta=2}
\end{cases}
$$
$$(2)
\begin{cases}
{-3\beta=0} \\
{\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=1} \\
{\beta=0}
\end{cases}
$$
$$(3)
\begin{cases}
{2\alpha-4\beta=0} \\
{-\alpha+2\beta=0}
\end{cases}\implies
\begin{cases}
{\alpha=2} \\
{\beta=1}
\end{cases}
$$
$$
\begin{pmatrix}
{x} \\
{y} 
\end{pmatrix} =
C_0 \begin{pmatrix}
{1} \\
{2} 
\end{pmatrix} e^{t}+
C_1 \begin{pmatrix}
{1} \\
{0} 
\end{pmatrix} e^{-t}+
C_2 \begin{pmatrix}
{2} \\
{1} 
\end{pmatrix} e^{-2t}
$$
# Диффуры IDZ 3 (834-840)
## 834

$$\begin{cases}
{x'=x+2y}\\
{y'=x-5\sin t}
\end{cases}$$
$$\begin{pmatrix}
{1-\lambda} && {2} \\
{1} && {-\lambda}
\end{pmatrix}$$
$$-\lambda(1-\lambda)-2=\lambda^2 -\lambda-2=0\implies \lambda_1=-1\quad\lambda_2=2$$$$(1) \begin{cases}
{2\alpha + 2\beta=0} \\
{\alpha+\beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{-1}
\end{pmatrix}$$
$$(2) \begin{cases}
{-\alpha + 2\beta=0} \\
{\alpha-2\beta=0}
\end{cases}\implies
\begin{pmatrix}
{2} \\
{1}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{A_1 \sin t+B_1 \cos t}\\ {A_2 \sin t +B_2 \cos t}\end{pmatrix}
$$
$$\begin{pmatrix}{A_1\cos t-B_1 \sin t}\\ {A_2\cos t-B_2 \sin t}\end{pmatrix}=
\begin{pmatrix}{(A_1+2A_2) \sin t+(B_1+2B_2) \cos t}\\ {(A_1 - 5) \sin t +B_1 \cos t}\end{pmatrix}
$$
$$\begin{cases}
{A_1=B_1+2B_2} \\
{-B_1=A_1+2A_2} \\
{A_2=B_1} \\
{-B_2=A_1-5}
\end{cases}\implies \begin{cases}
{A_1=-\dfrac 1 3 A_1+10-2A_1} \\
{A_1=-3A_2=-3B_1} \\
{A_2=B_1} \\
{B_2=5-A_1}
\end{cases}\implies \begin{cases}
{A_1=3} \\
{A_2=-1} \\
{B_1=-1} \\
{B_2=2}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{3 \sin t- \cos t}\\ {-\sin t +2 \cos t}\end{pmatrix} + 
C_0\begin{pmatrix}{1}\\ {-1}\end{pmatrix} e^{-t} +
C_1\begin{pmatrix}{2}\\ {1}\end{pmatrix} e^{2t}
$$

## 835
$$\begin{cases}
{x'=2x-4y}\\
{y'=x-3y+3e^t}
\end{cases}$$
$$\begin{pmatrix}
{2-\lambda} && {-4} \\
{1} && {-3-\lambda}
\end{pmatrix}$$
$$\lambda^2+\lambda-2=0\implies \lambda_1=1\quad\lambda_2=-2$$$$(1) \begin{cases}
{\alpha - 4 \beta=0} \\
{\alpha - 4 \beta=0}
\end{cases}\implies
\begin{pmatrix}
{4} \\
{1}
\end{pmatrix}$$
$$(2) \begin{cases}
{4\alpha - 4 \beta=0} \\
{\alpha-\beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{1}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{A_1 t+B_1 }\\ {A_2 t +B_2}\end{pmatrix} e^{t}
$$
$$\begin{pmatrix}{A_1t+B_1+A_1}\\ {A_2 t+B_2 + A_2}\end{pmatrix}=
\begin{pmatrix}{(2A_1+4A_2)t+2B_1 + 4B_2}\\ {(A_1-3A_2) t +B_1-3B_2 + 3}\end{pmatrix}
$$
$$\begin{cases}
{A_1=2A_1-4A_2} \\
{B_1+A_1=2B_1-4B_2} \\
{A_2=A_1-3A_2} \\
{B_2+A_2=B_1-3B_2+3}
\end{cases}\implies \begin{cases}
{A_1=4A_2} \\
{A_1=B_1-4B_2} \\
{A_1=A_2-3} \\
{A_2=B_1-4B_2+3}
\end{cases}\implies \begin{cases}
{A_1=-4} \\
{A_2=-1} \\
{B_1=0} \\
{B_2=1}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{-4t}\\ {1-t}\end{pmatrix} e^{t} + 
C_0\begin{pmatrix}{1}\\ {-1}\end{pmatrix} e^{-t} +
C_1\begin{pmatrix}{2}\\ {1}\end{pmatrix} e^{2t}
$$

## 836

$$\begin{cases}
{x'=2x-y}\\
{y'=-2x+y+18t}
\end{cases}$$
$$\begin{pmatrix}
{2-\lambda} && {-1} \\
{-2} && {1-\lambda}
\end{pmatrix}$$
$$\lambda^2-3\lambda=0\implies \lambda_1=3\quad\lambda_2=0$$$$(1) \begin{cases}
{-\alpha -  \beta=0} \\
{-2\alpha - 2 \beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{-1}
\end{pmatrix}$$
$$(2) \begin{cases}
{2\alpha - \beta=0} \\
{-2\alpha+\beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{2}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{A_1 t^2+B_1 t + C_1 }\\ {A_2 t^2 +B_2 t + C_2}\end{pmatrix}
$$
$$\begin{pmatrix}{2A_1 t+B_1}\\ {2A_2 t+B_2}\end{pmatrix}=
\begin{pmatrix}{(2A_1-A_2)t^2+(2B_1 - B_2)t+2C_1-C_2}\\ {(-2A_1+A_2) t^2 +(-2B_1+B_2)t - 2C_1+C_2 + 18t}\end{pmatrix}
$$
$$\begin{cases}
{0=2A_1-A_2} \\
{2A_1=2B_1-B_2} \\
{B_1=2C_1-C_2} \\
{0=-2A_1+A_2} \\
{2A_2=-2B_1+B_2+18} \\
{B_2=C_2-2C_1} 
\end{cases}\implies \begin{cases}
{2A_1=A_2} \\
{A_1=9-A_2} \\
{B_1=-B_2} \\
{2A_2=-2B_1+B_2+18} \\
{B_2=C_2-2C_1} 
\end{cases}\implies \begin{cases}
{A_1=3} \\
{A_2=6} \\
{B_1=2} \\
{B_2=-2} \\
{C_1=1} \\
{C_2=0}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{3t^2+2t+1}\\ {6t^2-2t}\end{pmatrix} + 
C_0\begin{pmatrix}{1}\\ {-1}\end{pmatrix} e^{3t} +
C_1\begin{pmatrix}{1}\\ {2}\end{pmatrix} 
$$

## 837

$$\begin{cases}
{x'=x+2y+16te^t}\\
{y'=2x-2y}
\end{cases}$$
$$\begin{pmatrix}
{1-\lambda} && {2} \\
{2} && {-2-\lambda}
\end{pmatrix}$$
$$\lambda^2+\lambda-6=0\implies \lambda_1=2\quad\lambda_2=-3$$$$(1) \begin{cases}
{-\alpha +2\beta=0} \\
{2\alpha - 4 \beta=0}
\end{cases}\implies
\begin{pmatrix}
{2} \\
{1}
\end{pmatrix}$$
$$(2) \begin{cases}
{4\alpha + 2\beta=0} \\
{2\alpha + \beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{-2}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{A_1 t+B_1 }\\ {A_2 t +B_2}\end{pmatrix} e^{t}
$$
$$\begin{pmatrix}{A_1t+B_1+A_1}\\ {A_2 t+B_2 + A_2}\end{pmatrix}=
\begin{pmatrix}{(A_1+2A_2 + 16)t+B_1 + 2B_2}\\ {(2A_1-2A_2) t +2B_1-2B_2}\end{pmatrix}
$$
$$\begin{cases}
{A_1=A_1+2A_2+16} \\
{B_1+A_1=B_1+2B_2} \\
{A_2=2A_1-2A_2} \\
{B_2+A_2=2B_1-2B_2}
\end{cases}\implies \begin{cases}
{A_1=4A_2} \\
{A_1=B_1-4B_2} \\
{A_1=A_2-3} \\
{A_2=B_1-4B_2+3}
\end{cases}\implies \begin{cases}
{A_1=-12} \\
{A_2=-8} \\
{B_1=-12} \\
{B_2=-6}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
-2\begin{pmatrix}{6t+6}\\ {4t+3}\end{pmatrix} e^{t} + 
C_0\begin{pmatrix}{2}\\ {1}\end{pmatrix} e^{2t} +
C_1\begin{pmatrix}{1}\\ {-2}\end{pmatrix} e^{-3t}
$$

## 838


$$\begin{cases}
{x'=2x+4y-8}\\
{y'=3x+6y}
\end{cases}$$
$$\begin{pmatrix}
{2-\lambda} && {4} \\
{3} && {6-\lambda}
\end{pmatrix}$$
$$\lambda^2-8\lambda=0\implies \lambda_1=0\quad\lambda_2=8$$$$(1) \begin{cases}
{2\alpha +4 \beta=0} \\
{3\alpha +6 \beta=0}
\end{cases}\implies
\begin{pmatrix}
{-2} \\
{1}
\end{pmatrix}$$
$$(2) \begin{cases}
{-6\alpha +4 \beta=0} \\
{3\alpha -2 \beta=0}
\end{cases}\implies
\begin{pmatrix}
{2} \\
{3}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{A_1 t+B_1 }\\ {A_2 t +B_2}\end{pmatrix}
$$
$$\begin{pmatrix}{A_1}\\ {A_2}\end{pmatrix}=
\begin{pmatrix}{(2A_1+4A_2)t+2B_1 + 4B_2}\\ {(A_1-3A_2) t +B_1-3B_2 + 3}\end{pmatrix}
$$
$$\begin{cases}
{A_1=2A_1-4A_2} \\
{B_1+A_1=2B_1-4B_2} \\
{A_2=A_1-3A_2} \\
{B_2+A_2=B_1-3B_2+3}
\end{cases}\implies \begin{cases}
{A_1=4A_2} \\
{A_1=B_1-4B_2} \\
{A_1=A_2-3} \\
{A_2=B_1-4B_2+3}
\end{cases}\implies \begin{cases}
{A_1=-4} \\
{A_2=-1} \\
{B_1=0} \\
{B_2=1}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{-4t}\\ {1-t}\end{pmatrix} e^{t} + 
C_0\begin{pmatrix}{1}\\ {-1}\end{pmatrix} e^{-t} +
C_1\begin{pmatrix}{2}\\ {1}\end{pmatrix} e^{2t}
$$

## 839
$$\begin{cases}
{x'=2x-3y}\\
{y'=x-2y+2\sin t}
\end{cases}$$
$$\begin{pmatrix}
{2-\lambda} && {-3} \\
{1} && {-2-\lambda}
\end{pmatrix}$$
$$\lambda^2-1=0\implies \lambda_1=1\quad\lambda_2=-1$$
$$(1) \begin{cases}
{\alpha - 3\beta=0} \\
{\alpha - 3 \beta=0}
\end{cases}\implies
\begin{pmatrix}
{3} \\
{1}
\end{pmatrix}$$
$$(2) \begin{cases}
{3\alpha -3 \beta=0} \\
{\alpha - \beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{1}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{A_1 \sin t+B_1 \cos t}\\ {A_2 \sin t +B_2 \cos t}\end{pmatrix}
$$
$$\begin{pmatrix}{A_1\cos t-B_1 \sin t}\\ {A_2\cos t-B_2 \sin t}\end{pmatrix}=
\begin{pmatrix}{(2A_1-3A_2) \sin t+(2B_1-3B_2) \cos t}\\ {(A_1-2A_2 +2) \sin t +(B_1 - B_2) \cos t}\end{pmatrix}
$$
$$\begin{cases}
{A_1=2B_1-3B_2} \\
{-B_1=2A_1-3A_2} \\
{A_2=B_1-B_2} \\
{-B_2=A_1-2A_2+2}
\end{cases}\implies \begin{cases}
{A_1=3} \\
{2B_1=B_2} \\
{A_2=B_1-B_2} \\
{B_2=1}
\end{cases}\implies \begin{cases}
{A_1=3} \\
{A_2=-\dfrac 1 2} \\
{B_1=\dfrac 1 2} \\
{B_2=1}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{3 \sin t-\dfrac 1 2 \cos t}\\ {-\dfrac 1 2\sin t + \cos t}\end{pmatrix} + 
C_0\begin{pmatrix}{3}\\ {1}\end{pmatrix} e^{t} +
C_1\begin{pmatrix}{1}\\ {1}\end{pmatrix} e^{-t}
$$

## 840
$$\begin{cases}
{x'=x-y+2\sin t}\\
{y'=2x-y}
\end{cases}$$
$$\begin{pmatrix}
{1-\lambda} && {-1} \\
{2} && {-1-\lambda}
\end{pmatrix}$$
$$\lambda^2+1=0\implies \lambda_{1,2}=\pm i$$
$$(1,2) \begin{cases}
{(1-i)\alpha - \beta=0} \\
{2\alpha - (1+i) \beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{1-i}
\end{pmatrix}$$
$$\begin{pmatrix}
{1} \\
{1-i}
\end{pmatrix}\cdot e^{it}=
\begin{pmatrix}
{\cos t + i\sin t} \\
{(1-i)(\cos t + i \sin t)}
\end{pmatrix}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{(A_1t+B_1) \sin t+ (C_1t+D_1)\cos t}\\ {(A_2t+B_2) \sin t+ (C_2t+D_2)\cos t}\end{pmatrix}
$$
$$\begin{pmatrix}{x'}\\ {y'}\end{pmatrix}=
\begin{pmatrix}{(-C_1t+A_1-D_1) \sin t+ (A_1t+C_1+B_1)\cos t}\\ {(-C_2t+A_2-D_2) \sin t+ (A_2t+C_2+B_2)\cos t}\end{pmatrix}
$$

$$\begin{cases}
{-C_1=A_1-A_2} \\
{A_1-D_1=B_1-B_2+2} \\
{A_1=C_1-C_2} \\
{C_1+B_1=D_1-D_2} \\
{-C_2=2A_1-A_2} \\
{A_2-D_2=2B_1-B_2} \\
{A_2=2C_1-C_2} \\
{C_2+B_2=2D_1-D_2}
\end{cases}\implies \begin{cases}
{C_2=0} \\
{C_1=2} \\
{A_1=2} \\
{B_1=-2} \\
{A_2=4} \\
{D_1=1} \\
{D_2=1} \\
{B_2=1}
\end{cases}$$
$$\begin{pmatrix}{x}\\ {y}\end{pmatrix}=
\begin{pmatrix}{(2t-2)\sin t + (2t+1)\cos t}\\ {(4t+1)\sin t + \cos t}\end{pmatrix} e^{t} + 
C_0\begin{pmatrix}{\cos t}\\ {\cos t+\sin t}\end{pmatrix} +
C_1\begin{pmatrix}{\sin t}\\ {\sin t - \cos t}\end{pmatrix}
$$
# Диффуры IDZ 4 (847-850)
## 847
$$\begin{cases}
{x'=-x+2y}\\
{y'=-3x+4y+\dfrac{e^{3t}}{e^{2t}+1}}
\end{cases}$$
$$\begin{pmatrix}
{-1-\lambda} && {2} \\
{-3} && {4-\lambda}
\end{pmatrix}$$
$$\lambda^2-3\lambda+2=0\implies \lambda_1=1\quad\lambda_2=2$$
$$(1) \begin{cases}
{-2\alpha + 2\beta=0} \\
{-3\alpha+3\beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{1}
\end{pmatrix}$$
$$(2) \begin{cases}
{-3\alpha + 2\beta=0} \\
{-3\alpha+2\beta=0}
\end{cases}\implies
\begin{pmatrix}
{2} \\
{3}
\end{pmatrix}$$
$$\begin{cases}
{x=C_1 e^{t}+2C_2 e^{2t}}\\
{y=C_1 e^{t}+3C_2 e^{2t}}
\end{cases}$$
$$\begin{cases}
{x'=C_1' e^{t} + C_1 e^{t}+2C_2' e^{2t}+4C_2 e^{2t}}\\
{y'=C_1' e^{t} + C_1 e^{t}+3C_2' e^{2t}+6C_2 e^{2t}}
\end{cases}$$
$$\begin{cases}
{C_1' e^{t} + C_1 e^{t}+2C_2' e^{2t}+4C_2 e^{2t}=-C_1 e^{t} - 2C_2 e^{2t}+2C_1 e^{t}+6C_2 e^{2t}}\\
{C_1' e^{t} + C_1 e^{t}+3C_2' e^{2t}+6C_2 e^{2t}=-3C_1 e^{t} - 6 C_2 e^{2t} + 4C_1 e^{t} + 12 C_2 e^{2t}+\dfrac{e^{3t}}{e^{2t}+1}}
\end{cases}$$
$$\begin{cases}
{C_1' e^{t}+2C_2' e^{2t}= 0}\\
{C_1' e^{t}+3C_2' e^{2t}=\dfrac{e^{3t}}{e^{2t}+1}}
\end{cases}$$
$$\begin{cases}
{C_1'= -2\dfrac{e^{2t}}{e^{2t}+1}}\\
{C_2'=\dfrac{e^{t}}{e^{2t}+1}}
\end{cases}$$
Ответ:
$$\begin{cases}
{x=C_1 e^{t}+2C_2 e^{2t}}\\
{y=C_1 e^{t}+3C_2 e^{2t}}
\end{cases}$$
$$\begin{cases}
{C_1= -\ln{(e^{2t}+1)} + c_1}\\
{C_2=\arctan(e^t) + c_2}
\end{cases}$$
## 848
$$\begin{cases}
{x'=-4x-2y+\dfrac{2}{e^t - 1}}\\
{y'=6x+3y-\dfrac{3}{e^t - 1}}
\end{cases}$$
$$\begin{pmatrix}
{-4-\lambda} && {-2} \\
{6} && {3-\lambda}
\end{pmatrix}$$
$$\lambda^2+\lambda=0\implies \lambda_1=0\quad\lambda_2=-1$$
$$(1) \begin{cases}
{-4\alpha-2\beta=0} \\
{6\alpha+3\beta=0}
\end{cases}\implies
\begin{pmatrix}
{-1} \\
{2}
\end{pmatrix}$$
$$(2) \begin{cases}
{-3\alpha-2\beta=0} \\
{6\alpha+4\beta=0}
\end{cases}\implies
\begin{pmatrix}
{-2} \\
{3}
\end{pmatrix}$$
$$\begin{cases}
{x=-C_1+2C_2 e^{-t}}\\
{y=2C_1+3C_2 e^{-t}}
\end{cases}$$
$$\begin{cases}
{-C_1' +2 C_2' e^{-t}= \dfrac{2}{e^t - 1}}\\
{-2C_1' +3 C_2' e^{-t}=-\dfrac{3}{e^t - 1}}
\end{cases}$$
$$\begin{cases}
{C_1'= \dfrac{12}{e^t - 1}}\\
{C_2' =7\dfrac{e^{t}}{e^t - 1}}
\end{cases}$$
Ответ:
$$\begin{cases}
{x=C_1 e^{t}+2C_2 e^{2t}}\\
{y=C_1 e^{t}+3C_2 e^{2t}}
\end{cases}$$
$$\begin{cases}
{C_1= 12\ln(e^t - 1)-12t + c_1}\\
{C_2=7\ln(e^t - 1) + c_2}
\end{cases}$$
## 849

$$\begin{cases}
{x'=x-y+\dfrac{1}{\cos t}}\\
{y'=2x-y}
\end{cases}$$
$$\begin{pmatrix}
{1-\lambda} && {-1} \\
{2} && {-1-\lambda}
\end{pmatrix}$$
$$\lambda^2+1=0\implies \lambda_{1,2}=\pm i$$
$$(1) \begin{cases}
{(1-i)\alpha-\beta=0} \\
{2\alpha-(1+i)\beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{1-i}
\end{pmatrix}$$
$$
\begin{pmatrix}
{1} \\
{1-i}
\end{pmatrix} e^{it} = 
\begin{pmatrix}
{\cos t + i\sin t} \\
{\cos t - \sin t + (\sin t-\cos t)i}
\end{pmatrix} 
$$
$$\begin{cases}
{x=C_1\cos t+C_2 \sin t}\\
{y=C_1(\cos t -\sin t)+C_2 (\sin t - \cos t)}
\end{cases}$$
$$\begin{cases}
{C_1'\cos t+C_2' \sin t=\dfrac 1 {\cos t}}\\
{C_1'(\cos t -\sin t)+C_2' (\sin t - \cos t)=0}
\end{cases}$$
$$\begin{cases}
{C_1'\cos t+C_2' \sin t=\dfrac 1 {\cos t}}\\
{C_1'\sin t+C_2' \cos t=0}
\end{cases}$$
$$\begin{cases}
{C_1'=\dfrac 1 {\cos 2t}}\\
{C_2' =-\dfrac {\tan x} {\cos 2t}}
\end{cases}$$
Ответ:
$$\begin{cases}
{x=C_1\cos t+C_2 \sin t}\\
{y=C_1(\cos t -\sin t)+C_2 (\sin t - \cos t)}
\end{cases}$$
$$\begin{cases}
{C_1=\dfrac 1 2 \ln(\sin 2t + 1)-\dfrac 1 2 \ln (\cos 2t) + c_1}\\
{C_2 =-\left(\dfrac{\sin\left(x\right)\,\ln\left(\sin\left(2\,t\right)+1\right)}{2\,\cos\left(x\right)}-\dfrac{\sin\left(x\right)\,\ln\left(\left|\cos\left(2\,t\right)\right|\right)}{2\,\cos\left(x\right)}+c_2\right)}
\end{cases}$$

## 850
$$\begin{cases}
{x'=3x-2y}\\
{y'=2x-y+15e^t\sqrt t}
\end{cases}$$
$$\begin{pmatrix}
{3-\lambda} && {-2} \\
{2} && {-1-\lambda}
\end{pmatrix}$$
$$\lambda^2-2\lambda+1=0\implies \lambda_{1, 2}=1$$
$$(1, 2) \begin{cases}
{2\alpha-2\beta=0} \\
{2\alpha-2\beta=0}
\end{cases}\implies
\begin{pmatrix}
{1} \\
{1}
\end{pmatrix}$$
$$\begin{cases}
{x=(a_1t+b_1)e^t}\\
{y=(a_2t+b_2)e^t}
\end{cases}$$
$$\begin{cases}
{a_1t+b_1+a_1=(3a_1-2a_2)t+3b_1-2b_2}\\
{a_2t+b_2+a_2=(2a_1-a_2)t+2b_1-b_2}
\end{cases}\iff
\begin{cases}
{a_1=2b_1-2b_2}\\
{a_2=2b_1-2b_2} \\
{a_2=a_1=C_1}
\end{cases}\iff
\begin{cases}
{a_1=2C_1} \\ 
{a_2=2C_1} \\
{b_1=C_2} \\
{b_2=C_2-C_1}
\end{cases}$$
$$\begin{cases}
{x=(2C_1t+C_2)e^t}\\
{y=(2C_1t+C_2-C_1)e^t}
\end{cases}$$
$$\begin{cases}
{x'=(2C_1t+C_2+2C_1+C_2'+2C_1't)e^t}\\
{y'=(2C_1t+C_2+C_1+C_2'-C_1'+2C_1't)e^t}
\end{cases}$$
$$\begin{cases}
{C_2'+2C_1't=0}\\
{C_2'-C_1'+2C_1't=15\sqrt t}
\end{cases}$$
$$\begin{cases}
{C_2'=30t\sqrt t}\\
{C_1'=-15\sqrt t}
\end{cases}$$
Ответ:
$$\begin{cases}
{x=(2C_1t+C_2)e^t}\\
{y=(2C_1t+C_2-C_1)e^t}
\end{cases}$$
$$\begin{cases}
{C_1=-10t\sqrt t+c_1} \\
{C_2=12t^2\sqrt t+c_2}
\end{cases}$$
# Диффуры IDZ 5 (869,870,873)
## 869
$$A=\begin{pmatrix}
{2} && {1} \\
{0} && {2}
\end{pmatrix}$$
$$\begin{pmatrix}
{2-\lambda} && {1} \\
{0} && {2-\lambda}
\end{pmatrix}$$
$$\lambda_{1, 2}=2$$
$$
x=\begin{pmatrix}
{a_1t+b_1} \\
{a_2t+b_2}
\end{pmatrix} e^{2t}
$$
$$
\begin{pmatrix}
{2a_1t+2b_1+a_1} \\
{2a_2t+2b_2+a_2}
\end{pmatrix} = 
\begin{pmatrix}
{(2a_1+a_2)t+(2b_1+b_2)} \\
{2a_2t+2b_2}
\end{pmatrix}
$$
$$
\begin{cases}
{2a_1=2a_1+a_2} \\ 
{2a_2=2a_2} \\
{2b_1+a_1=2b_1+b_2} \\
{2b_2+a_2=2b_2} 
\end{cases} \implies
\begin{cases}
{a_2=0} \\ 
{a_1=b_2} \\ 
\end{cases}\implies
\begin{cases}
{a_1=C_0} \\ 
{a_2=0} \\
{b_1=C_1} \\
{b_2=C_0} 
\end{cases}
$$
$$x=\begin{pmatrix}
{C_0t+C_1} \\ 
{C_0} 
\end{pmatrix}e^{2t}$$
$$\begin{pmatrix}
{C_1} \\ 
{C_0} 
\end{pmatrix}=\begin{pmatrix}
{1} \\
{0}
\end{pmatrix}\implies \begin{pmatrix}
{e^{2t}} \\
{0}
\end{pmatrix}$$
$$\begin{pmatrix}
{C_1} \\ 
{C_0} 
\end{pmatrix}=\begin{pmatrix}
{0} \\
{1}
\end{pmatrix}\implies \begin{pmatrix}
{te^{2t}} \\
{e^{2t}}
\end{pmatrix}$$
$$e^A=\begin{pmatrix}
{e^{2t}} && {te^{2t}} \\
{0} && {e^{2t}}
\end{pmatrix}$$
## 870
$$A=\begin{pmatrix}
{3} && {-1} \\
{2} && {0}
\end{pmatrix}$$
$$\lambda^2-3\lambda+2=0\implies\lambda_{1}=1, \lambda_2=2$$
$$(1)\begin{cases}
{2\alpha-\beta=0} \\
{2\alpha-\beta=0}
\end{cases}\implies \begin{pmatrix}
{1} \\ {2}
\end{pmatrix}$$
$$(2)\begin{cases}
{\alpha-\beta=0} \\
{2\alpha-2\beta=0}
\end{cases}\implies \begin{pmatrix}
{1} \\ {1}
\end{pmatrix}$$
$$x=C_0\begin{pmatrix}
{1} \\ 
{2}
\end{pmatrix} e^{t}
+C_1\begin{pmatrix}
{1} \\ 
{2}
\end{pmatrix} e^{2t}$$
$$C_0\begin{pmatrix}
{1} \\ 
{2}
\end{pmatrix}
+C_1\begin{pmatrix}
{1} \\ 
{1}
\end{pmatrix} = \begin{pmatrix}
{1} \\ 
{0}
\end{pmatrix} \implies \begin{cases}
{C_0=-1} \\ 
{C_1=2}
\end{cases}\implies \begin{pmatrix}
{2e^{2t}-e^{t}} \\ 
{4e^{2t}-2e^{t}}
\end{pmatrix}$$
$$C_0\begin{pmatrix}
{1} \\ 
{2}
\end{pmatrix}
+C_1\begin{pmatrix}
{1} \\ 
{1}
\end{pmatrix} = \begin{pmatrix}
{0} \\ 
{1}
\end{pmatrix} \implies \begin{cases}
{C_0=1} \\ 
{C_1=-1}
\end{cases}\implies \begin{pmatrix}
{e^{2t}-e^{t}} \\ 
{2e^{2t}-2e^{t}}
\end{pmatrix}$$
$$e^A=\begin{pmatrix}
{1} && {0} \\
{2} && {0}
\end{pmatrix}$$
## 873
$$A=\begin{pmatrix}
{2} && {1} && {0} \\
{0} && {2} && {1} \\
{0} && {0} && {2}
\end{pmatrix}$$
$$(2-\lambda)^3=0\implies\lambda_{1, 2, 3}=2$$
$$
x=\begin{pmatrix}
{a_1t^2+b_1t+c_1} \\
{a_2t^2+b_2t+c_2} \\
{a_3t^2+b_3t+c_3}
\end{pmatrix} e^{2t}
$$
$$
\begin{pmatrix}
{2a_1t^2+2b_1t+2c_1+2a_1t+b_1} \\
{2a_2t^2+2b_2t+2c_2+2a_2t+b_2} \\
{2a_3t^2+2b_3t+2c_3+2a_3t+b_3}
\end{pmatrix} = 
\begin{pmatrix}
{(2a_1+a_2)t^2+(2b_1+b_2)t+2c_1+c_2} \\
{(2a_2+a_3)t^2+(2b_2+b_3)t+2c_2+c_3} \\
{2a_3t^2+2b_3t+2c_3}
\end{pmatrix}
$$
$$
\begin{cases}
{a_2=0} \\ 
{a_3=0} \\
{2a_1=b_2} \\ 
{b_1=c_2} \\
{b_2=c_3} \\ 
{b_3=0}
\end{cases} \implies
\begin{cases}
{a_1=C_0} \\ 
{a_2=0} \\
{a_3=0} \\
{b_1=C_1} \\
{b_2=2C_0} \\
{b_3=0} \\
{c_1=C_2} \\
{c_2=C_1} \\
{c_3=2C_0}
\end{cases}
$$
$$
x=\begin{pmatrix}
{C_0t^2+C_1t+C_2} \\
{2C_0t+C_1} \\
{2C_0}
\end{pmatrix} e^{2t}
$$
$$
\begin{pmatrix}
{C_2} \\
{C_1} \\
{2C_0}
\end{pmatrix} =
\begin{pmatrix}
{1} \\
{0} \\
{0}
\end{pmatrix}\implies
\begin{pmatrix}
{e^{2t}} \\
{0} \\
{0}
\end{pmatrix}$$
$$
\begin{pmatrix}
{C_2} \\
{C_1} \\
{2C_0}
\end{pmatrix} =
\begin{pmatrix}
{0} \\
{1} \\
{0}
\end{pmatrix}\implies
\begin{pmatrix}
{te^{2t}} \\
{e^{2t}} \\
{0}
\end{pmatrix}$$
$$
\begin{pmatrix}
{C_2} \\
{C_1} \\
{2C_0}
\end{pmatrix} =
\begin{pmatrix}
{0} \\
{0} \\
{1}
\end{pmatrix}\implies
\begin{pmatrix}
{t^2e^{2t}} \\
{2te^{2t}} \\
{2e^{2t}}
\end{pmatrix}$$
$$e^A=\begin{pmatrix}
{e^2} && {e^2} && {e^2} \\
{0} && {e^2} && {2e^2} \\
{0} && {0} && {2e^2}
\end{pmatrix}$$
# Диффуры IDZ 6 (751-763,782)
## 751
$$
\begin{cases}
y'' - y = 2x \\
y(0) = 0 \\
y(1) = -1
\end{cases}
$$
$$
\lambda^{2} - 1 = 0
$$
$$
\begin{matrix}
\lambda = -1 \\
\lambda = 1
\end{matrix}
$$
$$
y = C_{1}e^{-x} + C_{2}e^{x}
$$
$$
\begin{cases}
C_1=-C_2 \\
C_1e^{-1}+C_2e=-1
\end{cases} \implies \begin{cases}
C_2=\dfrac 1 {e^{-1}-e} \\
C_{1} = -\dfrac 1 {e^{-1}-e}
\end{cases}
$$
$$
y = -\dfrac 1 {e^{-1}-e} e^{-1} + \dfrac 1 {e^{-1}-e} e^x
$$
## 752
$$
\begin{cases}
y'' + y' = 1 \\
y'(0) = 0 \\
y(1) = 1
\end{cases}
$$
$$
\lambda^{2} + \lambda = 0
$$
$$
\begin{matrix}
\lambda = -1 \\
\lambda = 0
\end{matrix}
$$
$$
y = C_{1}e^{-x} + C_2+x
$$
$$
\begin{cases}
1-C_1=0 \\
C_1e^{-1}+C_2=0
\end{cases} \implies \begin{cases}
C_1=1 \\
C_2=-e^{-1}
\end{cases}
$$
$$
y = e^{-x}-e^{-1}+x
$$
## 753

$$
\begin{cases}
y'' - y' = 0 \\
y(0) = -1 \\
y'(1) - y(1) = 2
\end{cases}
$$
$$
\lambda^{2} - \lambda = 0
$$
$$
\begin{matrix}
\lambda = 0 \\
\lambda = 1
\end{matrix}
$$
$$
y = C_{1} + C_{2}e^{x}
$$
$$
\begin{cases}
C_{1} + C_{2} = -1 \\
C_{2}e - C_{1} - C_{2}e = 2
\end{cases} \implies \begin{cases}
C_{2} = 1 \\
C_{1} = -2
\end{cases}
$$
$$
y = -2 + e^{x}
$$

## 754

$$
\begin{cases}
y'' + y = 1 \\
y(0) = 0 \\
y(\dfrac \pi 2) = 0
\end{cases}
$$
$$
\lambda^{2} + 1 = 0
$$
$$
\begin{matrix}
\lambda = \pm i
\end{matrix}
$$
$$
y = C_{1}\cos x + C_{2}\sin x+1
$$
$$
\begin{cases}
C_1=-1 \\
C_2 = -1
\end{cases} 
$$
$$
y = 1-\cos x - \sin x
$$
## 755

$$
\begin{cases}
y'' + y = 1 \\
y(0) = 0 \\
y(\pi) = 0
\end{cases}
$$
$$
\lambda^{2} + 1 = 0
$$
$$
\begin{matrix}
\lambda = \pm i
\end{matrix}
$$
$$
y = C_{1}\cos x + C_{2}\sin x+1
$$
$$
C_1=\pm 1 
$$
$$
y = 1\pm\cos x + C_2\sin x
$$
## 756

$$
\begin{cases}
y'' + y = 2x-\pi \\
y(0) = 0 \\
y(\pi) = 0
\end{cases}
$$
$$
\lambda^{2} + 1 = 0
$$
$$
\begin{matrix}
\lambda = \pm i
\end{matrix}
$$
$$
y = C_{1}\cos x + C_{2}\sin x+2x-\pi
$$
$$
C_1=\pi
$$
$$
y = 2x-\pi+C_2\sin x + \pi \cos x
$$
## 757

$$
\begin{cases}
y'' -y' - 2y = 0 \\
y'(0) = 2 \\
y(+\infty) = 0
\end{cases}
$$
$$
\lambda^{2}-\lambda - 2 = 0
$$
$$
\begin{matrix}
\lambda = -1 \\
\lambda = 2
\end{matrix}
$$
$$
y = C_{1}e^{-x} + C_2 e^{2x}
$$
$$
\begin{cases}
C_1=-2 \\
C_2 = 0
\end{cases} 
$$
$$
y = -2e^{-x}
$$
## 758

$$
\begin{cases}
y'' - y = 1 \\
y(0) = 0 \\
y(+\infty) - ограничена
\end{cases}
$$
$$
\lambda^{2} - 1 = 0
$$
$$
\begin{matrix}
\lambda = \pm 1
\end{matrix}
$$
$$
y = C_{1}e^x + C_{2}e^{-x}-1
$$
$$
\begin{cases}
C_1=0 \\
C_1+C_2=1
\end{cases} 
$$
$$
y = e^{-x}-1
$$
## 759

$$
\begin{cases}
y'' - 2iy = 0 \\
y(0) = -1 \\
y(+\infty) = 0
\end{cases}
$$
$$
\lambda^{2} - 2i = 0\implies \lambda^2 = 2e^{\dfrac \pi 2 i}\implies \lambda = \{ \sqrt2 e^{\dfrac \pi 4 i} ,\sqrt2 e^{\dfrac{5\pi} 4 i}\}=\{ 1+i, -1-i \}
$$
$$
y = C_1e^{x}e^{ix}+C_2e^{-x}e^{-ix}
$$
$$
\begin{cases}
C_1=0 \\
C_1+C_2=-1
\end{cases} 
$$
$$
y = -e^{-(1+i)x}
$$
## 760

$$
\begin{cases}
x^2y'' - 6y = 0 \\
{y(0) - \text{ограничена}} \\
y(1) = 2
\end{cases}
$$
$$
x=e^t
$$
$$
e^{2t}e^{-3t}(y''e^{t}-y'e^t)-6y=y''-y'-6y=0
$$
$$
D=5^2 \implies \lambda = \dfrac{1\pm 5}{2}=\{ 3, -2 \}
$$
$$
y = C_{1}e^{3x} + C_{2}e^{-2x}
$$
$$
\begin{cases}
C_2=0 \\
C_1e^3=2
\end{cases} 
$$
$$
y = \dfrac 2 {e^3} e^{3x}
$$
## 761


$$
\begin{cases}
x^2y'' - 2xy' +2y = 0 \\
{y(x\to0) = o(x)} \\
y(1) = 3
\end{cases}
$$
$$
x=e^t
$$
$$
e^{2t}e^{-3t}(y''e^{t}-y'e^t) - 2e^t e^{-t} y'+2y=y''-3y'+2y=0
$$
$$
\lambda =\{ 1, 2 \}
$$
$$
y = C_{1}e^{x} + C_{2}e^{2x}
$$
$$
\begin{cases}
\lim\limits_{x\to0}\dfrac y x =0\implies  С_1=С_2=0 \\
y(1)=3
\end{cases} 
$$
$$
\not \exists y
$$
## 762


$$
\begin{cases}
x^2y'' + 5xy' +3y = 0 \\
{y'(1) = 3} \\
y(x\to +\infty) = O(x^{-2})
\end{cases}
$$
$$
x=e^t
$$
$$
e^{2t}e^{-3t}(y''e^{t}-y'e^t) + 5e^t e^{-t} y'+3y=y''+4y'+3y=0
$$
$$
\lambda =\{ -1, -3 \}
$$
$$
y = C_{1}e^{-x} + C_{2}e^{-3x}
$$
$$
\begin{cases}
\lim\limits_{x\to+\infty}y x^2 =\infty\implies С_1=С_2=0 \\
y'(1)=0
\end{cases} 
$$
$$
\not \exists y
$$
## 763

$$
\begin{cases}
y'' + ay' = 1 \\
{y(0) = 0} \\
y(1) = 0
\end{cases}
$$
Когда нет решений?
$$
\lambda^2+a\lambda=0\implies\lambda = \{ 0, -a \}
$$
$$a=0$$
$$y''=1$$
$$y=\dfrac {x^2} 2+C_1x + C_2$$
$$\begin{cases}
{C_2=0} \\
{C_1+C_2=-\dfrac 1 2}
\end{cases}$$
$$a\neq 0$$
$$
y = C_{1} + C_{2}e^{-ax}+\dfrac x a
$$
$$
\begin{cases}
{C_1+C_2=0} \\
{C_1+C_2e^{-a}+\dfrac 1 a=0}
\end{cases} 
$$
$$
\begin{cases}
{C_1=\dfrac 1 {a(e^{-a}-1)}} \\
{C_2=-\dfrac 1 {a(e^{-a}-1)}}
\end{cases} 
$$
Есть всегда?
## 782
$$
\begin{cases}
y'' = ky \\
y(0) = 0 \\
y(l) = 0
\end{cases}
$$
Найти $k, y \not \equiv 0$

$$\lambda ^2 = k\implies \lambda = \pm\sqrt k$$
$$k=0$$
$$y=C_1x+C_0$$
$$\begin{cases}
{C_0=0} \\
{C_1l+C_0=0\implies C_1=0}
\end{cases}$$
$$k>0$$
$$y=C_0e^{\sqrt kx}+C_1 e^{-\sqrt kx}$$
$$\begin{cases}
{C_0+C_1=0} \\
{C_0e^{\sqrt k l}+C_1e^{-\sqrt k l}=0}
\end{cases}$$
$$k<0$$
$$y=C_0\cos (\sqrt{-k}x)+C_1 \sin(\sqrt{-k}x)$$
$$\begin{cases}
{C_0=0} \\
{\sin(\sqrt{-k}l)=0\implies k=-\dfrac{\pi^2 n^2}{l^2}}
\end{cases}$$
$$k=-\dfrac{\pi^2 n^2}{l^2}\quad n\in \mathbb Z$$
# Диффуры IDZ 7 (766,767,769-772)
## 766
$$y''+y'=f(x)$$
$$y(0)=0$$
$$y'(1)=0$$
$$y=C_0e^{-x}+C_1$$
$$\begin{cases}
C_0+C_1=0  \\
-\dfrac{C_0}{e}=0
\end{cases}$$
$$y_1=e^{-x}+1$$
$$y_2=1$$
$$G(x, s)=\begin{cases}
{a(s)(e^{-x}+1) \quad 0 \le x\le s} \\
{b(s) \quad s \le x \le 1}
\end{cases}$$
$$\begin{cases}
{a(s)(e^{-x}+1)=b(s)} \\
{a(s)e^{-x}=1}
\end{cases}$$
$$\begin{cases}
{b(s)=1+e^x} \\
{a(s)=e^x}
\end{cases}$$
$$G(x, s)=\begin{cases}
{e^s(e^{-x}+1) \quad 0 \le x\le s} \\
{(e{-s}+1) \quad s \le x \le 1}
\end{cases}$$
## 767
$$y''-y=f(x)$$
$$y'(0)=0$$
$$y'(2)+y(2)=0$$
$$y=C_0e^{-x}+C_1e^{x}$$
$$\begin{cases}
C_0=C_1  \\
-C_0e^{-2}+C_1e^{2}+C_0e^{-2}+C_1e^{2}=0
\end{cases}$$
$$\begin{cases}
C_0=C_1  \\
2C_1e^{2}=0
\end{cases}$$
$$y_1=e^{-x}+e^x$$
$$y_2=e^{-x}$$
$$G(x, s)=\begin{cases}
{a(s)(e^{-x}+e^{x}) \quad 0 \le x\le s} \\
{b(s)e^{-x} \quad s \le x \le 2}
\end{cases}$$
$$\begin{cases}
{a(s)(e^{-x}+e^{x})=b(s)e^{-x}} \\
{-b(s)e^{-x}=a(s)(-e^{-x}+e^{x})+1}
\end{cases}$$
$$\begin{cases}
{a(s)=-e^{-x}} \\
{b(s)=(e^{-x}+e^{x})}
\end{cases}$$
$$G(x, s)=\begin{cases}
{e^{-s}(e^{-x}+e^x) \quad 0 \le x\le s} \\
{(e^{-s}+e^s)e^{-x} \quad s \le x \le 2}
\end{cases}$$
## 769

$$x^2y''+2xy'=f(x)$$
$$y(1)=0$$
$$y'(3)=0$$
$$y=\dfrac{C_0}{x}+C_1$$
$$\begin{cases}
C_0=-C_1  \\
-\dfrac{C_0}{x^2}=0
\end{cases}$$
$$\begin{cases}
C_0=-C_1  \\
C_0=0
\end{cases}$$
$$y_1=\dfrac 1 x-1$$
$$y_2=1$$
$$G(x, s)=\begin{cases}
{a(s)(\dfrac 1 x - 1) \quad 1 \le x\le s} \\
{b(s) \quad s \le x \le 3}
\end{cases}$$
$$\begin{cases}
{a(s)(\dfrac{1}{s} - 1)=b(s)} \\
{0=-a(s)\dfrac{1}{s^2}+\dfrac{1}{s^2}}
\end{cases}$$
$$\begin{cases}
{b(s)=\dfrac{1}{s} - 1} \\
{a(s)=1}
\end{cases}$$
$$G(x, s)=\begin{cases}
{\dfrac 1 x - 1 \quad 1 \le x\le s} \\
{\dfrac 1 s - 1 \quad s \le x \le 3}
\end{cases}$$

## 770

$$xy''-y'=f(x)$$
$$y'(1)=0$$
$$y(2)=0$$
$$y=C_0x^2+C_1$$
$$\begin{cases}
2C_0 = 0 \\
4C_0+C_1=0
\end{cases}$$
$$y_1=1$$
$$y_2=4x^2-1$$
$$G(x, s)=\begin{cases}
{a(s) \quad 1 \le x\le s} \\
{b(s)(4x^2-1) \quad s \le x \le 2}
\end{cases}$$
$$\begin{cases}
{a(s)=b(s)(4s^2-1)} \\
{8b(s)s=\dfrac 1 s}
\end{cases}$$
$$\begin{cases}
{b(s)=\dfrac 1 {8s^2}} \\
{a(s)=\dfrac 1 2(1-\dfrac 1 {4s^2})}
\end{cases}$$
$$G(x, s)=\begin{cases}
{\dfrac 1 2 (1-\dfrac{1}{4s^2}) \quad 1 \le x\le s} \\
{\dfrac{1}{8s^2} (4x^2-1) \quad s \le x \le 2}
\end{cases}$$
## 771
$$x^2y''-2y=f(x)$$
$$y(1)=0$$
$$y(2)+2y'(2)=0$$
$$y=C_0x^2+\dfrac{C_1} x$$
$$\begin{cases}
C_0+C_1=0 \\
4C_0+\dfrac 1 2 C_1+8C_0-\dfrac 1 2 C_1=0
\end{cases}$$
$$\begin{cases}
C_0=-C_1 \\
C_0=0
\end{cases}$$
$$y_1=x^2-\dfrac 1 x$$
$$y_2=\dfrac 1 x$$
$$G(x, s)=\begin{cases}
{a(s) (x^2-\dfrac 1 x) \quad 1 \le x\le s} \\
{b(s)\dfrac 1 x \quad s \le x \le 2}
\end{cases}$$
$$\begin{cases}
{a(s)(s^2-\dfrac 1 s)=b(s)\dfrac 1 s} \\
{-b(s)\dfrac 1 {s^2}=a(s)(2s+\dfrac1 {s^2})+\dfrac 1 {s^2}}
\end{cases}$$
$$\begin{cases}
{b(s)=-\dfrac 1 {3s^3}(s^3-1)} \\
{a(s)=-\dfrac 1 {3s^3}}
\end{cases}$$
$$G(x, s)=\begin{cases}
{-\dfrac 1 {3s^3}(x^2-\dfrac 1 x) \quad 1 \le x\le s} \\
{-\dfrac 1 {3s^3}(s^3-1)\dfrac 1 x \quad s \le x \le 2}
\end{cases}$$
## 772
$$y''=f(x)$$
$$y(0)=0$$
$$y(+\infty)- ограничено$$
$$y=C_0x+C_1$$
$$\begin{cases}
C_1=0 \\
C_0=0
\end{cases}$$
$$y_1=x$$
$$y_2=1$$
$$G(x, s)=\begin{cases}
{a(s) x \quad 0 \le x\le s} \\
{b(s) \quad s \le x \le +\infty}
\end{cases}$$
$$\begin{cases}
{a(s)s=b(s)} \\
{a(s)=-1}
\end{cases}$$
$$\begin{cases}
{b(s)=-s} \\
{a(s)=-1}
\end{cases}$$
$$G(x, s)=\begin{cases}
{-x \quad 0 \le x\le s} \\
{-s \quad s \le x \le +\infty}
\end{cases}$$
# Диффуры IDZ 8 (882-888,899-906)
## 882
$$\dot{x}=-x,\quad\dot{y}=-2y$$
$$y'=2\dfrac{y}{x}$$
$$\ln y=\ln Cx^2$$
$$y=Cx^2$$
![[Pasted image 20250120221853.png]]
Нулевое решение асимптотически устойчиво

## 883
$$\dot{x}=x,\quad\dot{y}=2y$$
$$y'=2\dfrac{y}{x}$$
$$\ln y=\ln Cx^2$$
$$y=Cx^2$$
![[Pasted image 20250120221947.png]]
Нулевое решение не устойчиво

## 884
$$\dot{x}=-x,\quad\dot{y}=y$$
$$y'=-\dfrac{y} {x}$$
$$y=\dfrac C x$$
![[Pasted image 20250121092313.png]]
Нулевое решение не устойчиво

## 885
$$\dot{x}=-y,\quad\dot{y}=2x^3$$
$$y'=-2\dfrac{x^3}y$$
$$y^2+\dfrac{x^4}{2}=C$$
![[Pasted image 20250121092701.png]]
Нулевое решение устойчиво по Ляпунову, но не асимптотически

## 886
$$\dot{x}=y,\quad\dot{y}=-\sin x$$
$$y'=-\dfrac{\sin x}y$$
$$y^2=\cos x+C$$
![[Pasted image 20250121093507.png]]
Нулевое решение устойчиво по Ляпунову

## 887
$$\dot{x}=y,\quad\dot{y}=x^3(1+y^2)$$
$$y'=\dfrac{x^3(1+y^2)}{y}$$
$$\ln(y^2+1)=\dfrac{x^4}{2}+C$$
![[Pasted image 20250121101648.png]]
Нулевое решение не устойчиво

## 888
$$\dot{x}=-y\cos x,\quad\dot{y}=\sin x$$
$$y'=-y\tan x$$
$$y=C\cos x$$
![[Pasted image 20250121101157.png]]
Нулевое решение не устойчиво

## 899
$$\begin{cases}
{\dot x = 2xy-x+y} \\
{\dot y = 5x^4 + y^3 + 2x - 3y}
\end{cases}$$
$$\begin{cases}
{\dot x = -x+y} \\
{\dot y = 2x-3y}
\end{cases}$$
$$\begin{pmatrix}
{-1-\lambda} && {1} \\
{2} && {-3-\lambda}
\end{pmatrix}$$
$$\lambda^2 + 4\lambda + 1 = 0$$
$$\lambda = -2\pm\sqrt{3}$$
Нулевое решение асимптотически устойчиво

## 900
$$\begin{cases}
{\dot x = x^2+y^2-2x} \\
{\dot y = 3x^2-x+3y}
\end{cases}$$
$$\begin{cases}
{\dot x = -2x} \\
{\dot y = -x+3y}
\end{cases}$$
$$\begin{pmatrix}
{-2-\lambda} && {0} \\
{-1} && {3-\lambda}
\end{pmatrix}$$
$$\lambda_{1, 2} = -2, 3$$
Нулевое решение неустойчиво

## 901
$$\begin{cases}
{\dot x = e^{x+2y}-\cos 3x} \\
{\dot y = \sqrt{4+8x}-2e^y}
\end{cases}$$
$$\begin{cases}
{\dot x = x+2y } \\
{\dot y = 2x-2y}
\end{cases}$$
$$\begin{pmatrix}
{1-\lambda} && {2} \\
{2} && {-2-\lambda}
\end{pmatrix}$$
$$\lambda^2 + \lambda - 6 = 0$$
$$\lambda = \dfrac{-1\pm5}{2}$$
Нулевое решение не устойчиво

## 902
$$\begin{cases}
{\dot x = \ln (4y+e^{-3x})} \\
{\dot y = 2y-1+\sqrt[3]{1-6x}}
\end{cases}$$
$$\begin{cases}
{\dot x = -3x+4y } \\
{\dot y = -6x+2y }
\end{cases}$$
$$\begin{pmatrix}
{-3-\lambda} && {4} \\
{-6} && {2-\lambda}
\end{pmatrix}$$
$$\lambda^2 + \lambda + 18 = 0$$
$$\lambda = \dfrac{-1\pm \sqrt{-71}}{2}$$
Нулевое решение асимптотически устойчиво

## 903
$$\begin{cases}
{\dot x = \ln (3e^y-2\cos x)} \\
{\dot y = 2e^x-\sqrt[3]{8+12y}}
\end{cases}$$
$$\begin{cases}
{\dot x = 3y } \\
{\dot y = 2x-3 y }
\end{cases}$$
$$\begin{pmatrix}
{-\lambda} && {3} \\
{2} && {-3-\lambda}
\end{pmatrix}$$
$$\lambda^2 + 3 \lambda - 6 = 0$$
$$\lambda = \dfrac{-3\pm \sqrt{33}}{2}$$
Нулевое решение не устойчиво

## 904
$$\begin{cases}
{\dot x = \tan(y-x)} \\
{\dot y = 2^y-2\cos(\dfrac \pi 3 - x)}
\end{cases}$$
$$\begin{cases}
{\dot x = -x+y } \\
{\dot y = -\sqrt 3x+\ln(2)y }
\end{cases}$$
$$\begin{pmatrix}
{-1-\lambda} && {1} \\
{-\sqrt3} && {\ln(2)-\lambda}
\end{pmatrix}$$
$$\lambda^2 - (\ln 2-1) \lambda -\ln2 - \sqrt3 = 0$$
$$\begin{cases}
{\lambda_1+\lambda_2=\ln 2-1} \\
{\lambda_1\cdot\lambda_2=-\ln 2 -\sqrt 3}
\end{cases}$$

Нулевое решение не устойчиво

## 905
$$\begin{cases}
{\dot x = \tan(z-y)-2x} \\
{\dot y = \sqrt{9+12x}-3e^y} \\
{\dot z = -3y}
\end{cases}$$
$$\begin{cases}
{\dot x = -2x - y + z} \\
{\dot y = 2x-3y} \\
{\dot z = -3y}
\end{cases}$$
$$\begin{pmatrix}
{-2-\lambda} && {-1} && {1} \\
{2} && {-3-\lambda} && {0} \\
{0} && {-3} && {-\lambda}
\end{pmatrix}$$
$$-\lambda^3 - 5 \lambda^2 + 4 \lambda - 6 = 0$$
![[Pasted image 20250121195603.png]]

Нулевое решение не устойчиво

## 906
$$\begin{cases}
{\dot x = e^x-e^{-3z}} \\
{\dot y = 4z-3\sin(x+y)} \\
{\dot z = \ln(1+z-3x)}
\end{cases}$$
$$\begin{cases}
{\dot x = x+3y} \\
{\dot y = x+y+4z} \\
{\dot z = -3x+z}
\end{cases}$$
$$\begin{pmatrix}
{1-\lambda} && {3} && {0} \\
{1} && {1-\lambda} && {4} \\
{-3} && {0} && {1-\lambda}
\end{pmatrix}$$
$$(1-\lambda)^3+3(1-\lambda)-36 = 0$$
![[Pasted image 20250121200242.png]]

Нулевое решение не устойчиво








