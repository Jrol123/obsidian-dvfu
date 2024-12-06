---
Редакторы: Serepok
Тэги:
  - Информация
Статус: В процессе
---
  

### 1. Замена переменной

- Пусть функция $\mathsf  
    {  
    t = \phi(x)  
    }$ определена и дифференцируема на множестве E, определённая на множестве значений D, имеет первообразную $\mathsf{F(t)}$.
- Тогда функция $\mathsf  
    {  
    f(\phi(x)) \cdot \phi`(x)  
    }$ имеет первообразную $\mathsf  
    {  
    F(\phi(x))  
    }$, т. е.
- $\mathsf  
    {  
    \int f(\phi(x)) \cdot \phi`(x)dx = F(\phi(x)) + C  
    }$

### 2. Интегралы, содержащие квадратный трёхчлен

$\mathsf  
{  
I_1 = \int \frac{dx}{ax^2 + bx + c}  
}$

$\mathsf  
{  
I_2 = \int \frac{(Ax + B) dx}{ax^2 + bx + c}  
}$

$\mathsf  
{  
I_3 = \int \frac{dx}{\sqrt{ax^2 + bx + c}}  
}$

$\mathsf  
{  
I_4 = \int \frac{(Ax + B)dx}{\sqrt{ax^2 + bx + c}}  
}$

  

1. Вынести за интеграл коэффициент при $\mathsf{x^2}$ в $\mathsf{I_1 ~и~ I_2}$ выносится а,  
    В  
    $\mathsf  
    {  
    I_3 ~и~ I_4  
    }$ выносится $\mathsf  
    {  
    \sqrt{|a|}  
    }$
    1. $\mathsf  
        {  
        ax^2 + bx + c = a(x^2 + \frac{b}{a}x + \frac{c}{a})  
        = a(x^2 + px + q)  
        }$
    2. $\mathsf  
        {  
        ax^2 + bx + c = |a|(\pm x^2 + \frac{b}{|a|}x + \frac{c}{|a|})  
        = |a|(\pm x^2 + px + q)  
        }$

  

1. Выделение полного квадрата
    1. $\mathsf  
        {  
        x^2 + px + q = x^2 + 2x \frac{p}{2} + \left( \frac{p}{2} \right)^2 - \left( \frac{p}{2} \right)^2 + q = (x + \frac{p}{2})^2 - (\frac{p}{2})^2 + q  
        }$
    2. $\mathsf  
        {  
        -x^2 + px + q = -(x^2 - 2x \frac{p}{2} + \left( \frac{p}{2} \right)^2 - \left( \frac{p}{2} \right)^2 - q) = -(x - \frac{p}{2})^2 + (\frac{p}{2})^2 + q  
        }$

  

1. Замена переменной
    
    1. $\mathsf  
        {  
        t = x + \frac{p}{2}  
        }$ или $\mathsf  
        {  
        t = x - \frac{p}{2}  
        }$
    2. $\mathsf  
        {  
        dt = dx  
        }$
    
      
    
2. Разложение на сумму двух интегралов
    
    1. $\mathsf  
        {  
        \int \frac{t \cdot dt}{t^2 \pm m^2}  
        }$ и $\mathsf  
        {  
        \int \frac{dt}{t^2 \pm m^2}  
        }$
    2. $\mathsf  
        {  
        \int \frac{t \cdot dt}{\sqrt{\pm t^2 \mp m^2)}}  
        }$ и $\mathsf  
        {  
        \int \frac{dt}{\sqrt{\pm t^2 \mp m^2}}  
        }$
    
    $\mathsf{m = (\frac{p}{2})^2+q}$
    

  

1. Возвращение к переменной x

  

- Замечание:
    
    Интеграл вида: $\mathsf  
    {  
    I = \int \frac{dx}{(x + \alpha)^r \cdot \sqrt{ax^2 + bx + c}}  
    }$, где $\mathsf {r = 1 \ или \ 2}$
    
    Сводится к интегралу $\mathsf  
    {  
    I_3 ~или~ I_4  
    }$ заменой переменной
    
    $\mathsf  
    {  
    t = \frac{1}{x + \alpha}  
    }$
    

