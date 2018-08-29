---
title: MathJax Reference
layout: post
toc: true
categories: latex
---

[MathJax quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

<!--more-->

### 1. Greek letters

{% raw %}$$ \alpha, \beta, … \omega $${% endraw %} ```\alpha, \beta, …, \omega```

{% raw %}$$ \Gamma, \Delta, …, \Omega $${% endraw %} ```\Gamma, \Delta, …, \Omega```

### 2. Superscripts and Subscripts

{% raw %}$$ x_i^2 $${% endraw %} ``` x_i^2 ```

{% raw %}$$ \log_2 x $${% endraw %} ``` \log_2 x ```

### 3. Groups
A “group” is either a single symbol, or any formula surrounded by curly braces ```{```…```}```.

{% raw %}$$ 10^10 $${% endraw %} ``` 10^10 ```

{% raw %}$$ 10^{10} $${% endraw %} ``` 10^{10} ```

{% raw %}$$ x_i^2 $${% endraw %} ``` x_i^2 ```

{% raw %}$$ x_{i^2} $${% endraw %} ``` x_{i^2} ```

### 4. Parentheses 
Ordinary symbols ```()[]``` make parentheses and brackets (2+3)[4+4]. Use ```\{``` and ```\}``` for curly braces {% raw %}$$ \{\} $${% endraw %}.

{% raw %}$$ (\frac{\sqrt x}{y^3}) $${% endraw %} ``` (\frac{\sqrt x}{y^3}) ```

{% raw %}$$ \left(\frac{\sqrt x}{y^3}\right) $${% endraw %} ``` \left(\frac{\sqrt x}{y^3}\right) ```

{% raw %}$$ \Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr) $${% endraw %} ``` \Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr) ```

### 5. Sums and integrals

{% raw %}$$ \sum_1^n $${% endraw %} ``` \sum_1^n ```

{% raw %}$$ \sum_{i=0}^\infty i^2 $${% endraw %} ``` \sum_{i=0}^\infty i^2 ```

{% raw %}$$ \prod $${% endraw %} ``` \prod ```

{% raw %}$$ \int $${% endraw %} ``` \int ```

{% raw %}$$ \bigcup $${% endraw %} ``` \bigcup ```

{% raw %}$$ \bigcap $${% endraw %} ``` \bigcap ```

{% raw %}$$ \iint $${% endraw %} ``` \iint ```

### 6. Fractions

{% raw %}$$ \frac ab $${% endraw %} ``` \frac ab ```

{% raw %}$$ \frac{a+1}{b+1} $${% endraw %} ``` \frac{a+1}{b+1} ```

{% raw %}$$ {a+1\over b+1} $${% endraw %} ``` {a+1\over b+1} ```

{% raw %}$$ \cfrac{a}{b} $${% endraw %} ``` \cfrac{a}{b} ```

### 7. Radical signs

{% raw %}$$ \sqrt{x^3} $${% endraw %} ``` \sqrt{x^3} ```

{% raw %}$$ \sqrt[3]{\frac xy} $${% endraw %} ``` \sqrt[3]{\frac xy} ```

### 8. Plain text

{% raw %}$$ \{x\in s\mid x\text{ is extra large}\} $${% endraw %} ``` \{x\in s\mid x\text{ is extra large}\} ```

### 9. Fonts
Use ```\mathbb``` or ```\Bbb``` for "blackboard bold"

{% raw %}$$ \mathbb{CHNQRZ} $${% endraw %} ``` \mathbb{CHNQRZ} ```

### 10. Special symbols and notations

{% raw %}$$ \lt \gt \le \leq \leqq \leqslant \ge \geq \geqq \geqslant \neq $${% endraw %} ``` \lt \gt \le \leq \leqq \leqslant \ge \geq \geqq \geqslant \neq ```

{% raw %}$$ x\cdot y \times \div \pm \mp $${% endraw %} ``` x\cdot y \times \div \pm \mp ```

{% raw %}$$ \cup \cap \setminus \subset \subseteq \subsetneq \supset \in \notin \emptyset \varnothing $${% endraw %} ``` \cup \cap \setminus \subset \subseteq \subsetneq \supset \in \notin \emptyset \varnothing ```

{% raw %}$$ {n+1 \choose 2k} \binom{n+1}{2k} $${% endraw %} ``` {n+1 \choose 2k} \binom{n+1}{2k} ```

{% raw %}$$ \to \rightarrow \leftarrow \Rightarrow \Leftarrow \mapsto $${% endraw %} ``` \to \rightarrow \leftarrow \Rightarrow \Leftarrow \mapsto ```

{% raw %}$$ \land \lor \lnot \forall \exists \top \bot \vdash \vDash $${% endraw %} ``` \land \lor \lnot \forall \exists \top \bot \vdash \vDash ```

