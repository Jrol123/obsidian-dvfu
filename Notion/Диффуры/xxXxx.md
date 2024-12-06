---
Owner: Artemii
---
# №1

$\mathsf{  
\cos^3(y) y' - \cos(2x + y) = \cos(2x - y)  
}$

  

$\mathsf{  
\cos^3(y) y' - 2 \cos(2x)\cos(y) = 0  
}$

# №2

# №3

$\mathsf{  
x^2 y' = yx + y^2  
}$

Однородное

  

$\mathsf{  
t = \dfrac y x  
}$

$\mathsf{  
dy = tdx + xdt  
}$

$\mathsf{  
x^2 dy = yxdx + y^2 dx  
}$

  

$\mathsf{  
x^2 \left(tdx + xdt\right) = (t + t^2)x^2dx  
}$

$\mathsf{  
x^2t^2 dx = x^3dt  
}$

  

$\mathsf{  
\dfrac{dx}{x} = \dfrac{dt}{t^2}  
}$

$\mathsf{  
\ln(x) = - \dfrac 1 t + C  
}$

$\mathsf{  
\dfrac x y = C - \ln(x)  
}$

$\mathsf{  
y = - \dfrac{x}{\ln(x) + C}  
}$

## Особые решения

1. $\mathsf{  
    x = 0  
    }$
    
    **НЕ ПОДХОДИТ**
    
2. $\mathsf{  
    t = 0  
    }$
    
    $\mathsf{  
    y = 0  
    }$
    
    **ПОДХОДИТ**
    
    **ЯВЛЯЕТСЯ ОСОБЫМ РЕШЕНИЕМ**
    

  

  

# №4

$\mathsf{  
y' - 3x^2 y - x^2 e^{x^3} = 0  
}$

$\mathsf{  
y(0) = 0  
}$

  

Линейное

  

Используем метод Лагранжа

  

$\mathsf{  
y' = 3x^2 y  
}$

$\mathsf{  
\dfrac{dy}{y} = 3x^2dx  
}$

  

$\mathsf{  
\ln(y) = x^3 + C  
}$

  

$\mathsf{  
y = C(x)e^{x^3}  
}$

$\mathsf{  
y' = C'(x) e^{x^3} + 3C(x) x^2 e^{x^3}  
}$

  

$\mathsf{  
C'(x)e^{x^3} + 3C(x) x^2 e^{x^3} - 3 C(x)x^2 e^{x^3} - x^2 e^{x^3} = 0  
}$

$\mathsf{  
C'(x) e^{x^3} = x^2 e^{x^3}  
}$

  

$\mathsf{  
C(x) = \dfrac{x^3}{3} + \overline C  
}$

  

$\mathsf{  
y = (\dfrac{x^3}{3} + \overline C) e^{x^3}  
}$

  

$\mathsf{  
0 = (\dfrac{0}{3} + \overline C) e^{0}  
}$

$\mathsf{  
\overline C = 0  
}$

  

$\mathsf{  
y = \dfrac{x^3 e^{x^3}}{3}  
}$

## Особые решения

1. $\mathsf{  
    y = 0  
    }$
    
    **НЕ ЯВЛЯЕТСЯ ОСОБЫМ РЕШЕНИЕМ**
    
2. $\mathsf{  
    e^{x^3} = 0  
    }$
    
    **НЕ ЯВЛЯЕТСЯ ОСОБЫМ РЕШЕНИЕМ**
    
      
    

# №5

$\mathsf{  
y' - y + y^2 \cos(x) = 0  
}$

  

Уравнение Бернулли.

Метод Бернулли

  

$\mathsf{y=u\cdot v}$

  

$\mathsf{  
u'v + v'u - uv = - u^2v^2 \cos(x)  
}$

$\mathsf{  
v' - v = 0  
}$

$\mathsf{  
\ln(v) = x  
}$

$\mathsf{  
v = e^x  
}$

  

$\mathsf{  
u'e^x = -u^2 e^{2x} \cos(x)  
}$

$\mathsf{  
\dfrac{du}{u^2} = -e^x \cos(x)dx  
}$

  

$\mathsf{  
- \dfrac 1 u = -\dfrac{e^x}2 \left(\sin(x) + \cos(x)\right) + C  
}$

$\mathsf{  
u = \dfrac{2}{e^x \sin(x) + e^x \cos(x) + C}  
}$

  

$\mathsf{  
y=\dfrac{2\,{e}^{x}}{{e}^{x}\,\sin\left(x\right)+{e}^{x}\,\cos\left(x\right)+C}  
}$