### 3. Интегрирование по частям

Пусть функции $\mathsf{u(x) \ и \ v(x)}$ дифференцируемы на множестве E и на множестве E существует первообразная функции $\mathsf{V(x) \cdot u`(x)}$, тогда на множестве E существует первообразная функции $\mathsf{U(x) \cdot v`(x)}$ и выполняется неравенство

$$\mathsf  
{  
\int u(x) \cdot v`(x)dx = u(x) \cdot v(x) - \int v(x) \cdot u`(x)dx  
}$$

Или

$$\mathsf  
{  
\int u \cdot dv = u\cdot v - \int v \cdot du  
}$$

  

### 4. Простейшие тригонометрические функции

$$\mathsf  
{  
\int \sin^n(x) \cdot \cos^m(x) dx  
}$$

1. $\mathsf{n}$ или $\mathsf{m}$ - нечётное положительное, то замена переменной
    
    $\mathsf  
    {  
    \begin{matrix}  
    \mathsf{n = 2k + 1} & \mathsf{t = \cos(x)} & \mathsf{dt = - \sin(x) dx} & \mathsf{\sin^2(x) = 1 - \cos^2(x)} \\  
    \mathsf{m = 2k+1} & \mathsf{t = \sin (x)} & \mathsf{dt = \cos (x)dx} & \mathsf{\cos^2(x)=1-\sin^2(x)}  
    \end{matrix}  
    }$
    
2. $\mathsf{n}$ и $\mathsf{m}$ - чётные положительные, то понижение степени
    
    $\mathsf  
    {  
    \begin{matrix}  
    \mathsf{\sin^2(x) = \frac{1}{2}(1-\cos(2x))} &  
    \mathsf{\cos^2(x)=\frac{1}{2}(1+\cos(2x))} &  
    \mathsf{\sin(x)\cdot \cos (x) = \frac{1}{2}\sin(2x)}  
    \end{matrix}  
    }$
    

3. $  
$$\mathsf{n+m}$ - четное отрицательное, то замена переменной

$\mathsf  
{  
t=\tg(x)  
}$ или $\mathsf  
{  
t=\ctg(x)\quad\frac{1}{\cos^2(x)}=1+\tg^2(x)\quad\frac{1}{\sin^2(x)}=1+\ctg^2(x)  
}$

4. $\mathsf  
{  
n + m  
}$ - нечётная отрицательная, то повышение степени

$\mathsf{  
1 = \sin^2(x)+\cos^2(x)  
}$

  

$$\mathsf  
{  
\int \tg^n(x) dx\quad \quad \int \ctg^m(x) dx  
}$$

Используются формулы: $\mathsf  
{  
\tg^2(x) = \frac 1 {\cos^2(x)} - 1  
\quad \quad \ctg^2(x) = \frac 1 {\sin^2(x)} - 1  
}$

  

$$\mathsf  
{  
\int \sin^n(\alpha x) \cdot \cos^m (\beta x) dx  
}$$

(где n и m - целые числа)

  

Используются формулы:

$\mathsf  
{  
\sin(\alpha) \cdot \cos(\beta) = \frac 1 2 (\sin(\alpha - \beta) + \sin(\alpha + \beta))  
}$

$\mathsf  
{  
\sin (\alpha) \cdot \sin(\beta) =  
\frac 1 2 (\cos(\alpha - \beta) - \cos(\alpha + \beta))  
}$ $\mathsf  
{  
\cos(\alpha) \cdot \cos(\beta) =  
\frac 1 2 (\cos(\alpha - \beta) + \cos (\alpha + \beta))  
}$

### 5. Тригонометрические подстановки

Интегрирование рациональных функций от x и от $\mathsf  
{  
\sqrt{x^2 \pm a^2}  
}$ или $\mathsf{\sqrt{a^2 - x^2}}$

