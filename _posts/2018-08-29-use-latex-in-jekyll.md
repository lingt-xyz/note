---
title: Use Latex in Jekyll
layout: post
categories: latex
comments: true
---
Two things need to be done.

<!--more-->

1. Import MathJax: make sure use ```https```
    ``` html
    <script type="text/javascript"
        src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    </script>
    ```
2. Put the code in ```{% raw %} {% endraw %}```
    ```
    {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}
        $$ put MathJax here $$
    {% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %}
    ```
    
### Style Examples

* Inline
    {% raw %}
    $$ a^2 + b^2 = c^2 $$ --> note that all equations between these tags will not need escaping! 
    {% endraw %}

    ```
    $$ a^2 + b^2 = c^2 $$ --> note that all equations between these tags will not need escaping!
    ```

* Block
    {% raw %}
    $$ a^2 + b^2 = c^2 $$
    {% endraw %}

    ```
    $$a^2 + b^2 = c^2$$
    ```


### Examples:

* Indent

    1. Must contain 0: 

        {% raw %}$$
        \left.
        \begin{array}{l}
        0\quad \_\quad \_\quad \_\quad \_:&10^4\\
        \_\quad 0\quad \_\quad \_\quad \_:&10^4\\
        \_\quad \_\quad 0\quad \_\quad \_:&10^4\\
        \_\quad \_\quad \_\quad 0\quad \_:&10^4\\
        \_\quad \_\quad \_\quad \_\quad 0:&10^4
        \end{array}
        \right\}
        =5\times10^4
        $${% endraw %}

        * How about {% raw %}$$00012$${% endraw %}, it was counted three times.
        * {% raw %}$$10^5 - 9^5$${% endraw %}: {% raw %}$$9^5$${% endraw %} is who does not contain 0.

    2. Must contain 0 and 1: {% raw %}$$10^5-9^5-9^5+8^5$${% endraw %}

    ```
    {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}
    1. Must contain 0: 

        {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}
        \left.
        \begin{array}{l}
        0\quad \_\quad \_\quad \_\quad \_:&10^4\\
        \_\quad 0\quad \_\quad \_\quad \_:&10^4\\
        \_\quad \_\quad 0\quad \_\quad \_:&10^4\\
        \_\quad \_\quad \_\quad 0\quad \_:&10^4\\
        \_\quad \_\quad \_\quad \_\quad 0:&10^4
        \end{array}
        \right\}
        =5\times10^4
        {% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %}

        * How about {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}$$00012{% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %}, it was counted three times.
        *  {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}$$10^5 - 9^5$${% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %}: {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}$$9^5$${% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %} is who does not contain 0.

    2. Must contain 0 and 1: {% raw %}{%{% endraw %} raw {% raw %}%}{% endraw %}$$10^5-9^5-9^5+8^5$${% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %}
    {% raw %}{%{% endraw %} endraw {% raw %}%}{% endraw %}
    ```