{% raw %}$$ \star \ast \oplus \circ \bullet $${% endraw %} ``` \star \ast \oplus \circ \bullet ```

{% raw %}$$ \star \ast \oplus \circ \bullet $${% endraw %} ``` \star \ast \oplus \circ \bullet ```

{% raw %}$$ \approx \sim \simeq \cong \equiv \prec \lhd \therefore $${% endraw %} ``` \approx \sim \simeq \cong \equiv \prec \lhd \therefore ```

{% raw %}$$ a\equiv b\pmod n $${% endraw %} ``` a\equiv b\pmod n ```

{% raw %}$$ a_1, a_2, \ldots ,a_n $${% endraw %} ``` a_1, a_2, \ldots ,a_n ```

{% raw %}$$ a_1+a_2+\cdots+a_n $${% endraw %} ```a_1+a_2+\cdots+a_n  ```

### 11. Accents and diacritical marks

{% raw %}$$ \hat x $${% endraw %} ``` \hat x ```

{% raw %}$$ \widehat{xy} $${% endraw %} ``` \widehat{xy} ```

{% raw %}$$ \bar x $${% endraw %} ``` \bar x ```

{% raw %}$$ \overline{xyz} $${% endraw %} ``` \overline{xyz} ```

{% raw %}$$ \vec x $${% endraw %} ``` \vec x ```

{% raw %}$$ \overrightarrow{xy} $${% endraw %} ``` \overrightarrow{xy} ```

{% raw %}$$ \frac d{dx}x\dot x =  \dot x^2 +  x\ddot x $${% endraw %} ``` \frac d{dx}x\dot x =  \dot x^2 +  x\ddot x ```

### 12. Escape characters
```\```

{% raw %}$$ \backslash $${% endraw %} ``` \backslash ```

{% raw %}$$ \_ $${% endraw %} ``` \_ ```

### 13. Matrices

{% raw %}
$$ 
\begin{matrix}
    1 & x & x^2 \\
    1 & y & y^2 \\
    1 & z & z^2 \\
\end{matrix}
$$
{% endraw %} 

``` tex
\begin{matrix}
    1 & x & x^2 \\
    1 & y & y^2 \\
    1 & z & z^2 \\
