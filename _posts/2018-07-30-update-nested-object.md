---
title:  Throw statement with no expression
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
vs
``` c#
public void foo()
{
    try {
        // some code
    }
    catch (Exception) 
    {
       throw;
    }
}
```
[throw (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/throw)