1. $\mathsf  
    {  
    \int R(x, \sqrt{a^2 - x^2})dx  
    }$
    
    Замена переменной:
    
    $\mathsf  
    {  
    x = a \cdot \sin(t) ~ или ~\mathsf  
    {  
    x = a \cdot \cos(t)  
    }; \quad  
    dx = a \cdot \cos(t) dt; \quad \sqrt{a^2 - x^2} = \sqrt{a^2 - a^2\sin^2(t)} = a \cdot \cos(t)  
    }$  
      
    $\mathsf  
    {  
    t = \arcsin(\frac x a)  
    }$  
    (или )  
    
2. $\mathsf  
    {  
    \int R(x, \sqrt{x^2 + a^2})dx  
    }$
    
    Замена переменной:
    
    $\mathsf  
    {  
    x = a \cdot \tg (t); \quad  
    dx = \frac{a \cdot dt} {\cos^2(t)}; \quad  
    \sqrt{x^2 + a^2} = \sqrt{a^2 \cdot \tg^2(t) + a^2} = \frac a {\cos(t)}  
    }$  
      
    $\mathsf  
    {  
    t = \arctg (\frac x a)  
    }$
    
3. $\mathsf  
    {  
    \int R(x, \sqrt{x^2 - a^2})  
    }$
    
    Замена переменной: $\mathsf  
    {  
    x = \frac a {\cos(t)}; \quad  
    dx = \frac{a \cdot \sin(t)}{\cos^2(t)} dt; \quad  
    \sqrt{x^2 - a^2} = \sqrt{\frac{a^2}{\cos^2(t)} - a^2} = a \cdot \tg(t)  
    }$  
      
    $\mathsf  
    {  
    t = \arccos (\frac a x)  
    }$
    

### 6. Рациональные дроби

Пусть $\mathsf{\frac{P(x)}{Q(x)}}$ - правильная рациональная функция, и вещественные числа $\mathsf  
{  
a_1, a_2, \ldots, a_r  
}$ являются корнями $\mathsf{Q(x)}$ кратности $\mathsf  
{  
\alpha_1, \alpha_2, \ldots, \alpha_r  
}$, а комплексные числа $\mathsf  
{  
z_1, z_2, \ldots, z_s  
}$ являются корнями $\mathsf{Q(x)}$ кратности $\mathsf  
{  
\beta_1, \beta_2, \ldots, \beta_r  
}$, т. е.

  

$\mathsf  
{  
Q(x) = (x - a_1)^{\alpha_1} \cdot (x - a_2)^{\alpha_2} \cdot \ldots \cdot  
}$

$\mathsf  
{  
\cdot (x - a_r)^{\alpha_r} \cdot (x^2 + p_1 x + q_1)^{\beta_1} \cdot (x^2 + p_2 x + q_2)^{\beta_2} \cdot \ldots \cdot (x^2 + p_s x + q_s)^{\beta_s}  
}$

Тогда существуют вещественные числа $\mathsf  
{  
A_i^{(\alpha)}; \quad  
M_j^{(\beta)}; \quad  
N_j^{(\beta)}  
}$, где $\mathsf  
{  
i = 1, 2, \ldots, \alpha_i; \quad j = 1, 2, \ldots, \beta_j  
}$ при которых выполняется равенство:

$\mathsf{\frac{P(x)}{Q(x)} =  
\frac{A^{(\alpha_1)}_{1}}{(x-a_1)^{\alpha_1}}  
+ \frac{A^{(\alpha1)}_{2}}{(x-a_1)^{\alpha_1-1}}+\cdots  
+ \frac{A^{(\alpha_1)}_{\alpha_1}}{(x-a_1)}  
+ \frac{A^{(\alpha_2)}_{1}}{(x-a_2)^{\alpha_{2}}}  
+ \frac{A^{(\alpha_2)}_{2}}{(x-a_2)^{\alpha_{2}-1}}+\cdots  
+ \frac{A^{(\alpha_2)}_{\alpha_2}}{(x-a_2)}+\cdots+  
}$

