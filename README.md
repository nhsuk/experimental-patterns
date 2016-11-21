# NHS.UK experimental patterns

**This is not a pattern library.**


This a growing collection of patterns emerging from NHS.UK beta prototypes. They will continue to be iterated on. They are in no way finished or finalised.

- [Base](#base)
- [Callout](#callout)
- [Panel](#panel)


## Base

- Font TBC
- Body copy 20px
- Baseline grid 4px
- All margins, padding and line heights should be multiples of 4
- Headings in sentence case

### Headings

![Headings](base/headings.png)

### Body copy

![Headings](base/paragraph.png)

### Bullet list

![Headings](base/list/bullets.png)

### Numbered list

![Headings](base/list/numbered.png)

### Chevron list

![Headings](base/list/chevron.png)

```
list--chevron
```

### Check list

![Headings](base/list/check.png)

```
list--check
```

### Cross list

![Headings](base/list/check.png)

```
list--cross
```

### Table

![Headings](base/table/table.png)

```
list--cross
```

## Callout

Callouts are used to draw attention to a piece of content and prompt people to take action.  

#### Notes

- Six variants which roughly correspond with the urgency of the action to be taken
- Different border styles are used to differentiate other than by colour

### Muted

![Muted callout](callout/muted.png)

```
<div class="callout callout--muted">...</div>
```

### Info

![Info callout](callout/info.png)

```
<div class="callout callout--info">...</div>
```

### Attention

![Attention callout](callout/attention.png)

```
<div class="callout callout--attention">...</div>
```

### Warning

![Warning callout](callout/warning.png)

```
<div class="callout callout--warning">...</div>
```

### Alert

![Alert callout](callout/alert.png)

```
<div class="callout callout--alert">...</div>
```

### Severe

![Alert callout](callout/severe.png)

```
<div class="callout callout--severe">...</div>
```

### Compact

- Tighter padding
- Makes callout flow to width of content
- Can be applied to any callout

![Info callout](callout/info-compact.png)

```
<div class="callout callout--compact">...</div>
```

## Panel

- Mini content assembly
- Orientation/understanding/action

### Panel with header

![Panel with header](panel/header.png)

```
<article class="panel">
  <header class="panel__header">...</footer>
  <div class="panel__content">...</div>
</article>
```

### Panel with footer

![Panel with footer](panel/footer.png)

```html
<article class="panel">
  <div class="panel__content">...</div>
  <footer class="panel__footer">...</footer>
</article>
```

### Panel table

- Comparison of binary lists where individual items have direct opposite

![Panel table](table/panel.png)

```
<table class="panel">...</table>
```

### Panel with binary lists

- Comparison of binary themed lists where individual items are not directly opposing

![Panel with binary lists](panel/binary.png)

```
panel panel--binary
panel__column
panel__content
```
