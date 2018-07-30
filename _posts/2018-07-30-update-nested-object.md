---
title:  Update nestedobject
layout: post
categories: javascript
tags: javascript vue
---

Update nested object in vue.js
<!--more-->
``` javascript
let aiVue = null;
let ai = something;

if (aiVue) {
    aiVue.$data.player = ai;
} else {
    aiVue = new Vue({
        el: '#divAi',
        data: {
            player: ai
        }
    })
}
```

``` html
<span v-for="some in player.someCollection" v-html="some.toHtml()"></span>
<span>Hand: {{ player.someCollection.length }} </span>
```
[throw (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/throw)
