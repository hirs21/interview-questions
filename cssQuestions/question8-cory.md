* What are your favourite image replacement techniques and which do you use when?

  My favorite technique to to using the psuedo :before property to push the element aside.  This still has all the SEO and screen reader benefits without the browser having to draw a large box.

### Example

Markup:
```
  <h1 class="replaceMe">Replaced</h1>
```

CSS:

```
.replaceMe {
  width: 200px;
  overflow: hidden;
}

.replaceMe:before {
  content: url('pathToImg');
}
```
