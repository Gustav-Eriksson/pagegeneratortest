---
layout: page
title: About
permalink: /about/
---

### html entities

&rsquo;



markdown : {{ site.markdown }}

highlighter : {{ site.highlighter }}

kramdown setup : {{ site.kramdown | inspect }}


``` js
{% include code/js-code.js %}
```

This block-level element is used to attach attributes to another block-level element. A block inline attribute list (block IAL) has the same structure as an ALD except that the colon/reference name/colon part is replaced by a colon. A block IAL (or two or more block IALs) has to be put directly before or after the block-level element to which the attributes should be attached. If a block IAL is directly after and before a block-level element, it is applied to preceding element. The block IAL is ignored in all other cases, for example, when the block IAL is surrounded by blank lines.
{: .my-class}

<style>
.my-class{
   text-align: justify;
}
</style>
