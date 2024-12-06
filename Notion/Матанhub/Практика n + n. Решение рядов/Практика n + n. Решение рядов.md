---
Редакторы: Artemii
Тэги:
  - II семестр
  - Практика
Статус: В процессе
---
### №1

$\mathsf{  
\underset{n = 1}{\overset \infin \sum} \dfrac{(-1)^n}{\cos(\dfrac \pi {3 \sqrt n}) \cdot \sqrt[3]{3n + \ln(n)}}  
}$

  

==**Признак Лейбница:**==

$\mathsf{  
\underset{n = 1}{\overset \infin \sum} (-1)^n a_n - cx  
}$ $\mathsf{\iff a_n\ge0}$ и $\mathsf{a_n}$ равномерно $\mathsf{\to 0}$

  

$\mathsf{  
\sum \dfrac 1 {\cos(\dfrac \pi {3 \sqrt n}) \sqrt[3]{3n + \ln(n)}}  
}$

![[/Untitled 48.png|Untitled 48.png]]

  

$\mathsf{  
\dfrac 1 {\cos(\dfrac \pi {3 \sqrt n}) \sqrt[3]{3n + \ln(n)}} \underset{n \to \infin}\sim \dfrac 1 {\sqrt[3]n}  
}$

и $\mathsf{  
\sum \dfrac 1 {n^\frac 1 3}  
}$ - расходится (так как $\mathsf{  
\dfrac 1 3 \lt 1  
}$)

$\mathsf{  
\sqrt[3]{n + \ln(n)} \underset{n \to \infin} \sim \sqrt[3] n  
}$

$\mathsf{  
\dfrac{\sqrt[3]{n + \ln(n)}}{\sqrt[3] n} = \sqrt[3]{1 + \dfrac{\ln(n)} n} \underset{n \to \infin} \to 1  
}$

Сходится так как $\mathsf{  
\dfrac 1 {\cos(\dfrac \pi {3 \sqrt n}) \sqrt[3]{3n + \ln(n)}} -  
}$монотонно $\to 0$

  

### №2