$\mathsf{  
+ \frac{A^{(\alpha_r)}_{1}}{(x-a_r)^{\alpha_{r}}}  
+ \frac{A^{(\alpha_r)}_{2}}{(x-a_r)^{\alpha_{r}-1}}+\cdots  
+ \frac{A^{(\alpha_r)}_{\alpha_r}}{(x-a_r)}+  
  
}$$\mathsf{\frac{M^{(\beta_1)}_{1}\cdot x+N^{(\beta_1)}_{1}}{(x^2+p_1\cdot x + q_1)^{\beta_1}}+}$$\mathsf{\cdots +\frac{M^{(\beta_1)}_{\beta_1}\cdot x+N^{(\beta_1)}_{\beta_1}}{(x^2+p_1\cdot x + q_1)}}+\cdots +$

$\mathsf{  
\frac{M^{(\beta_s)}_{1}\cdot x+N^{(\beta_s)}_{1}}{(x^2+p_s\cdot x + q_s)}+\cdots +  
}$$\mathsf{  
\frac{M^{(\beta_s)}_{\beta_s}\cdot x+N^{(\beta_s)}_{\beta_s}}{(x^2+p_s\cdot x + q_s)}  
}$.

### 7. Элементарные дроби

$\mathsf  
{  
\begin{matrix}  
\mathsf{1)} & \mathsf{k = 1} && \mathsf{\int \frac{Adx}{x - a} = A \cdot \ln |x - a| + c} \\  
\mathsf{2)} & \mathsf{k = 2, 3, \ldots} && \mathsf{\int \frac{Adx}{(x - a)^k} = \frac{-A}{(k - 1)(x - a)^{k - 1}} + c} \\  
\mathsf{3)} & \mathsf{k = 1} && \mathsf{\int\frac{Ax + B}{x^2 + px + q}dx = \int\frac{Ax + B}{(x + \frac p 2)^2 - \underset{>0}{\underbrace{\frac{p^2}{4} + q}}} =  
\begin{vmatrix}  
\mathsf{t = x + \frac p 2} \\  
\mathsf{x = t - \frac p 2} \\  
\mathsf{dx = dt}  
\end{vmatrix}} \\  
\mathsf{4)} & \mathsf{k = 2, 3, \ldots} && \mathsf{\int \frac{Ax + B}{(x^2 + px + q)^k}dx} =  
\begin{vmatrix}  
\mathsf{t = x + \frac p 2} \\  
\mathsf{x = t - \frac p 2} \\  
\mathsf{dx = dt}  
\end{vmatrix}  
\end{matrix}  
}$

Рекуррентная формула нахождения интеграла:

$$\mathsf  
{  
I_{k + 1} = \frac{t}{2km^2(t^2 + m^2)^k} + \frac{2k - 1}{2km^2} I_k  
}$$

### 8. Универсальная тригонометрическая подстановка

Т. к. $\mathsf  
{  
\tg(x) = \frac{\sin(x)}{\cos(x)}; \quad \ctg(x) = \frac{\cos(x)}{\sin(x)}  
}$, то рациональную функцию относительно тригонометрической функции можно привести к виду $\mathsf  
{  
R(\sin(x), \cos(x))  
}$ - рациональной относительно $\mathsf{\sin(x)}$ и $\mathsf  
{  
\cos(x)  
}$. Такая функция сводится к рациональной с помощью универсальной тригонометрической подстановки:

$\mathsf  
{  
t = \tg(\frac x 2)  
}$

**Замечание**

При чётной степени $\mathsf  
{  
t = \tg(x)  
}$

### 9. Дробно линейные иррациональности

Рассмотрим функцию $\mathsf{R(x,(\frac{ax+b}{cx+d})^{r_1},(\frac{ax+b}{cx+d})^{r_2}, \cdots, (\frac{ax+b}{cx+d})^{r_s})}$

где $\mathsf{r_1, r_2, \cdots, r_s}$ - рациональное число; $\mathsf{  
\begin{vmatrix}  
\mathsf{a} & \mathsf{b} \\  
\mathsf c & \mathsf d  
\end{vmatrix} \not = 0  
};$ $\mathsf{a, b, c, d}$ - константы;

