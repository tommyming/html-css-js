# Introduction

### What is CSS?

Basically, it is the style of the Webpage, it controls all the STYLING STUFFS

It describes how HTML displays on the screen, paper, etc.

Later, we will use this specific document to show the changes of the CSS:

http://scratchpad.io/nostalgic-rest-6290

### So, how does it works?

Let's take a look at the following example:

```
<html>
  <head>
    (some import stuffs and metas)
  </head>
  
  <body>
    <p id = poop_colour> I like poop. </p>
  </body>
</html>
```

So, how do we change the colour of the text ***I like poop*** ?

Here is what CSS can do its job, by setting up a stylesheet for the <p> tag.

CSS can be separated into 3 different Categories:

### Inline style

It is the ***style*** attribute in the tag, yeah, thats all

```
<p style="font-family:??? ; colour: Yellow"> I like poop</p>
```

### Inline Styelsheet

It is using the ***style*** tag to import the styles for the HTML

```
<style>
  p {
    font-family: Microsoft JengHei UI
    colour: Black
</style>
<p> I like poop </p>
```

### External Stylesheet (Recommended)

Same as the format above, but it is in an independent file XXX.css
It is separated from the HTML

With using the ***id*** or ***class*** attribute, you can call the specific styler with ease.