\end{matrix}
```

{% raw %}
$$ 
\begin{pmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{pmatrix}
$$
{% endraw %} 

``` tex
\begin{pmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{pmatrix}
```

{% raw %}
$$ 
\begin{bmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{bmatrix}
$$
{% endraw %} 

``` tex
\begin{bmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{bmatrix}
```

{% raw %}
$$ 
\begin{Bmatrix }
    1 & 2 \\
    3 & 4 \\ 
\end{Bmatrix }
$$
{% endraw %} 

``` tex
\begin{Bmatrix }
    1 & 2 \\
    3 & 4 \\ 
\end{Bmatrix }
```

{% raw %}
$$ 
\begin{vmatrix }
    1 & 2 \\
    3 & 4 \\ 
\end{vmatrix }
$$
{% endraw %} 

``` tex
\begin{vmatrix }
    1 & 2 \\
    3 & 4 \\ 
\end{vmatrix }
```

{% raw %}
$$ 
\begin{Vmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{Vmatrix}
$$
{% endraw %} 

``` tex
\begin{Vmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{Vmatrix}
```

{% raw %}
$$
\begin{pmatrix}
 1 & a_1 & a_1^2 & \cdots & a_1^n \\
 1 & a_2 & a_2^2 & \cdots & a_2^n \\
 \vdots  & \vdots& \vdots & \ddots & \vdots \\
 1 & a_m & a_m^2 & \cdots & a_m^n    
\end{pmatrix}
$$
{% endraw %} 

``` tex
\begin{pmatrix}
 1 & a_1 & a_1^2 & \cdots & a_1^n \\
 1 & a_2 & a_2^2 & \cdots & a_2^n \\
 \vdots  & \vdots& \vdots & \ddots & \vdots \\
 1 & a_m & a_m^2 & \cdots & a_m^n    
\end{pmatrix}
```

{% raw %}
$$
\left[
\begin{array}{cc|c}
  1&2&3\\
  4&5&6
\end{array}
\right]
$$
{% endraw %} 

``` tex
\left[
\begin{array}{cc|c}
  1&2&3\\
  4&5&6
\end{array}
\right]
```

{% raw %}
$$
\left[
\begin{array}{cc|c}
  1&2&3\\
  4&5&6
\end{array}
\right]
$$
{% endraw %} 

``` tex
\left[
\begin{array}{cc|c}
  1&2&3\\
  4&5&6
\end{array}
\right]
```

### 14. Aligned equations

{% raw %}
$$
\begin{align}
\sqrt{37} & = \sqrt{\frac{73^2-1}{12^2}} \\
 & = \sqrt{\frac{73^2}{12^2}\cdot\frac{73^2-1}{73^2}} \\ 
 & = \sqrt{\frac{73^2}{12^2}}\sqrt{\frac{73^2-1}{73^2}} \\
 & = \frac{73}{12}\sqrt{1 - \frac{1}{73^2}} \\ 
 & \approx \frac{73}{12}\left(1 - \frac{1}{2\cdot73^2}\right)
\end{align}
$$
{% endraw %} 

``` tex
\begin{align}
\sqrt{37} & = \sqrt{\frac{73^2-1}{12^2}} \\
 & = \sqrt{\frac{73^2}{12^2}\cdot\frac{73^2-1}{73^2}} \\ 
 & = \sqrt{\frac{73^2}{12^2}}\sqrt{\frac{73^2-1}{73^2}} \\
 & = \frac{73}{12}\sqrt{1 - \frac{1}{73^2}} \\ 
 & \approx \frac{73}{12}\left(1 - \frac{1}{2\cdot73^2}\right)
\end{align}
```

### 15. Piecewise functions

{% raw %}
$$
f(n) =
\begin{cases}
n/2,  & \text{if $n$ is even} \\
3n+1, & \text{if $n$ is odd}
\end{cases}
$$
{% endraw %} 

``` tex
f(n) =
\begin{cases}
n/2,  & \text{if $n$ is even} \\
3n+1, & \text{if $n$ is odd}
\end{cases}
```

{% raw %}
$$
\left.
\begin{array}{l}
\text{if $n$ is even:}&n/2\\
\text{if $n$ is odd:}&3n+1
\end{array}
\right\}
=f(n)
$$
{% endraw %} 

``` tex
\left.
\begin{array}{l}
\text{if $n$ is even:}&n/2\\
\text{if $n$ is odd:}&3n+1
\end{array}
\right\}
=f(n)
```


### 16. Arrays

{% raw %}
$$
\begin{array}{c|lcr}
n & \text{Left} & \text{Center} & \text{Right} \\
\hline
1 & 0.24 & 1 & 125 \\
2 & -1 & 189 & -8 \\
3 & -20 & 2000 & 1+10i
\end{array}
$$
{% endraw %} 

``` tex
\begin{array}{c|lcr}
n & \text{Left} & \text{Center} & \text{Right} \\
\hline
1 & 0.24 & 1 & 125 \\
2 & -1 & 189 & -8 \\
3 & -20 & 2000 & 1+10i
\end{array}
```

{% raw %}
$$
% outer vertical array of arrays
\begin{array}{c}
% inner horizontal array of arrays
\begin{array}{cc}
% inner array of minimum values
\begin{array}{c|cccc}
\text{min} & 0 & 1 & 2 & 3\\
\hline
0 & 0 & 0 & 0 & 0\\
1 & 0 & 1 & 1 & 1\\
2 & 0 & 1 & 2 & 2\\
3 & 0 & 1 & 2 & 3
\end{array}
&
% inner array of maximum values
\begin{array}{c|cccc}
\text{max}&0&1&2&3\\
\hline
0 & 0 & 1 & 2 & 3\\
1 & 1 & 1 & 2 & 3\\
2 & 2 & 2 & 2 & 3\\
3 & 3 & 3 & 3 & 3
\end{array}
\end{array}
\\
% inner array of delta values
\begin{array}{c|cccc}
\Delta&0&1&2&3\\
\hline
0 & 0 & 1 & 2 & 3\\
1 & 1 & 0 & 1 & 2\\
2 & 2 & 1 & 0 & 1\\
3 & 3 & 2 & 1 & 0
\end{array}
\end{array}
$$
{% endraw %} 

``` tex
% outer vertical array of arrays
\begin{array}{c}
% inner horizontal array of arrays
\begin{array}{cc}
% inner array of minimum values
\begin{array}{c|cccc}
\text{min} & 0 & 1 & 2 & 3\\
\hline
0 & 0 & 0 & 0 & 0\\
1 & 0 & 1 & 1 & 1\\
2 & 0 & 1 & 2 & 2\\
3 & 0 & 1 & 2 & 3
\end{array}
&
% inner array of maximum values
\begin{array}{c|cccc}
\text{max}&0&1&2&3\\
\hline
0 & 0 & 1 & 2 & 3\\
1 & 1 & 1 & 2 & 3\\
2 & 2 & 2 & 2 & 3\\
3 & 3 & 3 & 3 & 3
\end{array}
\end{array}
\\
% inner array of delta values
\begin{array}{c|cccc}
\Delta&0&1&2&3\\
\hline
0 & 0 & 1 & 2 & 3\\
1 & 1 & 0 & 1 & 2\\
2 & 2 & 1 & 0 & 1\\
3 & 3 & 2 & 1 & 0
\end{array}
\end{array}
```



{% raw %}$$  $${% endraw %} ```  ```

{% raw %}
$$

$$
{% endraw %} 

``` tex

```