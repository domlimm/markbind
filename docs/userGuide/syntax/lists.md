## Lists


****Unordered lists:****

<include src="codeAndOutput.md" boilerplate >
<variable name="highlightStyle">markdown</variable>
<variable name="code">
* Item 1
  * Sub item 1.1
  * Sub item 1.2<br>
    Second line
    * Sub item 1.2.1
* Item 2
* Item 3
</variable>
</include>

****Ordered lists:****

<include src="codeAndOutput.md" boilerplate >
<variable name="highlightStyle">markdown</variable>
<variable name="code">
1. Item 1
   1. Sub item 1.1
   1. Sub item 1.2
1. Item 2
1. Item 3
</variable>
</include>

<box type="tip" seamless>
You can also start an ordered list at a particular number by changing the
<popover>
first number
<template slot="content">
<div style="text-align: center; margin-bottom: 5px;">{{ icon_example }}</div>
<include src="codeAndOutputSeparate.md" boilerplate>
<variable name="highlightStyle">markdown</variable>
<variable name="code">
10. Item 1
   1. Sub item 1.1
   1. Sub item 1.2
1. Item 2
</variable>
<variable name="output">
10. Item 1
   1. Sub item 1.1
   1. Sub item 1.2
1. Item 2
{.ps-0 .ms-0}
</variable>
</include>
</template>
</popover>!
</box>

<small>More info on above list types: https://www.markdownguide.org/basic-syntax#lists</small>

****Task lists**** (from GFMD):

<div id="main-example-gfmd">
<include src="codeAndOutput.md" boilerplate >
<variable name="highlightStyle">markdown</variable>
<variable name="code">
- [ ] Item 1
   - [ ] Sub item 1.1
   - [x] Sub item 1.2
- [x] Item 2
- [ ] Item 3
</variable>
</include>
</div>


****Radio-button lists:****
<div id="main-example-markbind">
<include src="codeAndOutput.md" boilerplate >
<variable name="highlightStyle">markdown</variable>
<variable name="code">
- ( ) Item 1
- ( ) Item 2
- (x) Item 3
</variable>
</include>
</div>

<div id="short" class="d-none">

```markdown
1. Item 1
   1. Sub item 1.1
   1. Sub item 1.2
* Item 2
  * item 2.1
- [ ] Item 3
- [x] Item 4
- ( ) Item 5
```
</div>
<div id="examples" class="d-none">

1. Item 1
   1. Sub item 1.1
   1. Sub item 1.2
* Item 2
  * item 2.1
- [ ] Item 3
- [x] Item 4
- ( ) Item 5
</div>
