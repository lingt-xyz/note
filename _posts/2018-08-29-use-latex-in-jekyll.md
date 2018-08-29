---
title: Use Latex in Jekyll
layout: post
categories: latex
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