Обозначим общий знаменатель дробей $\mathsf  
{  
r_1, r_2, \ldots, r_s  
}$ буквой m, тогда $\mathsf  
{  
r_i = \frac{P_i}{m}  
}$, где

$\mathsf{P_i}$ - целые числа. Замена переменной $\mathsf  
{  
t^m = \frac{ax + b}{cx + d}  
}$ приводит интеграл от данной функции к интегралу от рациональной функции.

Действительно: $\mathsf  
{  
(\frac{ax + b}{cx + d})^{r_i} = t^{m \cdot r_i} = t^{m \cdot\frac{P_i}{m}} = t^{P_i}  
}$

Найдём x: $\mathsf  
{  
(cx +d)^m t = ax + b; \quad  
ct^m x - ax = b - d \cdot t^m; \quad  
x = \frac{b - d \cdot t^m}{c \cdot t^m - a}  
}$ - рациональная функции.

Т. к. производная от рациональной функции является рациональной функцией, то $\mathsf  
{  
dx = (\frac{b - dt^m}{ct^m - a})' \cdot dt  
}$ является рациональной функцией.

В частном случае этим методом интегрируются функции вида:

$\mathsf  
{  
R(x, (ax + b)^{r_1}, (ax + b)^{r_2}, \ldots, (ax + b)^{r_s})  
}$ или $\mathsf  
{  
R(x, x^{r_1}, x^{r_2}, \ldots, x^{r_s})  
}$

### 10. Подстановки Чебышева

**Биноминальный дифференциал**

$\mathsf{x^m(a+bx^n)^p}$, где $\mathsf{m, n, p} $ - рациональные числа

  

**Биноминальный дифференциал** интегрируется (рационализируется) только в 3 случаях:

  

1. Если p - целое число. То возведя бином $\mathsf{(a+bx^n)}$ в степень $\mathsf{p}$ получим рациональную функцию от радикалов:
    
    $\mathsf{R(x,x^r_1, x^r_2,\cdots, x^r_s)}$ и заменой $\mathsf{x = t^k}$, где $\mathsf{k}$ - общий знаменатель дробей $\mathsf  
    {  
    r_1, r_2, \ldots, r_s  
    }$ приводится к рациональной функции.
    
      
    
2. Число $\mathsf  
    {  
    \frac{m + 1} n  
    }$ - целое, тогда используется подстановка $\mathsf  
    {  
    z = (a + bx^n)^{\frac 1 s}  
    }$, где $\mathsf s$ - знаменатель числа $\mathsf p $ ($\mathsf p$ - дробное число).
    
    Тогда: $\mathsf  
    {  
    z^s = a + bx^n; \quad (\frac{z^s - a}{b})^{\frac 1 n} = x; \quad dx = \frac 1 n(\frac{z^s - a}{b})^{\frac 1 n - 1} \cdot s \cdot z^{s - 1} dz  
    }$
    
3. Если $\mathsf{\frac {m+1}{n}+p}$ - целое число, то $\mathsf{z=(\frac{a}{x^n}+b)^\frac 1 s  
    }$, где $\mathsf{s}$ знаменатель числа $\mathsf p$.

Найдем $\mathsf x$:

$\mathsf{z^s = \frac {a}{x^n}+b; x^n = \frac{a}{z^s-b}; x = \frac{a^\frac 1 n}{(z^s-b)^\frac 1 n}}$;

Тогда:

$\mathsf{  
dx = - \frac 1 n a^{\frac 1 n} (z^s-b)^{- \frac1 n - 1}sz^{s-1}dz  
}$

### 11. Подстановки Эйлера

Интеграл вида $\mathsf  
{  
\int R(x, \sqrt{ax^2 + bx + c})dx  
}$ сводится с помощью подстановок Эйлера к интегралу от рациональной функции.

  