$\mathsf{  
\underset{n = 1}{\overset \infin \sum} \dfrac{(2 + \cos(\dfrac{n\pi}2)\sqrt n}{\sqrt[4]{n^7 + 5}}  
}$

  

$\mathsf{  
0 \le \dfrac{(2 + \cos(\dfrac{\pi n} 2)\sqrt n}{\sqrt[4]{n^7 + 5}} \le \dfrac{3 \sqrt n}{n^{\frac 7 4} } = \dfrac 3 {n^{\frac 5 4}}  
}$

и $\mathsf{  
\sum \dfrac 3 {n^{\frac 5 4}} = 3 \sum \dfrac 1 {n^{\frac 5 4}}  
}$ - сходится, т. к. $\mathsf{  
\dfrac 5 4 \gt 1  
}$

  

### №3

$\mathsf{  
\underset{n = 1}{\overset \infin \sum} \dfrac{n!}{(2n)!} \tg(\dfrac 1 {5^n})  
}$

$\mathsf{  
\dfrac{n!}{(2n)!} \cdot \tg(\dfrac 1 {5^n}) \underset{n \to \infin} \sim \dfrac{n!}{(2n)!} \cdot \dfrac{1}{5^n}  
}$

$\mathsf{  
\underset{n = 1}{\overset \infin \sum} \dfrac{n!}{(2n)!} \cdot \dfrac 1 {5^n}  
}$

  

$\mathsf{  
D_n = \dfrac {a_{n + 1}}{a_n} = \dfrac{(n + 1)! (2n)! 5^n}{(2n + 2)! 5^n n!} = \dfrac{n + 1}{5 (2n + 2)(2n + 1)} \le \dfrac{2n}{20 n^2} \dfrac 1 {10n} \underset{n \to \infin} \to 0 < 1  
}$ - ряд сходится

  

### №4

$\mathsf{  
\overset \infin \sum \dfrac{(-1)^{n + 1}}{\ln(n + 1)}  
}$

  

$\mathsf{  
\underset{n = 1}{\overset \infin \sum} \dfrac 1 {\ln(n + 1)}  
}$

$\mathsf{  
\dfrac 1 {\ln(n + 1)} > \dfrac 1 {n + 1}  
}$

и $\mathsf{  
\sum \dfrac 1 {n + 1}  
}$ - расходится

  

$\mathsf{  
(\ln(x))' = \dfrac 1 x > 0 \to \ln(x) \uparrow  
\implies \dfrac 1 {\ln(n + 1)} \downarrow 0\implies}$сходится

  

  

### №5

$\mathsf{  
\underset 1 {\overset \infin \sum} \dfrac{(n!)^2}{2^{n^2}}  
}$

  

$\mathsf{  
D_n = \dfrac{a_{n + 1}}{a_n} = \dfrac{((n + 1)!)^2 2^{n^2}}{2^{(n + 1)^2 \cdot (n!)^2}} = \dfrac{(n + 1)^2}{2^{2n + 1}} \le \dfrac{(2n)^2}{2 \cdot 4^n} = 2 \dfrac{n^2}{4^n} \underset{n \to \infin} \to 0 < 1  
}$ → расходится по правилу Дальмбера.

  

### №6

  

  

### №7

$\mathsf{  
\sum \dfrac{n!}{2^{n^2}}  
}$

$\mathsf{  
D_n = \dfrac{a_{n + 1}}{a_n} = \dfrac{(n + 1)! \cdot 2^{n^2}}{2^{(a + 1)^2} \cdot n!} = \dfrac{n + 1}{2^{n + 1}} \underset{n \to + \infin} \to 0 < 1  
}$ - сходится по Деламберу

$\mathsf{  
2^{(n + 1)^2} = 2^{n^2 + 2n + 1}  
}$

  

  

### №8

$\mathsf{  
\sum \dfrac 1 {(3n - 5) \ln^2(4n - 7)}  
}$

  

$\mathsf{  
\dfrac 1 {(3n - 5) \ln^2 (4n - 7)} \underset{n \to \infin} \sim \dfrac 1 {3n \cdot \ln(n)^2}  
}$

$\mathsf{  
\ln^2(4n - 7) \sim \ln^2(4n) = (\ln(4) + \ln(n))^2 \sim \ln^2(n)  
}$

  

==**Коши-Маклорен**==

$\mathsf{  
\underset{n = k} \sum a_n  
}$

$\mathsf{  
a_n \downarrow 0  
}$ и $\mathsf{  
f(x) \downarrow 0  
}$ $\mathsf{f(n) = a_n}$

(монотонно убывает к 0)

$\mathsf{  
\sum a_n - cx \iff \underset k {\overset \infin \int} f(x) dx - cx  
}$

  

$\mathsf{  
f(x) = \dfrac 1 {3x \ln^2(x)} \underset{x > 3 \to \infin}\downarrow 0  
}$

$\mathsf{  
f(n) = \dfrac 1 {3n \ln^2(n)}  
}$

  

$\mathsf{  
\dfrac 1 3 \underset 3 {\overset \infin \int} \dfrac 1 {x \ln^2 (x)}dx = \dfrac 1 3 \underset{A \to \infin}\lim \underset 3 {\overset A \int} \dfrac {dx}{x \ln^2(x)} = \dfrac 1 {3 \ln(3)} - cx  
}$

  

### №9

$\mathsf{  
\underset 1 {\overset \infin \sum} \ln(\dfrac{n^3}{n^3 + 1})  
}$

  

$\mathsf{  
\ln(\dfrac{n^3}{n^3 + 1}) = \ln(\dfrac{n^3 + 1 - 1}{n^3 + 1}) = \ln(1 - \dfrac 1 {n^3 + 1})  
}$

  

$\mathsf{  
\ln(1 + x) \underset{x \to 0} \sim x  
}$

  

$\mathsf{  
\begin{cases}  
\mathsf{\sin(x) \sim x} \\  
\mathsf{a^x - 1 \sim x \ln(a)} \\  
\mathsf{\log_a(1 + x) \sim \dfrac x {\ln(a)}} \\  
\mathsf{(1 + x)^\alpha - 1 \sim \alpha x}  
\end{cases}  
}$

$\mathsf{  
\sum \dfrac 1 {n^3}  
}$ - сходится

$\mathsf{  
\sum q^n  
}$ - сходится $\mathsf{  
\iff |q| < 1  
}$

$\mathsf{  
\sum \dfrac 1 {n^ \alpha}  
}$ - сходится $\mathsf{  
\iff \alpha > 1  
}$

$\mathsf{  
\sum \dfrac 1 {n^ \alpha \ln^\beta n} -  
\begin{cases}  
\mathsf{\alpha > 1} & \mathsf{сходится} \\  
\mathsf{\alpha < 1} & \mathsf{расходится} \\  
\mathsf{\alpha = 1} & \begin{cases}  
\mathsf{\beta > 1} & \mathsf{сходится} \\  
\mathsf{\beta \le 1} & \mathsf{расходится}  
\end{cases}  
\end{cases}  
}$

  

  

Ввод $\mathsf{ \epsilon > 0}$

  

$\begin{matrix}  
\mathsf{\sum = 0} \\  
\mathsf{a_n = - \dfrac 1 2} \\  
\mathsf{d_n = 2} \\  
\mathsf{n = 1} \\  
\mathsf{R_n = 1}  
\end{matrix}$

  

$\mathsf{  
\sum+= a_n  
}$

  

$\mathsf{  
d_n \cdot=2  
}$

  

$\mathsf{  
R_n = \dfrac n {d_n}  
}$

  

$\mathsf{  
R_n < \epsilon  
}$

Если да, вывод $\sum$

Если нет

$\mathsf{  
n ++  
}$

$\mathsf{  
z_n \cdot= -1  
}$

$\mathsf{  
a_n = -R_n  
}$

Возвращение на этап $\mathsf{\sum += a_n}$