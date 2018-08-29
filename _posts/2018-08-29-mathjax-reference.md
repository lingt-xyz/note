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

```
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

```
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

```
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

```
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

```
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

```
\begin{Vmatrix}
    1 & 2 \\
    3 & 4 \\ 
\end{Vmatrix}
```



{% raw %}$$  $${% endraw %} ```  ```