1. Квадратный трёхчлен $\mathsf{ax^2+bx+c}$ имеет комплексные корни и коэффициенты $\mathsf{a>0}$.
    
    Тогда используется подстановка: $\mathsf{\sqrt{ax^2+bx+c}=\pm t~ \pm \sqrt a \cdot x}$, знаки используются в любой комбинации.
    
    Выразим x:
    
    Возведём обе части в квадрат:
    
    $\mathsf{  
    ax^2+bx+c=t^2 \pm 2 \sqrt a \cdot x\cdot t+ax^2  
    }$
    
    $\mathsf  
    {  
    bx \mp 2\sqrt a xt = t^2 - c  
    }$, Тогда $\mathsf  
    {  
    x = \frac{t^2 - c}{b \mp 2\sqrt a\cdot t} = R_1(t)  
    }$ - рациональная функция от t
    
    Дифференцируя x получим: $\mathsf  
    {  
    dx = R'_1(t) dt  
    }$, производная $\mathsf  
    {  
    R_1'(t)  
    }$ рациональной функции является рациональной функцией.
    
    При этом:
    
    $\mathsf  
    {  
    \sqrt{ax^2 + bx + c} = \pm t~ \pm \sqrt a \cdot R_1(t) = R_2(t)  
    }$ - рациональная функция
    
    Интеграл примет вид:
    
    $\mathsf{\int R(x, \sqrt{ax^2+bx+c})\cdot dx = \int R(R_1(t), R_2(t))\cdot R_1' (t) \cdot dt}$
    
    является интегралом от рациональной функции, т. к. суперпозиция рациональных функций есть рациональная функция.
    
2. Квадратный трёхчлен имеет действительные корни
    1. **Корни квадратные**, т. е. $\mathsf  
        {  
        x_1 = x_2  
        }$, тогда $\mathsf  
        {  
        ax^2 + bx + c = a(x - x_1)^2  
        }$
        
        Значит $\mathsf  
        {  
        \sqrt{ax^2 + bx + c} = \sqrt{a(x - x_1)^2} = \sqrt a \cdot |x - x_1|  
        }$
        
        Если при этом $\mathsf  
        {  
        a < 0  
        }$, то подынтегральная функция имеет оба определения только в комплексных числах.
        
        Если $\mathsf  
        {  
        a > 0  
        }$, то подынтегральная функция не содержит иррациональности, но имеет две формулы $\mathsf{  
        x \ge x_1  
        }$ и $\mathsf {x < x_1}$
        
    2. **Корни различные** $\mathsf  
        {  
        x_1 \ne x_2  
        }$, тогда $\mathsf  
        {  
        ax^2 + bx + c = a(x - x_1)(x - x_2)  
        }$
        
        Тогда используется вторая подстановка Эйлера: $\mathsf  
        {  
        t = \frac{\sqrt{ax^2 + bx + c}}{x - x_1}  
        }$
        
        Возводим в квадрат $\mathsf  
        {  
        t^2 = \frac{ax^2 + bx + c}{(x - x_1)^2} = \frac{a(x - x_1)(x - x_2)}{(x - x_1)^2}  
        }$; $\mathsf  
        {  
        t^2 = \frac{a(x - x_2)}{x - x_1}  
        }$
        
        Выразим x: $\mathsf  
        {  
        t^2x - t^2x_1 = ax - ax_2; \  
        x = \frac{t^2 x_1 - ax_2}{t^2 - a} = R_3(t)  
        }$ - рациональная функция.
        
        Тогда $\mathsf  
        {  
        dx = R3'(t) dt  
        }$ - рациональная функция
        
        $\mathsf  
        {  
        \sqrt{ax^2 + bx + c} = t \cdot(x - x_1) = t \cdot R_3(t) - t x_1 = R_4(t)  
        }$ - рациональная функция
        
        Таким образом, интеграл примет вид:  
          
        $\mathsf  
        {  
        \int R(x, \sqrt{ax^2 + bx + c})dx = \int R(R_3(t);\ R_4(t)) \cdot R_3'(t) dt  
        }$ - интеграл от рациональной функции.
        
3. Коэффициенты $\mathsf{c>0}$
    
    Тогда используется подстановка:
    
    $\mathsf{  
    \sqrt{ax^2+bx+c} =\pm \sqrt c \pm xt  
    }$
    
    Выразим $\mathsf x$:
    
    Возведём в квадрат:
    
    $\mathsf{  
    ax^2+bx+c=c \pm 2 \sqrt c \cdot x \cdot t+x^2t^2  
    }$
    
    Разделим на $\mathsf x$:
    
    $\mathsf{ax+b= \pm 2 \sqrt c \cdot t+xt^2}$; $\mathsf{  
    b \mp 2 \sqrt c \cdot t = x t^2-ax  
    }$;
    
    $\mathsf{x = \frac {b \mp 2 \sqrt c \cdot t}{t^2-a} = R_5(t)}$ - рациональная функция.
    
    Тогда:
    
    $\mathsf{dx = R'_5(t)dt}$ - рациональная функция
    
    Интеграл примет вид:
    
    $\mathsf{\int R(x, \sqrt{ax^2+bx+c})\cdot dx = \int R(R_5(t), R_6(t))\cdot R'_5(t)\cdot dt}$ - интеграл от рациональной функции
    
    **Замечание:**
    
    Квадратичные иррациональности можно привести к интегральному виду
    
    $\mathsf  
    {  
    \int R(t, \sqrt{t^2 \pm A^2})dt  
    }$ или $\mathsf  
    {  
    \int R(t, \sqrt{A^2 - t^2})dt  
    }$
    
    выделением в выражении $\mathsf  
    {  
    ax^2 + bx + c  
    }$ полного квадрата и заменой переменной.
    
    Подстановки Эйлера используются, когда интеграл не удаётся вычислить другим способом, т. к. они приводят к громоздким вычислениям.
    

### 12. Интеграл вида $\mathsf{\int \frac{P_n(x)dx}{\sqrt{ax^2 + bx + c}}}$

$\mathsf  
{  
\int \frac{P_n(x) \cdot dx}{\sqrt{ax^2 + bx + c}} = Q_{n-1}(x) \cdot \sqrt{ax^2 + bx + c} + \alpha \cdot \int \frac {dx}{\sqrt{ax^2 + bx + c}}  
}$, где $\mathsf  
{  
Q_{n - 1}(x)  
}$ - многочлен степени $\mathsf {(n - 1)}$, $\mathsf  
{  
\alpha  
}$ - вещественное число.

**Замечание:**

К интегралу данного вида сводится интеграл $\mathsf{  
\int \frac{dx}{(x+A)^k\cdot \sqrt{ax^2+bx+c}}  
}$ , с помощью замены переменной $\mathsf  
{  
t = \frac 1 {x + A}  
}$ При $\mathsf  
{  
k \ge 2  
}$ многочлен в числителе будет иметь степень $\mathsf  
{  
n = k - 1  
}$.

### 13. Метод Остроградского

Пусть $\mathsf  
{  
Q(x) = (x + a_1)^{\alpha_1} \cdot \ldots \cdot (x + a_r)^{\alpha_r} \cdot (x^2 + p_1x + q_q)^{\beta_1} \cdot \ldots \cdot (x^2 + p_sx + q_s)^{\beta_s}  
}$

$\mathsf{\int \frac{P(x)}{Q(x)}\cdot dx = \frac{P_1(x)}{Q_1(x)} + \int \frac{P_2(x)}{Q_2(x)}\cdot dx}$, где

$\mathsf  
{  
Q_1(x) = (x + a_1)^{\alpha_1 - 1} \cdot \ldots \cdot (x + a_r)^{\alpha_r - 1} \cdot(x^2 + p_1x + q_1)^{\beta_1 - 1} \cdot \ldots \cdot (x^2 + p_sx + q_s)^{\beta_s - 1}  
}$

$\mathsf  
{  
Q_2(x) = (x + a_1) \cdot \ldots \cdot (x + a_r) \cdot(x^2 + p_1x + q_1) \cdot \ldots \cdot(x^2 + p_sx +q_s)  
}$, степени многочленов $\mathsf{P_1(x), ~P_2(x)}$ меньше степени многочленов $\mathsf{Q_1(x), ~Q_2(x)}$ соответственно.