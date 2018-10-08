Function appendChildren should add a new child div to each existing div. New divs should be decorated by calling decorateDiv.

For example, after appendChildren is executed, the following divs:

```html
<div id="a">
  <div id="b">
  </div>
</div>
```

should take the following form (assuming decorateDiv does nothing):

```html
<div id="a">
  <div id="b">
    <div></div>
  </div>
  <div></div>
</div>
```

The code below should do the job, but for some reason it goes into an infinite loop. Fix the bugs.

