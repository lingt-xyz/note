---
title: Use Latex in Jekyll
layout: post
categories: latex
---
Import MathJax: make sure ```use https```

<!--more-->
```
<script type="text/javascript"
    src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```

### Examples

* Inline
{% raw %}
  $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping! 
{% endraw %}

```
{% raw %}
  $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping! 
{% endraw %}
```

* Block
{% raw %}
  $$a^2 + b^2 = c^2$$
{% endraw %}

```
{% raw %}
  $$a^2 + b^2 = c^2$$
{% endraw %}
```